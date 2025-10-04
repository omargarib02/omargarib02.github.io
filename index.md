---
layout: single
title: ""
author_profile: true
classes: wide

# Featured research cards (Aviation testbed → SimuGAN → Metadata)
research_cards:
  - image_path: /assets/img/research/airhilt_scenarios.png
    alt: "Aviation testbed scenario montage"
    title: "Human‑in‑the‑Loop Aviation Testbed"
    excerpt: "Open simulation for pilot/air traffic control‑in‑the‑loop evaluation."
    url: /research/#aviation-testbed
    btn_label: "Read more"
    btn_class: "btn--primary"

  - image_path: /assets/img/research/simugan_spectrogram.png
    alt: "Spectrogram comparison (SimuGAN‑Whisper‑ATC)"
    title: "SimuGAN‑Whisper‑ATC"
    excerpt: "GAN‑based noise modeling for ATC audio; robust Whisper fine‑tuning."
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
---

## About

**I'm an MS student in Computational Science & Engineering at Georgia Tech** (Aerospace Systems Design Lab, ASDL).

I build **multimodal, human‑in‑the‑loop intelligent systems** for safety‑critical autonomy, combining **speech**, **vision**, and **3D spatial reasoning**, and I also develop **automated document/knowledge‑extraction pipelines**.

My research interests center on human–AI/robot collaboration, social and assistive robotics, and building mutlimodal intelligent systems that integrate vision, speech, and spatial reasoning in safety-critical environments.

## Highlights
- **Human‑in‑the‑Loop Aviation Testbed** — an open simulation testbed for **multimodal AI copilots in aviation**. Models for ASR/vision/decision/TTS plug in via lightweight adapters, making it easy to swap architectures and **run hundreds of scripted terminal/en‑route scenarios** to measure assistant performance and ablations.
- **SimuGAN‑Whisper‑ATC** — a **GAN‑based noise‑modeling pipeline** that captures air‑traffic‑control radio artifacts and **injects them during Whisper fine‑tuning**, yielding a **WER drop from 14.66 → 3.58** on real ATC audio.
- **LLM/RAG document extraction** — multimodal mining of engineering **artifacts** for **metadata & discovery**.

## Featured research
{% include feature_row id="research_cards" %}
