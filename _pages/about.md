---
layout: archive
title: "About"
permalink: /
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

{% include base_path %}

<div class="hero-card">
  <h2 class="hero-greeting">Hi, I'm Feng <span class="hero-wave">👋</span></h2>
  <p class="hero-lede">
    I'm a PhD candidate in <strong>Biomedical and Health Informatics</strong> at the
    <strong>University of Washington</strong>, advised by
    <a href="https://faculty.washington.edu/cohenta/" target="_blank" rel="noopener">Prof. Trevor Cohen</a>.
    My research applies <em>natural language processing</em>, <em>large language models</em>,
    and <em>speech technology</em> to better understand clinical communication and to build
    accessible, equitable health technologies.
  </p>
  <p class="hero-actions">
    <a class="hero-btn" href="{{ base_path }}/files/CV_Feng_Chen_2026.pdf" target="_blank" rel="noopener"><i class="fas fa-file-pdf"></i> Curriculum Vitae</a>
    <a class="hero-btn hero-btn--ghost" href="{{ site.author.googlescholar }}" target="_blank" rel="noopener"><i class="ai ai-google-scholar"></i> Google Scholar</a>
    <a class="hero-btn hero-btn--ghost" href="mailto:{{ site.author.email }}"><i class="fas fa-envelope"></i> Email</a>
  </p>
</div>

## Research Interests

I work at the intersection of clinical NLP, mental health, and human-centered AI. I'm particularly interested in:

<div class="topic-grid">
  <div class="topic-card">
    <div class="topic-icon"><i class="fas fa-brain"></i></div>
    <h4>Mental Health NLP</h4>
    <p>Detecting PTSD, depression, and thought disorder from clinical interviews using transformer models and LLMs.</p>
  </div>
  <div class="topic-card">
    <div class="topic-icon"><i class="fas fa-balance-scale"></i></div>
    <h4>Bias &amp; Equity in Clinical AI</h4>
    <p>Identifying and mitigating racial and demographic bias in patient–provider conversations and EHR-based models.</p>
  </div>
  <div class="topic-card">
    <div class="topic-icon"><i class="fas fa-microphone-alt"></i></div>
    <h4>Speech &amp; Multimodal Signals</h4>
    <p>Using ASR, speaker diarization, and acoustic-linguistic features to characterize clinical dialogue.</p>
  </div>
  <div class="topic-card">
    <div class="topic-icon"><i class="fas fa-users"></i></div>
    <h4>Accessible LLM Systems</h4>
    <p>Co-designing voice-enabled LLM chatbots with older adults to improve technology and eHealth literacy.</p>
  </div>
</div>

## Current Projects

- **PTSD &amp; Depression Detection** — Comparative analysis of transformer and embedding-based NLP models (Mental-RoBERTa, SentenceBERT, LLaMA) and DSM-5-informed LLM prompting on clinical interview transcripts.
- **Biased Social Signals** — Automated detection of biased social signals in patient–provider clinical dialogs from real recorded encounters.
- **Clinical Signatures for Hallucinations** — Building a multimodal pipeline that derives data-driven signatures from mobile behavioral tasks to predict severe outcomes among people experiencing hallucinations.
- **Voice-Enabled Chatbots for Older Adults** — User-centered design and evaluation of LLM-powered chatbots deployed in a retirement community.

## Background

I earned my <strong>M.S. in Biomedical Informatics</strong> from <strong>Harvard Medical School</strong> (GPA 3.96), where I worked with Dr. Li Zhou and Prof. Pengyu Hong on bias in EHR-based AI and mortality prediction for ARDS. Before that I completed a double major in <strong>Biochemistry &amp; Computer Science</strong> at <strong>Brandeis University</strong>, receiving the Jacques Cohen Award in Computer Science. I have also interned at <strong>Amazon</strong> (Supply Chain Optimization SDE) and <strong>Gordian Ventures</strong> (biotech investment research).

## Get in Touch

I'm always happy to chat about clinical NLP, mental health AI, or collaborations. Reach me at <a href="mailto:fengc9@uw.edu">fengc9@uw.edu</a> — or browse my <a href="{{ base_path }}/publications/">publications</a> and <a href="{{ base_path }}/experience/">experience</a>.
