---
layout: archive
title: "Experience"
permalink: /experience/
author_profile: true
redirect_from:
  - /cv
  - /research
---

{% include base_path %}

<p class="cv-download">
  <a class="hero-btn" href="{{ base_path }}/files/CV_Feng_Chen_2026.pdf" target="_blank" rel="noopener"><i class="fas fa-file-pdf"></i> Download full CV (PDF)</a>
</p>

## Education

<div class="timeline">
  <div class="timeline-item">
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <div class="timeline-head">
        <h4>University of Washington</h4>
        <span class="timeline-date">Sep 2023 – Present</span>
      </div>
      <p class="timeline-sub">PhD Candidate, Biomedical and Health Informatics &middot; Seattle, WA</p>
      <p>Advisor: Prof. Trevor Cohen. Research on clinical NLP, mental-health language models, and bias in patient–provider conversations.</p>
    </div>
  </div>
  <div class="timeline-item">
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <div class="timeline-head">
        <h4>Harvard Medical School</h4>
        <span class="timeline-date">Sep 2021 – Dec 2022</span>
      </div>
      <p class="timeline-sub">M.S. in Biomedical Informatics &middot; Longwood, MA &middot; GPA 3.96</p>
    </div>
  </div>
  <div class="timeline-item">
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <div class="timeline-head">
        <h4>Brandeis University</h4>
        <span class="timeline-date">Jan 2018 – Dec 2020</span>
      </div>
      <p class="timeline-sub">B.S., Double Major in Biochemistry &amp; Computer Science &middot; Waltham, MA</p>
      <p>GPA 3.59 (Dean's List), Math &amp; CS GPA 3.78. Recipient of the Jacques Cohen Award in Computer Science.</p>
    </div>
  </div>
</div>

## Research Experience

### University of Washington
*Research Assistant &middot; Advisor: Prof. Trevor Cohen &middot; Seattle, WA*

**Natural Language Processing for Social Signals Detection in Patient–Provider Clinical Dialogs** *(Sep 2023 – Present)*
* Used ASR (Whisper) and speaker diarization (Pyannote) to transcribe and analyze patient–clinician conversations.
* Applied NLP and LLM models to classify social-signal scores for patients and clinicians.
* Investigated implicit racial bias in clinical dialogs and optimized predictive performance for detecting biased signals.

**Comparative Analysis of LLMs in Detecting PTSD in Clinical Interviews** *(Jan 2025 – Present)*
* Developed and compared transformer- and embedding-based NLP models (Mental-RoBERTa, SentenceBERT, LLaMA) for PTSD classification from clinical transcripts.
* Implemented prompt-based PTSD classification using LLaMA with DSM-5-informed prompts.
* Conducted error analysis on symptom severity and depression comorbidity, revealing model sensitivity to clinical subtleties.

**Data-driven Clinical Signatures for People with Hallucinations** *(Mar 2024 – Present)*
* Built an automatic pipeline to derive multimodal data-driven clinical signatures from mobile behavioral tasks to predict severe negative outcomes.
* Developed and improved an automatic sentence-coherence measurement package to evaluate verbal-recall audio recordings.
* Identified and mitigated bias in ASR and predictive models across demographic groups.

**LLM-based Chatbot Design for the Elderly Community** *(Mar 2024 – Present)*
* Designed and developed an LLM-powered chatbot to improve life for residents at a retirement community.
* Conducted user interviews and training sessions to refine accessibility features (adjustable font sizes, high-contrast modes, voice-to-text).
* Engineered prompts and interfaces to enhance accessibility and user satisfaction.

### Harvard Medical School
*Research Assistant / Project Core Member &middot; Advisors: Dr. Li Zhou &amp; Prof. Pengyu Hong &middot; Longwood, MA*

**Bias and Missingness Handling in Mortality Prediction for ARDS** *(Feb 2022 – Dec 2022)*
* Preprocessed MIMIC-IV and retrieved ARDS-patient ICU ventilation data; quantified demographics and missingness across prediction features.
* Built a workflow to impute missing values across four imputation methods based on missingness type.
* Applied propensity-score matching to detect and reduce bias, then compared ML model performance for mortality prediction.

**Systematic Review of Bias in Healthcare AI using EHR Data** *(Dec 2022 – Dec 2023)*
*Project Lead / First Author &middot; Advisors: Dr. Li Zhou &amp; Dr. Liqin Wang*
* Used scripted keyword search and the PRISMA workflow to manually screen 200+ papers on bias handling in healthcare AI.
* Coded full-text papers for evaluation metrics, bias types, and mitigation methods.
* Published a systematic review summarizing bias-handling strategies in EHR-based AI in JAMIA.

### Brandeis University
*Research Assistant / Co-first Author &middot; Advisors: Prof. Hongfu Liu &amp; Prof. Pengyu Hong &middot; Waltham, MA*

**Network-based Cross-species Prediction of SARS-CoV-2 Virus–Host Interactions** *(Mar 2020 – Aug 2020)*
* Compared SARS-CoV-2 against other coronaviruses via multiple sequence alignment for domains, functions, and mutations.
* Built protein-similarity and PPI graphs and applied graph embedding + deep learning to a cross-species model.
* Predicted high-potential PPIs and pathways of SARS-CoV-2 across animal hosts.

**Predicting SARS-CoV-2 Mutation with Deep Learning &amp; Evolutionary Algorithms** *(Apr 2020 – Sep 2021)*
* Curated SARS-CoV-2 mutation data over time and location; calculated mutation rates and identified hot zones.
* Combined evolutionary algorithms with GANs to forecast SARS-CoV-2 mutations from history.
* Studied the impact of mutations on viral protein 3-D structure.

### Massachusetts Institute of Technology
*Research Intern &middot; Advisor: Prof. Jean-Francois Hamel &middot; Cambridge, MA*

**Bioreactor Simulators &amp; Vaccine-Production Parameter Optimization** *(Jan 2020 – Aug 2020)*
* Used bioreactor simulators to cultivate mammalian and yeast cells and study bioprocesses.
* Performed AAV-based simulator experiments to optimize parameters for COVID-19 vaccine production yield.
* Authored weekly progress and summary reports on optimal conditions for expanded-scale production.

## Industry Experience

**Amazon** — *Software Development Engineer Intern* &middot; Bellevue, WA *(May 2022 – Aug 2022)*
* Developed and optimized a shortest-path algorithm for the Supply Chain Optimization group.
* Applied clustering and ML methods to partition the logistic network for transportation.
* Visualized network state and improvement statistics before and after optimization.

**Gordian Ventures** — *Investment Intern* &middot; Shanghai, China *(Mar 2023 – Aug 2023)*
* Researched emerging technologies (t-RNA, aptamers, brain–computer interfaces) and contributed to a published information book.
* Mapped early-stage biotech companies funded by leading ventures; clustered and visualized drug-discovery trends.
* Modeled market size and growth for the peptide-drug market and supported DCF-based valuation of newly incubated companies.

## Skills

**Programming:** Python, Java, SQL, R, Scheme, MATLAB, HTML
**Tools &amp; Platforms:** AWS, Git/GitHub, Linux/CLI, Photoshop, Microsoft Office, Cortellis
**Research:** Machine learning, deep learning, NLP, large language models, ASR, clinical data processing, bioinformatics analysis, data cleaning/visualization, qualitative coding, proposal &amp; manuscript writing, paper review
