# YouTube thumbnail — I tested 3 image models

**Command:** `/youtubethumbnail`

## What it does

High-contrast 16:9 thumbnail: huge subject, few words, thumbnail-legible type.

## Works best for

Video titles you will actually publish. Specify the exact 2-5 words on the image.

## Quick prompt

```text
/youtubethumbnail I tested 3 image models
```

`/youtubethumbnail` is shorthand. If the model ignores the slash token, use the expanded prompt.

## Better prompt

```text
Create a YouTube thumbnail, 16:9.

Big readable words: I TESTED 3 IMAGE MODELS
Three small tiles hinting ChatGPT / Gemini / Grok without official logos if that is cleaner.
High contrast, face optional. Not a desktop screenshot. Not a 4K wallpaper.
Leave a little safe margin so YouTube crop does not kill the type.
```

## Tested

Pending — generate the same expanded prompt on ChatGPT Images, Gemini, Grok, and MAI Playground (MAI-Image), then drop files in `examples/youtubethumbnail/` and date this section. Do not mark a model as working until then.

## Related

- `/thumbnail`
- `/adcreative`
- `/ogimage`
