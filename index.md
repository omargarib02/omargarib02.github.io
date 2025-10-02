---
layout: single
title: ""
author_profile: true
classes: wide
---

<!--
Three columns total:
- Left column is the theme sidebar (author_profile + News) – handled via _config.yml defaults
- Center and Right columns are created below with a safe Flexbox container
-->

<div class="content-columns" style="display:flex;gap:2rem;align-items:flex-start;flex-wrap:nowrap;">
  <!-- Column 2 (center) : About + Highlights -->
  <div class="content-columns__main" style="flex:0 1 64%;min-width:520px;">
    <h2>About</h2>
    <p><strong>I'm an MS student in Computational Science & Engineering at Georgia Tech</strong> (Aerospace Systems Design Lab, ASDL).</p>

    <p>I build <strong>multimodal, human-in-the-loop intelligent systems</strong> for safety-critical autonomy, combining <strong>speech</strong>, <strong>vision</strong>, and <strong>3D spatial reasoning</strong>, and I also develop <strong>automated document/knowledge-extraction pipelines</strong>.</p>

    <p>My research interests center on <strong>human–AI/robot collaboration</strong>: social and assistive robotics, <strong>human-aware</strong> timing and intent inference, and perception-driven decision-making that people can trust—especially in high-stakes settings.</p>

    <h3>Highlights</h3>
    <ul>
      <li><strong>AIRHILT</strong> — an open simulation testbed for <strong>multimodal AI copilots in aviation</strong>. Models for ASR/vision/decision/TTS plug in via lightweight adapters, making it easy to swap architectures and <strong>run hundreds of scripted terminal/en-route scenarios</strong> to measure assistant performance and ablations.</li>
      <li><strong>SimuGAN-Whisper-ATC</strong> — a <strong>GAN-based noise-modeling pipeline</strong> that captures air-traffic-control radio artifacts and <strong>injects them during Whisper fine-tuning</strong>, yielding a <strong>WER drop from 14.66 → 3.58</strong> on real ATC audio.</li>
      <li><strong>LLM/RAG document extraction</strong> — multimodal mining of engineering <strong>artifacts</strong> for <strong>metadata & discovery</strong>.</li>
    </ul>
  </div>

  <!-- Column 3 (right) : Featured Research + Coursework -->
  <aside class="content-columns__aside" style="flex:0 0 34%;min-width:300px;">
    <h2>Featured Research</h2>

    <div class="research-cards">
      <div class="research-card">
        <img src="/assets/img/research/airhilt_scenarios.png" alt="AIRHILT scenario montage">
        <h4>AIRHILT testbed</h4>
        <p>Open simulation for pilot/air traffic control-in-the-loop evaluation.</p>
        <a href="/research/#airhilt" class="btn btn--primary">Read more</a>
      </div>

      <div class="research-card">
        <img src="/assets/img/research/simugan_spectrogram.png" alt="Spectrogram comparison">
        <h4>SimuGAN-Whisper-ATC</h4>
        <p>GAN-based noise modeling for ATC audio; robust Whisper fine-tuning.</p>
        <a href="/research/#simugan-whisper-atc" class="btn btn--primary">Read more</a>
      </div>

      <div class="research-card">
        <img src="/assets/img/research/metadata_pipeline.png" alt="Multimodal metadata pipeline">
        <h4>Multimodal metadata tagging</h4>
        <p>OCR + VLM + RAG to structure engineering knowledge.</p>
        <a href="/research/#metadata-extraction" class="btn btn--primary">Read more</a>
      </div>
    </div>

    <h3>Selected Coursework</h3>
    <table>
      <thead>
        <tr>
          <th>Course</th>
          <th>Instructor</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>CS 6476 <strong>Computer Vision</strong></td>
          <td>Humphrey Shi</td>
        </tr>
        <tr>
          <td>CS 7650 <strong>Natural Language Processing</strong></td>
          <td>Alan Ritter</td>
        </tr>
        <tr>
          <td>CS 8803 <strong>Deep Reinforcement Learning</strong></td>
          <td>Sehoon Ha</td>
        </tr>
        <tr>
          <td>CSE 6740 <strong>Machine Learning</strong></td>
          <td>—</td>
        </tr>
        <tr>
          <td>CSE 6643 <strong>Numerical Linear Algebra</strong></td>
          <td>—</td>
        </tr>
        <tr>
          <td>CSE 6140 <strong>Algorithms</strong></td>
          <td>—</td>
        </tr>
        <tr>
          <td>CSE 6730 <strong>Modeling & Simulation</strong></td>
          <td>—</td>
        </tr>
      </tbody>
    </table>
  </aside>
</div>
