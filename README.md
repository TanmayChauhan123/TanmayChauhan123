<!-- Animated header -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1f6feb,100:58a6ff&height=220&section=header&text=YOUR%20NAME&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Full-Stack%20%C2%B7%20AI%20Systems%20%C2%B7%20DevOps&descSize=18&descAlignY=58" alt="header" />

  <!-- Typing animation -->
  <a href="https://github.com/TanmayChauhan123">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&width=700&lines=Building+AI-powered+real-time+products;Designing+RAG+pipelines+%26+local+LLM+apps;Shipping+with+Docker+%2B+CI%2FCD;Turning+ideas+into+scalable+systems" alt="typing" />
  </a>

  <p>
    <a href="https://www.linkedin.com/in/tanmay-chauhan-388358281/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
    <a href="mailto:tanmaychauhan2005@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
    <a href="https://YOUR_PORTFOLIO.com"><img src="https://img.shields.io/badge/Portfolio-0d1117?style=for-the-badge&logo=vercel&logoColor=white" /></a>
    <img src="https://komarev.com/ghpvc/?username=YOUR_USERNAME&label=Profile%20views&color=1f6feb&style=for-the-badge" />
  </p>
</div>

---

## `~/about`

```ts
const developer = {
  name: "YOUR NAME",
  role: "Full-Stack & AI Engineer",
  location: "Delhi, India",
  focus: ["RAG systems", "Real-time apps", "ML pipelines", "DevOps & observability"],
  currentlyLearning: ["Agentic workflows", "Advanced RAG", "Cloud-native architecture"],
  principles: [
    "Ship small, iterate fast",
    "Validate on the server, trust nothing from the client",
    "If it isn't monitored, it isn't done",
    "Prefer local-first AI where privacy and cost matter",
  ],
  openTo: ["Internships", "Collaborations", "Open source"],
};
```

---

## `~/stack`

<div align="center">

| Layer | Technologies |
|:--|:--|
| **Languages** | <img src="https://skillicons.io/icons?i=js,ts,python,html,css" /> |
| **Frontend** | <img src="https://skillicons.io/icons?i=react,tailwind,vite" /> |
| **Backend** | <img src="https://skillicons.io/icons?i=nodejs,express" /> |
| **Database** | <img src="https://skillicons.io/icons?i=mongodb" /> |
| **AI / ML** | <img src="https://skillicons.io/icons?i=sklearn,jupyter" /> ![Ollama](https://img.shields.io/badge/Ollama-000?style=flat-square&logo=ollama&logoColor=white) ![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white) |
| **DevOps** | <img src="https://skillicons.io/icons?i=docker,githubactions,git,linux" /> |

</div>

---

## `~/projects`

> Click a category to expand.

<details open>
<summary><b>🤖 AI & Machine Learning</b></summary>
<br>

| Project | What it does | Stack |
|:--|:--|:--|
| [**RAG-Pilot**](https://github.com/YOUR_USERNAME/RAG-Pilot) | Adaptive RAG that routes each query by complexity: simple retrieval, query rewriting with re-ranking, or multi-hop reasoning | `Python` `RAG` `LLM` |
| [**InsightPulse**](https://github.com/YOUR_USERNAME/InsightPulse) | Student performance prediction with explainable AI, RAG, and a locally hosted LLM | `Python` `ML` `XAI` `RAG` |
| [**Credit-Card-Fraud-Detection**](https://github.com/YOUR_USERNAME/Credit-Card-Fraud-Detection) | Fraud detection with Logistic Regression and Random Forest, class imbalance handling, and full model evaluation | `Jupyter` `scikit-learn` |

</details>

<details open>
<summary><b>🌐 Full-Stack Applications</b></summary>
<br>

| Project | What it does | Stack |
|:--|:--|:--|
| [**DevSync**](https://github.com/YOUR_USERNAME/DevSync) | Real-time collaborative project management: team workspaces, Kanban boards, chat, AI dev tools | `React` `Node.js` `WebSockets` |
| [**ChessArena**](https://github.com/YOUR_USERNAME/ChessArena) | Multiplayer chess with spectator mode, server-side move validation, Stockfish analysis, and an AI coach | `JavaScript` `WebSockets` `Stockfish` |
| [**QueueLess**](https://github.com/YOUR_USERNAME/QueueLess) | Digital tokens, live queue tracking, estimated wait times, and business queue management | `TypeScript` |
| [**PrepForge**](https://github.com/YOUR_USERNAME/PrepForge) | AI interview prep platform with JWT auth and local Ollama AI | `Node.js` `Express` `MongoDB` `Ollama` |
| [**HabitMind**](https://github.com/YOUR_USERNAME/HabitMind) | AI habit tracker with glassmorphism UI, light/dark mode, and Gemini-powered insights | `MERN` `Tailwind v4` `Gemini` |

</details>

<details open>
<summary><b>⚙️ DevOps & Observability</b></summary>
<br>

| Project | What it does | Stack |
|:--|:--|:--|
| [**OpsPulse**](https://github.com/YOUR_USERNAME/OpsPulse) | Real-time observability and incident management: app health, logs, metrics, and service failures | `Monitoring` `Logging` |
| [**CloudBridge**](https://github.com/YOUR_USERNAME/CloudBridge) | Deployment dashboard showing containerization, CI/CD automation, and deployment monitoring | `Docker` `CI/CD` |

</details>

---

## `~/architecture`

<details>
<summary><b>How RAG-Pilot routes queries</b></summary>

```mermaid
flowchart LR
    Q[User Query] --> R{Complexity Router}
    R -->|Simple| S[Direct Retrieval]
    R -->|Moderate| W[Query Rewriting + Re-ranking]
    R -->|Complex| M[Multi-hop Reasoning]
    S --> G[LLM Generation]
    W --> G
    M --> G
    G --> A[Answer]
```

</details>

<details>
<summary><b>Typical full-stack AI app flow</b></summary>

```mermaid
flowchart LR
    C[React Client] -->|REST / WebSocket| API[Express API]
    API --> Auth[JWT Auth]
    API --> DB[(MongoDB)]
    API --> AI[Ollama / Gemini]
    API --> Mon[Logs & Metrics]
```

</details>

---

## `~/stats`

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=1f6feb" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff" />
  <br>
  <img src="https://streak-stats.demolab.com?user=YOUR_USERNAME&theme=github-dark-blue&hide_border=true" />
  <br>
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=YOUR_USERNAME&bg_color=0d1117&color=58a6ff&line=1f6feb&point=ffffff&area=true&hide_border=true" />
</div>

---

## `~/contact`

```bash
$ git remote add collab YOUR_EMAIL
$ echo "Open to internships, collaborations, and interesting problems."
```

<div align="center">
  <sub>⭐ If something here helped you, a star is always appreciated.</sub>
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1f6feb,100:58a6ff&height=120&section=footer" alt="footer" />
</div>
