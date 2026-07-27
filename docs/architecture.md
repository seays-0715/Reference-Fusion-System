# Architecture & Design Principles

## Core Idea: Reference Responsibility

Traditional multi-reference prompting mixes all images together.  
The model has no clear signal about which image controls which attribute.

RFW solves this by enforcing **strict responsibility assignment**:

| Reference Type | Controls | Must Not Affect |
|----------------|----------|-----------------|
| Identity | Face, eyes, nose, lips, jaw, hair, skin, age | Body, pose, outfit, scene |
| Body | Proportions, silhouette, height impression | Face, identity |
| Pose | Skeleton, limb placement, head angle | Face, body proportions, identity |
| Outfit | Clothing, fabric, color, accessories | Face, body, pose |
| Scene | Location, background, atmosphere | Character identity & clothing |
| Lighting | Key / fill / rim, color temperature, mood | Geometry of subject |
| Camera | Focal length, framing, depth of field | Subject content |
| Style | Overall aesthetic direction | All previous locks |

## Sequential Locking

```
Immutable attributes are established early.
Mutable attributes are introduced late.
```

Once Identity + Face Lock are done, the face should never be renegotiated.  
Once Body is locked, proportions should stay stable while pose and clothing change.

This is why the order matters.

## Why Not One-Shot?

One-shot multi-reference generation forces the model to solve too many constraints simultaneously:

- Who is this person?
- What body type?
- What pose?
- What clothes?
- Where are they?
- How is it lit?

RFW reduces the problem to a series of smaller, better-defined tasks.

## Design Goals

1. **Maximized identity consistency** across iterations
2. **Isolated control** — change one thing without breaking others
3. **Recoverability** — when something breaks, you know exactly which step to re-run
4. **Model-agnostic** — works with any multi-reference image model
5. **Human-readable** — easy for others to understand, modify, and extend

## Mental Model

Think of RFW as a **pipeline of constraints**, not a collection of prompts.

Each step adds a new constraint while freezing the previous ones.
