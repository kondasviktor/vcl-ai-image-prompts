# Exploded view — Apple MacBook

**Command:** `/explodedview` (viral alias: `/explode`)

## What it does

Separates components along a shared axis so you can see how the product is built. Roundups often write this as `/explode` — same idea.

## Works best for

Laptops, cameras, appliances, furniture, toys.

## Quick prompt

```text
/explodedview Apple MacBook
```

`/explodedview` is shorthand. If the model ignores the slash token, use the expanded prompt.

## Better prompt

```text
Create an exploded-view technical illustration of an Apple MacBook.

Separate along a vertical axis:
- lid / display assembly
- keyboard deck
- battery
- logic board
- speakers
- trackpad
- bottom case
- screws as small callouts (optional)

Studio lighting, dark background, photoreal materials, even spacing between parts, 16:9.
No people. No extra logos besides a tasteful Apple-like mark if needed for recognition.
```

## Style demo

`examples/explodedview/before.png` → `demo.png` (look of this recipe). Not a dated ChatGPT / Gemini / Grok / MAI bake-off.

## Tested

Pending — generate the same expanded prompt on ChatGPT, Gemini, Grok, and Microsoft AI (MAI Playground chat), then drop `chatgpt.png` / `gemini.png` / `grok.png` / `mai.png` in `examples/explodedview/` and date this section. Do not mark a model as working until then.

## Related

- `/xray`
- `/cutaway`
- `/assembly`
