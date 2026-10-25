<div align="center">

<img src="assets/header.svg" alt="Anshul Sharma — AI/ML Engineer · Agent Harness Engineering · Construction AI" width="100%"/>

<a href="https://github.com/AnshulSharma9340">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=2600&pause=900&color=A78BFA&center=true&vCenter=true&width=820&height=40&lines=Building+agents+that+read+construction+drawings+%F0%9F%8F%97%EF%B8%8F;Harness+engineering+%C2%B7+tool+use+%C2%B7+MCP+%C2%B7+evals;Fine-tuning+LLMs+on+a+4+GB+GPU+%E2%9A%A1;Real-time+voice+AI+%E2%80%94+question+to+answer+in+~3+s" alt="Typing SVG"/>
</a>

<br/>

<a href="https://www.linkedin.com/in/anshulaiml/"><img src="https://img.shields.io/badge/LinkedIn-anshulaiml-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://portfolio-sandy-five-8ulr675iy1.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-Visit-111827?style=for-the-badge&logo=vercel&logoColor=white"/></a>
<a href="mailto:anshulsharma7162@gmail.com"><img src="https://img.shields.io/badge/Email-anshulsharma7162%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<img src="https://komarev.com/ghpvc/?username=AnshulSharma9340&label=Profile%20views&color=7c3aed&style=for-the-badge" alt="Profile views"/>

</div>

---

## ⚡ `whoami`

```python
from dataclasses import dataclass

@dataclass(frozen=True)
class AnshulSharma:
    role      = "AI/ML Engineer @ Rapid Innovation"
    focus     = ("Construction AI", "Agent harness engineering", "Real-time voice AI")
    building  = [
        "multi-agent systems that review construction scopes against drawing sets",
        "agent harnesses: tool use, MCP servers, sandboxing, evals, retries",
        "streaming speech → LLM pipelines that answer in ~3 seconds",
    ]
    trains    = ["QLoRA / Unsloth fine-tunes", "reasoning distillation", "small LLMs end to end"]
    education = "B.Tech CSE (Data Science) · ITM Gwalior · 2023–2027"
    motto     = "Ship it. Measure it. Make it 10x faster."
```

---

## 🏗️ What I'm building now

<table>
<tr>
<td width="33%" valign="top">

### 🏗️ Construction AI
Agents that read a **Scope of Work** and a full **drawing set**, do a visual take-off of every sheet, and cross-check the two in both directions. Each finding carries its proof: the exact quote, the sheet, and a highlighted crop.

</td>
<td width="33%" valign="top">

### 🧩 Harness Engineering
The layer that makes LLMs **reliable**: orchestration of parallel specialist agents, independent QA passes that reject unproven claims, sealed tool sandboxes, MCP servers, streaming, retries and evals.

</td>
<td width="33%" valign="top">

### 🎙️ Real-time Voice AI
Streaming speech recognition on a consumer GPU, then a **primed LLM pool** for first words in ~2 s. Also from-scratch speech enhancement (VAD + echo cancellation + denoising) in a 20 ms pass.

</td>
</tr>
</table>

---

## 🚀 Featured work

<table>
<tr>
<td width="50%" valign="top">

### 🎙️ [Cue — Real-time Interview Copilot](https://github.com/AnshulSharma9340/cue-interview-copilot)
Listens to a call, transcribes both sides with **local Whisper on the GPU**, detects questions and streams an answer **~3 s** after the question ends. No API keys needed.<br/>
<img src="https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white"/> <img src="https://img.shields.io/badge/faster--whisper-FF6F00?style=flat-square"/> <img src="https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white"/> <img src="https://img.shields.io/badge/WebSockets-010101?style=flat-square"/>

</td>
<td width="50%" valign="top">

### 🏗️ [SOW Agent — Construction Scope Intelligence](https://github.com/AnshulSharma9340/Subcontractor-sow-agent)
Reviews a trade's **Scope of Work against the drawing set**: Claude vision take-off per sheet, **7 specialist agents** in parallel, and an independent QA pass. Every finding shows its proof.<br/>
<img src="https://img.shields.io/badge/Claude%20Opus-D97757?style=flat-square&logo=anthropic&logoColor=white"/> <img src="https://img.shields.io/badge/Multi--Agent-7C3AED?style=flat-square"/> <img src="https://img.shields.io/badge/PyMuPDF-0F172A?style=flat-square"/> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧠 [ReasonMind-3B — Reasoning Distillation](https://github.com/AnshulSharma9340/ReasonMind-3B)
Distils **DeepSeek-R1-style chain-of-thought** into Llama-3.1 3B with **Unsloth + 4-bit QLoRA**, training about 0.5% of the parameters, with a `<think>` phase. Shipped as **GGUF** for offline inference.<br/>
<img src="https://img.shields.io/badge/Llama%203.1-0467DF?style=flat-square&logo=meta&logoColor=white"/> <img src="https://img.shields.io/badge/Unsloth-111827?style=flat-square"/> <img src="https://img.shields.io/badge/QLoRA-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/> <img src="https://img.shields.io/badge/GGUF-334155?style=flat-square"/>

</td>
<td width="50%" valign="top">

### 🔊 [Lyra-Audio — Real-time Speech Enhancement](https://github.com/AnshulSharma9340/lyra-audio-model)
A from-scratch **VAD + echo cancellation + noise suppression** model in one ~20 ms pass (DeepFilterNet-style U-Net + GRU). **~250× real time** on an RTX 2050, +2.76 dB SI-SDR.<br/>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/> <img src="https://img.shields.io/badge/DSP-0EA5E9?style=flat-square"/> <img src="https://img.shields.io/badge/LibriSpeech-334155?style=flat-square"/>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🛡️ [MedSafeNet — Medical AI Guardrail](https://github.com/AnshulSharma9340/MedSafeNet)
A **DistilBERT safety classifier** (safe / medical / dangerous / self-harm / misinformation) that filters queries in real time before generation, served over **FastAPI** with streaming.<br/>
<img src="https://img.shields.io/badge/DistilBERT-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>

</td>
<td width="50%" valign="top">

### 🔬 [Custom-Nano — 3B LLM, end to end](https://github.com/AnshulSharma9340/Custom-nano)
Training a custom **3B-parameter LLM** with Karpathy's *nanochat* pipeline, from tokenizer through pretraining to SFT, with my own SFT data mixes.<br/>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/> <img src="https://img.shields.io/badge/Pretraining-7C3AED?style=flat-square"/> <img src="https://img.shields.io/badge/SFT-0F172A?style=flat-square"/>

</td>
</tr>
</table>

<details>
<summary><b>➕ More projects</b></summary>
<br/>

| Project | What it is |
|---|---|
| [Luminal](https://github.com/AnshulSharma9340/luminal-ai-research-engine) · [NEXUS-AI](https://github.com/AnshulSharma9340/NEXUS-AI) | Perplexity-style research engines: live search, extraction, Gemini synthesis with citations |
| [Slate](https://github.com/AnshulSharma9340/Slate) | Local-first notes + infinite whiteboard + links (Electron, React, SQLite) |
| [Employee Insight Engine](https://github.com/AnshulSharma9340/Employee-Insight-Engine) | 4 ML models for attrition and performance prediction |
| [PneumoScan AI](https://github.com/AnshulSharma9340/PneumoScan-AI) | Pneumonia detection from chest X-rays |
| [Suspicious Transaction Detection](https://github.com/AnshulSharma9340/Online-suspicious-transaction-detection-) | Real-time anomaly detection with a Streamlit UI |
| [DisciplineX](https://github.com/AnshulSharma9340/Discipline-X) | Accountability platform: FastAPI, Supabase, React, Socket.IO |

</details>

---

## 💼 Experience

| | Role | Highlights |
|:---:|---|---|
| 🟢 **Now** | **AI/ML Engineer · Rapid Innovation** | Construction-intelligence agents · agent harness engineering · production LLM integrations |
| 2025 | **Data Analytics Intern · Veridia.io** | Built a **Resume Intelligence System**: ML candidate scoring and categorization |
| 2025 | **Machine Learning Intern · Cognify Technologies** | **Employee Insight Engine**: 4 models for attrition and performance prediction |
| Earlier | **Data Science Intern · Prodigy Infotech** | Live **suspicious transaction detection** using anomaly detection |

---

## 🧰 Arsenal

<div align="center">

**🤖 LLMs & Agents**<br/>
<img src="https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white"/>
<img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white"/>
<img src="https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white"/>
<img src="https://img.shields.io/badge/MCP-0F172A?style=for-the-badge&logo=anthropic&logoColor=white"/>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white"/>
<img src="https://img.shields.io/badge/RAG-7C3AED?style=for-the-badge"/>

**🧪 Training & Models**<br/>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>
<img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/>
<img src="https://img.shields.io/badge/Unsloth-111827?style=for-the-badge"/>
<img src="https://img.shields.io/badge/QLoRA%20%2F%20PEFT-334155?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Whisper-FF6F00?style=for-the-badge"/>
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white"/>

**🛠️ Engineering**<br/>
<img src="https://skillicons.dev/icons?i=python,ts,cpp,fastapi,flask,nodejs,react,nextjs,electron,tailwind,postgres,mongodb,redis,supabase,docker,githubactions,gcp,azure,linux&perline=10" alt="Engineering stack"/>

</div>

---

## 📊 GitHub in numbers

<div align="center">

<img width="100%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=AnshulSharma9340&theme=tokyonight" alt="Profile summary"/>

<img height="170" src="https://github-readme-stats-salesp07.vercel.app/api?username=AnshulSharma9340&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&rank_icon=github" alt="GitHub stats"/>
<img height="170" src="https://github-readme-stats-salesp07.vercel.app/api/top-langs/?username=AnshulSharma9340&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top languages"/>

<img src="https://streak-stats.demolab.com?user=AnshulSharma9340&theme=tokyonight&hide_border=true" alt="GitHub streak"/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AnshulSharma9340/AnshulSharma9340/output/github-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/AnshulSharma9340/AnshulSharma9340/output/github-snake.svg"/>
  <img alt="Contribution snake" src="https://raw.githubusercontent.com/AnshulSharma9340/AnshulSharma9340/output/github-snake.svg"/>
</picture>

</div>

---

## 🏅 Certifications

<details>
<summary><b>View 10+ verified credentials</b></summary>
<br/>

| ☁️ Cloud | Issuer |
|---|---|
| Oracle Cloud Infrastructure & Data Science Professional | Oracle |
| Azure Developer Associate | Microsoft |
| Google Cloud Data Analytics | Google Cloud |

| 🧠 AI / ML & Development | Issuer |
|---|---|
| Deep Learning | NPTEL · IIT Ropar |
| Google AI/ML Internship | Eduskills · AICTE |
| Python Full Stack Developer | Eduskills · AICTE |
| Data Science | Cisco |
| Data Analytics Internship | Alteryx |

</details>

---

<div align="center">

### 🤝 Let's build something intelligent

Open to collaborations on **agents**, **LLM infrastructure** and **voice AI**.

<a href="https://www.linkedin.com/in/anshulaiml/"><img src="https://img.shields.io/badge/-Connect%20on%20LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/></a>
<a href="mailto:anshulsharma7162@gmail.com"><img src="https://img.shields.io/badge/-Say%20hello-EA4335?style=flat-square&logo=gmail&logoColor=white"/></a>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7c3aed,50:0ea5e9,100:10b981&height=120&section=footer" width="100%"/>

</div>
