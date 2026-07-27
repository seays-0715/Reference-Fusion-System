# Limitations

This workflow improves consistency. It does **not** create magic.

## What RFW cannot guarantee

- Perfect identity preservation on every model and every seed
- Exact 1:1 clothing reproduction (especially complex patterns or logos)
- Exact hand and finger poses
- Exact camera angle matching between references
- Perfect anatomy in extreme poses
- Zero style bleed from strong aesthetic references

## What performance depends on

- Capability of the underlying image model
- Quality and clarity of your reference images
- How strongly the model respects reference weighting
- Consistency of camera angle / lighting between references

## Honest Expectations

RFW is a **process framework**, not a model.  
It reduces the chance of common failure modes by isolating responsibilities.  
It cannot overcome fundamental limitations of the image generator you are using.

If a model is weak at multi-reference control, RFW will still help, but results will be limited by the model.
