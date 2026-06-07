<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:1a1b27&height=220&section=header&text=PARALLEL%20YOU%20ENGINE&fontSize=50&fontColor=e6edf3&fontAlignY=35&desc=Psychological%20Profiling%20%E2%80%A2%20Decision%20DNA%20%E2%80%A2%20Scenario%20Simulation&descSize=16&descAlignY=55&descColor=8b949e&animation=fadeIn" width="100%" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white&labelColor=0d1117&color=0d1117" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=white&labelColor=0d1117&color=0d1117" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white&labelColor=0d1117&color=0d1117" />
  <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white&labelColor=0d1117&color=0d1117" />
</p>

---

## 🪞 What is this?

**Parallel You Engine** builds a psychological model of *you* — then uses it to simulate what you'd do in any scenario you've never faced.

It works in two phases:

### Phase 1: The Interview
The engine conducts a deep conversational interview, probing your values, fears, instincts, and decision-making patterns. It maps your cognitive biases, risk tolerance, emotional triggers, and moral boundaries.

### Phase 2: The Simulation
Once your **decision-making DNA** is constructed, you can throw any scenario at it:

> *"You discover your best friend has been lying to you for years. What do you do?"*

The engine doesn't give you the *right* answer. It gives you *your* answer — the one that aligns with the psychological profile it built, including the rationalizations you'd use and the consequences you'd ignore.

> *You already know what you'd do. This just proves it.*

---

## ⚙️ How It Works

```
┌──────────────────────────────────────────────────────────┐
│              PHASE 1: THE INTERVIEW 🎙️                   │
│                                                          │
│  ┌──────────────┐    ┌──────────────┐                   │
│  │ Conversational│───▶│ Response     │                   │
│  │ Probing      │    │ Analysis     │                   │
│  └──────────────┘    └──────┬───────┘                   │
│                             │                            │
│  Questions adapt based on your answers                   │
│  Values · Fears · Biases · Triggers mapped              │
└─────────────────────────────┬────────────────────────────┘
                              │
                              ▼
┌──────────────────────────────────────────────────────────┐
│              🧬 DECISION DNA PROFILE                     │
│                                                          │
│  ┌─────────┐ ┌────────────┐ ┌──────────┐ ┌───────────┐ │
│  │ Values  │ │ Risk       │ │ Emotional│ │ Moral     │ │
│  │ Matrix  │ │ Tolerance  │ │ Triggers │ │ Boundaries│ │
│  └─────────┘ └────────────┘ └──────────┘ └───────────┘ │
└─────────────────────────────┬────────────────────────────┘
                              │
                              ▼
┌──────────────────────────────────────────────────────────┐
│              PHASE 2: SCENARIO ENGINE 🎭                 │
│                                                          │
│  Input: Any hypothetical scenario                        │
│                                                          │
│  ┌──────────────┐    ┌──────────────┐                   │
│  │ Scenario     │───▶│ DNA-Weighted │───▶ YOUR response │
│  │ Context      │    │ Simulation   │    + reasoning     │
│  └──────────────┘    └──────────────┘    + blind spots   │
└──────────────────────────────────────────────────────────┘
```

---

## 🧱 Tech Stack

| Layer | Technology | Purpose |
|:------|:-----------|:--------|
| **Frontend** | React | Interview UI + scenario simulation |
| **Build** | Vite | Fast dev server & bundling |
| **AI** | Ollama (Local LLM) | Profiling engine & simulation |
| **Language** | JavaScript | Core application logic |
| **Styling** | CSS | Custom interface design |

---

## 🚀 Getting Started

### Prerequisites

```bash
node >= 18.0.0
ollama           # Running locally with a model pulled
```

### Installation

```bash
# Clone the repository
git clone https://github.com/Ap-0007/parallel-you-engine.git
cd parallel-you-engine

# Install dependencies
npm install

# Start the development server
npm run dev

# Open in browser
open http://localhost:5173
```

> Make sure Ollama is running with a model loaded before starting the app.

---

## 📁 Project Structure

```
parallel-you-engine/
├── public/                 # Static assets
├── src/                    # Application source
│   ├── components/         # React components
│   │   ├── Interview/      # Phase 1: profiling interface
│   │   └── Simulation/     # Phase 2: scenario engine
│   ├── services/           # Ollama integration & profiling
│   ├── utils/              # Helper functions
│   ├── App.jsx             # Root component
│   └── main.jsx            # Entry point
├── index.html              # HTML template
├── vite.config.js          # Vite configuration
├── eslint.config.js        # ESLint configuration
└── package.json            # Dependencies
```

---

## 🤝 Contributing

If you're interested in personality modeling, cognitive science, or just want to know yourself better — PRs are welcome.

```bash
# Fork the repo
# Create your feature branch
git checkout -b feat/your-feature

# Commit your changes
git commit -m "feat: add your feature"

# Push and open a PR
git push origin feat/your-feature
```

---

<p align="center">
  <img src="https://img.shields.io/badge/license-MIT-e6edf3?style=flat-square&labelColor=0d1117&color=161b22" />
</p>

<p align="center">
  <sub>Built by <a href="https://github.com/Ap-0007">vanta.nox</a> · you already know what you'd do</sub>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:1a1b27&height=100&section=footer" width="100%" />
