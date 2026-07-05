---
"gradio": patch
---

fix:Warn when a non-empty `value` is passed to `gr.Textbox(type="password")`, since the value is serialized into the client config in cleartext and the `password` type only masks it visually.