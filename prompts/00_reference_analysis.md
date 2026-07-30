# Goal

Analyze the uploaded reference image and convert it into a standardized RFW Reference Analysis for image reconstruction.

The purpose is to extract reusable visual attributes for prompt generation.

Describe only observable visual characteristics.

Do NOT generate a new image.

Do NOT infer hidden information or invent missing details.

---

# Analysis Rules

- Analyze only what is clearly visible.
- If a characteristic cannot be determined confidently, output:
  Unknown
- Do not guess.
- Remain objective and descriptive.
- Use concise, generation-friendly language.
- Prefer concrete physical descriptions over abstract interpretations.
- Do not include quality-enhancing prompt terms (e.g. masterpiece, best quality, 8k, ultra detailed).

---

# Identity

Apparent Age:

Gender Presentation:

Ethnicity / Appearance:
(Only if visually apparent. Otherwise: Unknown.)

Face Shape:

Eyes:
(openness, visible shape, gaze)

Eyebrows:

Nose:

Lips:

Jawline:

Hair:
(length, texture, style, movement)

Hair Color:

Skin Tone:

Distinctive Facial Features:

---

# Body

Body Type:

Overall Physique:

Visible Body Proportions:

Shoulders:

Bust:

Waist:

Hips:

Legs:

Posture:

---

# Outfit

Top:

Bottom:

Outerwear:

Footwear:

Accessories:

Dominant Colors:

Material:

Patterns / Logos:

---

# Pose

Body Orientation:

Torso Rotation:

Head Position:

Eye Direction:

Arm Position:

Hand Position:

Leg Position:

Weight Distribution:

Gesture:

Hair Motion:

---

# Expression

Eyes:

Eyebrows:

Mouth:

Overall Expression:

---

# Camera

Framing:

Camera Distance:

Camera Angle:

Lens Perspective:
(Estimate only if visually apparent. Otherwise: Unknown.)

Composition:

Cropping:

Focus:
(e.g. sharp subject with soft background)

---

# Lighting

Lighting Type:

Light Direction:
(Only if clearly observable.)

Shadow Strength:

Color Temperature:

---

# Background

Environment:

Background Description:

---

# Style

Image Type:
(Photograph / Anime / Illustration / 3D / CGI / Game Screenshot / Other)

Rendering Style:

Realism Level:

---

# Distinctive Features

List the 3–5 most visually distinctive characteristics that immediately define this subject.

Use only observable characteristics.

Prioritize features that would significantly affect image reproduction.

---

# Identity Summary

Summarize the subject's appearance in no more than 3 concise sentences.

Describe only observable visual characteristics.

---

# RFW Prompt Components

Each section should contain concise prompt-ready phrases.

Avoid complete sentences.

Identity:

Body:

Outfit:

Pose:

Expression:

Camera:

Lighting:

Background:

Style:

---

# Generation Tags

Identity:
<comma-separated prompt keywords>

Body:
<comma-separated prompt keywords>

Outfit:
<comma-separated prompt keywords>

Pose:
<comma-separated prompt keywords>

Expression:
<comma-separated prompt keywords>

Camera:
<comma-separated prompt keywords>

Lighting:
<comma-separated prompt keywords>

Background:
<comma-separated prompt keywords>

Style:
<comma-separated prompt keywords>

Use commonly recognized image-generation keywords.

Avoid duplicate concepts.

---

# Negative Prompt Suggestions

List only visual characteristics that should be avoided when reproducing this image.

Examples:

- short hair
- open eyes
- frontal pose
- indoor background
- multiple people
- jacket
- hat

Do NOT include quality-related negative prompts.

---

# Reference Suitability

Evaluate how suitable this image is as a reference for each category.

Identity:
(Excellent / Good / Partial / Poor)

Body:
(Excellent / Good / Partial / Poor)

Outfit:
(Excellent / Good / Partial / Poor)

Pose:
(Excellent / Good / Partial / Poor)

Expression:
(Excellent / Good / Partial / Poor)

Camera:
(Excellent / Good / Partial / Poor)

Lighting:
(Excellent / Good / Partial / Poor)

Background:
(Excellent / Good / Partial / Poor)

---

# Overall Recommendation

Recommend the best role(s) for this image within the RFW workflow.

Examples:

- Identity Master
- Identity Support
- Body Reference
- Outfit Reference
- Pose Reference
- Expression Reference
- Camera Reference
- Lighting Reference
- Background Reference

Briefly explain the recommendation based only on observable characteristics.