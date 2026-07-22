# Hi there, I'm Paul 👋

### 🎓 Master's Student in AI @ **EPITA (SCIA Major)**
**AI & Systems Engineer.** I build AI systems that solve real-world problems, from medical image segmentation running in hospitals to agentic productivity tools shipped at hackathons, backed by the data infrastructure they run on. I don't just train models or design pipelines: I go low enough to write the compilers and shells underneath them too, and low enough to teach their fundamentals as a C#/OCaml teaching assistant at EPITA.

---

### 🚀 Flagship Projects

**[DealBoard AI Companion](https://github.com/Pauwit/Gemini-3-Hackathon-Paris): *Gemini Hackathon Paris***\
**Your second brain for work.** A chat/agent-based AI assistant with direct access to your personal Google Workspace to help you manage and analyze your daily tasks.
* **The Tech:** Next.js, TypeScript, Tailwind CSS, Node.js, Express.
* **The AI & Integrations:** Powered by **Gemini 3.1 Pro** and deeply connected to Google Workspace APIs with Google OAuth 2.0 thanks to the [Google Workspace CLI](https://github.com/googleworkspace/cli).
* **The Architecture:** Secure server-side session management handling user API keys and workspace authentication for seamless orchestration.

**[EyeSegmentation](https://github.com/Pauwit/EyeSegmentation): *Medical Computer Vision Pipeline***\
**End-to-end segmentation & classification pipeline for retinal Doppler holography images, in daily hospital use.** Built the full workflow (dataset creation, training, and fine-tuning **Ultralytics YOLO11** models) to segment optic discs and eye diaphragms and classify eye side, for medical diagnostics.
* **The Tech:** Python, PyTorch, Ultralytics YOLO11, Jupyter Notebooks, Matlab.
* **The Research Impact:** This work became the foundation for the Digital Holography Project's official [OpticDiscSegmentation](https://github.com/DigitalHolography/OpticDiscSegmentation) and [LeftRightEyeClassification](https://github.com/DigitalHolography/LeftRightEyeClassification) repos, with trained weights published on Hugging Face.
* **The Output:** Now running daily in [EyeFlow](https://github.com/DigitalHolography/EyeFlowMatlab), the lab's production hospital pipeline.

**42sh: *EPITA Systems Project* (private repo)**\
**A POSIX-ish shell built entirely from scratch in C.** Hand-rolled lexer and recursive-descent parser (no Flex/Bison), covering builtins, variable/glob expansion, pipes, redirections, and job control.
* **The Tech:** C, Autotools.
* **The "Why":** Wanted to understand what a shell is actually doing between a keystroke and a running process, not just use one.

---

### 🧩 More Projects & Hackathons

| Project | What it is | Stack |
|---|---|---|
| [`Hackathon-IA-Agentique-YAKAP`](https://github.com/joannejab/Hackathon-IA-Agentique-YAKAP) | 🥉 **3rd place**: 5-agent pipeline auditing course curricula against the job market & state of the art, hallucination-checked | Next.js, TypeScript, LLM agents |
| [`hackathon_fintech_paris_2026`](https://github.com/Chocolatine75/hackathon_fintech_paris_2026) | "Fine Print": AI covenant compliance review for loan agreements, results shown as an interactive knowledge graph | LLMs (Cerebras/Mistral), knowledge graphs |
| [`cpp-neural-net`](https://github.com/Pauwit/cpp-neural-net) | Neural network from scratch in C++, no ML libraries, just backprop and SGD on raw matrices, trained on MNIST | C++, CMake |
| `Tiger Compiler` (private repo) | Full compiler for the Tiger language targeting LLVM IR: lexing/parsing (Bison + RE/flex), AST, scope binding, type checking, desugaring, escape analysis, LLVM codegen | C++, LLVM, Bison, RE/flex, Autotools |
| `introduction-au-data-engineering` (private repo) | Data architecture PoC for real-time forest fire detection at IoT scale (~10M devices, 200GB/day), sub-second alerting plus long-term analytics | Kafka, Spark Structured Streaming, Akka HTTP, HDFS, Scala |
| [`mapf-drone-coordination`](https://github.com/Pauwit/mapf-drone-coordination) | Multi-Agent Path Finding for drone swarms modeled as a CP-SAT problem, with 3D airspace & NOTAM constraints | Python, CP-SAT |
| [`symbolic-graphrag`](https://github.com/Pauwit/symbolic-graphrag) | GraphRAG pipeline combining knowledge graphs with LLMs for multi-hop retrieval-augmented QA | Python, RDF/property graphs, LLMs |
| [`GIMP_mask_plugin`](https://github.com/Pauwit/GIMP_mask_plugin) | Custom GIMP 3.0 plugin that speeds up manual dataset annotation for CV pipelines | Python, GIMP API |
| [`jupyter-claude-integration`](https://github.com/Pauwit/jupyter-claude-integration) | MCP server giving Claude fine-grained read/write/execute access to Jupyter notebooks | Python, MCP |

---

### 🎮 Fun Stuff

**[Tanks](https://github.com/Pauwit/tanks): *Web Game Engine***\
**"Tanks in a Nutshell"**: A fully playable, multiplayer, web-based tank combat game built entirely from scratch, **by hand, without AI assistance**.
* **The Tech:** TypeScript, HTML5.
* **The "Why":** A deep dive into custom game engine logic, physics, multiplayer capabilities, and web rendering without relying on heavy out-of-the-box frameworks.

**[ASCII Realms](https://github.com/Pauwit/ascii-realms): *Terminal RPG***\
**A turn-based RPG that runs entirely in the terminal.** Wake up with no memory on a procedurally generated continent, explore, fight, loot, and work your way up to two mid-bosses and a final boss.
* **The Tech:** C++, CMake, Perlin noise.
* **The Details:** 51x51 procedurally generated world (height & temperature drive biome placement), turn-based combat, enemy AI behaviors (wandering, chasing, fleeing), and a full inventory/looting system.

---

### 🧠 My Tech Stack

* **AI, Data & Vision:** Python, PyTorch, Pandas, NumPy, Jupyter, Matlab, Hugging Face, OR-Tools/CP-SAT
* **Core & Systems:** C, C++, C#, Java, Rust, OCaml, Scala, Bash
* **Web & Cloud:** Next.js, React, TypeScript, Node.js, Angular, Tailwind CSS, PostgreSQL, Kafka
* **Tools:** Git, GitLab, CMake, Docker, LaTeX
<!--
<br>
<div align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="40" alt="python logo"  /> <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg" height="40" alt="pytorch logo"  /> <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" height="40" alt="numpy logo"  /> <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" height="40" alt="pandas logo"  /> <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original.svg" height="40" alt="jupyter logo"  /> <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/matlab/matlab-original.svg" height="40" alt="matlab logo"  /> <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" height="40" alt="c logo"  /> <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" height="40" alt="cplusplus logo"  /> <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" height="40" alt="csharp logo"  /> <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" height="40" alt="java logo"  /> <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/rust/rust-original.svg" height="40" alt="rust logo"  /> <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/ocaml/ocaml-original.svg" height="40" alt="ocaml logo"  /> <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bash/bash-original.svg" height="40" alt="bash logo"  /> <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="40" alt="typescript logo"  /> <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="40" alt="javascript logo"  /> <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="40" alt="react logo"  /> <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" height="40" alt="nextjs logo"  /> <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" height="40" alt="nodejs logo"  /> <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/angularjs/angularjs-original.svg" height="40" alt="angularjs logo"  /> <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="40" alt="html5 logo"  /> <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="40" alt="css logo"  /> <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" height="40" alt="postgresql logo"  /> <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apachekafka/apachekafka-original.svg" height="40" alt="apachekafka logo"  /> <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-plain-wordmark.svg" height="40" alt="docker logo"  /> <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/firebase/firebase-plain-wordmark.svg" height="40" alt="firebase logo"  /> <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/unity/unity-original.svg" height="40" alt="unity logo"  /> <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/gimp/gimp-original.svg" height="40" alt="gimp logo"  /> <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" height="40" alt="git logo"  /> <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" height="40" alt="github logo"  /> <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/gitlab/gitlab-original.svg" height="40" alt="gitlab logo"  /> <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cmake/cmake-original.svg" height="40" alt="cmake logo"  /> <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/gcc/gcc-original.svg" height="40" alt="gcc logo"  /> <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/latex/latex-original.svg" height="40" alt="latex logo"  /> <img width="12" />
</div>
-->
---

### 📫 Let's Connect

🌍 **Location:** Paris, France  
🎓 **Education:** Master of Science in CS & Engineering @ EPITA  
🧑‍🏫 **Teaching:** C#/OCaml Teaching Assistant @ EPITA (Sept 2024 to Jul 2025), supervising a 1st-year class and designing/running their lab sessions

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/paul-stanislas-witkowski)

---

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Pauwit/Pauwit/output/pacman-contribution-graph-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Pauwit/Pauwit/output/pacman-contribution-graph.svg">
    <img alt="pacman contribution graph" src="https://raw.githubusercontent.com/Pauwit/Pauwit/output/pacman-contribution-graph.svg">
  </picture>
</div>

