# Goal

Analyze the uploaded reference image and convert it into a standardized RFW Reference Analysis.

The purpose is to extract reusable visual attributes for prompt generation and image reconstruction.

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
- Describe observable appearance rather than semantic interpretation.
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

Bust / Chest:

Waist:

Hip Width:

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

Fit:
(fitted / loose / oversized / compression / tailored)

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

Field of View:
(close portrait / upper body / half body / full body)

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

Background Complexity:
(Simple / Moderate / Busy)

---

# Style

Image Type:
(Photograph / Anime / Illustration / 3D / CGI / Game Screenshot / Other)

Rendering Style:

Realism Level:

Color Palette:
(Warm / Cool / Neutral / Vibrant / Muted)

---

# Distinctive Features

List the 3–5 most visually distinctive characteristics that immediately define the subject.

Use only observable characteristics.

Prioritize features that would significantly affect image reproduction.

---

# Identity Summary

Summarize the subject's appearance in no more than 3 concise sentences.

Describe only observable visual characteristics.

---

# Reusable Prompt Components

Create reusable prompt-ready building blocks.

Use concise descriptive phrases rather than complete sentences.

Each section should be reusable independently.

Prioritize visually distinctive and reproducible characteristics.

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