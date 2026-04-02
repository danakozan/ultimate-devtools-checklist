# Core Engineering Ecosystem & Toolchain

> **Status:** Production-Ready | **Last Audit:** April 2026 | **License:** MIT

This repository serves as a curated foundation for building, scaling, and maintaining modern distributed systems. It focuses on the "Golden Path" of development—tools that prioritize developer velocity without sacrificing architectural integrity.

---

### Core Infrastructure & AI
| Tool | Category | Strategic Utility |
| :--- | :--- | :--- |
| **[Cursor](https://cursor.sh)** | AI-First IDE | Next-gen fork of VS Code with native AI orchestration and full-repo context. |
| **[Docker](https://www.docker.com)** | Containerization | Industry standard for ensuring environment parity across the SDLC. |
| **[GitHub Actions](https://github.com/features/actions)** | CI/CD | Native automation for testing, security scanning, and deployment pipelines. |
| **[Windsurf](https://codeium.com/windsurf)** | AI Agent | High-performance agentic workflows for complex, multi-file refactors. |

### Frontend & Design Systems
* **[Tailwind CSS](https://tailwindcss.com):** Utility-first styling engine that eliminates CSS technical debt.
* **[shadcn/ui](https://ui.shadcn.com):** Headless, accessible component primitives built on Radix UI. 
* **[Vite](https://vitejs.dev):** Next-generation frontend tooling with near-instant Hot Module Replacement (HMR).
* **[Lucide Icons](https://lucide.dev):** Consistent, pixel-perfect icon sets for professional interface design.

### Backend & API Orchestration
* **[Postman](https://www.postman.com):** The definitive platform for API design, automated testing, and documentation.
* **[Drizzle ORM](https://orm.drizzle.team):** TypeScript-first ORM providing type safety with zero abstraction overhead.
* **[Redis](https://redis.io):** In-memory data store for low-latency caching and real-time message brokering.
* **[LocalStack](https://localstack.cloud):** Fully functional local AWS cloud stack for offline cloud-native development.

### Productivity & Workflow
* **[Linear](https://linear.app):** High-velocity project management for teams that prioritize execution over overhead.
* **[fzf](https://github.com/junegunn/fzf):** Command-line fuzzy finder—essential for terminal-based navigation efficiency.
* **[Oh My Zsh](https://ohmyz.sh):** Advanced framework for managing shell configurations and productivity plugins.

---

### Architectural Principles
1. **Separation of Concerns:** Rigidly decouple business logic from the presentation layer.
2. **Type Safety:** All implementations must be strictly typed to prevent runtime regressions.
3. **Observability:** If a metric isn't being tracked (Grafana/Prometheus), the feature doesn't exist.

---

### 🤝 Contributing
I’m constantly auditing this list. If you have a tool that survives a **production-stress-test**, please open a PR!
