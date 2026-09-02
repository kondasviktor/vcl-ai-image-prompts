# Isometric — espresso machine

**Command:** `/isometric`

## What it does

30-degree isometric, equal scale on axes, no vanishing-point drama.

## Works best for

Products, rooms, cities, UI-as-isometric, board games.

## Quick prompt

```text
/isometric espresso machine
```

`/isometric` is shorthand. If the model ignores the slash token, use the expanded prompt.

## Better prompt

```text
Create a clean isometric illustration of a prosumer espresso machine.

True isometric (no perspective vanishing). Show portafilter, steam wand, drip tray, buttons.
Soft studio lighting, simple pedestal shadow, 16:9.
Product-design viz, not a cartoon city.
```

## Style demo

`examples/isometric/before.png` → `demo.png` (look of this recipe). Not a dated ChatGPT / Gemini / Grok / MAI bake-off.

## Tested

Pending — generate the same expanded prompt on ChatGPT, Gemini, Grok, and Microsoft AI (MAI Playground chat), then drop `chatgpt.png` / `gemini.png` / `grok.png` / `mai.png` in `examples/isometric/` and date this section. Do not mark a model as working until then.

## Related

- `/explodediso`
- `/productshot`
- `/3drender`
