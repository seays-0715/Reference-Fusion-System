# STEP 03 — Body Fusion

**Purpose**  
Apply body proportions while keeping identity locked.

**Input / Output**

```
[Current Character Identity]  +  [Body Reference]
                  ↓
            Body_Master_v1
```

| Image | Role |
|-------|------|
| Image 1 | Current Character Identity |
| Image 2 | Body Proportion Reference |

**Prompt**

```
# Goal

Apply the body proportions from Image 2 to the character in Image 1.

The face and identity must remain from Image 1.

# Reference Assignment

Image 1:
Current Character Identity Reference.

Image 2:
Body Proportion Reference.

Use Image 2 only for:
- body silhouette
- height impression
- body proportions
- shoulder width
- waist proportion
- leg length
- overall physical balance

# Preserve

Keep exactly:
- face
- hairstyle
- identity
- skin tone

# Restrictions

Do not copy Image 2 face.
Do not copy Image 2 identity.
Do not blend faces.
Do not change facial structure.

Maintain realistic anatomy.
Maintain harmonious body-face ratio.

# Output

Create one natural realistic person.
Photorealistic full body image.

Save:
Body_Master_v1
```
