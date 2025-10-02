---
layout: single
title: ""
author_profile: true

# Featured research cards (AIRHILT → SimuGAN → Metadata)
research_cards:
  - image_path: /assets/img/research/airhilt_scenarios.png
    alt: "AIRHILT scenario montage"
    title: "AIRHILT testbed"
    excerpt: "Open simulation for pilot/air traffic control-in-the-loop evaluation."
    url: /research/#airhilt
    btn_label: "Read more"
    btn_class: "btn--primary"
  - image_path: /assets/img/research/simugan_spectrogram.png
    alt: "Spectrogram comparison (SimuGAN‑Whisper‑ATC)"
    title: "SimuGAN‑Whisper‑ATC"
    excerpt: "GAN-based noise modeling for ATC audio; robust Whisper fine‑tuning."
    url: /research/#simugan-whisper-atc
    btn_label: "Read more"
    btn_class: "btn--primary"
  - image_path: /assets/img/research/metadata_pipeline.png
    alt: "Multimodal metadata pipeline"
    title: "Multimodal metadata tagging"
    excerpt: "OCR + VLM + RAG to structure engineering knowledge."
    url: /research/#metadata-extraction
    btn_label: "Read more"
    btn_class: "btn--primary"

# Sidebar content (appears under the author card)
sidebar:
  - title: "News"
    text: |
      <ul class="news">
        <li><strong>September 2025</strong> — Began research effort on designing an effective, personalized AI companion for the elderly.</li>
        <li><strong>September 2025</strong> — Submitted <strong>AIRHILT</strong> to ICRA.</li>
        <li><strong>August 2025</strong> — Two <strong>AIAA SciTech</strong> abstracts accepted.</li>
        <li><strong>May 2025</strong> — Began research collaboration with <strong>NASA Langley</strong> (Digital Transformation).</li>
      </ul>
---

**I’m an MS student in Computational Science & Engineering at Georgia Tech** (Aerospace Systems Design Lab, ASDL).

I build **multimodal, human‑in‑the‑loop intelligent systems** for safety‑critical autonomy, combining **speech**, **vision**, and **3D spatial reasoning**, and I also develop **automated document/knowledge‑extraction pipelines**.

My research interests center on **human–AI/robot collaboration**: social and assistive robotics, **human‑aware** timing and intent inference, and perception‑driven decision‑making that people can trust—especially in high‑stakes settings.

### Highlights
- **AIRHILT** — an open simulation testbed for **multimodal AI copilots in aviation**. Models for ASR/vision/decision/TTS plug in via lightweight adapters, making it easy to swap architectures and **run hundreds of scripted terminal/en‑route scenarios** to measure assistant performance and ablations.
- **SimuGAN‑Whisper‑ATC** — a **GAN‑based noise‑modeling pipeline** that captures air‑traffic‑control radio artifacts and **injects them during Whisper fine‑tuning**, yielding a **WER drop from 14.66 → 3.58** on real ATC audio.
- **LLM/RAG document extraction** — multimodal mining of engineering **artifacts** for **metadata & discovery**.

### Featured research
{% include feature_row id="research_cards" %}
  
<!-- Blank line above and below ensures the following Markdown is parsed correctly -->

### Selected coursework

| Course | Instructor |
|---|---|
| CS 6476 **Computer Vision** | Humphrey Shi |
| CS 7650 **Natural Language Processing** | Alan Ritter |
| CS 8803 **Deep Reinforcement Learning** | Sehoon Ha |
| CSE 6740 **Machine Learning** | — |
| CSE 6643 **Numerical Linear Algebra** | — |
| CSE 6140 **Algorithms** | — |
| CSE 6730 **Modeling & Simulation** | — |
