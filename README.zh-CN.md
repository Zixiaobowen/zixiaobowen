<div align="center">

<p><a href="./README.md">English</a> · <strong>简体中文</strong></p>

<h1>
  <a href="https://ascii.rest/banner/?text=zixiaobowen&amp;font=slim&amp;shadow=rounded&amp;color=2563eb%2C0d9488&amp;speed=slow&amp;size=l&amp;tagline=build.%20observe.%20debug.%20repeat.">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://ascii.rest/banner/zixiaobowen.dark.svg?font=slim&amp;shadow=rounded&amp;color=2563eb%2C0d9488&amp;speed=slow&amp;size=l&amp;tagline=build.%20observe.%20debug.%20repeat.">
      <img src="https://ascii.rest/banner/zixiaobowen.svg?font=slim&amp;shadow=rounded&amp;color=2563eb%2C0d9488&amp;speed=slow&amp;size=l&amp;tagline=build.%20observe.%20debug.%20repeat." alt="你好，我是 Zixiaobowen — 构建、观测、调试、持续改进。" width="696">
    </picture>
  </a>
</h1>

### 企业软件工程与 AI 工作流实践

前端 / 全栈工程师，工作覆盖虚拟化与容灾、前端平台、产品网站及多端业务系统。我也搭建和维护自己的 AI 研发工作流：配置模型路由、组织 Agent 协作，并在真实项目中验证结果。

<p>
  <img src="https://img.shields.io/badge/AI_Agents-111827?style=flat-square&logo=openai&logoColor=white" alt="AI Agents" />
  <img src="https://img.shields.io/badge/Agent_Orchestration-4F46E5?style=flat-square" alt="Agent Orchestration" />
  <img src="https://img.shields.io/badge/MCP-0F766E?style=flat-square" alt="Model Context Protocol" />
  <img src="https://img.shields.io/badge/Local_Models-B45309?style=flat-square" alt="Local Models" />
  <img src="https://img.shields.io/badge/Observable_by_Design-0369A1?style=flat-square" alt="Observable by Design" />
</p>

</div>

## AI 工作流实践

我负责需求判断、架构取舍和最终验收，Agent 在明确的任务范围内参与调查、实现与评审。

- **模型分工**：通过 Magpie 为 Tern / OMP 与 Hermes 配置共享模型路由，按任务类型和复杂度分配工作；通过 LM Studio 接入本地 Qwen 模型，与云端模型配合使用。
- **Agent 协作**：拆分可独立执行的任务，明确负责文件与验收条件；需要隔离的改动使用 Git worktree，由主代理整合结果。
- **上下文维护**：用版本化的 `AGENTS.md`、项目记忆和交接记录保存约束、决策与验证结果。将反复使用的流程整理为 Skills，明确适用范围和触发条件。
- **工具与环境维护**：通过 MCP、CLI 和浏览器接入仓库、文档与外部服务；维护 Agent 环境时，检查实际工具调用和运行入口是否生效。
- **交付验证**：按需运行相关测试、浏览器检查和打包/安装冒烟检查。代码已推送、制品已打包、服务已部署、真实集成已验收，分别记录和核实。

## 工程实践

- **虚拟化与容灾**——资源监控和告警、恢复点与容灾演练流程、GraphQL BFF 模型与类型契约，以及中英俄多语言支持。
- **前端平台治理**——Rspack/Rsbuild 升级、Module Federation 兼容性、深色模式与主题集成，以及持续的类型和测试技术债清理。
- **产品网站与知识平台**——双语产品网站和文档平台、文档全文搜索、技术内容、下载与装机分析，以及部署验证。
- **多端业务系统**——NestJS/Prisma API、PostgreSQL、Next.js Web、React Native/Expo 应用及 Taro 小程序；共享设计系统、Android 打包与发布质量治理。

## 技术栈

### AI 工作环境

- Agent 环境：`Tern / OMP` · `Hermes` · `Codex` · `Claude Code`
- 模型接入与路由：`Magpie` · `LM Studio` · `GPT` · `DeepSeek` · `Qwen / MLX`
- 上下文与工具：`AGENTS.md` · `Skills` · `MCP` · 项目记忆 · 交接记录
- 其他使用经验：`Cursor` · `GitHub Copilot` · `Claude` · `GLM` · `MiniMax`

### 语言与产品研发

<p>
  <img src="https://skillicons.dev/icons?i=ts,js,react,nextjs,astro,nodejs,nestjs,java,spring,graphql" alt="TypeScript、JavaScript、React、Next.js、Astro、Node.js、NestJS、Java、Spring 和 GraphQL" />
</p>

### 桌面与移动端

- 桌面：`Electron` · `Swift / SwiftUI` · `SQLite` · `CloudKit`
- 移动端：`React Native / Expo` · `Taro`
- 探索：`Tauri / Rust`

### 数据、工具与基础设施

<p>
  <img src="https://skillicons.dev/icons?i=postgres,mysql,redis,vite,vitest,jest,docker,git,githubactions,pnpm,bun" alt="PostgreSQL、MySQL、Redis、Vite、Vitest、Jest、Docker、Git、GitHub Actions、pnpm 和 Bun" />
</p>

`Nx` · `Rspack / Rsbuild` · `Module Federation` · `Prisma` · `Playwright` · `OpenAPI` · `Orama`

## 工程原则

- **快速失败**——绝不让错误悄无声息地被吞掉。
- **修复根因，而非症状**——不在 Bug 上堆叠掩盖问题的补丁。
- **保持可观测**——关键路径应当具备有效的日志、指标和链路追踪。
- **面向调试设计**——重要决策和状态变化应当可解释、可追溯。
- **让文档持续演进**——代码、契约与运维知识必须同步更新。
- **保护主干稳定**——隔离高风险工作，让每次变更都清晰可评审。
