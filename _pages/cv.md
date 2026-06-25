---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D. in Computer Science, **Fudan University**, School of Robotics and Advanced Manufacturing, 2026.09 – 2029.06 (expected)
* M.S. in Biomedical Engineering, **Beijing Institute of Technology**, School of Medical Technology, 2022.09 – 2025.09
* B.S. in Computer Science and Technology, **Beijing Institute of Technology**, Tezhili College, 2018.09 – 2022.06

Research Interests
======
Multimodal models and visual generation systems for real-world applications, including controllable & structure-preserving modeling, complex task decomposition, and unified understanding-and-generation.

Experience
======
* **Meituan**, LongCat Foundation Model Group — LongCat-Next Pre-training, 2026.06 – present
  * Building image-text interleaved agents and constructing multimodal chain-of-thought data to equip the unified multimodal model (LongCat-Next) with higher-order generation ability.

* **Kuaishou**, Kolors Foundation Model Group — Image Editing & Generation, 2025.09 – 2026.06
  * Research on image material editing, image editing agents, and text-to-image generation, focusing on controllable editing and system efficiency of visual generation in complex real-world settings.

* **Qiyuan Lab**, Multimodal LLM — Think with Images, 2025.02 – 2025.05
  * Explored an O3-style dynamic zoom mechanism in MLLMs for fine-grained perception, improving the model's perception and use of local key information in complex visual scenes.

* **Baidu**, Computer Vision Department — Intelligent Poster Design with MLLM, 2024.04 – 2024.12
  * Developed and deployed MLLM-based layout design algorithms for intelligent poster generation. Related work published at **ICCV 2025 (Highlight)**.

* **Microsoft Research Asia**, Image Inpainting, 2022.12 – 2023.08
  * Research and deployment on image inpainting, targeting real-world image cleanup and completion. Related work published in **Pattern Recognition**.

Skills
======
* Visual generation: diffusion models, text-to-image / image editing, texture editing
* Multimodal large models: MLLM fine-tuning, RLHF, RAG, chain-of-thought, agentic execution
* Deep learning engineering: PyTorch, large-scale training & inference
* Tooling: Python, ffmpeg-based video pipelines, LaTeX

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Awards
======
* National Mathematics Competition for College Students, Second Prize (National), 2021.11
* WeChat Mini-Program Design Competition, Third Prize (Provincial), 2020.10
* Beijing College Student Physics Competition, Second Prize (Provincial), 2019.11
