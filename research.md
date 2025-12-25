---
title: "Research"
permalink: /research/
layout: single
author_profile: true
---

My work focuses on reliable embodied AI for safety-critical autonomy, especially human-in-the-loop settings where the system must reason under uncertainty and coordinate with people.

## AIRHILT

A modular Godot + FastAPI simulation environment that synchronizes stochastic pilot speech, vision streams, and ADS-B telemetry to model information asymmetry in pilot and air traffic control interactions.

- **Architecture:** Architected a modular simulation environment (Godot/FastAPI) that synchronizes stochastic pilot speech, vision streams, and ADS-B telemetry for human-in-the-loop evaluation.
- **Decision logic:** Designed a confidence-gated decision logic that fuses uncertain perception, including a probabilistic evidence score that weights conflicting sensor inputs and triggers clarification requests under high uncertainty.
- **Validation:** Engineered a verification protocol using 6 conflict families (e.g., runway overlaps) and quantified how ASR and vision latency propagate into pilot warning time, achieving about a 7.7 s lead-time baseline for safe human-AI handover.

**Status:** Under review.  
**Preprint:** [arXiv](https://arxiv.org/abs/2511.18718) | [PDF](https://arxiv.org/pdf/2511.18718)

* * *

## VHF-Sim2Real

**AIAA SciTech Forum 2026, accepted.**

We develop an unpaired spectrogram-translation GAN to bridge the sim-to-real gap by adapting synthetic clear speech to match the texture of operational very high frequency (VHF) radio interference without paired data. Fine-tuning Whisper on the GAN-augmented dataset reduces word error rate (WER) on out-of-distribution real-world air traffic data by 75.0% (14.3% to 3.6%).

**Paper:** [PDF](/assets/papers/simugan_whisper_atc.pdf)

* * *

## Multimodal Metadata Tagging

**AIAA SciTech Forum 2026, accepted.**

Co-first author of a framework that fuses OCR, vision-language embeddings, and LLM-driven reasoning to autonomously recover semantic structure from unstructured engineering reports. The pipeline combines OCR text and vision-language captions with retrieval-augmented generation to produce structured JSON metadata aligned with an engineering ontology. Designed synthetic text-and-figure datasets and a multi-label benchmarking protocol to evaluate tag precision, recall, and F1 across engineering metadata categories.

**Paper:** [PDF](/assets/papers/multimodal_extraction.pdf)

* * *

## Preference-Aware Shared Autonomy for Assistive AI

**Work in progress.**

- Leading a user study with 150 older adults to model user preferences and reluctance toward AI assistance (Collaboration with Albert Einstein College of Medicine).
- Developing partially observable decision policies that balance safety interventions with user autonomy and daily routines, using learned preference and reluctance models to decide when to act versus when to defer.