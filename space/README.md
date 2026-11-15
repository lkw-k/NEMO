---
title: kcbert-NEMO
colorFrom: gray
colorTo: red
sdk: static
app_file: index.html
pinned: false
license: cc-by-nc-4.0
models:
- illimax/kcbert-NEMO
short_description: Korean offensive text classifier
---

# kcbert-NEMO

Type a Korean sentence and the model tells you whether it is clean or offensive.

Model card: [illimax/kcbert-NEMO](https://huggingface.co/illimax/kcbert-NEMO)

The model runs in your browser with transformers.js, using the 8-bit quantized ONNX weights (about 110MB, downloaded once).
Your text is not sent to a server.

The model was trained on only about 15,000 sentences, so it can make mistakes.
It works for Korean only and does not detect English swear words.

"Offensive" here includes swear words, insults, and hate speech.
Input is cut at 128 tokens.
