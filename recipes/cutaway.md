# Cutaway — two-story house

**Command:** `/cutaway`

## What it does

Removes part of the exterior so rooms and structure read as one scene (not a four-panel collage).

## Works best for

Buildings, vehicles, ships, appliances. Ask for a single camera, not a grid of panels.

## Quick prompt

```text
/cutaway two-story house
single camera, one scene
not a four-panel grid
```

`/cutaway` is shorthand. If the model ignores the slash token, use the expanded prompt.

## Better prompt

```text
Create a single-scene architectural cutaway of a two-story house.

One camera, 3/4 view. Cut the near facade away so you see:
- ground-floor living and kitchen
- stairs
- two bedrooms upstairs
- roof structure
- people-scale furniture for size

Photoreal daylight. Keep it ONE image, not four panels, not a dollhouse exploded into a grid. 16:9.
```

## Tested

Pending — generate the same expanded prompt on ChatGPT, Gemini, Grok, and Microsoft AI (MAI Playground chat), then drop files in `examples/cutaway/` and date this section. Do not mark a model as working until then.

## Related

- `/xray`
- `/crosssection`
- `/architecture`
