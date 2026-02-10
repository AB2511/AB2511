# 👋 Anjali Barge

**Computer Engineering Undergraduate — Neural Signal Modeling & AI Systems**

I work on understanding **why non-invasive EEG models fail to generalize across people**.
My projects explore the boundary between machine learning performance and cognitive variability — building end-to-end systems and then analyzing where they break.

I am interested in moving from *decoding brain signals* toward *modeling what they represent*.

🔗 [LinkedIn](https://www.linkedin.com/in/anjali-barge) • ✉ [bargeanjali650@gmail.com](mailto:bargeanjali650@gmail.com) • 🌐 [Portfolio](https://anjali-portfolio-eight.vercel.app/)

---

## Research Focus

Non-invasive BCI systems often perform well within a subject but degrade across users.

Across multiple projects (ERP, motor imagery, cognitive state), I repeatedly observed:

> performance failure is dominated by human variability rather than only model choice

My current direction is studying whether this variability reflects differences in cognitive processes rather than noise in measurement.

---

## Core Projects

### Cross-Subject Motor Imagery Classification (TSception FilterBank)

Evaluated deep learning vs classical methods under strict cross-subject validation (54-fold leave-one-run-out, BCI IV-2a).

* 74.0% ± 11.0 accuracy
* +8.6% over CSP-LDA baseline (p < 0.00001)
* 49 / 54 runs > 60%

Result: deep models improved performance but did not eliminate inter-subject variability.

Repo: [https://github.com/AB2511/MI-TSception-FilterBank](https://github.com/AB2511/MI-TSception-FilterBank)

---

### Real-Time P300 Cognitive State Interface

Built full pipeline: acquisition → preprocessing → inference → live visualization
(MNE + LSL + EEGNet)

* within-subject: ~0.85–0.90
* cross-subject: ~0.57

Result: real-time usability depends more on individual calibration than architecture choice.

Repo: [https://github.com/AB2511/NAI-project](https://github.com/AB2511/NAI-project)

---

### EEG Focus Detection (Classical ML)

Feature-based EEG classification reaching high dataset accuracy but unstable deployment behavior.

Result: dataset accuracy ≠ practical reliability

Repo: [https://github.com/AB2511/NeuroSync](https://github.com/AB2511/NeuroSync)

---

## Supporting Engineering Work

These projects demonstrate system building & deployment ability.

* EcoPulse — multimodal environmental impact estimator (Cloud Run deployment)
* SkimSage — adaptive AI study assistant (LLM-based)
* Data dashboards & analysis tools (Power BI / Python)

---

## Research Output

**Accepted conference paper (camera-ready pending)**
Cross-Subject Motor Imagery Classification Using TSception FilterBank Under Leave-One-Run-Out Evaluation

**Submitted manuscript**
Real-Time EEG Cognitive State Monitoring using P300

**Published review**
Eco-Fusion AI: Multimodal Habitat Monitoring Framework

---

## Skills

* **Signal & ML:** MNE, PyTorch, scikit-learn, EEGNet, ERP processing
* **Programming:** Python, Java, C++, SQL
* **Systems:** real-time pipelines, data preprocessing, experiment evaluation
* **Software:** React, Node.js, Streamlit, REST APIs
* **Tools:** Git, Linux, Google Cloud, AWS (basic)

---

## Current Direction

I aim to study neural signal modeling at the intersection of:

* machine learning
* cognitive modeling
* human variability in BCI systems
