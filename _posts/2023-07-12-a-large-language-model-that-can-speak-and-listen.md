---
permalink: /audio-palm-survey/
# header:
#   overlay_color: "#333"
header:
  image: /assets/images/audio-palm-idea.png
author_profile: true
toc: false
classes: wide
related: false
share: false
# gallery:
#   - url: /assets/images/mlflow.jpg
#     image_path: /assets/images/mlflow.jpg
#     alt: ""
#     title: "MLflow model registry including S3 bucket."
---

AudioPaLM: A Large Language Model That Can Speak and Listen.

This year gave us the breakthrough in large attention-based models. I find that some of them have the greatest potential in the further research. Here I present the survey of the AudioPaLM model.

## The approach

**Multimodal vocabulary**. AudioPaLM is a decoder-only transformer. It processes speech and text tokens without distinguishing the modalities. Its multimodal vocabulary is built in the following way: speech tokens form a finite set and text tokens are based on SentencePiece.

AudioPaLM is finetuned on a mixture of combined speech and text tasks including automatic speech recognition and machine translation.

<br>



