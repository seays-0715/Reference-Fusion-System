# STEP 05 — Outfit Fusion

**Purpose**  
Transfer clothing while locking face, body, and pose.

**Input / Output**

```
[Pose_Master]  +  [Outfit Reference]
            ↓
      Fashion_Master_v1
```

| Image | Role |
|-------|------|
| Image 1 | Pose_Master (Character Reference) |
| Image 2 | Outfit Reference |

**Prompt**

```
# Goal

Apply the outfit from Image 2 to the character in Image 1.

# Reference Assignment

Image 1:
Character Reference.

Image 2:
Outfit Reference.

# Apply

Transfer:
- clothing design
- fabric
- color
- texture
- patterns
- accessories
- shoes

# Preserve

Keep unchanged:
- face
- hairstyle
- identity
- body proportions
- pose

# Restrictions

Do not redesign the outfit.
Do not change body proportions.
Do not alter the character.

# Quality

Realistic fabric behavior.
Natural wrinkles and tension.
Fabric follows body movement and gravity naturally.
Correct clothing fit.
Photorealistic fashion image.

Save:
Fashion_Master_v1
```
