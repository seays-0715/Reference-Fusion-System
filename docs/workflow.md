# Workflow Guide

## Execution Order

Always run steps in sequence.  
Do not skip early stages unless you already have a locked Master from a previous session.

```
01 Identity
    ↓
02 Face Lock
    ↓
03 Body
    ↓
04 Pose
    ↓
05 Outfit
    ↓
06 Scene
    ↓
07 Lighting
    ↓
08 Camera
    ↓
09 Style
    ↓
10 Final
```

## Input / Output Chain

```
[Identity Ref]
      ↓
Identity_Master_v1
      +
[Body Ref]
      ↓
Body_Master_v1
      +
[Pose Ref]
      ↓
Pose_Master_v1
      +
[Outfit Ref]
      ↓
Fashion_Master_v1
      +
[Scene Ref]
      ↓
Scene_Master_v1
      ↓
Lighting_Master_v1
      ↓
Camera_Master_v1
      ↓
Style_Master_v1
      ↓
Final_Master_v1
```

## Step-by-Step Notes

### 01 — Identity Fusion
Establish the facial identity.  
This becomes the single source of truth for the face.

### 02 — Face Lock
Re-assert identity after any later step that may have caused drift.  
Run this whenever the face starts to change.

### 03 — Body Fusion
Transfer body proportions only.  
Face must remain from the previous Master.

### 04 — Pose Fusion
Transfer pose / skeleton only.  
Body proportions and face stay locked.

### 05 — Outfit Fusion
Transfer clothing and accessories.  
Pose, body, and face stay locked.

### 06 — Scene Fusion
Place the character into a new environment.  
Character must remain unchanged.

### 07 — Lighting & Mood
Improve lighting without changing geometry or identity.

### 08 — Camera & Composition
Adjust framing and lens characteristics.

### 09 — Style Lock
Apply final aesthetic direction without redesigning content.

### 10 — Final Polish
Enhance realism and technical quality only.

## Golden Rule

> Always feed the **previous Master** as Image 1.  
> New references are Image 2 (or later).  
> Never let a new reference overwrite identity.
