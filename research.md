---
layout: single
title: Research
permalink: /research/
---

## Human‑in‑the‑Loop Multimodal Aviation Testbed  {#aviation-testbed}
A modular **Godot + FastAPI** simulation environment with plug‑and‑play components for **automatic speech recognition (ASR)**, **vision**, **decision**, and **text‑to‑speech (TTS)** over REST/JSON. Supports **pilot/****air traffic control**‑in‑the‑loop trials and a scripted scenario suite (terminal & en‑route conflicts) for reproducible evaluation of intelligent‑system architectures.

**Status:** *in submission*.  
**Preprint:** [PDF](assets/papers/aviation_testbed_preprint.pdf)  
**Artifacts:** Code (coming soon) · Video (coming soon)

---

## SimuGAN–Whisper–ATC  {#simugan-whisper-atc}
**AIAA SciTech — accepted abstract**  
We introduce a **generative adversarial network (GAN)**‑based radio‑noise injection pipeline that learns realistic **very‑high‑frequency (VHF)** artifacts from **ATCO2** and **TartanAviation** and injects them into clean **ATCOSIM** utterances. Fine‑tuning Whisper on the enriched dataset reduces **word‑error‑rate (WER)** on real **air traffic control** speech from **14.66% → 3.58%** (≈**75.6%** relative reduction), moving toward deployable ASR for safety‑critical **air traffic control** workflows.

- [Abstract PDF](assets/papers/simugan_whisper_atc.pdf) · Code (coming soon)

---

## Multimodal Metadata Tagging for Engineering Simulation Repositories  {#metadata-extraction}
**AIAA SciTech — accepted abstract**  
A **multimodal, ontology‑guided metadata** pipeline for engineering reports: OCR + **vision‑language model (VLM)** captions + text chunks → vector DB → **retrieval‑augmented generation (RAG)** with an LLM to produce structured JSON metadata aligned with an engineering ontology. Initial results show **high recall** across categories and a working **faceted search** demonstrator.

- [Abstract PDF](assets/papers/multimodal_extraction.pdf) · Code (coming soon)

---

## Right‑Moment AI Companion for Older Adults (Work‑In‑Progress)  {#ai-companion}
**Goal.** Support older adults living alone with a **personalized AI companion** that **intervenes only at the right moments**—helpful, not intrusive.
