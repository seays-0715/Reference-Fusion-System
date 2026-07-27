# Best Practices

## Reference Images

- Use **high-resolution** references whenever possible
- Prefer references with **similar camera angle** to your current Master
- Prefer references with **similar focal length** (e.g. both ~85mm)
- Identity and Body references work best under **neutral lighting**
- One clear responsibility per reference — do not use a full fashion editorial as both pose + outfit + lighting reference

## Workflow Discipline

- Always feed the previous Master as **Image 1**
- New reference = **Image 2**
- Save every intermediate Master with the suggested filename
- If identity drifts, stop and run Face Lock before continuing
- Do not skip early stages when starting a new character

## Model Usage

- Stronger reference weight / higher influence on early stages (Identity, Face Lock, Body)
- Slightly lower influence on later aesthetic stages if the model over-styles
- Keep seed consistent across a chain when the model supports it

## Quality Checks After Each Step

| After Step | Check |
|------------|-------|
| Identity | Is this clearly the same person? |
| Face Lock | Did the face return to Identity_Master? |
| Body | Did proportions change while face stayed the same? |
| Pose | Is the skeleton correct without identity bleed? |
| Outfit | Is clothing accurate without face/body change? |
| Scene | Is the character still intact inside the new environment? |

## What to Avoid

- Mixing too many references in one step
- Using low-quality or heavily filtered identity references
- Changing multiple attributes at once
- Ignoring face drift and continuing downstream
