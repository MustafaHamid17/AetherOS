<div align="center">

# ⚡ AETHER OS & BOX IDE ⚡
### *The Intelligent Multi-Agent AI Operating System & Local Box IDE*

[![Release](https://img.shields.io/badge/Release-v10.4.0_Desktop_%26_Web-cyan?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/)
[![React](https://img.shields.io/badge/React-19.2-61dafb?style=for-the-badge&logo=react&logoColor=black)](https://react.dev/)
[![Vite](https://img.shields.io/badge/Vite-8.0-646cff?style=for-the-badge&logo=vite&logoColor=white)](https://vite.dev/)
[![Electron](https://img.shields.io/badge/Electron-43.2-47848F?style=for-the-badge&logo=electron&logoColor=white)](https://www.electronjs.org/)
[![Monaco Editor](https://img.shields.io/badge/Monaco_Editor-0.52-007acc?style=for-the-badge&logo=visualstudiocode&logoColor=white)](https://microsoft.github.io/monaco-editor/)
[![Python FastAPI](https://img.shields.io/badge/FastAPI-Local_AI-009688?style=for-the-badge&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)

<p align="center">
  <a href="#-desktop-downloads--releases"><strong>📥 Download Windows IDE</strong></a> •
  <a href="#-features-a-to-z"><strong>✨ Features (A-Z)</strong></a> •
  <a href="#-core-multi-agent-swarm"><strong>🤖 Multi-Agent Swarm</strong></a> •
  <a href="#-system-requirements"><strong>💻 Specs</strong></a> •
  <a href="#-architecture--sandboxing"><strong>🛡️ Security</strong></a> •
  <a href="#-proprietary-license-notice"><strong>⚖️ Private License</strong></a>
</p>

---

</div>

## 🌐 Live Web Portal & App

> **Live Deployment:** Experience Aether OS directly in your browser without installation:  
> 🔗 **[Launch Aether OS on Vercel](https://aetheros-kappa.vercel.app)** • **[Alternative Mirror](https://specsprojects-f4a88.firebaseapp.com)**

---

## 🔒 Private & Proprietary Software Notice

> [!IMPORTANT]
> **AETHER OS IS PROPRIETARY SOFTWARE.**
> The underlying core engine, multi-agent coordination system, and proprietary algorithms are **Private Intellectual Property**. 
> This public repository serves for **Official Releases**, **Binary Downloads (.exe / Portable)**, **Documentation**, **Public Skill Modules**, and **Issue Tracking**.

---

## 🌟 What is Aether OS?

**Aether OS** is a unified developer operating environment bridging cutting-edge LLMs with a local-first **Monaco Box IDE**. Unlike traditional chatbots that only write text in isolation, Aether OS:
1. **Reads & Writes Your Codebase:** Interacts with local project files with strict path-traversal sandboxing.
2. **Executes Shell Commands:** Features an interactive terminal for dev servers, testing suites, and git operations.
3. **Deconstructs Tasks Across 4 AI Roles:** Automatically coordinates **Planner**, **Executor**, **Reviewer**, and **Verifier** sub-agents.
4. **Specialized Skill Modules:** Dynamically activates domain-specific intelligence for React Frontend, AST Refactoring, Systematic Debugging, Security Auditing, API Architecture, and DevOps.

```
                  ┌────────────────────────────────────────┐
                  │          USER PROMPT / TASK            │
                  └───────────────────┬────────────────────┘
                                      │
                                      ▼
                        ┌───────────────────────────┐
                        │    🧠 SKILL ROUTER        │
                        │ (Specialized Capabilities)│
                        └─────────────┬─────────────┘
                                      │
                 ┌────────────────────┴────────────────────┐
                 │                                         │
                 ▼                                         ▼
   ┌───────────────────────────┐             ┌───────────────────────────┐
   │    1. PLANNER AGENT       │             │   LOCAL / CLOUD PROVIDER  │
   │  - Analyzes repository    │             │   - Google Gemini 2.5     │
   │  - Emits step roadmap     │             │   - OpenRouter            │
   └─────────────┬─────────────┘             │   - Local Ollama (GPU)    │
                 │                           └───────────────────────────┘
                 ▼                                         │
   ┌───────────────────────────┐                           │
   │    2. EXECUTOR AGENT      │ ◄─────────────────────────┘
   │  - Calls read_file        │
   │  - Calls write_file       │
   │  - Calls run_command      │
   └─────────────┬─────────────┘
                 │
                 ▼
   ┌───────────────────────────┐
   │    3. REVIEWER AGENT      │
   │  - Side-by-side git diff  │
   │  - Security & bug audit   │
   └─────────────┬─────────────┘
                 │
                 ▼
   ┌───────────────────────────┐
   │    4. VERIFIER AGENT      │
   │  - Runs test suites       │
   │  - Validates pass state   │
   └───────────────────────────┘
```

---

## 📥 Desktop Downloads & Releases

Aether OS for Windows is distributed in two formats:

| Distribution Format | Description | Architecture | Download Link |
|---|---|---|---|
| **Windows Installer** (`.exe`) | Full NSIS setup with Desktop and Start Menu shortcuts, auto-updater support. | `x64` (Win 10/11) | [Download Installer (`AetherOS-Setup-10.4.0.exe`)](https://github.com/Mustafahamid/Aether-OS/releases/latest) |
| **Portable Executable** (`.exe`) | Standalone binary. Zero install required; run directly from USB or any folder. | `x64` (Win 10/11) | [Download Portable (`AetherOS-10.4.0-Portable.exe`)](https://github.com/Mustafahamid/Aether-OS/releases/latest) |

### Cryptographic Checksum (SHA-256)
```text
e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855  AetherOS-Setup-10.4.0.exe
```

---

## 💻 System Requirements

| Hardware Component | Minimum Requirement | Recommended Specification | Production Optimal |
|---|---|---|---|
| **Operating System** | Windows 10 64-bit / Web Browser | Windows 11 64-bit | Windows 11 Pro / Enterprise |
| **Processor (CPU)** | Dual-Core Intel/AMD (2.0 GHz) | 8-Core Intel Core i7 / AMD Ryzen 7 | Intel Core i9 / AMD Ryzen 9 |
| **System Memory (RAM)** | 8 GB RAM (Cloud LLM Mode) | 16 GB – 32 GB RAM (Local AI) | 32 GB – 64 GB DDR5 |
| **Available Storage** | 500 MB Free Space | 15 GB+ (Local Models) | 50 GB+ NVMe SSD |
| **Graphics (GPU)** | Integrated Graphics (WebGL 2.0) | NVIDIA RTX 3060 (6GB VRAM) | NVIDIA RTX 4080 / 4090 (16GB+ VRAM) |

---

## ✨ Features (A to Z)

<details open>
<summary><strong>🔍 Click to expand the full A–Z capabilities matrix</strong></summary>

- **[A] Antigravity Multi-Agent Swarm:** Deconstructs complex tasks across Planner, Executor, Reviewer, and Verifier agents.
- **[B] Box IDE:** Complete development environment with Monaco editor, multi-tab file system, and integrated tools.
- **[C] Child-Process Terminal:** Hardware-accelerated terminal streaming native PowerShell/cmd child processes.
- **[D] Diff Review Engine:** Color-coded side-by-side git diff reviewer to safely inspect modifications before applying.
- **[E] Electron Desktop Shell:** Secure Windows desktop layer with native menu shortcuts and notification center.
- **[F] File System Access:** Native folder picker with full recursive tree explorer and file watcher.
- **[G] Git Operations:** Stage, commit, create branches, and push directly through the built-in Git assistant.
- **[H] Hybrid Cloud/Local AI:** Seamlessly toggle between cloud endpoints (Gemini, OpenRouter) and private offline models (Ollama).
- **[I] Interactive Live Preview:** Built-in iframe web sandbox with live hot reload for web prototyping.
- **[J] JSON / NDJSON Streaming:** Zero-lag token stream rendering with real-time markdown highlighting.
- **[K] Knowledge & Quota Limiter:** Intelligent history compression to prevent token limit exhaustion.
- **[L] Local AI Python Service:** Optional FastAPI microservice (`aether-ai`) for offline scripting.
- **[M] Monaco Editor Suite:** VS Code-grade editing experience with syntax support for 50+ programming languages.
- **[N] Native Windows Integration:** NSIS installer with system tray, custom protocol handlers, and native dialogs.
- **[O] Ollama GPU Acceleration:** Run Llama 3, DeepSeek-R1, and Qwen locally on your machine with zero data egress.
- **[P] Prompt & Skill Auto-Routing:** Inspects tasks to automatically inject specialized skill prompts for the task.
- **[Q] Quota Protection:** Configurable read and history caps to manage free-tier API usage.
- **[R] Role-Based Pipeline:** Strict role delegation prevents hallucinated tool calls.
- **[S] Sandboxed Security:** Main-process path traversal verification rejects unauthorized file operations.
- **[T] Terminal Session Multiplexing:** Run multiple terminal instances, watch tasks, and test runners simultaneously.
- **[U] Universal Workspace:** Open any existing workspace folder without project configuration lock-in.
- **[V] Voice & Multimodal Input:** Speech-to-text input and image attachment support for vision models.
- **[W] W3C Standards:** Built with modern React 19, ES modules, CSS variables, and modern web APIs.
- **[X] Xterm.js Engine:** Real terminal emulator with WebGL rendering and FitAddon viewport handling.
- **[Y] Yield-Optimized Agent Loops:** Multi-turn autonomous tool execution loops (up to 8 iterative passes).
- **[Z] Zero Data Leaks:** API credentials remain strictly inside local client storage.

</details>

---

## 🤖 Core Multi-Agent Swarm

Aether OS features a structured, role-based multi-agent execution pipeline:

```
agents/
├── 🧭 Planner Agent       → Milestone deconstruction, dependency graph analysis, and execution plan creation
├── ⚡ Executor Agent      → Clean AST-aware code synthesis, multi-file edits, and component scaffolding
├── 🔍 Reviewer Agent      → Side-by-side git diff verification, security checks, and static analysis
└── ✅ Verifier Agent      → Automated test suite runs, terminal validation, and regression prevention
```

---

## 🛡️ Architecture & Sandboxing

Aether OS enforces a multi-tier security model:

1. **Root Confinement (`resolveInRoot`):**
   When a user opens a folder, the system registers a unique `rootId`. Any relative path traversal (e.g. `../../Windows/System32`) is intercepted and rejected with `PATH_OUTSIDE_PROJECT_ROOT`.
2. **Context Isolation:**
   `contextIsolation: true`, `sandbox: true`, and `nodeIntegration: false`. The renderer has zero direct Node.js API access.
3. **Execution Guardrails:**
   Commands and file writes trigger interactive approval prompts unless explicitly enabled in developer preferences.

---

## 🏢 Leadership & Inciverse Enterprise

Aether OS is a flagship technology project developed under **Inciverse**.

### Leadership Team:
- **Mustafa Hamid** — Co-Founder of Inciverse & Creator of Aether OS
  - **Portfolio:** [mustafahamid.vercel.app](https://mustafahamid.vercel.app)
  - **Email:** `mustafahamid200917@gmail.com`
  - **LinkedIn:** [linkedin.com/in/mustafahamid17](https://www.linkedin.com/in/mustafahamid17/)
  - **GitHub:** [github.com/mustafahamid17](https://github.com/mustafahamid17)
  - **X (Twitter):** [@Mustafahamid](https://x.com/Mustafahamid)
  - **Instagram:** [@m._.stafahamid](https://www.instagram.com/m._.stafahamid/)

- **Yousuf Khan** — Co-Founder & Head of Marketing at Inciverse
  - **Email:** `inciverse001@gmail.com`
  - *Social channels currently in provisioning stage by Inciverse.*

---

## ⚖️ Proprietary License Notice

Copyright © 2026 Aether OS // A Project of **Inciverse**. Engineered by **Mustafa Hamid** & **Yousuf Khan**. All Rights Reserved.

The source code and multi-agent engine of Aether OS are **Proprietary & Private Software**. Unauthorized copying, redistribution, reverse engineering, or commercial sublicensing without written authorization is strictly prohibited.

For support, issues, or feature requests, please submit an issue on the public [GitHub Issues tracker](https://github.com/Mustafahamid/Aether-OS).
