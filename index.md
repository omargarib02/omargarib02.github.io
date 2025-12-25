---
layout: single
title: "About"
author_profile: true

# Featured research cards
research_cards:
  - image_path: /assets/img/research/airhilt_scenarios.png
    alt: "AIRHILT aviation testbed scenarios"
    title: "AIRHILT Aviation Testbed"
    excerpt: "Multimodal pilot/ATC simulation for human-in-the-loop conflict detection and safe handover."
    url: /research/#airhilt
    btn_label: "Read more"
    btn_class: "btn--primary"

  - image_path: /assets/img/research/simugan_spectrogram.png
    alt: "VHF-Sim2Real spectrogram comparison"
    title: "VHF-Sim2Real"
    excerpt: "GAN-based sim-to-real noise modeling for ATC ASR (WER 14.3% → 3.6% on real ATC audio)."
    url: /research/#vhf-sim2real
    btn_label: "Read more"
    btn_class: "btn--primary"

  - image_path: /assets/img/research/metadata_pipeline.png
    alt: "Multimodal metadata tagging pipeline"
    title: "Multimodal Metadata Tagging"
    excerpt: "VLM + RAG to recover structured metadata from engineering reports."
    url: /research/#multimodal-metadata-tagging
    btn_label: "Read more"
    btn_class: "btn--primary"
---

Hi, I'm **Omar**. I am a **Graduate Researcher** in Computational Science & Engineering at **Georgia Tech**, working with the Aerospace Systems Design Lab (ASDL).

My goal is to build **reliable embodied AI** for **safety-critical autonomy**, especially in settings where people stay in the loop and the system must communicate uncertainty clearly.

Recently, I’ve been building a human-in-the-loop aviation testbed (AIRHILT), developing sim-to-real methods for robust air-traffic-control speech recognition (VHF-Sim2Real), and working on multimodal information extraction and preference-aware assistive AI.

**Personal:** When I'm not debugging simulation pipelines or reading papers, I enjoy playing **soccer** and competing in **FIFA** on PlayStation.

## Research Interests

I work on **reliable embodied AI** for **safety-critical autonomy**, with an emphasis on systems that collaborate with people. I’m especially interested in:

*   **Decision-making under uncertainty:** Using POMDP-style formulations and **formal safety** so an assistant acts conservatively when perception is noisy.
*   **Human-Robot Interaction (HRI):** **Representation alignment** and preference-aware assistance, knowing when to act, ask, or defer.
*   **Vision-Language-Action (VLA):** Grounding language in perception and control for **shared autonomy**.

## News

*   **Feb 2026:** Incoming Visiting Researcher at **MBZUAI** (Robotics Cognition and Learning Group).
*   **Nov 2025:** AIRHILT preprint posted on arXiv; paper under review. [PDF](https://arxiv.org/pdf/2511.18718)
*   **Oct 2025:** Started a Human-AI Interaction collaboration with **Albert Einstein College of Medicine** (150-participant study).
*   **Aug 2025:** Two papers accepted at **AIAA SciTech Forum 2026**.
*   **May 2025:** Began research collaboration with **NASA Langley** (Digital Transformation Initiative).

## Featured Research
{% include feature_row id="research_cards" %}