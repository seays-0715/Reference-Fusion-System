**Prompt**

```

# Goal

Synchronize the character's complete body pose from the assigned pose reference while preserving the established character identity, facial appearance, canonical body, wardrobe, environment, camera, lighting, and rendering style.

The output should create a reusable Pose Asset independent of character appearance and scene presentation.

---

# Reference Assignment

Image 1:

Role:
Current Character

Image 2:

Role:
Pose Reference

---

# Stage Responsibility

Modify ONLY the character's pose, including:

- Full body posture
- Body orientation
- Head orientation
- Neck orientation
- Shoulder position
- Arm position
- Elbow position
- Wrist position
- Hand placement
- Finger pose
- Pelvis orientation
- Leg position
- Knee position
- Foot placement
- Weight distribution
- Body balance
- Sitting
- Standing
- Kneeling
- Lying
- Crouching
- Walking stance
- Eye direction
- Gesture

Do NOT intentionally modify any character appearance or scene attributes.

---

# Task

Transfer the complete body pose from Image 2 onto the character in Image 1.

Synchronize the character's posture, limb placement, body orientation, head orientation, eye direction, and gesture while preserving the established Character Canon and Character Assets.

If the requested pose requires environmental support (such as sitting, leaning, kneeling, or lying), assume the necessary supporting surface without modifying the environment itself.

This stage defines only the character's pose and must not modify the environment, camera, lighting, or rendering style.

---

# Preserve

Preserve all previously established character attributes from Image 1, including:

- Character identity
- Facial identity
- Facial structure
- Eyes
- Nose
- Mouth
- Eyebrows
- Facial expression
- Skin tone
- Hair
- Hairstyle
- Hair color
- Age appearance
- Ethnicity

Preserve the established body, including:

- Canonical body
- Body shape
- Skeletal framework
- Head-to-body ratio
- Height
- Overall body proportions
- Physique
- Body silhouette
- Muscle definition
- Body fat distribution
- Localized body refinements

Preserve the established wardrobe, including:

- Clothing
- Footwear
- Socks
- Stockings
- Pantyhose
- Wearable accessories

Do not modify:

- Environment
- Background
- Props
- Camera angle
- Perspective
- Composition
- Lighting
- Rendering style
- Image quality

---

# Restrictions

- Transfer only the body pose from the pose reference.
- Do not alter facial expression.
- Do not alter body proportions or physique.
- Do not alter wardrobe.
- Do not copy camera composition from the reference.
- Do not copy lighting from the reference.
- Do not copy background or environment from the reference.
- Do not alter facial identity.
- Preserve realistic anatomical articulation.
- Preserve natural joint limitations.
- Maintain realistic body balance and weight distribution.
- Generate only the pose independent of character appearance and scene presentation.

---

# Output

Asset Name:

05 Pose

Purpose:

Defines the character's reusable pose asset by synchronizing body posture, limb placement, body orientation, eye direction, and gesture while preserving the established Character Canon and Character Assets.

This asset controls only the character's pose and remains independent of environment, camera, lighting, and rendering style.