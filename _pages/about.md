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
  <h2 class="hero-greeting">Hi, I'm Feng</h2>
  <p class="hero-lede">
    I'm a PhD candidate in <strong>Health Informatics</strong> at the
    <strong>University of Washington</strong>, advised by
    <a href="https://bime.uw.edu/faculty/trevor-cohen/" target="_blank" rel="noopener">Prof. Trevor Cohen</a>.
    My research sits at the intersection of <em>natural language processing</em>,
    <em>large language models</em>, and <em>human-centered AI</em> — including LLM and agent
    evaluation, robustness and bias auditing, and speech- and language-based assessment of
    mental health.
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
    <p>Detecting PTSD, depression, thought disorder, and delusional content from clinical interviews and naturalistic speech using transformer models and LLMs.</p>
  </div>
  <div class="topic-card">
    <div class="topic-icon"><i class="fas fa-balance-scale"></i></div>
    <h4>Bias &amp; Equity in Clinical AI</h4>
    <p>Identifying and mitigating racial and demographic bias in patient–provider conversations and EHR-based models, and auditing robustness of language systems.</p>
  </div>
  <div class="topic-card">
    <div class="topic-icon"><i class="fas fa-microphone-alt"></i></div>
    <h4>Speech &amp; Multimodal Signals</h4>
    <p>Using ASR, speaker diarization, pause dynamics, and semantic coherence to characterize clinical dialogue.</p>
  </div>
  <div class="topic-card">
    <div class="topic-icon"><i class="fas fa-users"></i></div>
    <h4>Accessible LLM Systems</h4>
    <p>Co-designing voice-enabled LLM chatbots with older adults in retirement communities to improve technology and eHealth literacy.</p>
  </div>
</div>

## Current Projects

- **Mental Illness Detection** — Comparing transformer and embedding models (Mental-RoBERTa, SentenceBERT, LLaMA) and DSM-5-informed LLM prompts for PTSD and depression in clinical interviews, and tracing linguistic biomarkers in clinical interactions.
- **Biased Social Signals** — Training NLP and LLM models to classify social-signal scores and to detect implicit racial bias in patient–provider conversations transcribed with Whisper and Pyannote.
- **Clinical Signatures for Hallucinations** — A multimodal pipeline that derives data-driven signatures from mobile behavioral tasks, combining pause dynamics and semantic coherence to assess thought disorder.
- **Delusional Content in Audio Diaries** — A four-level prompt framework and multi-agent LLM pipeline (GPT-OSS, Qwen, GLM) for delusional themes and affective and behavioral responses in naturalistic speech.
- **Voice-Enabled Chatbots for Older Adults** — Co-design and evaluation of an LLM-powered, voice-enabled community chatbot with 30+ retirement-community residents.
- **Digital Therapeutic for PTSD** — Using LLMs to synthesize evidence-based treatment components, refine them with experts, and turn the validated content into specifications for a PTSD mHealth app.

## Background

I earned my <strong>Master of Biomedical Informatics</strong> from <strong>Harvard Medical School</strong> (GPA 3.96), where I worked with Dr. Li Zhou and Prof. Pengyu Hong on bias in EHR-based AI and mortality prediction for ARDS. Before that I completed a double major in <strong>Biochemistry &amp; Computer Science</strong> at <strong>Brandeis University</strong>, receiving the Jacques Cohen Award in Computer Science. I was an Applied Scientist Intern at <strong>Microsoft</strong> (robustness of enterprise AI agents) and a Software Development Engineer Intern at <strong>Amazon</strong> (Supply Chain Optimization), and I interned at <strong>Gordian Ventures</strong> (biotech investment research).

## Get in Touch

I'm always happy to chat about clinical NLP, mental health AI, or collaborations. Reach me at <a href="mailto:fengc9@uw.edu">fengc9@uw.edu</a> — or browse my <a href="{{ base_path }}/publications/">publications</a> and <a href="{{ base_path }}/experience/">experience</a>.
