# Poster — AI conference one-sheet

**Command:** `/poster`

## What it does

Turns the subject into a theatrical print poster: big title, one hero subject, clear hierarchy, poster margins.

## Works best for

Events, product launches, indie SaaS announcements, film-style one-sheets.

## Quick prompt

```text
/poster "VIBE CODING SUMMIT 2026"
dark background, neon green accent
one hero laptop silhouette
bold sans title top third
minimal Swiss layout
16:9
```

`/poster` is shorthand. If the chat ignores the slash token, use the expanded prompt.

## Better prompt

```text
Create a theatrical conference poster.

Title text exactly: "VIBE CODING SUMMIT 2026"
Layout: bold title in the top third, one large hero subject (laptop with soft neon rim light), lots of negative space, Swiss / Bauhaus restraint.
Colors: near-black background, #7fff6e accent, white secondary type.
No tiny unreadable paragraphs. No fake QR codes. No watermarks. 16:9.
```

## Style demo

`examples/poster/before.png` → `demo.png` (look of this recipe). Not a dated ChatGPT / Gemini / Grok / MAI bake-off.

## Tested

Pending — generate the same expanded prompt on ChatGPT, Gemini, Grok, and Microsoft AI (MAI Playground chat), then drop `chatgpt.png` / `gemini.png` / `grok.png` / `mai.png` in `examples/poster/` and date this section. Do not mark a model as working until then.

## Related

- `/youtubethumbnail`
- `/ogimage`
- `/landingpage`
