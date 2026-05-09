<div align="center">

# 🐙 GitHub Copilot 教程中文版

### 让中文开发者把 Copilot 从 IDE 补全到 Agent / Cloud / CLI / 团队治理一站讲透

> 💎 **不是官方文档的翻译，而是为中文新手重写的双路径教程：理解篇讲清楚 Copilot 多入口怎么分工，官方篇当事实手册——两条路径同时跑，不替代彼此。**

[![类型](https://img.shields.io/badge/类型-Tutorial-blue?style=for-the-badge)](https://aiworkflowtutorials.com/docs/github-copilot)
[![章节](https://img.shields.io/badge/章节-56_篇-brightgreen?style=for-the-badge)](https://aiworkflowtutorials.com/docs/github-copilot)
[![语言](https://img.shields.io/badge/语言-简体中文-DC322F?style=for-the-badge)](#)
[![出品方](https://img.shields.io/badge/出品方-GitHub-181717?style=for-the-badge)](https://github.com/features/copilot)
[![繁体](https://img.shields.io/badge/繁体-zh--Hant-9b59b6?style=for-the-badge)](https://aiworkflowtutorials.com/docs/github-copilot)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-orange?style=for-the-badge)](CONTRIBUTING.md)

</div>

---

> 🎯 **Copilot 早就不只是「IDE 里的补全」，而是把 Agent Mode、Cloud Agent、CLI、Skills、MCP 都拼到 GitHub 生态里的一整套产品线。中文新手最容易把它和 Claude Code / Codex / Cursor 搞混——这份教程把"Copilot 适合什么、不适合什么"先讲清楚。**
>
> 这份教程基于 GitHub Copilot 官方文档、VS Code Agent Mode 行为和翔宇工作流真实项目实践重写，按「中文新手 → 第一性原理 → 循序渐进」组织。
> 12 篇 **从原理到实战** 帮你建立心智模型，11 个分组的 **官方教程中文版** 覆盖入门、入口、补全 Chat、Agent Mode、Cloud Agent、CLI、上下文、MCP、安全治理、SDK、实战工作流。
>
> 完整教程托管在翔宇工作流的中文教程站，本仓库是公开门面入口，负责发现、反馈和样章预览。

<div align="center">

[🚀 立刻开始阅读](https://aiworkflowtutorials.com/docs/github-copilot) · [🧠 从原理到实战](https://aiworkflowtutorials.com/docs/github-copilot/understanding) · [📚 官方教程中文版](https://aiworkflowtutorials.com/docs/github-copilot/official) · [🐛 反馈问题](https://github.com/xiangyugongzuoliu/github-copilot-tutorial/issues)

</div>

---

## 📖 这是什么 (What)

> 💡 **核心定位**：中文开发者的 GitHub Copilot 学习入口 —— 一站把补全 × Chat × Agent Mode × Cloud Agent × CLI × MCP × 团队治理全链路讲透。

这是《AI 编程教程中文版》里的 GitHub Copilot 主题，由 [aiworkflowtutorials.com](https://aiworkflowtutorials.com/docs/github-copilot) 发布完整内容。本 GitHub 仓库只放门面入口、学习路线和样章摘录。

### 📐 双路径结构

| 路径 | 适合谁 | 章节数 | 入口 |
|------|--------|:------:|------|
| 🧠 **从原理到实战** | 想理解 Copilot 多入口怎么分工、和 Claude Code / Codex / Cursor 怎么选 | **12 篇** | [开始 →](https://aiworkflowtutorials.com/docs/github-copilot/understanding) |
| 📚 **官方教程中文版** | 想直接查每个入口的命令、配置、SDK、企业治理 | **44 篇** | [开始 →](https://aiworkflowtutorials.com/docs/github-copilot/official) |

两条路径**结构对称、互相引用**：理解篇遇到「具体怎么配」时跳官方篇，官方篇遇到「为什么要这样」时跳理解篇。

### 🎯 这份教程的不同

- 🇨🇳 **为中文新手重写**：每篇按"先讲场景再讲原理"的顺序，避免官方文档跳跃式叙述
- 🐙 **从补全到 Agent 全谱系**：从 IDE 内联补全 → Chat → Agent Mode → Cloud Agent → CLI 五个层级讲清楚演进
- 🏢 **团队治理视角**：第 11 章直接讲企业上线前怎么过安全和计费这两关
- 🔁 **简繁双语**：简体 + 繁体同时维护，海外华人开发者直接可用

---

## 🚀 怎么用 (How to Use)

> 💡 **最佳用法 · 交给 AI Agent 讲给你听**
>
> 把本仓库 clone 下来或整段贴给 **Claude Code / OpenAI Codex** 这类 AI 编程 Agent，让它读完 README 后**按你的节奏一篇一篇讲**——不懂的随时打断追问，比自己埋头通读高效得多。

### 推荐阅读顺序

1. 先读官方教程中文版的「**入门与定位 + 入口与使用场景**」8 篇，搞清楚 Copilot 各入口的差异
2. 再读从原理到实战 **01-05**，建立 Copilot 上下文工程、补全到 Agent Mode 的演进心智模型
3. 回到真实项目，用一个小改动练习"VS Code Agent Mode 写 → Cloud Agent 跑长任务 → PR 闭环"
4. 最后进入 **CLI / MCP / 安全治理 / SDK / 团队工作流**，把 Copilot 沉淀成团队级生产工具

### 🧠 从原理到实战（12 篇）

| # | 章节 | 链接 |
|:-:|------|------|
| 01 | GitHub Copilot 是什么 | [阅读 →](https://aiworkflowtutorials.com/docs/github-copilot/understanding/01-what-is-github-copilot) |
| 02 | Copilot 和 Claude Code、Codex、Cursor 怎么选 | [阅读 →](https://aiworkflowtutorials.com/docs/github-copilot/understanding/02-copilot-vs-claude-code-codex-cursor) |
| 03 | Copilot 的入口地图 | [阅读 →](https://aiworkflowtutorials.com/docs/github-copilot/understanding/03-copilot-surfaces-map) |
| 04 | 从补全到 Agent Mode | [阅读 →](https://aiworkflowtutorials.com/docs/github-copilot/understanding/04-from-autocomplete-to-agent) |
| 05 | Copilot 的上下文工程 | [阅读 →](https://aiworkflowtutorials.com/docs/github-copilot/understanding/05-context-engineering-for-copilot) |
| 06 | VS Code Agent Mode 怎么用 | [阅读 →](https://aiworkflowtutorials.com/docs/github-copilot/understanding/06-agent-mode-in-vscode) |
| 07 | Cloud Agent 到 PR 的闭环 | [阅读 →](https://aiworkflowtutorials.com/docs/github-copilot/understanding/07-cloud-agent-pr-loop) |
| 08 | Copilot CLI 工作流 | [阅读 →](https://aiworkflowtutorials.com/docs/github-copilot/understanding/08-copilot-cli-workflow) |
| 09 | 指令、Skills、Hooks 怎么分工 | [阅读 →](https://aiworkflowtutorials.com/docs/github-copilot/understanding/09-custom-instructions-rules-skills-hooks) |
| 10 | Copilot 和 MCP 怎么接 | [阅读 →](https://aiworkflowtutorials.com/docs/github-copilot/understanding/10-mcp-with-copilot) |
| 11 | 团队上线前的安全和治理 | [阅读 →](https://aiworkflowtutorials.com/docs/github-copilot/understanding/11-security-admin-billing) |
| 12 | 真实团队工作流 | [阅读 →](https://aiworkflowtutorials.com/docs/github-copilot/understanding/12-real-team-workflows) |

### 📚 官方教程中文版（11 个分组 · 44 篇）

| 分组 | 主题 | 篇数 | 入口 |
|------|------|:----:|------|
| 🟢 **入门与定位** | Copilot 适合什么 / 怎么选 / 第一次启用 | 4 | [开始 →](https://aiworkflowtutorials.com/docs/github-copilot/official/00-getting-started) |
| 🚪 **入口与使用场景** | IDE / Chat / Agent / CLI / Cloud 各入口怎么用 | 4 | [开始 →](https://aiworkflowtutorials.com/docs/github-copilot/official/01-surfaces) |
| ✍️ **补全与 Chat** | 内联补全 / Chat / 多文件改写 | 4 | [开始 →](https://aiworkflowtutorials.com/docs/github-copilot/official/02-code-suggestions-and-chat) |
| 🤖 **VS Code Agent Mode** | Agent Mode 工作流 + 任务编排 | 4 | [开始 →](https://aiworkflowtutorials.com/docs/github-copilot/official/03-vscode-agent-mode) |
| ☁️ **Cloud Agent** | Cloud Agent / PR 闭环 / 任务调度 | 4 | [开始 →](https://aiworkflowtutorials.com/docs/github-copilot/official/04-cloud-agent) |
| 💻 **Copilot CLI** | 命令行工作流 / 脚本化 | 4 | [开始 →](https://aiworkflowtutorials.com/docs/github-copilot/official/05-copilot-cli) |
| 📝 **上下文与定制** | Custom Instructions / Rules / Skills | 4 | [开始 →](https://aiworkflowtutorials.com/docs/github-copilot/official/06-context-customization) |
| 🔌 **MCP 与外部工具** | MCP 接入 / 工具管理 / 权限 | 4 | [开始 →](https://aiworkflowtutorials.com/docs/github-copilot/official/07-mcp) |
| 🔒 **安全、治理与计费** | 企业策略 / 审计 / 计费 / 合规 | 4 | [开始 →](https://aiworkflowtutorials.com/docs/github-copilot/official/08-security-governance) |
| 📦 **SDK 与自定义 Agent** | SDK / 编程接入 / 自定义 Agent | 4 | [开始 →](https://aiworkflowtutorials.com/docs/github-copilot/official/09-sdk-and-custom-agents) |
| 🛠️ **实战工作流** | 真实团队工作流 / 案例 | 4 | [开始 →](https://aiworkflowtutorials.com/docs/github-copilot/official/10-practical-playbooks) |

### 💡 第一次在项目里用 Copilot Agent Mode

```text
你（在 VS Code 切到 Copilot Agent Mode）：

  我在 ~/projects/{repo}，先读 README、入口模块、测试目录，
  告诉我这个项目是干什么的、主要模块怎么分工。
  接着提出三个最小的可改进点（每条不超过 1 行），
  我选一个之后你写多文件 diff，我审完再让 Cloud Agent 起 PR。
```

> 🎯 **Copilot 的关键是「IDE Agent Mode 写、Cloud Agent 跑长任务、PR 当验收线」**——三个层级各管一段，不要都用 IDE 里的 Agent 处理几十分钟的长任务。

---

## 🤝 怎么贡献 (Contribute)

本仓库**只接受 issue 反馈**，不接受完整教程正文 PR（完整内容在私有生产仓维护）。

适合提交的 issue：

- 🐛 **错别字 / 死链 / 事实错误**：教程站任意章节
- 🔗 **官方资料链接更新**：GitHub Copilot 文档结构调整的同步
- ✨ **样章表达问题**：本仓 `samples/` 里的样章
- 💡 **学习路径建议**：哪一章顺序应该调整、哪一篇应该补案例

[🐛 提交 Issue](https://github.com/xiangyugongzuoliu/github-copilot-tutorial/issues) · [📜 完整贡献指南](CONTRIBUTING.md) · [🔒 版权说明](COPYRIGHT.md)

如果这份教程帮到你，给本仓库一个 ⭐ 是最直接的鼓励——也方便其他中文开发者发现它。

---

## 👋 关于翔宇 (About)

> 🚀 **翔宇 — AI Agent 工作流研究者。**
>
> 把 AI 工具变成能持续运转的生产系统，专注 Claude Code / Codex 等 AI 编程 Agent 的真实工程化用法，把「AI 怎么帮普通人解决真实问题」作为长期方向。

### 📚 公开内容矩阵

| 平台 | 内容 | 链接 |
|------|------|------|
| 🌐 **翔宇工作流官网** | AI 编程 / Agent / 自动化深度教程 | [xiangyugongzuoliu.com](https://xiangyugongzuoliu.com) |
| 📺 **YouTube 频道** | AI 编程实战、Agent 知识库实战、视频教程 | [@xiangyugongzuoliu](https://www.youtube.com/@xiangyugongzuoliu) |
| 💻 **GitHub Profile** | 公开仓库 + 个人简介 | [@xiangyugongzuoliu](https://github.com/xiangyugongzuoliu) |
| 𝕏 **X / Twitter** | 工作流碎片 + 实战记录 | [@xiangyuworkflow](https://x.com/xiangyuworkflow) |
| 💬 **微信公众号** | 应用场景引流文 + 工作流案例 | 翔宇工作流 |

### 🎯 推荐先看

- 🤖 [**AI 编程教程中文版**](https://aiworkflowtutorials.com) — 本仓库所属的教程站全集
- 🎬 [**YouTube · Agent 知识库实战**](https://www.youtube.com/@xiangyugongzuoliu) — Claude Code / Codex 真实项目录屏
- 🌐 [**翔宇工作流官网**](https://xiangyugongzuoliu.com) — 项目复盘、踩坑记录、长文工作流

### 🎓 AI 编程实操课

想系统学习 AI 编程 / Agent 工作流（Claude Code / Codex 实战），可以看翔宇的 AI 编程实操课：

- 🇨🇳 **国内版（FlowUS）**：https://flowus.cn/xiangyugongzuoliu/share/d392dcad-b537-44ee-a3e2-56ff5af02bce
- 🌍 **国际版（Buy Me a Coffee）**：[buymeacoffee.com/xiangyu](https://buymeacoffee.com/xiangyu)

> 🎁 **会员附赠**：跟着课程一起交付的实战脚手架 + Custom Instructions / Cloud Agent PR 模板，把"读懂"变成"装进自己的工作流"。

---

<div align="center">

### ⭐ 如果这个教程对你有用，给一个 Star 让翔宇知道

[![翔宇官网](https://img.shields.io/badge/🌐_官网-xiangyugongzuoliu.com-FF6B35?style=for-the-badge)](https://xiangyugongzuoliu.com)
[![YouTube](https://img.shields.io/badge/📺_YouTube-频道-FF0000?style=for-the-badge)](https://www.youtube.com/@xiangyugongzuoliu)
[![GitHub](https://img.shields.io/badge/💻_GitHub-Profile-181717?style=for-the-badge)](https://github.com/xiangyugongzuoliu)

> 🎯 **工具一直在变，工作流不变。**
>
> 🛠️ **普通人对抗专业壁垒的唯一武器，就是工具。**

</div>
