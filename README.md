<div align="center">

<svg viewBox="0 0 620 180" xmlns="http://www.w3.org/2000/svg" font-family="'JetBrains Mono',monospace">
  <defs>
    <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1"><stop offset="0%" stop-color="#0D1117"/><stop offset="100%" stop-color="#161B22"/></linearGradient>
    <linearGradient id="g1" x1="0" y1="0" x2="1" y2="0"><stop offset="0%" stop-color="#00D4FF"/><stop offset="50%" stop-color="#7B61FF"/><stop offset="100%" stop-color="#FF6B35"/></linearGradient>
    <filter id="glow"><feGaussianBlur stdDeviation="4" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
  </defs>
  <rect width="620" height="180" rx="16" fill="url(#bg)"/>
  <rect width="620" height="180" rx="16" fill="none" stroke="#00D4FF" stroke-width="1" stroke-opacity="0.2"/>
  <!-- Neural nodes -->
  <circle cx="50" cy="90"  r="30" fill="none" stroke="#00D4FF" stroke-width="1" stroke-opacity="0.2" stroke-dasharray="3 3"/>
  <circle cx="50" cy="90"  r="18" fill="#0D1117" stroke="#00D4FF" stroke-width="2" filter="url(#glow)"/>
  <circle cx="50" cy="90"  r="8"  fill="#00D4FF" fill-opacity="0.2"/>
  <text x="50" y="97" text-anchor="middle" fill="#00D4FF" font-size="14" font-weight="800" filter="url(#glow)">T</text>
  <circle cx="50" cy="60"  r="4" fill="#00D4FF" filter="url(#glow)"/>
  <circle cx="50" cy="120" r="4" fill="#FF6B35" filter="url(#glow)"/>
  <circle cx="20" cy="90"  r="4" fill="#7B61FF" filter="url(#glow)"/>
  <circle cx="80" cy="90"  r="4" fill="#00D4FF" filter="url(#glow)"/>
  <line x1="50" y1="64"  x2="50" y2="72" stroke="#00D4FF" stroke-width="1.5" stroke-opacity="0.6"/>
  <line x1="50" y1="108" x2="50" y2="116" stroke="#FF6B35" stroke-width="1.5" stroke-opacity="0.6"/>
  <line x1="24" y1="90"  x2="32" y2="90" stroke="#7B61FF" stroke-width="1.5" stroke-opacity="0.6"/>
  <line x1="68" y1="90"  x2="76" y2="90" stroke="#00D4FF" stroke-width="1.5" stroke-opacity="0.6"/>
  <!-- Title -->
  <text x="105" y="72" fill="url(#g1)" font-size="40" font-weight="800" letter-spacing="-1" filter="url(#glow)">Turbo31150</text>
  <text x="106" y="98" fill="#8B949E" font-size="14" letter-spacing="0.5">Franc Delmas · Toulouse, France</text>
  <rect x="105" y="110" width="490" height="1.5" rx="1" fill="url(#g1)" opacity="0.3"/>
  <g transform="translate(105,124)">
    <rect x="0"   y="0" width="74" height="22" rx="5" fill="#00D4FF" fill-opacity="0.1" stroke="#00D4FF" stroke-width="0.7" stroke-opacity="0.5"/>
    <text x="37"  y="15" text-anchor="middle" fill="#00D4FF" font-size="10">AI Systems</text>
    <rect x="80"  y="0" width="80" height="22" rx="5" fill="#7B61FF" fill-opacity="0.1" stroke="#7B61FF" stroke-width="0.7" stroke-opacity="0.5"/>
    <text x="120" y="15" text-anchor="middle" fill="#7B61FF" font-size="10">GPU Clusters</text>
    <rect x="166" y="0" width="74" height="22" rx="5" fill="#FF6B35" fill-opacity="0.1" stroke="#FF6B35" stroke-width="0.7" stroke-opacity="0.5"/>
    <text x="203" y="15" text-anchor="middle" fill="#FF6B35" font-size="10">Trading AI</text>
    <rect x="246" y="0" width="86" height="22" rx="5" fill="#00D4FF" fill-opacity="0.1" stroke="#00D4FF" stroke-width="0.7" stroke-opacity="0.5"/>
    <text x="289" y="15" text-anchor="middle" fill="#00D4FF" font-size="10">Voice Platforms</text>
    <rect x="338" y="0" width="66" height="22" rx="5" fill="#7B61FF" fill-opacity="0.1" stroke="#7B61FF" stroke-width="0.7" stroke-opacity="0.5"/>
    <text x="371" y="15" text-anchor="middle" fill="#7B61FF" font-size="10">Automation</text>
  </g>
  <text x="105" y="168" fill="#484F58" font-size="10">22 repos · JARVIS·OS · JARVIS·TURBO · TRADEORACLE·AI · LUMEN·TRANSCRIBE · MIT</text>
</svg>

<br/><br/>

[![Python](https://img.shields.io/badge/Python-Expert-3776AB?style=flat-square&logo=python&logoColor=white)](#)
[![TypeScript](https://img.shields.io/badge/TypeScript-Advanced-3178C6?style=flat-square&logo=typescript&logoColor=white)](#)
[![CSharp](https://img.shields.io/badge/C%23-.NET-512BD4?style=flat-square&logo=csharp&logoColor=white)](#)
[![GPU](https://img.shields.io/badge/10_GPUs-78GB_VRAM-76B900?style=flat-square&logo=nvidia)](#)
[![JARVIS](https://img.shields.io/badge/JARVIS-OS_%2B_TURBO-7B61FF?style=flat-square)](#)
[![Repos](https://img.shields.io/badge/22_repos-publics-FF6B35?style=flat-square)](#projets)

</div>

---

## À propos

Développeur et architecte systèmes IA basé à **Toulouse, France**. Je construis des infrastructures IA distribuées, des systèmes de trading algorithmique autonomes, et des plateformes voix temps réel.

Mon infrastructure principale — **JARVIS** — est un écosystème dual : **JARVIS·OS** (Linux, cluster 4 nœuds, deepseek-r1 + qwen3, 850+ commandes vocales) et **JARVIS·TURBO** (Windows, 3 machines, 10 GPUs, 78GB VRAM, React 19 + Electron dashboard).

---

## Stack principale

```
Python 3.11 · TypeScript · C# .NET 8 · Node.js
SQLite3 · Docker · systemd · n8n
Whisper CUDA · LM Studio · Claude API · Gemini API
MEXC Futures API · Telegram Bot API · Twilio
React 19 · Vite 6 · Electron · WebSocket
```

---

## Projets phares

| Projet | Description | Stack |
|--------|-------------|-------|
| [**JARVIS·OS**](https://github.com/Turbo31150/jarvis-linux) | OS cognitif Linux — cluster 4 nœuds, 600+ MCP handlers, 850+ voice cmds | Python · TypeScript · Docker |
| [**JARVIS·TURBO**](https://github.com/Turbo31150/turbo) | Orchestrateur Windows multi-agents — 10 GPUs, React 19 dashboard, DERNI trading | Python · React 19 · Electron |
| [**TRADEORACLE·AI**](https://github.com/Turbo31150/TradeOracle) | Agent trading autonome — Gemini 3, 800+ paires MEXC, Domino Pipeline | Python · Gemini API |
| [**LUMEN·TRANSCRIBE**](https://github.com/Turbo31150/lumen-transcription-multilangue) | Transcription multilingue temps réel — 30+ langues, Whisper CUDA | TypeScript · React |
| [**WHISPERFLOW·CUDA**](https://github.com/Turbo31150/jarvis-whisper-flow) | Pipeline voix CUDA < 300ms — large-v3, JARVIS voice layer | Python · CUDA |
| [**PROMPT·VAULT**](https://github.com/Turbo31150/bibliotheque-prompts-multi-ia) | 300+ prompts optimisés — 5 IAs, Claude/GPT/Gemini/Perplexity | HTML · JSON |
| [**GITFLOW·AI**](https://github.com/Turbo31150/github-social-automation) | Automation GitHub IA — scan, Comet bridge, multi-publish, profile score | JavaScript · Node.js |
| [**ARIA·SENTINEL**](https://github.com/Turbo31150/aria-agents-hackathon) | 10 agents IA treasury risk — Monte Carlo, HITL — Airia Hackathon 2026 | Python · FastAPI |

---

## Infrastructure

```
JARVIS·OS (Linux cluster)
  Node-1 (Master)  · Node-2  · Node-3  · Cloud
  deepseek-r1      · qwen3   · compute · failover
  850+ voice cmds  · 600+ MCP handlers · WS:9742

JARVIS·TURBO (Windows)
  M1: Ryzen 7 5700X3D · 46GB · 6 GPUs (34GB VRAM)
  M2: LM Studio · qwen3-30b · deepseek-r1
  M3: 45GB RAM · 3× Quadro GPU (20GB+ VRAM)
  Dashboard: React 19 / Vite 6 / Electron
  Agents: OpenClaw 96 patterns · Whisperflow CUDA
  Trading: DERNI ULTIMATE n8n (32 nodes, MEXC)
```

---

## Hackathons

| Hackathon | Projet | Technologie |
|-----------|--------|-------------|
| **Google Cloud ADK** | TRADEORACLE·AI | Gemini 3 · MCP |
| **Google Cloud ADK** | GEMINI·LIVE·TRADER | Gemini Live API |
| **Google Cloud ADK** | GEMINI·STORYTELLER | Imagen 3 + Voice |
| **Google Cloud ADK** | GEMINI·UI·NAVIGATOR | Vision + Playwright |
| **Airia AI Agents** | ARIA·SENTINEL | 10 agents + Monte Carlo |
| **Agent Builder 2026** | NEXUS·ELASTIC | Elasticsearch + Gemini |
| **Hex 2026** | CRYPTOTIME·AI | Data correlation |

---

## Contact

- **GitHub** : [github.com/Turbo31150](https://github.com/Turbo31150)
- **Localisation** : Toulouse, France
- **Stack** : Python · TypeScript · C# · GPU · IA

---

<div align="center">

*Franc Delmas (Turbo31150) · Toulouse · MIT · Propulsé par JARVIS*

</div>
