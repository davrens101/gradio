---
"gradio": patch
---

fix:Fix `HighlightedText.preprocess()` return type to match documented `list[tuple[str, str | float | None]]` signature and enable round-tripping with `postprocess()`
