<div align="center">

<p><strong>English</strong> · <a href="./README.zh-CN.md">简体中文</a></p>

<h1>
  <a href="https://ascii.rest/banner/?text=zixiaobowen&amp;font=slim&amp;shadow=rounded&amp;color=2563eb%2C0d9488&amp;speed=slow&amp;size=l&amp;tagline=build.%20observe.%20debug.%20repeat.">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://ascii.rest/banner/zixiaobowen.dark.svg?font=slim&amp;shadow=rounded&amp;color=2563eb%2C0d9488&amp;speed=slow&amp;size=l&amp;tagline=build.%20observe.%20debug.%20repeat.">
      <img src="https://ascii.rest/banner/zixiaobowen.svg?font=slim&amp;shadow=rounded&amp;color=2563eb%2C0d9488&amp;speed=slow&amp;size=l&amp;tagline=build.%20observe.%20debug.%20repeat." alt="Hi, I'm Zixiaobowen — build. observe. debug. repeat." width="696">
    </picture>
  </a>
</h1>

### Enterprise software engineering and AI workflows

Frontend / full-stack engineer working on virtualization and disaster recovery, frontend platforms, product websites, and multi-client business systems. I also build and maintain AI workflows: configuring model routing, coordinating agents, and verifying their work in real projects.

<p>
  <img src="https://img.shields.io/badge/AI_Agents-111827?style=flat-square&logo=openai&logoColor=white" alt="AI Agents" />
  <img src="https://img.shields.io/badge/Agent_Orchestration-4F46E5?style=flat-square" alt="Agent Orchestration" />
  <img src="https://img.shields.io/badge/MCP-0F766E?style=flat-square" alt="Model Context Protocol" />
  <img src="https://img.shields.io/badge/Local_Models-B45309?style=flat-square" alt="Local Models" />
  <img src="https://img.shields.io/badge/Observable_by_Design-0369A1?style=flat-square" alt="Observable by Design" />
</p>

</div>

## AI Engineering Workflows

I make the requirements and architecture decisions and take responsibility for final acceptance. Agents work on scoped research, implementation, and review tasks.

- **Model routing** — configure shared routing through Magpie for Tern / OMP and Hermes, assigning work by task type and complexity. Connect local Qwen models through LM Studio alongside cloud models.
- **Agent collaboration** — split independent tasks, define file ownership and acceptance criteria, and use Git worktrees when changes need isolation. The lead agent integrates the results.
- **Persistent context** — maintain versioned `AGENTS.md`, project memory, and handoff records with constraints, decisions, and verification results. Turn recurring procedures into skills with explicit scope and triggers.
- **Tools and runtime** — connect repositories, documents, and external services through MCP, CLIs, and the browser. Check actual tool calls and runtime entry points when maintaining the agent environment.
- **Delivery evidence** — run targeted tests, browser checks, and package/install smoke checks as needed. Track code pushed, artifacts packaged, services deployed, and live integrations verified as separate outcomes.

## Engineering Work

- **Virtualization & disaster recovery** — resource monitoring and alarms, recovery-point and DR-drill workflows, GraphQL BFF models and type contracts, and Chinese/English/Russian localization.
- **Frontend platform engineering** — Rspack/Rsbuild upgrades, Module Federation compatibility, dark-mode and theming integrations, and ongoing type/test-debt cleanup.
- **Product sites & knowledge platforms** — bilingual product and documentation sites, full-text documentation search, technical content, download/installation analytics, and deployment verification.
- **Multi-client business apps** — NestJS/Prisma APIs, PostgreSQL, Next.js web, React Native/Expo apps, and a Taro mini-program; a shared design system, Android packaging, and release hardening.

## Tech Stack

### AI · Foundation Models & Agent Engineering

| Layer | Tools & practice |
| --- | --- |
| **Foundation Models** | `GPT` · `Claude` · `DeepSeek` · `Qwen / MLX` · `GLM` · `MiniMax`; model routing through `Magpie`, local inference through `LM Studio`. |
| **Harness** | `OMP` · `Hermes` · `Codex` · `Claude Code`; agent interaction in `Tern`, with tool permissions, session context, and execution boundaries. |
| **Loop** | Task decomposition, tool calls, verification, and feedback; delegate scoped tasks to subagents, integrate results, and continue execution. |
| **Graph** | `Graphify` · `Madar`; query call chains and dependencies, and extract code context for the task. |
| **Skills** | Organize procedures, scripts, and references in `SKILL.md`, with explicit triggers, scope, and verification steps. |
| **Workflow** | Connect requirements, implementation, review, testing, and release acceptance through `AGENTS.md`, project memory, and handoff records. |

Tool integration: `MCP` · `CLI` · browser automation. Editor assistance: `Cursor` · `GitHub Copilot`.

---

### Traditional Engineering · Frontend, Full-stack & Cross-platform

TypeScript / React is my main focus, alongside backend services, desktop and mobile apps, builds, testing, and deployment.

#### Frontend

<p>
  <img src="https://skillicons.dev/icons?i=ts,js,react,nextjs,astro" alt="TypeScript, JavaScript, React, Next.js and Astro" />
</p>

Design systems, theming, and localization; `Nx` · `Module Federation` · `Vite` · `Rspack / Rsbuild`.

#### Backend & Data

- APIs: `Node.js` · `NestJS` · `GraphQL` · `OpenAPI` · `Java / Spring`
- Data & search: `PostgreSQL` · `MySQL` · `Redis` · `Prisma` · `Orama`

#### Cross-platform

- Desktop: `Electron` · `Swift / SwiftUI` · `SQLite` · `CloudKit`
- Mobile & mini-programs: `React Native / Expo` · `Taro`
- Exploration: `Tauri / Rust`

#### Tooling & Deployment

<p>
  <img src="https://skillicons.dev/icons?i=vitest,jest,docker,nginx,git,githubactions,pnpm,bun" alt="Vitest, Jest, Docker, Nginx, Git, GitHub Actions, pnpm and Bun" />
</p>

- Testing & acceptance: `Vitest` · `Jest` · `Playwright`, covering targeted tests, browser verification, and package/install checks.
- Builds & delivery: `Git` · `pnpm` · `Bun` · `GitHub Actions`; web builds and desktop/mobile packaging.
- Deployment: `Docker` · `Nginx` · `Linux / SSH`; service configuration, deployment verification, and production debugging.

## Engineering Principles

- **Fail fast** — errors should never pass silently.
- **Fix causes, not symptoms** — avoid papering over bugs.
- **Make it observable** — critical paths need useful logs, metrics, and traces.
- **Design for debugging** — important decisions and state transitions should be explainable.
- **Keep documentation alive** — code, contracts, and operational knowledge evolve together.
- **Protect the mainline** — isolate risky work and keep changes reviewable.
