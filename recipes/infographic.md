# Infographic — how HTTPS works

**Command:** `/infographic`

## What it does

Explains a process with a few locked-in panels and almost no paragraph text.

## Works best for

Protocols, recipes, comparisons, how-X-works for developers.

## Quick prompt

```text
/infographic how HTTPS works
```

`/infographic` is shorthand. If the model ignores the slash token, use the expanded prompt.

## Better prompt

```text
Create a clean infographic: How HTTPS works, for developers.

Four or five steps max: DNS, TCP, TLS handshake, encrypted HTTP.
Flat vector, limited palette, large readable labels, 16:9.
No tiny paragraph walls. No fake browser chrome clutter.
Dark or light — pick one and stay consistent.
```

## Style demo

`examples/infographic/before.png` → `demo.png` (look of this recipe). Not a dated ChatGPT / Gemini / Grok / MAI bake-off.

## Tested

Pending — generate the same expanded prompt on ChatGPT, Gemini, Grok, and Microsoft AI (MAI Playground chat), then drop `chatgpt.png` / `gemini.png` / `grok.png` / `mai.png` in `examples/infographic/` and date this section. Do not mark a model as working until then.

## Related

- `/processdiagram`
- `/flowchart`
- `/architecture`
