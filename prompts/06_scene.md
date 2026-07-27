# STEP 06 — Scene Fusion

**Purpose**  
Place the locked character into a new environment.

**Input / Output**

```
[Fashion_Master]  +  [Scene Reference]
              ↓
        Scene_Master_v1
```

| Image | Role |
|-------|------|
| Image 1 | Fashion_Master (Character Reference) |
| Image 2 | Scene Reference |

**Prompt**

```
# Goal

Place the character into the environment from Image 2.

# Reference Assignment

Image 1:
Character Reference.

Image 2:
Scene Reference.

# Apply

Transfer:
- location
- background
- atmosphere
- environment style

# Preserve

Keep unchanged:
- identity
- face
- hairstyle
- outfit
- pose

# Integration

Match:
- lighting direction
- color temperature
- realistic shadows
- reflections
- depth relationship

Create seamless environment integration.

# Output

Professional fashion photography.

Save:
Scene_Master_v1
```
