# STEP 04 — Pose Fusion

**Purpose**  
Transfer pose while preserving identity and body proportions.

**Input / Output**

```
[Body_Master]  +  [Pose Reference]
            ↓
      Pose_Master_v1
```

| Image | Role |
|-------|------|
| Image 1 | Body_Master (Character Reference) |
| Image 2 | Pose Reference |

**Prompt**

```
# Goal

Transfer the pose from Image 2 onto the character in Image 1.

# Reference Assignment

Image 1:
Character Reference.

Image 2:
Pose Reference.

# Apply only:

- body position
- arm position
- hand placement
- leg position
- head angle
- body orientation

# Preserve

Keep:
- face
- hairstyle
- body proportions
- identity

# Restrictions

Do not copy Image 2 identity.
Do not copy Image 2 face.
Do not change the character.

Maintain realistic body mechanics.
Maintain natural gravity and weight distribution.

# Output

Same person with the new pose.
Professional fashion photography.

Save:
Pose_Master_v1
```
