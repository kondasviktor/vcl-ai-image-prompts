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

## Style demo

`examples/crosssection/before.png` → `demo.png` (look of this recipe). Not a dated ChatGPT / Gemini / Grok / MAI bake-off.

## Tested

Pending — generate the same expanded prompt on ChatGPT, Gemini, Grok, and Microsoft AI (MAI Playground chat), then drop `chatgpt.png` / `gemini.png` / `grok.png` / `mai.png` in `examples/crosssection/` and date this section. Do not mark a model as working until then.

## Related

- `/cutaway`
- `/xray`
- `/schematic`
