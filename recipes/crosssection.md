# Cross-section — electric motor

**Command:** `/crosssection`

## What it does

One cutting plane. Interior on the cut face, exterior on the far side.

## Works best for

Engines, motors, batteries, fruit, planets, pipes.

## Quick prompt

```text
/crosssection electric motor
```

`/crosssection` is shorthand. If the model ignores the slash token, use the expanded prompt.

## Better prompt

```text
Create a technical cross-section of a small industrial electric motor.

One vertical cutting plane through the axis. Show stator, rotor, windings, shaft, bearings, housing.
Cut face in true materials; uncut side remains intact.
Neutral studio background, 16:9, sparse labels only if they stay readable.
Not an exploded view. Not a four-panel diagram.
```

## Tested

Pending — generate the same expanded prompt on ChatGPT Images, Gemini, and Grok, then drop files in `examples/crosssection/` and date this section. Do not mark a model as working until then.

## Related

- `/cutaway`
- `/xray`
- `/schematic`
