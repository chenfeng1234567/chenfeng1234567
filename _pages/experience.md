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
      <p class="timeline-sub">PhD Candidate, Health Informatics &middot; Seattle, WA &middot; GPA 3.90</p>
      <p>Advisor: Prof. Trevor Cohen. Research on clinical NLP, speech- and language-based mental-health assessment, and bias in patient–provider conversations.</p>
    </div>
  </div>
  <div class="timeline-item">
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <div class="timeline-head">
        <h4>Harvard Medical School</h4>
        <span class="timeline-date">Sep 2021 – Dec 2022</span>
      </div>
      <p class="timeline-sub">Master of Biomedical Informatics &middot; Longwood, MA &middot; GPA 3.96</p>
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
      <p>GPA 3.59 (Dean's List), Math &amp; CS GPA 3.78. Recipient of the Jacques Cohen Award in Computer Science, awarded for excellent researchers.</p>
    </div>
  </div>
</div>

**Main coursework:** Deep Learning for Natural Language Processing; Data Structures and Algorithms; Statistical Machine Learning; Deep Learning for Biomedical Data; Clinical Informatics; Data Visualization; Precision Medicine; Data Science for Medical Decision Making.

## Research Experience

### University of Washington
*Research Assistant &middot; Advisor: Prof. Trevor Cohen &middot; Seattle, WA*

**NLP for Social Signals Detection in Patient–Provider Clinical Dialogs** *(Sep 2023 – Present)*
* Used ASR (Whisper) and speaker diarization (Pyannote) to transcribe and analyze patient–clinician conversations.
* Trained and compared NLP and LLM models to classify social-signal scores for patients and clinicians.
* Investigated implicit racial bias in clinical dialogs and optimized predictive performance for detecting social signals.

**Data-driven Clinical Signatures for People with Hallucinations** *(Mar 2024 – Present)*
* Building an automated pipeline to derive multimodal, data-driven clinical signatures from mobile behavioral tasks to predict individual differences in severe negative outcomes among people experiencing hallucinations.
* Developed an automated sentence-coherence package for verbal-recall audio, combining pause dynamics and semantic coherence to assess thought disorder (published in *Neuropsychologia*).
* Identifying and mitigating bias in automatic speech recognition and predictive models across demographic groups.

**Comparative Analysis of LLMs for Mental Illness Detection in Interviews** *(Jan 2025 – Present)*
* Developed and compared transformer-based and embedding-based NLP models (Mental-RoBERTa, SentenceBERT, LLaMA) for PTSD and depression classification from clinical transcripts.
* Implemented prompt-based PTSD classification using LLaMA with DSM-5-informed prompts.
* Conducted error analysis on symptom severity and depression comorbidity, showing where models are sensitive to clinical subtleties.
* Identified linguistic biomarkers and temporal patterns for depression in clinical interactions.

**Automated Detection of Delusional Content in Audio Diaries** *(Mar 2025 – Present)*
* Designed a four-level prompt-engineering framework to extract delusional themes and affective and behavioral responses from naturalistic speech transcripts.
* Implemented a multi-agent LLM pipeline (GPT-OSS, Qwen, GLM) for fine-grained multi-label annotation and benchmarked its consistency against human annotations.

**LLM-based Chatbot Design for the Elderly Community** *(Mar 2024 – Present)*
* Designed and developed an LLM-powered chatbot prototype to improve daily life for residents of a retirement community.
* Conducted user interviews and co-design workshops with 30+ residents.
* Engineered prompts for clear responses and implemented a voice-enabled interface to improve accessibility and satisfaction.

**LLM-driven Development of a Digital Therapeutic for PTSD** *(Jan 2025 – Present)*
* Led foundational research for a PTSD mHealth app, using LLMs to synthesize evidence-based treatment components.
* Ran a human-in-the-loop workshop with experts to iteratively refine AI-generated therapeutic content.
* Used LLMs to generate technical specifications from expert-validated content for app prototyping.

### Harvard Medical School
*Research Assistant / Project Core Member &middot; Advisors: Dr. Li Zhou &amp; Prof. Pengyu Hong &middot; Longwood, MA*

**Bias and Missingness Handling in Mortality Prediction for ARDS** *(Feb 2022 – Dec 2022)*
* Preprocessed MIMIC-IV and retrieved ARDS-patient ICU ventilation data; quantified demographics and missingness across prediction features.
* Built a workflow to impute missing values with four methods chosen by missingness type.
* Applied propensity-score matching to detect and reduce bias, then compared machine-learning models for mortality prediction.
* Contributed to grant applications for the lab’s work on handling bias in EHR data.

**Systematic Review of Bias in Healthcare AI Using EHR Data** *(Dec 2022 – Dec 2023)*
*Project Lead / First Author &middot; Advisors: Dr. Li Zhou &amp; Dr. Liqin Wang*
* Followed a PRISMA workflow and scripted keyword search to screen 200+ papers on bias handling in healthcare AI.
* Coded full texts for evaluation metrics, bias types, and mitigation methods.
* First-authored a systematic review of bias handling in EHR-based AI, published in JAMIA.

### Brandeis University
*Research Assistant / Co-first Author &middot; Advisors: Prof. Hongfu Liu &amp; Prof. Pengyu Hong &middot; Waltham, MA*

**Virus–Host Interactions of SARS-CoV-2 Predicted by a Network-based Cross-species Model** *(Mar 2020 – Aug 2020)*
* Compared SARS-CoV-2 with previously published coronaviruses after multiple sequence alignment of domains, functions, and mutations.
* Built graphs of viral and host protein similarity and protein–protein interaction networks.
* Used graph embedding and a network-based cross-species deep learning model to predict high-potential PPIs and pathways of SARS-CoV-2 across animal species.

**The Prediction of SARS-CoV-2 Mutation Using Deep Learning and Evolutionary Algorithms** *(Apr 2020 – Sep 2021)*
* Curated SARS-CoV-2 mutation data over time and location; calculated mutation rates and identified hot zones.
* Combined evolutionary algorithms with GANs to forecast SARS-CoV-2 mutations from history.
* Studied how mutations affect viral protein 3-D structure.

### Massachusetts Institute of Technology
*Research Intern &middot; Advisor: Prof. Jean-Francois Hamel &middot; Cambridge, MA &amp; Online*

**Bioreactor Simulation for Vaccine Production Optimization** *(Jan 2020 – Aug 2020)*
* Used bioreactor simulators to cultivate mammalian and yeast cells and study bioprocesses.
* Ran AAV-based simulator experiments, compared them with experimental results, and optimized parameters for COVID-19 vaccine production yield.
* Wrote weekly progress reports and a summary report on conditions for expanded-scale production.

## Industry Experience

**Microsoft** — *Applied Scientist Intern* &middot; Redmond, WA *(Jun 2026 – Aug 2026)*

*Evaluating the Robustness of Enterprise AI Agents to Communication Style Variation*
* Investigated how directness, formality, verbosity, politeness, emotional tone, and grammaticality in user requests affect enterprise AI agents.
* Developed a communication-style taxonomy and an automated generation framework that produces controlled linguistic variants while preserving semantic intent.
* Ran large-scale evaluations across enterprise email, retrieval, and tool-use agents, measuring task completion, retrieval quality, and tool-use reliability.
* Built experimentation pipelines for variant generation, benchmark construction, orchestration, and analysis, and quantified robustness gaps with matched-pair analysis, bootstrap confidence intervals, and significance testing.
* Extended the study to multilingual and dialectal variation to assess fairness for diverse user populations.
* First-authored a manuscript accepted at the Workshop on Evaluation of Interactive Agents (IAEval) @ NeurIPS 2026, with an extended version submitted to NAACL.

**Amazon** — *Software Development Engineer Intern* &middot; Bellevue, WA *(May 2022 – Aug 2022)*
* Developed and optimized shortest-path algorithms for the Supply Chain Optimization group.
* Used clustering and machine learning to partition the logistics network for transportation.
* Visualized the network before and after optimization, together with the statistics the algorithm improved.

**Gordian Ventures** — *Investment Intern* &middot; Shanghai, China *(Mar 2023 – Aug 2023)*
* Researched emerging technologies, including t-RNA therapeutics, aptamers, and brain–computer interfaces, and wrote a published information book.
* Mapped biotech companies funded by major ventures, summarized their technologies and pipelines, and clustered and visualized drug-discovery trends.
* Estimated market size and growth for the peptide drug market and supported DCF valuation of newly incubated companies.

## Service &amp; Leadership

**Local Chair, Conference on Health, Inference, and Learning (CHIL) 2026** *(2025 – Present)*
* Coordinating local logistics, venue, and community engagement for CHIL 2026, held in Seattle.

**Research Mentor, LLM-Powered Chatbot for Retirement Communities** *(2024 – Present)*
* Mentored two groups of high school students in user-centered research, chatbot prototyping, data analysis, and academic writing.
* The collaboration produced two conference papers presented at GSA 2025 and AMIA 2026.

**Peer Reviewer** *(2023 – Present)*
* Reviewer for conferences and journals in NLP, machine learning, and biomedical informatics.

## Skills

**Programming:** Python (proficient), Java (proficient), SQL, R, Scheme, MATLAB, HTML
**ML &amp; NLP:** PyTorch, Hugging Face Transformers, scikit-learn, Whisper (ASR), Pyannote (diarization), pandas/NumPy
**LLM &amp; evaluation:** prompt engineering, multi-agent LLM pipelines, benchmark and eval-harness design, controlled variant generation, robustness and fairness auditing, statistical validation
**Software &amp; tools:** AWS, Git/GitHub, Linux/CLI, Claude Code, Microsoft Office, Cortellis, Photoshop
**Research:** large language models, machine learning, deep learning, natural language processing, clinical data processing, automatic speech recognition, bioinformatics analysis, data cleaning, analysis, and visualization, PRISMA systematic review, qualitative coding, proposal and manuscript writing, paper reviewing
