# Adarsh Arun

**AI Safeguards Engineer** · Bengaluru, India

I work where ML systems meet adversaries. Most of what I build answers one question:
**what happens when this model is given something it should refuse?**

Currently building guardrails for agentic healthcare AI **@ XelerAIT**.
CS undergrad at BNMIT (CGPA 9.70).

[![Portfolio](https://img.shields.io/badge/portfolio-adarsh04arun.in-5b8aae?style=flat-square)](https://adarsh04arun.in)
[![LinkedIn](https://img.shields.io/badge/linkedin-adarsh3arun-0a66c2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/adarsh3arun)
[![Email](https://img.shields.io/badge/email-adarsh3arun@gmail.com-5fc99a?style=flat-square)](mailto:adarsh3arun@gmail.com)

---

## What I'm working on

```
PROMPT ──▶ BROKER ──▶ SCHEMA ──▶ MODEL ──▶ AUDIT
untrusted   regex +   structured  policy-   verdict
  input    metaprompt    json    bound call   log
```

- **[Wardline](https://github.com/Adarsh04Arun/Wardline)** — an embeddable guardrail evaluation
  library for Rust. Guards run inline in the request path and return a blocking verdict:
  allow, block, or modify. A library you call in-process, not a proxy you deploy — no network
  hop, no async runtime. Guards are ordinary Rust implementing one trait, so they're testable
  like any other code. *(pre-alpha · Apache-2.0 / MIT)*
- **Guardrails for production agentic AI in healthcare @ XelerAIT** — safety, reliability, and
  compliance enforced at the framework layer rather than bolted on after an incident.
- **AI red-teaming** — evaluation harnesses for agentic systems, adversarial robustness, and more
  upstream contributions to open-source trust & safety tooling.

## Selected work

| Project | What it is |
|---|---|
| [Wardline](https://github.com/Adarsh04Arun/Wardline) | Embeddable, synchronous, trait-based guardrail library for Rust. Four-crate workspace with panic isolation and a bounded audit trace. |
| [ISTVON Prompt Review Engine](https://github.com/Adarsh04Arun/ISTVON-Prompt-Review-Engine) | Security broker for LLM prompts — dual-layer regex + metaprompt screening, JSON structuring that isolates malicious payloads, audited verdicts. |
| [Vendor Risk Assessor](https://github.com/Adarsh04Arun/Kaggle_AI_Agent_-Vendor-Risk-Assessment-) | Hierarchical Google ADK agent pipeline over an MCP tool server. Risk score computed deterministically in Python — the LLM writes prose, never the number. *(Kaggle Agentic AI Competition)* |
| [Telecom SOC Simulation](https://github.com/Adarsh04Arun/Telecom-SOC) | DFIR automation with RAG-backed MITRE ATT&CK mapping over MDE investigation packages. |
| [Adaptive Triage Engine](https://github.com/Adarsh04Arun/Adaptive-Triage-Engine-for-SOC) | Contextual-bandit RL policy that scores and triages SOC alerts from forensic feature data. |
| [Satellite Land-Use Classification](https://github.com/Adarsh04Arun/Satellite-Image-Classification-for-Land-Use-Custom_CNN-ResNet50-VGG16-) | Custom CNN vs. ResNet50 vs. VGG16, benchmarked head-to-head on EuroSAT imagery. |

## Open source

- **[roostorg/osprey #451](https://github.com/roostorg/osprey/pull/451)** — merged upstream into
  Roost's trust & safety rules engine. `docker compose up` failed on Windows because Git's default
  `core.autocrlf=true` checks out `*.sh` with CRLF, turning the shebang into `#!/bin/bash\r`. The
  repo's pre-commit hook fixed line endings at *commit* time; nothing enforced LF at *checkout*
  time. Two lines of `.gitattributes`, zero content churn.

## Stack

**Languages** — Python · TypeScript · Rust · Java · C/C++ · SQL

**AI / ML** — LangChain · LlamaIndex · Google ADK · MCP · Gemini API · Claude API · TensorFlow ·
scikit-learn · RAG · contextual bandits · multi-agent orchestration

**Security** — LLM guardrails · prompt-injection defense · MITRE ATT&CK mapping · DFIR pipelines ·
alert triage · compliance architecture

**Systems** — Next.js · React · Node.js · FastAPI · Docker · AWS · GCP · MongoDB · UNIX/WSL

## How I think about it

> Threat-model before you optimize.
>
> A guardrail you cannot audit is a guess.
>
> Latency and cost are safety properties too.

---

<div align="center">

![Adarsh's GitHub stats](https://github-readme-stats.vercel.app/api?username=Adarsh04Arun&show_icons=true&hide_border=true&theme=dark&hide_title=true)

</div>
