<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:1a1b27&height=220&section=header&text=parallel-you-engine&fontSize=50&fontColor=e6edf3&fontAlignY=35&desc=Build%20your%20decision-making%20DNA.%20Then%20simulate%20what%20YOU%20would%20do.&descSize=15&descAlignY=55&descColor=8b949e&animation=fadeIn" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=white&labelColor=0d1117&color=0d1117" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white&labelColor=0d1117&color=0d1117" />
  <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logoColor=white&labelColor=0d1117&color=0d1117" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white&labelColor=0d1117&color=0d1117" />
</p>

---

## 🪞 What is this?

**parallel-you-engine** is a two-phase system that answers: *what would I actually do in situation X?*

**Phase 1 — Profile:** An AI interviewer asks you a sequence of targeted questions about past decisions, values, and reasoning patterns. It builds your psychological decision-making profile.

**Phase 2 — Simulate:** Given any scenario, the engine simulates what *you specifically* would do — not a generic person, but the decision-maker the interview revealed.

> *You don't simulate futures. You simulate yourself.*

---

## ⚙️ Two-Phase Architecture

```
┌──────────────────────────────────────────────────────────┐
│                  PHASE 1: THE INTERVIEW                  │
│                                                          │
│  AI asks targeted questions about your past decisions:   │
│  ├── "Describe a time you chose stability over risk"     │
│  ├── "How do you weigh short vs long-term outcomes?"     │
│  └── "What do you regret most about a past choice?"      │
│                                                          │
│  Builds your Decision DNA:                               │
│  { risk_tolerance: 0.7, loss_aversion: 0.85,            │
│    time_preference: "long", anchor_bias: "moderate" }   │
└───────────────────────────────┬──────────────────────────┘
                                │
                                ▼
┌──────────────────────────────────────────────────────────┐
│                 PHASE 2: THE SIMULATION                  │
│                                                          │
│  Input: Any scenario + your Decision DNA                 │
│  Output: What YOU would likely do, and why               │
│                                                          │
│  "Given your profile, you would probably accept the      │
│   offer but negotiate harder on equity than salary,      │
│   because your loss aversion outweighs risk tolerance    │
│   in high-uncertainty financial decisions."              │
└──────────────────────────────────────────────────────────┘
```

---

## 🧱 Tech Stack

| Layer | Technology | Purpose |
|:---|:---|:---|
| **Frontend** | React + Vite | Fast SPA, interview & simulation UI |
| **AI** | Ollama (local LLM) | Interview + profile building + simulation |
| **Language** | TypeScript | Type-safe profile schema |
| **Styling** | CSS Modules | Component-scoped styles |

---

## 🚀 Getting Started

### Prerequisites

```bash
# Install Ollama
curl -fsSL https://ollama.ai/install.sh | sh
ollama pull llama3.2

node >= 18.0.0
```

### Installation

```bash
git clone https://github.com/Ap-0007/parallel-you-engine.git
cd parallel-you-engine

npm install
npm run dev
# App at http://localhost:5173
```

---

## 🏛️ Philosophy

Most decision tools give you frameworks. This gives you a mirror.

The goal isn't to tell you what's optimal. It's to show you what *you* would actually do — so you can decide if that's the person you want to be.

---

## 🔗 Related

- **[regret-simulator](https://github.com/Ap-0007/regret-simulator)** — run your parallel-you profile through 3-trajectory simulations

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:58a6ff,60:1f6feb,100:0d1117&height=120&section=footer&animation=fadeIn" width="100%" />
</p>
