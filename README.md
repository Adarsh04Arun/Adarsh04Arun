<div align="center">

# Adarsh Arun

**AI Safeguards Engineer** &nbsp;·&nbsp; Bengaluru, India

*I work where ML systems meet adversaries.*

<a href="https://adarsh04arun.in"><img alt="Portfolio" src="https://img.shields.io/badge/portfolio-adarsh04arun.in-5b8aae?style=for-the-badge&labelColor=0d1117"></a>
<a href="https://linkedin.com/in/adarsh3arun"><img alt="LinkedIn" src="https://img.shields.io/badge/linkedin-adarsh3arun-5b8aae?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0d1117"></a>
<a href="mailto:adarsh3arun@gmail.com"><img alt="Email" src="https://img.shields.io/badge/email-adarsh3arun-5fc99a?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0d1117"></a>
<br>
<img alt="Followers" src="https://img.shields.io/github/followers/Adarsh04Arun?style=flat-square&label=followers&labelColor=0d1117&color=5b8aae">
<img alt="Stars" src="https://img.shields.io/github/stars/Adarsh04Arun?style=flat-square&label=stars&labelColor=0d1117&color=5fc99a">

</div>

```console
$ whoami

operator     Adarsh Arun
role         AI Safeguards Engineering Intern @ XelerAIT
location     Bengaluru, IN
education    BE CSE, BNM Institute of Technology
focus        AI guardrails / LLM security / detection engineering
shipping     Wardline — Rust guardrail library (pre-alpha)
open source  roostorg/osprey — PR #451 merged
uptime       since Aug 2023
```

Most of what I build answers one question: **what happens when this model is given something it
should refuse?** At XelerAIT I design guardrails for production agentic AI in healthcare — safety,
reliability, and compliance enforced at the framework layer rather than bolted on after an incident.

---

## ▸ Currently building

```
   PROMPT   ──▶   BROKER    ──▶   SCHEMA    ──▶   MODEL     ──▶   AUDIT
  untrusted      regex +        structured      policy-         verdict
    input       metaprompt         json        bound call         log
```

**[Wardline](https://github.com/Adarsh04Arun/Wardline)** &nbsp;
<img alt="stars" src="https://img.shields.io/github/stars/Adarsh04Arun/Wardline?style=flat-square&label=%E2%98%85&labelColor=0d1117&color=5fc99a">
<img alt="license" src="https://img.shields.io/badge/Apache--2.0%20%2F%20MIT-5b8aae?style=flat-square&labelColor=0d1117">
<img alt="status" src="https://img.shields.io/badge/pre--alpha-e0a458?style=flat-square&labelColor=0d1117">

An embeddable guardrail evaluation library for Rust. Guards run inline in the request path — before
an action is taken or an LLM response is released — and return a blocking verdict: **allow**,
**block**, or **modify**. A library you call in-process, not a proxy you deploy: no separate
service, no network hop, no async runtime. Guards are ordinary Rust implementing one trait, so a
guard is testable like any other code.

---

## ▸ Selected work

<table>
<tr><th align="left">Project</th><th align="left">What it is</th></tr>

<tr><td valign="top">

**[Wardline](https://github.com/Adarsh04Arun/Wardline)**<br>
<sub><code>Rust</code> <code>tower/axum</code></sub>

</td><td valign="top">

Embeddable, synchronous, trait-based guardrail library. Four-crate workspace with panic isolation and a bounded audit trace.

</td></tr>

<tr><td valign="top">

**[ISTVON Prompt Engine](https://github.com/Adarsh04Arun/ISTVON-Prompt-Review-Engine)**<br>
<sub><code>Python</code> <code>Streamlit</code> <code>Gemini</code></sub>

</td><td valign="top">

Security broker for LLM prompts — dual-layer regex + metaprompt screening, JSON structuring that isolates malicious payloads, audited verdicts.

</td></tr>

<tr><td valign="top">

**[Vendor Risk Assessor](https://github.com/Adarsh04Arun/Kaggle_AI_Agent_-Vendor-Risk-Assessment-)**<br>
<sub><code>Google ADK</code> <code>MCP</code> <code>FastAPI</code> <code>Docker</code></sub>

</td><td valign="top">

Hierarchical agent pipeline over an MCP tool server. Risk score computed deterministically in Python — **the LLM writes prose, never the number.**<br>
<sub>Kaggle Agentic AI Competition</sub>

</td></tr>

<tr><td valign="top">

**[Telecom SOC Simulation](https://github.com/Adarsh04Arun/Telecom-SOC)**<br>
<sub><code>Python</code> <code>RAG</code> <code>AutoAI</code></sub>

</td><td valign="top">

DFIR automation with RAG-backed MITRE ATT&amp;CK mapping over MDE investigation packages.

</td></tr>

<tr><td valign="top">

**[Adaptive Triage Engine](https://github.com/Adarsh04Arun/Adaptive-Triage-Engine-for-SOC)**<br>
<sub><code>Contextual Bandits</code> <code>scikit-learn</code></sub>

</td><td valign="top">

RL policy that scores and triages SOC alerts from forensic feature data, evaluated on reward distributions and precision-recall trade-offs.

</td></tr>

<tr><td valign="top">

**[Satellite Land-Use](https://github.com/Adarsh04Arun/Satellite-Image-Classification-for-Land-Use-Custom_CNN-ResNet50-VGG16-)**<br>
<sub><code>TensorFlow</code> <code>ResNet50</code> <code>VGG16</code></sub>

</td><td valign="top">

Custom CNN vs. ResNet50 vs. VGG16, benchmarked head-to-head on EuroSAT imagery.

</td></tr>

</table>

<details>
<summary><b>More projects</b></summary>
<br>

- **[AI-Powered Educational Feedback System](https://github.com/Adarsh04Arun/AI-Powered-Educational-Feedback-System)** — NLP analysis of student writing and code. Sentiment via VADER *and* RoBERTa, readability metrics, style checks, and a Python path that flags syntax, logic, efficiency, and PEP 8 issues with fixes.
- **[Retail Analytics Dashboard](https://github.com/Adarsh04Arun/Retail-Analytics-Dashboard)** — Apriori market-basket rules and RFM customer segmentation over a year of UCI Online Retail transactions.
- **[Multi-Client Group Chat](https://github.com/Adarsh04Arun/Group-Chatting-Application)** — Low-latency messaging on raw Java TCP/IP sockets; multi-threaded server with synchronized broadcasting.

</details>

---

## ▸ Open source

**[roostorg/osprey #451](https://github.com/roostorg/osprey/pull/451)** — merged upstream into
Roost's trust &amp; safety rules engine.

> `docker compose up` failed on Windows because Git's default `core.autocrlf=true` checks out
> `*.sh` with CRLF, turning the shebang into `#!/bin/bash\r` — surfacing as a misleading
> `no such file or directory`. The repo's pre-commit hook fixed line endings at *commit* time;
> nothing enforced LF at *checkout* time. Two lines of `.gitattributes`, zero content churn.

---

## ▸ Stack

<img alt="Python" src="https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=5b8aae">
<img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-0d1117?style=flat-square&logo=typescript&logoColor=5b8aae">
<img alt="Rust" src="https://img.shields.io/badge/Rust-0d1117?style=flat-square&logo=rust&logoColor=5b8aae">
<img alt="Java" src="https://img.shields.io/badge/Java-0d1117?style=flat-square&logo=openjdk&logoColor=5b8aae">
<img alt="C++" src="https://img.shields.io/badge/C%2B%2B-0d1117?style=flat-square&logo=cplusplus&logoColor=5b8aae">
<img alt="SQL" src="https://img.shields.io/badge/SQL-0d1117?style=flat-square&logo=postgresql&logoColor=5b8aae">
<br>
<img alt="LangChain" src="https://img.shields.io/badge/LangChain-0d1117?style=flat-square&logo=langchain&logoColor=5fc99a">
<img alt="LlamaIndex" src="https://img.shields.io/badge/LlamaIndex-0d1117?style=flat-square&logo=llamaindex&logoColor=5fc99a">
<img alt="Gemini" src="https://img.shields.io/badge/Gemini%20API-0d1117?style=flat-square&logo=googlegemini&logoColor=5fc99a">
<img alt="Claude" src="https://img.shields.io/badge/Claude%20API-0d1117?style=flat-square&logo=claude&logoColor=5fc99a">
<img alt="TensorFlow" src="https://img.shields.io/badge/TensorFlow-0d1117?style=flat-square&logo=tensorflow&logoColor=5fc99a">
<img alt="scikit-learn" src="https://img.shields.io/badge/scikit--learn-0d1117?style=flat-square&logo=scikitlearn&logoColor=5fc99a">
<br>
<img alt="Next.js" src="https://img.shields.io/badge/Next.js-0d1117?style=flat-square&logo=nextdotjs&logoColor=c9d1d9">
<img alt="React" src="https://img.shields.io/badge/React-0d1117?style=flat-square&logo=react&logoColor=c9d1d9">
<img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-0d1117?style=flat-square&logo=fastapi&logoColor=c9d1d9">
<img alt="Docker" src="https://img.shields.io/badge/Docker-0d1117?style=flat-square&logo=docker&logoColor=c9d1d9">
<img alt="GCP" src="https://img.shields.io/badge/Google%20Cloud-0d1117?style=flat-square&logo=googlecloud&logoColor=c9d1d9">
<img alt="MongoDB" src="https://img.shields.io/badge/MongoDB-0d1117?style=flat-square&logo=mongodb&logoColor=c9d1d9">
<img alt="Linux" src="https://img.shields.io/badge/UNIX%2FWSL-0d1117?style=flat-square&logo=linux&logoColor=c9d1d9">

<sub>**Security** — LLM guardrails · prompt-injection defense · MITRE ATT&amp;CK mapping · DFIR pipelines · alert triage · compliance architecture<br>
**AI** — RAG · contextual bandits · Model Context Protocol · multi-agent orchestration</sub>

---

## ▸ How I think about it

> **Threat-model before you optimize.**
>
> **A guardrail you cannot audit is a guess.**
>
> **Latency and cost are safety properties too.**

<div align="center">
<br>
<sub><a href="https://adarsh04arun.in">adarsh04arun.in</a> &nbsp;·&nbsp; the site has a terminal — type <code>help</code></sub>
</div>
