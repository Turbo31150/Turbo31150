<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a1b27,100:00ffd1&height=180&section=header&text=Projets%20de%20Franck%20Delmas&fontSize=42&fontColor=ffffff&fontAlignY=35&desc=Catalogue%20complet%20%E2%80%94%20106%20repos%20%C2%B7%201.3%20GB%20code&descSize=18&descAlignY=58&animation=fadeIn" width="100%" />

</div>

---

## 📖 Lecture rapide

| Total | Public | Privé | Archived | Stack dominante |
|:---:|:---:|:---:|:---:|:---:|
| **106 repos** | 44 | 62 | 49 (itérations) | Python (51) + TS (8) + Bash/PS (6) |

**Niveau évalué (16 axes)** : Lead × 1 · Expert × 5 · Senior+ × 3 · Senior × 5 · Confirmé × 4 · Junior × 1

> 🔒 Les 62 repos privés (trading prod, outils business B2B, hackathons sous NDA) ne sont pas listés ici.
> Détails sur demande, sous accord de confidentialité.

---

## 🏆 Projets phares

---

### JARVIS OS — Distributed AI Operating System

[![Repo](https://img.shields.io/badge/GitHub-jarvis--linux-181717?style=flat-square&logo=github)](https://github.com/Turbo31150/jarvis-linux)
[![Stars](https://img.shields.io/github/stars/Turbo31150/jarvis-linux?style=flat-square&color=00ffd1)](https://github.com/Turbo31150/jarvis-linux)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](https://github.com/Turbo31150/jarvis-linux)
[![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)](https://github.com/Turbo31150/jarvis-linux)

A 9-layer autonomous operating system spanning boot to voice, running **928 AI agents** across a 6-GPU cluster.
Score **98/100 Claude Code**. JARVIS coordinates multi-model inference, voice pipelines, trading engines,
browser automation, and self-healing domino chains — all on Linux, **zero cloud**.

| Metric | Value |
|--------|-------|
| **Autonomous agents** | 928 across distributed nodes |
| **Voice commands** | 2 658 recognized, Whisper CUDA pipeline (&lt;300ms p95) |
| **MCP handlers** | 88+ orchestrated via Claude Agent SDK |
| **Domino chains** | 835 automation pipelines, self-healing |
| **Trading engine** | 6-model consensus, MEXC Futures, 800+ pairs |
| **Inference** | 6 NVIDIA GPUs / 46GB VRAM, LM Studio + Ollama |
| **License** | MIT — open-source |

```text
Layer 9  ─  Vocal / Conversational interface
Layer 8  ─  Multi-Agent Orchestration
Layer 7  ─  Trading Consensus Engine
Layer 6  ─  Browser & Web Automation
Layer 5  ─  MCP Tool Registry
Layer 4  ─  GPU Cluster Management
Layer 3  ─  Domino Pipeline Engine
Layer 2  ─  systemd Service Layer
Layer 1  ─  Linux Boot Integration
```

**Ecosystem :**
[`jarvis-cowork`](https://github.com/Turbo31150/jarvis-cowork) — 249 agents · 570+ QA scripts · auto-repair |
[`jarvis-core`](https://github.com/Turbo31150/jarvis-core) — Unified orchestration engine · 26 modules |
[`JARVIS-OMEGA`](https://github.com/Turbo31150/JARVIS-OMEGA) — Distributed AI OS · 961 agents · zero cloud

---

### TradeOracle — Multi-Model Consensus Trading

[![Repo](https://img.shields.io/badge/GitHub-TradeOracle-181717?style=flat-square&logo=github)](https://github.com/Turbo31150/TradeOracle)
[![Stars](https://img.shields.io/github/stars/Turbo31150/TradeOracle?style=flat-square&color=00ffd1)](https://github.com/Turbo31150/TradeOracle)
[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://github.com/Turbo31150/TradeOracle)

Algorithmic trading engine using **multi-model AI consensus** (Claude · Gemini · GPT · DeepSeek · Mistral · Qwen).
Detects BREAKOUT, REVERSAL, and MOMENTUM patterns with automatic TP/SL placement on MEXC Futures across 800+ pairs.
**Production live**.

| Feature | Detail |
|---------|--------|
| **Consensus** | 6 AI models vote on every signal — majority required |
| **Patterns** | BREAKOUT / REVERSAL / MOMENTUM detection |
| **Exchange** | MEXC Futures, real-time execution |
| **Alerts** | Telegram notifications, dashboard integration |
| **Backtesting** | Monte Carlo simulations via Nexus-Elastic |
| **Iterations** | 22 versions itérées (publics + privés) |

**Related repos :**
[`TradeOracle-Nexus-Elastic`](https://github.com/Turbo31150/TradeOracle-Nexus-Elastic) — Elasticsearch financial intelligence + Monte Carlo |
[`tradingviewMaison`](https://github.com/Turbo31150/tradingviewMaison) — Local TradingView clone with MEXC orderbook live |
[`gemini-live-trading-agent`](https://github.com/Turbo31150/gemini-live-trading-agent) — Voice-driven trading

---

### JARVIS-CLUSTER — Enterprise Docker Swarm AI Infra

[![Repo](https://img.shields.io/badge/GitHub-JARVIS--CLUSTER-181717?style=flat-square&logo=github)](https://github.com/Turbo31150/JARVIS-CLUSTER)
[![Stars](https://img.shields.io/github/stars/Turbo31150/JARVIS-CLUSTER?style=flat-square&color=00ffd1)](https://github.com/Turbo31150/JARVIS-CLUSTER)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)](https://github.com/Turbo31150/JARVIS-CLUSTER)

Multi-node AI infrastructure with Docker Swarm orchestration across 6 GPUs.
**928 agents** managed across 4 inference backends (LM Studio M1/M2 + Ollama OL1 + GPU local) with **failover &lt;2s**.

**Highlights**
- Layer caching obsessionnel : builds GPU **12 min → 30s**
- GPU passthrough avec `--gpus all` + `nvidia-container-toolkit`
- Healthchecks customs par backend (HTTP `/v1/models` + métriques GPU)
- Bascule de traffic intelligente, pas naïve

---

### jarvis-mcp-toolkit — 88+ MCP Handlers

[![Repo](https://img.shields.io/badge/GitHub-jarvis--mcp--toolkit-181717?style=flat-square&logo=github)](https://github.com/Turbo31150/jarvis-mcp-toolkit)
[![MCP](https://img.shields.io/badge/MCP-Early%20Adopter-00ffd1?style=flat-square)](https://github.com/Turbo31150/jarvis-mcp-toolkit)

**Early adopter MCP** — premiers commits Q1 2025, alors qu'Anthropic a publié le protocole fin 2024.
88+ handlers MCP pour agents autonomes, intégration Claude Agent SDK profonde, multi-model consensus.
Avantage compétitif rare en France 2026.

**Related :**
[`browser-mcp-orchestrator`](https://github.com/Turbo31150/browser-mcp-orchestrator) — Dual-browser CDP automation · 18 actions

---

### jarvis-whisper-flow — Real-time CUDA Voice AI

[![Repo](https://img.shields.io/badge/GitHub-jarvis--whisper--flow-181717?style=flat-square&logo=github)](https://github.com/Turbo31150/jarvis-whisper-flow)
[![Stars](https://img.shields.io/github/stars/Turbo31150/jarvis-whisper-flow?style=flat-square&color=00ffd1)](https://github.com/Turbo31150/jarvis-whisper-flow)
[![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)](https://github.com/Turbo31150/jarvis-whisper-flow)

Real-time voice-to-text pipeline with **&lt;300ms p95 latency** on local GPU.
Continuous voice recognition · speaker diarization · native MCP integration · zero cloud.

**Optimisations clés :** chunking streaming CUDA · VAD pour couper les silences · GPU passthrough sans wrapper Python.

---

### lumen — Real-time Multilingual Transcription UI

[![Repo](https://img.shields.io/badge/GitHub-lumen-181717?style=flat-square&logo=github)](https://github.com/Turbo31150/lumen)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://github.com/Turbo31150/lumen)
[![React](https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black)](https://github.com/Turbo31150/lumen)

React 19 web application — live multilingual transcription · **50+ langues** · Whisper large-v3.
5 workspaces · AI translation · TTS synthesis · JARVIS cluster integration.

---

### turbo — JARVIS Dashboard

[![Repo](https://img.shields.io/badge/GitHub-turbo-181717?style=flat-square&logo=github)](https://github.com/Turbo31150/turbo)
[![Stars](https://img.shields.io/github/stars/Turbo31150/turbo?style=flat-square&color=00ffd1)](https://github.com/Turbo31150/turbo)

Real-time GPU cluster monitoring · WebSocket live data · cyberpunk UI · 6 GPUs santé tracking.

---

## 📚 Outils &amp; bibliothèques

---

### bibliotheque-prompts-multi-ia — 397+ Optimized Prompts

[![Repo](https://img.shields.io/badge/GitHub-bibliotheque--prompts--multi--ia-181717?style=flat-square&logo=github)](https://github.com/Turbo31150/bibliotheque-prompts-multi-ia)

Library curated of **397+ production-tested prompts** optimized for Claude · GPT · Gemini · Mistral.
Organisée par domaine (coding · trading · analysis · creative) avec benchmarks per model.

---

### awesome-local-ai — Self-host AI Resources

[![Repo](https://img.shields.io/badge/GitHub-awesome--local--ai-181717?style=flat-square&logo=github)](https://github.com/Turbo31150/awesome-local-ai)

Collection de ressources pour self-host AI · GPU optimisation · LM Studio · Ollama · Whisper · MCP.

---

## 🏆 Hackathons (publics)

| Hackathon | Repo | Stack |
|---|---|---|
| **Milan AI Agent Olympics** (lablab.ai) | [`jarvis-multi-agent-orchestra`](https://github.com/Turbo31150/jarvis-multi-agent-orchestra) | FastAPI · async multi-agent |
| **Splunk Agentic Ops 2026** | [`splunk-agentic-ops`](https://github.com/Turbo31150/splunk-agentic-ops) | 5-agent autonomous ops |
| **ZerveHack 2026** | [`zervehack-jarvis`](https://github.com/Turbo31150/zervehack-jarvis) | Local AI multi-agent |
| **DSH Hacks V1 2026** | [`dsh-hacks-jarvis`](https://github.com/Turbo31150/dsh-hacks-jarvis) | Multi-agent data analytics |
| **Find Evil Hackathon** | [`find-evil-jarvis`](https://github.com/Turbo31150/find-evil-jarvis) | Cybersecurity multi-agent |
| **GenLink Hacks 2026** | [`genlink-jarvis-agent`](https://github.com/Turbo31150/genlink-jarvis-agent) | Semantic link graph LLM |
| **GenZ Can Hack 2026** | [`genz-can-hack`](https://github.com/Turbo31150/genz-can-hack) | AI productivity |
| **Hackathon Hex 2026** | [`school-crypto-timing`](https://github.com/Turbo31150/school-crypto-timing) | School schedule + ML crypto |
| **Orion Build 2026** | [`orion-fintech-agent`](https://github.com/Turbo31150/orion-fintech-agent) | AI credit scoring |
| **Agents Assemble Healthcare** | [`agents-assemble-healthcare`](https://github.com/Turbo31150/agents-assemble-healthcare) | Multi-agent healthcare |
| **MeDo Mental Health** | [`medo-mental-health-agent`](https://github.com/Turbo31150/medo-mental-health-agent) | Conversational AI wellness |
| **ElevenLabs AI 2026** | [`jarvis-voice-platform`](https://github.com/Turbo31150/jarvis-voice-platform) | TTS + Whisper STT pipeline |

> + 5 hackathons privés (sous NDA) non listés ici.

---

## 🗺️ Vue d'ensemble (catégories)

```
Turbo31150/
├── JARVIS Ecosystem (8 repos · 742 MB)
│   ├── jarvis-linux .............. Core OS · 928 agents · 9 layers
│   ├── jarvis-core ............... Unified orchestration · 26 modules
│   ├── jarvis-cowork ............. 249 agents · auto-repair
│   ├── jarvis-whisper-flow ....... Voice <300ms p95
│   ├── JARVIS-CLUSTER ............ Docker Swarm enterprise · 6 GPUs
│   ├── JARVIS-OMEGA .............. Distributed AI OS · 961 agents
│   ├── jarvis-multi-agent-orchestra .. Async parallel agents
│   └── jarvis-mcp-toolkit ........ 88+ MCP handlers · early adopter
│
├── Trading (5 publics · 17 privés)
│   ├── TradeOracle ............... Multi-model consensus · live
│   ├── TradeOracle-Nexus-Elastic . Elasticsearch · Monte Carlo
│   ├── tradingviewMaison ......... Local TradingView clone
│   ├── gemini-live-trading-agent . Voice-driven trading
│   └── (17 repos privés sous NDA)
│
├── Voice / Speech / Multilangue
│   ├── lumen ..................... React 19 · 50+ langues
│   ├── jarvis-whisper-flow ....... Pipeline CUDA <300ms
│   └── jarvis-voice-platform ..... ElevenLabs + Whisper
│
├── MCP / Claude Agent SDK
│   ├── jarvis-mcp-toolkit ........ 88+ handlers
│   ├── browser-mcp-orchestrator .. CDP dual-browser
│   └── (3 repos privés)
│
├── Cluster / Infra
│   ├── JARVIS-CLUSTER ............ Docker Swarm · failover <2s
│   ├── turbo ..................... GPU monitoring dashboard
│   └── (3 repos privés ops/SSH)
│
├── Hackathons (12 publics · 5 privés)
│   ├── Milan AI Olympics · Splunk · ZerveHack · DSH · Hex · Orion
│   ├── ElevenLabs · GenZ · Find Evil · GenLink · Healthcare · MeDo
│   └── (5 hackathons privés sous NDA)
│
├── Business / Automation B2B (privé)
│   └── (9 repos non listés — facturation · prospection · SaaS productivity)
│
└── Resources publiques
    ├── bibliotheque-prompts-multi-ia .. 397+ prompts optimisés
    └── awesome-local-ai ............... Self-host AI resources
```

---

<div align="center">

[![Profile](https://img.shields.io/badge/%E2%86%A9%20Back%20to%20Profile-00ffd1?style=for-the-badge&logo=github&logoColor=0d1117)](https://github.com/Turbo31150)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a1b27,100:00ffd1&height=100&section=footer" width="100%" />

*Production-first autodidact · Mon GitHub est mon diplôme.*

</div>
