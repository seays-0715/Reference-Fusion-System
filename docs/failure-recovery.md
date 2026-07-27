# Failure Recovery

When something breaks, do **not** restart from scratch.  
Re-run only the responsible step.

## Common Problems

### Face Drift
Symptoms: eyes, nose, jaw, or overall likeness changed.

```
→ Run Face Lock again
  Image 1 = current drifted result
  Image 2 = Identity_Master_v1
```

### Body Proportions Changed
Symptoms: taller/shorter, different shoulder/waist ratio, leg length shifted.

```
→ Run Body Fusion again
  Image 1 = current character (correct face)
  Image 2 = original Body Reference
```

### Pose Collapsed / Unnatural
Symptoms: broken limbs, floating hands, wrong weight distribution.

```
→ Run Pose Fusion again
  Image 1 = Body_Master (or latest good body)
  Image 2 = Pose Reference
```

### Outfit Lost or Distorted
Symptoms: clothing design changed, fabric wrong, accessories missing.

```
→ Run Outfit Fusion again
  Image 1 = Pose_Master (or latest good pose)
  Image 2 = Outfit Reference
```

### Background / Scene Changed Unexpectedly
Symptoms: environment no longer matches the Scene Reference.

```
→ Run Scene Fusion again
  Image 1 = Fashion_Master
  Image 2 = Scene Reference
```

### Lighting Inconsistent
Symptoms: harsh shadows, wrong color temperature, flat look.

```
→ Run Lighting & Mood again
```

### Overall Quality Drop
Symptoms: soft details, bad skin texture, color issues.

```
→ Run Final Polish again
```

## Recovery Principle

Identify the **earliest broken stage** and restart from there.  
Later stages can be re-applied on top of a corrected Master.
