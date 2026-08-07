---
layout: paper
title: Generative AI for Classification, Prediction, and Discovery of Consumer Product Recalls
image: /images/papers/2026-JCISE-bolanos-recalls.png
authors: Bolaños D, Ataei M, Grandi D, and Goucher-Lambert K.
year: 2026
ref: Bolaños et al. <i>ASME J. Comput. Inf. Sci. Eng. </i> 2026
journal: Journal of Computing and Information Science in Engineering
pdf: /pdfs/papers/bolanos-recalls-jcise.pdf
doi: https://doi.org/10.1115/1.4072427
---

# Abstract
Historical information offers valuable insights throughout product development, and recalled products in particular reveal potential design risks, yet they remain underutilized. We curate RECALL-MM, a multimodal dataset from the US Consumer Product Safety Commission (CPSC) recall database, augmented using generative methods. First, we employ generative artificial intelligence (GenAI) to classify hazards from textual descriptors; using GPT-4o, we achieve a relaxed accuracy of 0.73 against reference hazard labels. Second, we benchmark five state-of-the-art vision–language models (VLMs) on hazard prediction from product images, where Top-1 accuracy ranges from 23–40% and Top-3 reaches 67% with GPT-5. Although classical retrieval baselines (Sentence-BERT and ResNet50 nearest-neighbors) exceed VLM accuracy, the foundation models still identify the correct hazard among three plausible guesses well above chance, zero-shot, from a single image. The near-equivalence of image-feature and LLM-distilled text retrieval suggests that visual interpretation carries most of the predictive signal, motivating continued development of flexible multimodal models. To complement these metrics, we apply an LLM-as-Judge framework that scores long-form predictions on a two-axis rubric, highlighting GenAI strengths and challenges in capturing hazard mechanisms and modalities. Finally, two application studies present interactive clustering maps that embed all recalls into a shared latent space to support hazard discovery. Together, these studies show how computational and GenAI-driven methods can leverage recall archives to classify, predict, and discover hazards, ultimately supporting risk-informed tools in early-stage engineering design.
