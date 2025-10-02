---
layout: page
title: Research
permalink: /research/
---

## AIRHILT: Human-in-the-Loop Multimodal Testbed  {#airhilt}
Modular **Godot + FastAPI** simulation environment with plug-and-play ASR (automatic speech recognition), visual detection, decision, and TTS (text-to-speech) via REST/JSON. Supports **pilot/ATC-in-the-loop** trials and a scripted scenario suite (terminal + en-route conflicts) for reproducible experimentation.

**Status:** IEEE ICRA — *in submission*.  
Artifacts: Code (coming soon) · Video (coming soon)

---

## SimuGAN–Whisper–ATC  {#simugan-whisper-atc}
**Abstract (AIAA SciTech – accepted)**  
Air traffic control (ATC) operations are cognitively demanding. We explore robustness improvements to ASR using Whisper by introducing a **GAN-based noise injection pipeline** that learns realistic VHF radio artifacts from **ATCO2** and **TartanAviation** and injects them into clean **ATCOSIM** utterances. Fine-tuning Whisper on this enriched dataset reduces WER on real ATC speech from **14.66%** (prior baseline) to **3.58%**, suggesting a promising path toward deployable ASR for safety-critical ATC workflows.

- [Abstract PDF](/assets/papers/simugan_whisper_atc_abstract.pdf) · Code (coming soon)

---

## Multimodal Document Extraction for Simulation Repositories  {#metadata-extraction}
**Abstract (AIAA SciTech – accepted)**  
We present a **multimodal, LLM-driven metadata tagging framework** for engineering simulation reports. The pipeline integrates OCR and VLM-derived visual captions with textual chunks into a vector database, then applies **RAG with an LLM** to produce structured metadata (JSON) guided by an engineering ontology. Initial experiments on real and synthetic reports demonstrate **high recall** across metadata categories and a working **faceted search** prototype for discoverability.

- [Abstract PDF](/assets/papers/metadata_tagging_abstract.pdf) · Code (coming soon)
