# Azusa010 👋

🎓 **Student**  
🔭 Currently learning **AI Agent** development

---

### 🌟 Core Learning Project

#### 🤖 [PersonalAgent](https://github.com/Azusa010/personal-agent) — Local Agent

> *A local Agent runtime system for desktop environments.*  
> A desktop-oriented Agent runtime system that enables local Agents to safely access system capabilities within a controlled sandbox through strict layered contracts and defense-in-depth security.

- **📐 Agent Capabilities**
  - **Context engineering**: Prompt orchestration, status bar support for environment information injection, and context compression.
  - **User memory and knowledge base**: Memory hierarchy design, including working memory and long-term memory; memory formats such as Simple Notes and Advanced JSON Cards; and long-term memory categories such as episodic and semantic memory.
  - **Tools**: Web search, code interpreter, persistent command-line tools, directory listing, `grep`/`glob`, and an `old string -> new string` file-editing tool with linter and syntax checks after editing; support for parallel tools and more.
  - **Coding capabilities**: Using code tools for precise calculations and strict logical reasoning; guiding Agents to provide correct tool parameters with code; and generating UIs using an A2UI-style protocol.
  - **Testing**: Running scripts for automated testing.
- **🛡️ Five-layer security policy chain**
  - Tool calls pass through the following layers: `Scope` (task authorization) ➔ `Retriever` (capability retrieval) ➔ `Binder` (parameter validation and path resolution) ➔ `Executor` (policy evaluation) ➔ `Path-Guard` (path normalization and protection).
- **📊 Real-world evaluation**
  - The project includes an end-to-end evaluation framework covering **real-world daily office tasks, complex multi-step reasoning with GAIA, and human-Agent collaboration with τ-bench**, across 38 core evaluation sets. The evaluations are run on real hardware.
- **🏗️ Engineering**
  - Built as a Monorepo with a complete `pnpm verify` pipeline integrating TypeScript type checking, ESLint, Python Ruff, Vitest, and Pytest as cross-language quality gates.

### 💻 More Project Experience

- **[SakiFlow](https://github.com/Azusa010/SakiFlow)**: A frontend design project based on Vue 3.
- **[SakiVault](https://github.com/Azusa010/SakiVault)**: A Vue 3 frontend project using the Bangumi API.

### 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Azusa010&layout=compact)
