**Prompt**

```

# Goal

Edit the Base Image by transferring ONLY the character's upper body pose from the Reference Image.

---

# Image Roles

## Base Image

Image 1

The image to edit.

Preserve this image as the foundation of the final result.

---

## Reference Image

Image 2

Use ONLY as the reference for the character's upper body pose.

Do not copy unrelated visual information from this image.

---

# Primary Instruction

Transfer ONLY:

- Upper Body Pose

Replicate the upper body pose from the Reference Image as accurately as possible.

This includes:

- Head orientation
- Neck orientation
- Shoulder position
- Upper torso rotation
- Chest orientation
- Upper arm position
- Elbow position
- Forearm position
- Wrist position
- Hand placement
- Finger articulation
- Eye direction

Match the reference faithfully.

Do not reinterpret, redesign, stylize, or approximate the reference unless explicitly requested.

---

# Secondary Instruction

Preserve all unrelated visual attributes from the Base Image.

---

# Stage-specific Restrictions

- Do not transfer facial identity, hairstyle, facial expression, body characteristics, lower body pose, wearable wardrobe, props, environment, camera, lighting, or rendering style from the Reference Image.
- Preserve the established character identity, canonical body, lower body pose, wearable wardrobe, props, environment, camera, lighting, and rendering style from the Base Image.
- Preserve the established lower body pose, including pelvis orientation, leg position, foot placement, weight distribution, balance, and stance.
- Preserve all established handheld and equipped props, adapting the transferred upper body pose naturally to support them.
- Generate only the minimum necessary upper-body articulation required to reproduce the transferred pose naturally.
- Minor adjustments to clothing, accessories, props, hair, or object attachment are permitted only when required to maintain realistic physical interaction with the transferred upper body pose.
- Maintain anatomical consistency, realistic balance, and natural integration between the transferred upper body pose and the preserved lower body pose.

---

# Output Constraint

The output should appear identical to the Base Image, with only the character's upper body pose transferred from the Reference Image.

Apply only the minimum necessary modifications required to complete the requested edit.

Generate a natural, visually coherent, and anatomically consistent result.