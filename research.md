---
layout: page
title: Research
permalink: /research/
---

## AIRHILT: Human‑in‑the‑Loop Multimodal Testbed  {#airhilt}
A modular **Godot + FastAPI** simulation environment with plug‑and‑play components for **ASR**, **vision**, **decision**, and **TTS** over REST/JSON. Supports **pilot/ATC‑in‑the‑loop** trials and a scripted scenario suite (terminal & en‑route conflicts) for reproducible evaluation of intelligent‑system architectures.

**Status:** IEEE ICRA — *in submission*.  
**Artifacts:** Code (coming soon) · Video (coming soon)

---

## SimuGAN–Whisper–ATC  {#simugan-whisper-atc}
**AIAA SciTech — accepted abstract**  
We introduce a **GAN‑based radio‑noise injection** pipeline that learns realistic VHF artifacts from **ATCO2** and **TartanAviation** and injects them into clean **ATCOSIM** utterances. Fine‑tuning Whisper on the enriched dataset reduces WER on real ATC speech from **14.66% → 3.58%** (≈**75.6%** relative reduction), moving toward deployable ASR for safety‑critical ATC workflows.

- [Abstract PDF](/assets/papers/simugan_whisper_atc.pdf) · Code (coming soon)

---

## Multimodal Metadata Tagging for Engineering Simulation Repositories  {#metadata-extraction}
**AIAA SciTech — accepted abstract**  
A **multimodal, ontology‑guided metadata** pipeline for engineering reports: OCR + VLM captions + text chunks → vector DB → **RAG** with an LLM to produce structured JSON metadata aligned with an engineering ontology. Initial results show **high recall** across categories and a working **faceted search** demonstrator.

- [Abstract PDF](/assets/papers/multimodal_extraction.pdf) · Code (coming soon)
