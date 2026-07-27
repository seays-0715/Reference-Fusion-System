# STEP 02 — Face Lock

**Purpose**  
Restore and strictly lock facial identity when drift occurs.

**Input / Output**

```
[Current Character]  +  [Identity_Master]
              ↓
    Face_Locked_Master_v1
```

| Image | Role |
|-------|------|
| Image 1 | Current Character (may have drift) |
| Image 2 | Identity_Master (true face reference) |

**Prompt**

```
# Goal

Restore and strictly lock the original facial identity.

# Reference Assignment

Image 1:
Current character that may have identity drift.

Image 2:
Identity_Master true face reference.

# Priority

Highest priority:
Exact facial identity match.

# Preserve

Match exactly:
- eye shape and color
- eyebrows
- nose structure
- lips shape and fullness
- jawline
- face shape
- hairstyle
- hair details
- skin tone

# Restrictions

Do not change:
- body
- pose
- outfit
- background

Do not redesign anything except correcting facial identity.
Do not create a different person.

# Output

Same person with restored facial identity.
Natural realistic appearance.
Photorealistic.

Save:
Face_Locked_Master_v1
```
