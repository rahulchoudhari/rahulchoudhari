<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1F4E79,100:2E75B6&height=200&section=header&text=Rahul%20Choudhari&fontSize=50&fontColor=ffffff&fontAlignY=38&desc=Lead%20SRE%20%7C%20Platform%20Engineer%20%7C%20Agentic%20AI%20%7C%20Creator%20of%20CARE&descAlignY=58&descColor=c9d8f0" />

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/rahulchoudhari)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dreamtechrc@gmail.com)
[![CARE Framework](https://img.shields.io/badge/CARE%20Framework-1F4E79?style=for-the-badge&logo=github&logoColor=white)](https://github.com/rahulchoudhari/Customer-AI-Reliability-Engineering)
[![Location](https://img.shields.io/badge/Indianapolis%2C%20IN-2E75B6?style=for-the-badge&logo=googlemaps&logoColor=white)](#)
</div>

---

## 👋 About Me

I'm a **Lead SRE, Security Engineer, and Platform Engineer** with **19+ years** of experience building, securing, and scaling cloud-native platforms at **Cisco**, **Equifax**, and **Eli Lilly**.

I specialize in the intersection of **Agentic AI**, **platform engineering**, and **enterprise security** — where automation meets reliability and compliance. I architect systems that don't just react to problems, but eliminate them autonomously.

After 19 years in SRE, I identified a gap no existing framework addressed: **how do you apply reliability engineering to AI systems making real decisions in customer environments?** I built CARE to answer that.

> *"Security and reliability aren't features you bolt on — they're foundations you architect from day one."*

---

## 🆕 Open Source — CARE Framework

<div align="center">

[![CARE](https://img.shields.io/badge/CARE-Customer%20AI%20Reliability%20Engineering-1F4E79?style=for-the-badge&logo=github&logoColor=white)](https://github.com/rahulchoudhari/Customer-AI-Reliability-Engineering)

</div>

> **Customer AI Reliability Engineering (CARE)** — SRE extended for the AI era.

After 19 years in SRE and two years operating AI-driven platforms at Cisco, I kept hitting the same wall: **SRE doesn't have a chapter for AI failure modes.**

LLM hallucinations. Prompt regressions. Agentic loops. AI systems confidently wrong. Customer environments that are your production. None of it is in the SRE handbook.

So I wrote one.

**CARE is not a reinvention of SRE.** It reuses every core SRE concept — SLIs, SLOs, error budgets, blameless postmortems — and adds two dimensions SRE doesn't cover:

```
Dimension 1: AI Systems → Prompt versioning · Model drift · Evals · Agentic governance
Dimension 2: Customer Environments → Every deployment treated as production
```

**The CARE Loop:**
```
Promise → Signals → Guardrails → Response → Learning
```

| Stage | Question |
|---|---|
| Promise | What reliability commitment are we making? |
| Signals | How do we know it's working — from the customer's view? |
| Guardrails | How do we prevent unsafe AI outcomes? |
| Response | What happens when it breaks? Who owns it? |
| Learning | How does every incident make the system stronger? |

**What's in the repo:**
- ✅ 10 AI-assisted CARE skills with copyable prompts (Claude / GPT-4 ready)
- ✅ Checklists: go-live, rollback readiness, AI guardrails
- ✅ Templates: reliability promise, incident report, postmortem, runbook, PRR
- ✅ Full worked example: QR Authenticity Service (complete SEV1 incident walkthrough)
- ✅ Automation levels model for governing agentic AI in production
- ✅ Interactive docs site — open `site/index.html`, no server needed

📖 **[Explore the CARE Framework →](https://github.com/rahulchoudhari/Customer-AI-Reliability-Engineering)**

---

## 🚀 Flagship Projects

#### ✨ Unified Operations Center (UOC) — *Cisco (Proprietary)*

> A proprietary **Agentic AI platform** I architected at Cisco that serves as the single command center for security, compliance, and operations.

```
  DATA SOURCES
  ┌──────────┐  ┌────────────┐  ┌───────────┐  ┌──────┐  ┌───────────┐
  │ Wiz CSPM │  │GitGuardian │  │ SonarQube │  │ Jira │  │ PagerDuty │
  └────┬─────┘  └─────┬──────┘  └─────┬─────┘  └──┬───┘  └─────┬─────┘
       └───────────────┴───────────────┴────────────┴────────────┘
                                       │
  AI ORCHESTRATOR                      ▼
  ┌──────────────────────────────────────────────────────────────────┐
  │           AI Agent Orchestrator  ·  LLM  ·  RAG  ·  Agentic AI  │
  └──────┬──────────────┬────────────────┬─────────────┬────────────┘
         │              │                │             │
         ▼              ▼                ▼             ▼
  CAPABILITIES
  ┌──────────┐  ┌────────────┐  ┌──────────┐  ┌──────────┐  ┌──────────┐
  │  Vuln    │  │ Compliance │  │ Auto RCA │  │   Ops    │  │  Voice   │
  │  Mgmt    │  │ FedRAMP    │  │Confluence│  │ Support  │  │  Jira    │
  └──────────┘  └────────────┘  └──────────┘  └──────────┘  └──────────┘
  MTTR ↓35%     200+ hrs saved   Auto-docs     Zero-touch    Hands-free
```

#### 🔹 [CTXPress — AI Token Optimizer](https://github.com/rahulchoudhari/ctxpress)

Self-hosted AI context and prompt optimization platform designed to reduce LLM token consumption, improve prompt efficiency, and lower operational cost before requests reach the model.

**Pipeline:**  
`User Request → Context Collection → RTK Filter → Caveman Compress → Prompt Optimizer → LLM Call`

---

## 📊 Impact by the Numbers

<div align="center">

| Metric | Result |
|--------|--------|
| 🔒 Critical vulnerabilities reduced | **40% in 6 months** |
| 🚀 Deployment velocity increase | **60% faster** |
| ✅ Compliance hours saved | **200+ hrs/quarter** |
| 🤖 SAST findings eliminated pre-prod | **95% reduction** |
| ⚡ PR review cycle time | **50% faster** |
| 🛠️ Incident response improvement | **50% faster MTTR** |
| 📦 Environment build time | **Days → under 2 hours** |
| 💰 Cloud infrastructure cost reduction | **20% at Equifax** |

</div>

---

## 🛠️ Tech Stack

### ☁️ Cloud & Security
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Wiz](https://img.shields.io/badge/Wiz-00AEEF?style=flat-square&logoColor=white)
![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=flat-square&logo=sonarqube&logoColor=white)
![GitGuardian](https://img.shields.io/badge/GitGuardian-1B1C1D?style=flat-square&logo=gitguardian&logoColor=white)

### 🤖 Agentic AI & Reliability
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/Agentic%20AI-412991?style=flat-square&logo=openai&logoColor=white)
![RAG](https://img.shields.io/badge/RAG%20Pipelines-FF6B35?style=flat-square&logoColor=white)
![CARE](https://img.shields.io/badge/CARE%20Framework-1F4E79?style=flat-square&logo=github&logoColor=white)

### 🏗️ IaC & DevOps
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)

### 📊 Monitoring & Observability
![Datadog](https://img.shields.io/badge/Datadog-632CA6?style=flat-square&logo=datadog&logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat-square&logo=splunk&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![PagerDuty](https://img.shields.io/badge/PagerDuty-06AC38?style=flat-square&logo=pagerduty&logoColor=white)

### 📋 Compliance
![FedRAMP](https://img.shields.io/badge/FedRAMP-003087?style=flat-square&logoColor=white)
![SOC2](https://img.shields.io/badge/SOC%202-1F4E79?style=flat-square&logoColor=white)
![PCI DSS](https://img.shields.io/badge/PCI%20DSS-00599C?style=flat-square&logoColor=white)
![HIPAA](https://img.shields.io/badge/HIPAA-2E7D32?style=flat-square&logoColor=white)
![SOX](https://img.shields.io/badge/SOX-B71C1C?style=flat-square&logoColor=white)

---

## 💼 Experience Timeline

```
2023 ──────────────────────────────────────────────────── Present
  🔵  Cisco  |  Staff SRE & Security Engineer — Tech Lead
      └─ UOC (Agentic AI Platform) · ETD Infrastructure · FedRAMP
      └─ CARE Framework (open source) · AI reliability governance
      └─ Mentoring 4–8 engineers · Org-wide security standards

2021 ──────────────────────────────────────────────────── 2023
  🟢  EPAM Systems  (Client: Equifax)  |  Senior Systems Engineer
      └─ Multi-cloud AWS/GCP · Terraform IaC · SLO/SLI frameworks

2013 ──────────────────────────────────────────────────── 2021
  🟡  TCS  (Client: Eli Lilly)  |  Cloud & DevOps Architect
      └─ 8 years · AWS/Azure · OpenShift · HIPAA/SOX compliance
      └─ 50+ app migrations · Zero audit findings 3 years running

2011 ──────────────────────────────────────────────────── 2013
  🟠  TCS  (Client: General Motors)  |  Unix Systems Administrator
      └─ Global server fleet · P2V/V2V migrations · SOX audits
      └─ Troy, MI  &  Seoul, South Korea 🌏

2006 ──────────────────────────────────────────────────── 2011
  ⚪  Mphasis  &  HCL Technologies  |  Unix/Linux Administrator
      └─ RHEL · HP-UX · Solaris · AIX · DR automation
```

---

## 🏆 Certifications

> 🏅 [View all verified badges on Credly](https://www.credly.com/users/rahulchoudhari/badges)

| | Certification | Issuer |
|---|---|---|
| ☁️ | AWS Certified Solutions Architect | Amazon Web Services |
| ⚙️ | Certified Kubernetes Administrator (CKA) | CNCF |
| ⚙️ | Certified Kubernetes Application Developer (CKAD) | CNCF |
| 🔷 | Microsoft Certified: Azure Administrator & Expert | Microsoft |
| 🔧 | Certified Jenkins Engineer | CloudBees |
| 🤖 | Generative AI Certification | Cisco |
| 🔒 | Cybersecurity Tools and Essentials | IBM Coursera |

---

## 🛠️ Personal Projects

> Built for fun, family, and sharpening Python + Streamlit skills outside of work hours.

---

### 📊 [FlowViz](https://github.com/rahulchoudhari/flowviz) — Industry Data Analytics Platform

> Professional-grade Streamlit app for visualizing and analyzing business data with ML-powered insights.

Upload any CSV/Excel → ML auto-recommends the best chart type → export interactive Plotly visualizations and month-over-month comparison reports. Includes secure login, session management, and data export.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

---

### 🎯 [SpellBowl](https://github.com/rahulchoudhari/spellbowl) — Pronunciation & Spelling Master

> Full-featured spelling bee practice app with voice pronunciation, leaderboards, and timed competition mode. Co-built with my daughter **Aashrita** 👧

Hear a word → type what you heard → instant feedback with similarity scoring, ARPAbet phonetic notation, case-sensitivity detection, and revision tracking. Supports 750 curated words + PDF word extraction.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![gTTS](https://img.shields.io/badge/gTTS-4285F4?style=flat-square&logo=google&logoColor=white)
![NLTK](https://img.shields.io/badge/NLTK-154F5B?style=flat-square&logoColor=white)

---

### 🎮 [LaserTag Operator](https://github.com/rahulchoudhari/lasertagoperator) — Tournament Manager

> Real-time laser tag tournament system — because why not automate the fun?

Create Best of 3/5 tournaments, manage up to 4 teams × 20 players, track eliminations live on a visual grid, auto-detect winners, and maintain full match history with a 30-minute match timer.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

---

### ➕ [LearnMath](https://github.com/rahulchoudhari/Learnmath) — Fun Math for Kids

> Built with ❤️ for my daughter **Aashrita** to make arithmetic fun and engaging.

Practice addition, subtraction, multiplication, and division across 3 difficulty levels. 20-challenge mode with real-time accuracy tracking and celebratory 🎈 balloons on completion.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

---

### 🌈 [LearnColorPattern](https://github.com/rahulchoudhari/learncolorpattern) — Kindergarten Learning Game

> Interactive educational app for young learners — letters, colors, shapes, weather, numbers, and pattern recognition.

Six game modes for kindergarten & 1st grade. Uses deterministic logic (not ML) for reliable, transparent pattern generation — so parents and teachers always know what's being taught and why.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

---

## 🎯 What I'm Working On

- 🧠 **CARE v0.2** — Agentic AI reliability guide, LLM eval framework, prompt versioning SOP, industry-specific playbooks (Healthcare/FedRAMP/PCI DSS)
- 🔁 Expanding the **UOC** with multi-agent orchestration and self-healing infrastructure capabilities
- 🔍 Exploring **SBOM** and software supply chain security integration into CI/CD pipelines
- 📖 Deepening expertise in **FinOps** for multi-cloud cost governance at scale

---

## 📬 Let's Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/Connect%20on%20LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/rahulchoudhari)
[![Email](https://img.shields.io/badge/Send%20an%20Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dreamtechrc@gmail.com)
[![CARE Framework](https://img.shields.io/badge/CARE%20on%20GitHub-1F4E79?style=for-the-badge&logo=github&logoColor=white)](https://github.com/rahulchoudhari/Customer-AI-Reliability-Engineering)

</div>

---

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2E75B6,100:1F4E79&height=100&section=footer" />
</div>
