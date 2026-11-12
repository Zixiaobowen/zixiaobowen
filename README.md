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

### AI Environment

- Agent environments: `Tern / OMP` · `Hermes` · `Codex` · `Claude Code`
- Model access & routing: `Magpie` · `LM Studio` · `GPT` · `DeepSeek` · `Qwen / MLX`
- Context & tools: `AGENTS.md` · `Skills` · `MCP` · project memory · handoff records
- Other tools and models used: `Cursor` · `GitHub Copilot` · `Claude` · `GLM` · `MiniMax`

### Languages & Product Engineering

<p>
  <img src="https://skillicons.dev/icons?i=ts,js,react,nextjs,astro,nodejs,nestjs,java,spring,graphql" alt="TypeScript, JavaScript, React, Next.js, Astro, Node.js, NestJS, Java, Spring and GraphQL" />
</p>

### Desktop & Mobile

- Desktop: `Electron` · `Swift / SwiftUI` · `SQLite` · `CloudKit`
- Mobile: `React Native / Expo` · `Taro`
- Exploration: `Tauri / Rust`

### Data, Tooling & Infrastructure

<p>
  <img src="https://skillicons.dev/icons?i=postgres,mysql,redis,vite,vitest,jest,docker,git,githubactions,pnpm,bun" alt="PostgreSQL, MySQL, Redis, Vite, Vitest, Jest, Docker, Git, GitHub Actions, pnpm and Bun" />
</p>

`Nx` · `Rspack / Rsbuild` · `Module Federation` · `Prisma` · `Playwright` · `OpenAPI` · `Orama`

## Engineering Principles

- **Fail fast** — errors should never pass silently.
- **Fix causes, not symptoms** — avoid papering over bugs.
- **Make it observable** — critical paths need useful logs, metrics, and traces.
- **Design for debugging** — important decisions and state transitions should be explainable.
- **Keep documentation alive** — code, contracts, and operational knowledge evolve together.
- **Protect the mainline** — isolate risky work and keep changes reviewable.
