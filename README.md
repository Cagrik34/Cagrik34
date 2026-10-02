<div align="center">
  <img src="https://raw.githubusercontent.com/Cagrik34/Cagrik34/main/github_banner.jpg" alt="Çağrı Giray Keşan (Cagri Giray Kesan), Full-Stack & AI Systems Developer" width="100%" />

  <h1>Çağrı Giray Keşan</h1>

  <h3>Full-Stack & AI Systems Developer</h3>

  <p>I build client-side web applications, developer tools, and hybrid retrieval-augmented generation (RAG) systems.<br/>My focus is deterministic grounding and local-first architecture.</p>

  <p>Based in Istanbul · Open to full-time Software Engineer roles (hybrid or remote)</p>
</div>

## Tech Stack

<div>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" title="React" alt="React" width="40" height="40"/>&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" title="TypeScript" alt="TypeScript" width="40" height="40"/>&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nextjs/nextjs-original.svg" title="Next.js" alt="Next.js" width="40" height="40"/>&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" title="Python" alt="Python" width="40" height="40"/>&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/fastapi/fastapi-original.svg" title="FastAPI" alt="FastAPI" width="40" height="40"/>&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg" title="Node.js" alt="Node.js" width="40" height="40"/>&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/sqlite/sqlite-original.svg" title="SQLite" alt="SQLite" width="40" height="40"/>&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" title="Docker" alt="Docker" width="40" height="40"/>&nbsp;
</div>

## GitHub Stats

<p align="center">
  <a href="https://github.com/Cagrik34"><img src="https://github-readme-stats-anuraghazra1.vercel.app/api?username=Cagrik34&count_private=true&show_icons=true&include_all_commits=true&title_color=e6f1ff&text_color=bcd0e6&icon_color=4aa8ff&bg_color=0a0f1a&border_color=e6f1ff&border_radius=8" alt="GitHub Stats" width="390" /></a>
  <a href="https://github.com/Cagrik34"><img src="https://my-streak-stats-psi.vercel.app/?user=Cagrik34&timezone=Europe/Istanbul&background=0a0f1a&border=e6f1ff&stroke=30363D&ring=FF8C00&fire=FF8C00&currStreakNum=FF8C00&currStreakLabel=FF8C00&sideNums=38BDF8&sideLabels=38BDF8&dates=94A3B8&border_radius=8" alt="GitHub Streak" width="390" /></a>
</p>

## Open-Source Contributions

| Repository | PR | Contribution |
| :--- | :--- | :--- |
| [microsoft/PhiCookBook](https://github.com/microsoft/PhiCookBook) | [#571](https://github.com/microsoft/PhiCookBook/pull/571) (merged) | Local hybrid RAG recipe: SQLite FTS5 BM25 and `phi-4-mini` inference through the Foundry Local SDK. |
| [google-gemini/cookbook](https://github.com/google-gemini/cookbook) | [#1347](https://github.com/google-gemini/cookbook/pull/1347) (merged) | Local hybrid RAG recipe: SQLite FTS5 BM25 and `gemini-embedding-001`, fused with Reciprocal Rank Fusion (k=60), with grounded synthesis through the `google-genai` Interactions API. |

## Experience

**Artificial Intelligence Intern, Microsoft** · May 2026 – Aug 2026 · Remote<br/>
AI Innovators Summer Program. Built Zenith AI, a local RAG assistant on the Foundry Local SDK, with hybrid retrieval (dense embeddings + SQLite FTS5 BM25 via RRF), SSE streaming, and an automated evaluation benchmark suite.

**Frontend Development Intern, Turknet** · May 2025 – Dec 2025 · Hybrid<br/>
Built production interfaces with live user traffic using React, Next.js, and TypeScript. Implemented Figma designs as responsive components, managed global state with Redux, added feature toggles for production releases, and integrated REST APIs within an Agile/Scrum team.

**Earlier:** Frontend Intern (volunteer), ONFTECH, 2024 · IT Intern, Paynet Ödeme Hizmetleri, 2022 – 2023

## Selected Projects

### [Hybrid RAG Issue & PR Assistant](https://github.com/Cagrik34/hybrid-rag-action)
GitHub Action ([Marketplace](https://github.com/marketplace/actions/hybrid-rag-issue-pr-assistant)) · Node.js 24 · `@vercel/ncc` · Okapi BM25 · dense vectors · RRF

- Triages issues and pull requests by fusing Okapi BM25 with dense semantic embeddings through Reciprocal Rank Fusion (k=60).
- Uses Markdown AST-aware chunking to return verifiable line-span citations (`[file#L<start>-L<end>]`).
- Ships as a single dependency-free bundle via `@vercel/ncc`.

### [Zenith AI: Local RAG Assistant](https://github.com/Cagrik34/microsoft-foundry-local-rag-assistant)
Python · FastAPI · React 18 · TypeScript · Foundry Local SDK · SQLite FTS5 · Docker

- Runs `phi-4-mini` (3.8B) and `qwen3-embedding-0.6b` (1024-d) on-device, with no external API calls and no data leaving the machine.
- Combines dense retrieval and FTS5 BM25 with RRF (k=60). Streams tokens over SSE and supports offline speech-to-text with `faster-whisper`.
- Includes an automated evaluation suite (`tests/test_evaluation_benchmark.py`). On the repository's internal benchmark: 89.4% composite score, 96.2% faithfulness, 100% groundedness.

### [Zenith Istanbul: Codebase Topology Visualizer and CI Gate](https://github.com/Cagrik34/zenith-istanbul)
JavaScript (ESM) · Node.js · Three.js · Tarjan SCC · zero dependencies · [Live demo](https://cagrik34.github.io/zenith-istanbul/)

- Statically analyzes JavaScript and TypeScript dependencies and renders the module graph as an interactive 3D scene.
- Detects circular dependencies with Tarjan's SCC algorithm in O(V+E) and generates decoupled TypeScript contract interfaces.
- Audits architectural boundaries against CWE-668, CWE-200, and CWE-798. Runs headless in CI (`--fail-on-cycle --fail-on-leak`).
- Local analysis has no CDN dependencies and no telemetry. Covered by 48 unit and integration tests (48/48 passing).

### [Zenith Atlas: Quantitative Analytics Terminal](https://github.com/Cagrik34/zenith-atlas)
React 19 · TypeScript 5.8 · Vite 6 · Web Workers · PWA · IndexedDB · [Live demo](https://cagrik34.github.io/zenith-atlas/)

- Runs entirely in the browser over 1,051 TEFAS funds plus BIST, FX, and macro data. Portfolio data stays on the device.
- Implements 11 quantitative engines, including Black-Litterman, HRP, and a 10,000-path Monte Carlo, executed in Web Workers.
- Exports a 4-page A4 PDF report. Covered by 23 Vitest tests (23/23 passing).

### [Zenith Nexus: Local-First Developer Toolkit](https://github.com/Cagrik34/zenith-nexus)
React 19 · TypeScript 5.8 · Vite 6 · Web Workers · SQLite FTS5 · Vitest · [Live demo](https://cagrik34.github.io/zenith-nexus/)

- **RepoSense:** real-time AST codebase topology.
- **DevForge:** JSON-to-TypeScript/Zod conversion, cURL translation, WASM sandbox.
- **MindVault:** note search with SQLite FTS5 BM25.

Also: [Real-Time Face Emotion & Intensity System](https://github.com/Cagrik34/RealTime-Face-Emotion-Recognition) (Python, TensorFlow/Keras, OpenCV)

## Writing

- 📖 **[Medium]** [Hybrid RAG with SQLite FTS5 and Reciprocal Rank Fusion](https://medium.com/@cagrigiraykesan/i-ditched-cloud-vector-databases-for-sqlite-fts5-and-my-rag-pipeline-got-10x-better-05b79764adad)
- 📝 **[DEV.to]** [I Ditched Cloud Vector Databases for SQLite FTS5](https://dev.to/cagrik34/i-ditched-cloud-vector-databases-for-sqlite-fts5-and-my-rag-pipeline-got-10x-better-759)
- 💬 **[GitHub Discussion #205923]** [Deterministic BM25 and Dense Semantic Fusion for Repository Triage](https://github.com/community/community/discussions/205923)

## Skills

- **Frontend & Systems:** React 19, Next.js, TypeScript, JavaScript, Redux Toolkit, Tailwind CSS, Vite, Three.js, Web Workers
- **Backend & Data:** Python, FastAPI, Node.js, Express, REST APIs, SQLite (FTS5), PostgreSQL, MongoDB, Docker
- **AI & Retrieval:** Hybrid Search (BM25 + Dense Vectors), Reciprocal Rank Fusion (RRF), RAG, SLM On-Device Inference
- **Engineering Tools:** Git, GitHub Actions, Vitest, Jira, Agile/Scrum

## Education & Programs

- 🎓 **Istanbul University** &bull; Web Design & Coding *(2025 – Present)*
- 🎓 **Istanbul Beykent University** &bull; Associate Degree in Computer Programming *(GPA: 3.61/4.00)*
- 🌟 **Aspire Leaders Program (2026)** &bull; Global Finalist *(Top 10,588 of 50,284 worldwide)*, CEO Letter of Recognition
- 📜 **McKinsey.org Forward Program (2026)** &bull; MECE Framework & Structured Problem Solving
- 🌐 **HUAWEI Bootcamp & GDG Build With AI Türkiye** &bull; Machine Learning & Applied AI Participant

## Contact

<p align="left">
  <a href="mailto:cagrigiraykesan@gmail.com">cagrigiraykesan@gmail.com</a> &bull;
  <a href="https://www.linkedin.com/in/cagrigiraykesan">LinkedIn</a> &bull;
  <a href="https://github.com/Cagrik34">GitHub</a>
</p>
