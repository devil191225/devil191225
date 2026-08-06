<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=1000&size=28&pause=1000&color=00D4FF&center=true&vCenter=true&width=700&lines=Security+Engineer+%7C+AI+Researcher;Adversarial+ML+%7C+Agentic+Systems;Bug+Bounty+%7C+Red+Team+Tooling;Building+at+the+intersection+of+AI+%2B+Security" alt="Typing SVG" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/aditya-srikar-konduri/)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ask92@duke.edu)

</div>

---

## About Me

Security engineer focused on **agentic AI** and **offensive + defensive security tooling**. I build systems where LLMs and agents don't just generate text — they drive real investigations and attacks: AI-assisted SOC triage platforms, autonomous bug bounty pipelines, and DFIR agents that orchestrate actual tools end-to-end.

I've operated on both sides of the fence:
- **Blue Team / DFIR / Threat Intel** — Tesla, Palo Alto Networks Unit 42, Duke × Recorded Future
- **Offensive Research & Bug Bounty** — critical and high-severity findings in large production environments

**Current focus:** agentic security systems, adversarial AI, attested forensics, and security data pipelines that turn noisy telemetry into reliable decisions and exploits. Right now I'm building AI-native security tooling across the full stack — an agentic Bug Bounty OS, AI-driven SOC triage, and an agentic DFIR assistant — to prove that one person with the right agents can do the work of an entire small security team.

> **7 repos are public** (research + defensive tooling). Advanced offensive/defensive infrastructure remains private — access granted on request. Reach out directly if you're a recruiter, researcher, or potential collaborator.

---

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**AI / ML**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Claude](https://img.shields.io/badge/Claude_MCP-CC785C?style=flat-square&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)

**Security**

![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=portswigger&logoColor=white)
![MITRE ATT&CK](https://img.shields.io/badge/MITRE_ATT%26CK-C00000?style=flat-square)
![Nuclei](https://img.shields.io/badge/Nuclei-00BFFF?style=flat-square)
![OWASP](https://img.shields.io/badge/OWASP-000000?style=flat-square&logo=owasp&logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat-square&logo=splunk&logoColor=white)
![Microsoft Sentinel](https://img.shields.io/badge/Microsoft_Sentinel-0078D4?style=flat-square&logo=microsoft&logoColor=white)
![Volatility](https://img.shields.io/badge/Volatility-4A4A4A?style=flat-square)
![MISP](https://img.shields.io/badge/MISP-1A1A2E?style=flat-square)
![Velociraptor](https://img.shields.io/badge/Velociraptor-6A0DAD?style=flat-square)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![CrowdStrike](https://img.shields.io/badge/CrowdStrike-E01B22?style=flat-square)

**Infrastructure**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)

---

## Projects

### Security Engineering & Agentic Systems

| | Project | Description | Stack | LOC |
|-|---------|-------------|-------|-----|
| 🔓 | [**risk-agent**](https://github.com/ASK191225/risk-agent) | Agentic cyber risk assessment pipeline for Claude Code. 12-stage subagent workflow: scenario in, top-5 prioritized risks with mitigations, residual estimates, and NIST CSF / ISO 27001 / SOC 2 alignment out. Schema-validated artifacts, policy engine, and skeptic pass with human-review flags | Python · Claude Code · Pydantic | 3.4K |
| 🔒 | [**endpoint-intelligence-agent**](https://github.com/ASK191225/endpoint-intelligence-agent) | Production-grade zero-trust endpoint intelligence platform. Tamper-proof Ed25519 audit logging, WORM storage, Streamlit SOC dashboard, Kubernetes-ready deployment | Python · React · K8s | 30K |
| 🔒 | [**agentic-soc**](https://github.com/ASK191225/agentic-soc) | Full-stack AI-powered Security Operations Center. 9-stage investigation lifecycle, Claude-driven analysis engine, FastAPI backend, PostgreSQL provenance tracking, Splunk integration | FastAPI · React · TS · PostgreSQL | 21K |
| 🔒 | [**threat-intel-agent**](https://github.com/ASK191225/threat-intel-agent) | MCP-backed threat intelligence chatbot. Hybrid semantic search over CVE/NVD data, SBOM processing, multi-LLM support (Claude/OpenAI/local), real-time risk scoring | Python · MCP · Streamlit | 8K |
| 🔒 | [**dfir-agentic-kit**](https://github.com/ASK191225/dfir-agentic-kit) | AI-powered DFIR investigation orchestrator. Arsenal forensic image mounter, hypothesis engine, MITRE ATT&CK automated mapping, timeline reconstruction | Python · Elasticsearch · ATT&CK | 6K |

### Adversarial AI & ML Security

| | Project | Description | Stack | LOC |
|-|---------|-------------|-------|-----|
| 🔓 | [**adversarial-ai-defense**](https://github.com/ASK191225/adversarial-ai-defense) | End-to-end adversarial patch attack and defense pipeline for computer vision models. Ensemble defense stack: entropy filtering, frequency analysis, gradient saliency maps, cyberphysical attack simulation | Python · PyTorch | 11K |
| 🔓 | [**causalguard**](https://github.com/ASK191225/causalguard) | Causal, explainable anomaly detection on industrial control system (ICS) telemetry. Evaluated on the SWaT dataset with formal verification and adversarial robustness benchmarks | Python · scikit-learn | 6K |
| 🔓 | [**lolbin-detection**](https://github.com/ASK191225/lolbin-detection) | Living-off-the-land binary (LOLBin) behavioral detection system. FastAPI backend with SQLAlchemy ORM, Streamlit dashboard, Docker-ready | Python · FastAPI · Streamlit | 14K |
| 🔒 | [**Quantum-Resistant-AI-Algorithm**](https://github.com/ASK191225/Quantum-Resistant-AI-Algorithm) | Post-quantum cryptography parameter optimizer. Genetic algorithm search over Kyber lattice parameters + ML-based vulnerability prediction | Python · React | 3K |
| 🔒 | [**real-time-voice-cloning**](https://github.com/ASK191225/real-time-voice-cloning) | Adversarial audio research pipeline — real-time voice spoofing and deepfake synthesis (SV2TTS architecture). Full encoder/synthesizer/vocoder stack with 5-second speaker adaptation. Built to understand and simulate audio-based attack surfaces for red team and detection research | Python · PyTorch | 7K |

### Bug Bounty & Offensive Tooling

| | Project | Description | Stack | LOC |
|-|---------|-------------|-------|-----|
| 🔒 | [**claude-bug-bounty**](https://github.com/ASK191225/claude-bug-bounty) | Autonomous bug bounty agent built on LangGraph ReAct. Multi-provider LLM brain (2,200-line router), intentionally vulnerable demo app for testing, HackerOne MCP server, memory system, scope enforcement | Python · LangGraph · MCP | 20K |
| 🔓 | [**bugbounty-kit**](https://github.com/ASK191225/bugbounty-kit) | Production bug bounty operations toolkit. Token scanner, HAI payload builder, RAG knowledge base, hunt journal, audit trail — full pipeline from recon to report | Python · Node.js | 17K |
| 🔒 | [**malware-lab-orchestrator**](https://github.com/ASK191225/malware-lab-orchestrator) | Air-gapped malware analysis lab orchestration system. FastAPI orchestrator, Apache Guacamole RDP integration, remote Linux agent runner | Python · FastAPI | 1.5K |

### Research & Specialized Tools

| | Project | Description | Stack | LOC |
|-|---------|-------------|-------|-----|
| 🔓 | [**qaca**](https://github.com/ASK191225/qaca) | Synthetic quantum-adaptive crypto-agility (QACA) simulator. Algorithm registry, causal graph analysis, research PoC for post-quantum migration strategies | Python | 3.5K |
| 🔓 | [**ml-ids-notebook**](https://github.com/ASK191225/ml-ids-notebook) | Machine learning intrusion detection system. Classifier benchmarks across multiple architectures with trained model artifacts included | Python · Jupyter | 3K |

---

## GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=devil191225&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=devil191225&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" />

</div>

<div align="center">

![GitHub Streak](https://streak-stats.demolab.com?user=ASK191225&theme=tokyonight&hide_border=true)

</div>

---

<div align="center">

*Building production security systems and sharing the work publicly.*
*All offensive tooling is for authorized testing, research, and education only.*

</div>
