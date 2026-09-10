<div align="center">

# Awesome Claude Code [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<p>
  <strong>精选的 Claude Code 项目、工具、框架、扩展和资源合集。</strong>
</p>

<p>
  <a href="README.md">🇺🇸 English</a> | <a href="README_CN.md">🇨🇳 中文</a>
</p>

<p>
  <img src="https://img.shields.io/badge/仓库数量-185%2B-blue" alt="repos">
  <img src="https://img.shields.io/badge/欢迎-PR贡献-brightgreen" alt="PRs welcome">
  <img src="https://img.shields.io/badge/许可证-CC%20BY%204.0-lightgrey" alt="license">
</p>

</div>

> **Claude Code** 是 Anthropic 出品的 AI 编程助手，在终端中运行，深度理解你的代码库，并通过自主执行常规任务帮助你更快速地编写代码。
> 官网：[claude.ai/code](https://claude.ai/code) | 文档：[docs.anthropic.com/en/docs/claude-code](https://docs.anthropic.com/en/docs/claude-code)

---

## 目录

- [官方项目](#官方项目)
- [框架与配置系统](#框架与配置系统)
- [多智能体编排](#多智能体编排)
- [路由与代理](#路由与代理)
- [界面、网页与桌面应用](#界面网页与桌面应用)
- [记忆与上下文工程](#记忆与上下文工程)
- [MCP 服务器与集成](#mcp-服务器与集成)
- [技能与子智能体合集](#技能与子智能体合集)
- [Slash 命令](#slash-命令)
- [Hooks 与自动化](#hooks-与自动化)
- [模板、CLAUDE.md 与最佳实践](#模板claudemd-与最佳实践)
- [用量统计与监控](#用量统计与监控)
- [IDE 与编辑器集成](#ide-与编辑器集成)
- [安全与权限管理](#安全与权限管理)
- [CI/CD 与 DevOps](#cicd-与-devops)
- [垂直领域技能](#垂直领域技能)
- [教程与学习资源](#教程与学习资源)
- [提示词泄露与系统提示词](#提示词泄露与系统提示词)
- [精选合集与 Awesome 列表](#精选合集与-awesome-列表)

---

## 官方项目

| 仓库 | 星标 | 简介 |
|---|---|---|
| [anthropics/claude-code](https://github.com/anthropics/claude-code) | 113k ⭐ | 官方 Claude Code —— 在终端运行的 AI 编程助手，理解你的代码库，自主执行编程任务 |
| [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official) | 16.8k ⭐ | Anthropic 官方维护的高质量 Claude Code 插件目录 |
| [anthropics/claude-code-action](https://github.com/anthropics/claude-code-action) | 7k ⭐ | 官方 GitHub Action —— 将 Claude Code 集成到 CI/CD 流水线中 |

---

## 框架与配置系统

完整的系统、框架和配置方案，用于扩展或增强 Claude Code 的核心能力。

| 仓库 | 星标 | 简介 |
|---|---|---|
| [affaan-m/everything-claude-code](https://github.com/affaan-m/everything-claude-code) | 153k ⭐ | Agent Harness 性能优化系统 —— 技能、本能、记忆、安全机制和研究优先的开发理念 |
| [garrytan/gstack](https://github.com/garrytan/gstack) | 70.8k ⭐ | Garry Tan 的完整 Claude Code 配置 —— 23 个工具扮演 CEO、设计师、工程经理、发版经理、文档工程师和 QA |
| [code-yeongyu/oh-my-openagent](https://github.com/code-yeongyu/oh-my-openagent) | 51k ⭐ | 最佳 Agent Harness（前身为 oh-my-opencode） |
| [gsd-build/get-shit-done](https://github.com/gsd-build/get-shit-done) | 51.4k ⭐ | 轻量而强大的元提示、上下文工程和规范驱动开发系统 |
| [SuperClaude-Org/SuperClaude_Framework](https://github.com/SuperClaude-Org/SuperClaude_Framework) | 22.3k ⭐ | 为 Claude Code 添加专用命令、认知角色和开发方法论的配置框架 |
| [coleam00/context-engineering-intro](https://github.com/coleam00/context-engineering-intro) | 13.1k ⭐ | 上下文工程入门 —— 让 AI 编程助手真正发挥作用的方法，以 Claude Code 为核心 |
| [coleam00/Archon](https://github.com/coleam00/Archon) | 17.1k ⭐ | 首个开源 AI 编程 Harness 构建器 —— 让 AI 编程变得可确定、可复现 |
| [aden-hive/hive](https://github.com/aden-hive/hive) | 10.2k ⭐ | 生产级 AI 多智能体 Harness |
| [e10nMa2k/cc-mini](https://github.com/e10nMa2k/cc-mini) | 776 ⭐ | 超轻量 AI Agent Harness 脚手架 —— Claude Code 的 mini 版 |
| [1rgs/nanocode](https://github.com/1rgs/nanocode) | 2.3k ⭐ | 极简 Claude Code 替代品 —— 单 Python 文件、零依赖、约 250 行 |
| [ProjectBarks/gopher-code](https://github.com/ProjectBarks/gopher-code) | 514 ⭐ | 用 Go 重写的 Claude Code —— 零 Node.js、零 Electron、单二进制文件 |
| [dfinke/PSClaudeCode](https://github.com/dfinke/PSClaudeCode) | 77 ⭐ | PowerShell 实现的 Claude Code：Agent 循环 + 工具 + 权限管理 |
| [can1357/oh-my-pi](https://github.com/can1357/oh-my-pi) | 2.9k ⭐ | 终端 AI 编程 Agent —— 哈希锚定编辑、优化工具 Harness、LSP、Python、浏览器支持 |
| [vibeeval/vibecosystem](https://github.com/vibeeval/vibecosystem) | 459 ⭐ | Claude Code 的 AI 软件团队 —— 138 个 Agent、295 个技能、73 个 Hook，自学习多智能体群 |
| [keli-wen/agentic-harness-patterns-skill](https://github.com/keli-wen/agentic-harness-patterns-skill) | 204 ⭐ | Harness 工程 Agent 技能 —— 记忆、权限、上下文工程、多智能体协调 |

---

## 多智能体编排

并行运行、管理和协调多个 Claude Code Agent 的工具。

| 仓库 | 星标 | 简介 |
|---|---|---|
| [wshobson/agents](https://github.com/wshobson/agents) | 33.5k ⭐ | Claude Code 的智能自动化和多智能体编排 |
| [ruvnet/ruflo](https://github.com/ruvnet/ruflo) | 31.5k ⭐ | 领先的 Claude Agent 编排平台 —— 部署智能多智能体群，协调自主工作流 |
| [Yeachan-Heo/oh-my-claudecode](https://github.com/Yeachan-Heo/oh-my-claudecode) | 28.1k ⭐ | 面向团队的 Claude Code 多智能体编排框架 |
| [BloopAI/vibe-kanban](https://github.com/BloopAI/vibe-kanban) | 24.9k ⭐ | 让 Claude Code 效率提升 10 倍的看板式编排工具 |
| [Kilo-Org/kilocode](https://github.com/Kilo-Org/kilocode) | 18k ⭐ | 一体化 AI 工程平台 —— OpenRouter 上最受欢迎的开源编程 Agent，150 万+ 用户 |
| [VoltAgent/awesome-claude-code-subagents](https://github.com/VoltAgent/awesome-claude-code-subagents) | 17.1k ⭐ | 100+ 个专用 Claude Code 子智能体，覆盖各类开发场景 |
| [smtg-ai/claude-squad](https://github.com/smtg-ai/claude-squad) | 7k ⭐ | 管理多个 AI 终端 Agent（Claude Code、Codex、OpenCode、Amp） |
| [yohey-w/multi-agent-shogun](https://github.com/yohey-w/multi-agent-shogun) | 1.2k ⭐ | 武士主题的 Claude Code 多智能体系统 —— 通过 tmux 编排并行 AI 任务 |
| [Dicklesworthstone/claude_code_agent_farm](https://github.com/Dicklesworthstone/claude_code_agent_farm) | — | 同时运行 20+ 个 Claude Code Agent 的编排框架，支持自动修复 Bug |
| [opslane/opslane](https://github.com/opslane/opslane) | 772 ⭐ | 并行运行多个 Claude Code 会话 |
| [stravu/crystal](https://github.com/stravu/crystal) | 3k ⭐ | 在并行 git worktree 中运行多个 Codex 和 Claude Code AI 会话 |
| [ceedaragents/cyrus](https://github.com/ceedaragents/cyrus) | 513 ⭐ | 支持 Linear、Slack、GitHub、GitLab 的 Claude Code 后台 Agent |
| [MiniCodeMonkey/chief](https://github.com/MiniCodeMonkey/chief) | 444 ⭐ | 用 Claude Code 构建大型项目 —— 将工作拆解为任务并循环执行直到完成 |
| [bfly123/claude_code_bridge](https://github.com/bfly123/claude_code_bridge) | 2.2k ⭐ | Claude、Codex & Gemini 实时多 AI 协作 —— 持久上下文，最少 Token 开销 |
| [santifer/career-ops](https://github.com/santifer/career-ops) | 31.8k ⭐ | 基于 Claude Code 的 AI 求职系统 —— 14 种技能模式、Go 看板、PDF 生成 |

---

## 路由与代理

通过不同模型路由 Claude Code 请求或创建兼容 API 代理的工具。

| 仓库 | 星标 | 简介 |
|---|---|---|
| [musistudio/claude-code-router](https://github.com/musistudio/claude-code-router) | 32.1k ⭐ | 以 Claude Code 为编程基础设施 —— 自定义模型交互方式，同时享受 Anthropic 的持续更新 |
| [farion1231/cc-switch](https://github.com/farion1231/cc-switch) | 43.5k ⭐ | 跨平台桌面一体化助手 —— 支持 Claude Code、Codex、OpenCode、openclaw & Gemini CLI |
| [router-for-me/CLIProxyAPI](https://github.com/router-for-me/CLIProxyAPI) | 25.4k ⭐ | 将 Gemini CLI、Codex、Claude Code、Qwen Code 封装为 OpenAI/Gemini/Claude 兼容 API |
| [fuergaosi233/claude-code-proxy](https://github.com/fuergaosi233/claude-code-proxy) | 2.4k ⭐ | Claude Code 转 OpenAI API 代理 |
| [ericc-ch/copilot-api](https://github.com/ericc-ch/copilot-api) | 3.6k ⭐ | 将 GitHub Copilot 转为 OpenAI/Anthropic 兼容 API —— 可配合 Claude Code 使用 |
| [Wei-Shaw/claude-relay-service](https://github.com/Wei-Shaw/claude-relay-service) | 11k ⭐ | 自建 Claude Code 镜像/中转服务 —— 统一接入 Claude、OpenAI、Gemini、Droid，支持拼车共享 |
| [ding113/claude-code-hub](https://github.com/ding113/claude-code-hub) | 2.4k ⭐ | 现代化 Claude Code & Codex API 代理 —— 智能负载均衡、用户管理、用量统计 |
| [glidea/claude-worker-proxy](https://github.com/glidea/claude-worker-proxy) | — | Cloudflare Worker 代理，轻松部署 Claude Code 中转服务 |
| [starbaser/ccproxy](https://github.com/starbaser/ccproxy) | 197 ⭐ | 为 Claude Code 构建 Mod：拦截任意请求、修改任意响应、使用自定义模型 |
| [UfoMiao/zcf](https://github.com/UfoMiao/zcf) | 5.9k ⭐ | Claude Code & Codex 零配置代码流 |
| [automazeio/vibeproxy](https://github.com/automazeio/vibeproxy) | 2.4k ⭐ | 原生 macOS 菜单栏应用 —— 在 AI 编程工具中使用 Claude Code & ChatGPT 订阅 |
| [heyhuynhgiabuu/proxypal](https://github.com/heyhuynhgiabuu/proxypal) | 1.1k ⭐ | 桌面应用 —— 将 Claude、ChatGPT、Gemini、GitHub Copilot 订阅用于编程工具 |

---

## 界面、网页与桌面应用

用于 Claude Code 的图形界面、Web UI 和桌面应用程序。

| 仓库 | 星标 | 简介 |
|---|---|---|
| [siteboon/claudecodeui](https://github.com/siteboon/claudecodeui) | 9.7k ⭐ | 在手机和网页上使用 Claude Code（CloudCLI） —— 免费开源 WebUI，支持远程会话管理 |
| [slopus/happy](https://github.com/slopus/happy) | 17.8k ⭐ | Codex 和 Claude Code 的移动端 + 网页客户端 —— 实时语音、加密、全功能 |
| [winfunc/opcode](https://github.com/winfunc/opcode) | 21.4k ⭐ | 强大的 Claude Code GUI 应用和工具包 —— 创建自定义 Agent，管理交互式会话 |
| [iOfficeAI/AionUi](https://github.com/iOfficeAI/AionUi) | 21.6k ⭐ | 免费、本地、开源的 24/7 协作应用，支持 Gemini CLI 的 OpenClaw |
| [jarrodwatts/claude-hud](https://github.com/jarrodwatts/claude-hud) | 18.7k ⭐ | Claude Code 插件 —— 实时显示上下文用量、活跃工具、运行中的 Agent |
| [superset-sh/superset](https://github.com/superset-sh/superset) | 9.5k ⭐ | AI Agent 时代的代码编辑器 —— 在本机运行 Claude Code、Codex 等 Agent 大军 |
| [LKbaba/Claude-code-ChatInWindows](https://github.com/LKbaba/Claude-code-ChatInWindows) | 210 ⭐ | VS Code 中的 Claude Code 全功能 GUI —— 支持 Windows（无需 WSL）、macOS，第三方 API，MCP 插件 |
| [opactorai/Claudable](https://github.com/opactorai/Claudable) | 3.9k ⭐ | 利用 Claude Code、Codex 等本地 CLI Agent 的开源 Web 构建器 |
| [Gitlawb/openclaude](https://github.com/Gitlawb/openclaude) | 21k ⭐ | 开源编程 Agent CLI，支持 OpenAI、Gemini、DeepSeek、Ollama、Codex、GitHub Models |
| [Iamshankhadeep/ccseva](https://github.com/Iamshankhadeep/ccseva) | 789 ⭐ | 精美的 macOS 菜单栏应用 —— 实时追踪 Claude Code 用量 |
| [matt1398/claude-devtools](https://github.com/matt1398/claude-devtools) | 3.1k ⭐ | Claude Code 的 DevTools —— 检查会话日志、工具调用、Token 用量、子 Agent |
| [steipete/CodexBar](https://github.com/steipete/CodexBar) | 10.6k ⭐ | 无需登录即可查看 OpenAI Codex 和 Claude Code 用量统计 |
| [nyatinte/ccexp](https://github.com/nyatinte/ccexp) | 264 ⭐ | 交互式终端界面 —— 发现、预览和管理 Claude Code 配置 |
| [kaida-palooza/ccpoke](https://github.com/kaida-palooza/ccpoke) | 97 ⭐ | AI 编程 Agent 与手机之间的桥梁 —— 通知、双向聊天、权限管理 |

---

## 记忆与上下文工程

持久记忆、上下文管理和智能上下文注入工具。

| 仓库 | 星标 | 简介 |
|---|---|---|
| [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem) | 50k+ ⭐ | Claude Code 插件 —— 自动捕获会话内容，用 AI 压缩后注入未来会话的上下文 |
| [OthmanAdi/planning-with-files](https://github.com/OthmanAdi/planning-with-files) | 18.6k ⭐ | 用 Manus 风格持久 Markdown 规划实现 Claude Code 工作流 |
| [rohitg00/agentmemory](https://github.com/rohitg00/agentmemory) | 939 ⭐ | 基于真实场景基准测试的 AI 编程 Agent 持久记忆方案 #1 |
| [HelloRuru/claude-memory-engine](https://github.com/HelloRuru/claude-memory-engine) | 114 ⭐ | 用 Hooks + Markdown 构建的 Claude Code 记忆系统 —— 零依赖 |
| [rohitg00/pro-workflow](https://github.com/rohitg00/pro-workflow) | 1.9k ⭐ | Claude Code 从错误中学习 —— 自我修正记忆，50+ 会话持续积累 |
| [tirth8205/code-review-graph](https://github.com/tirth8205/code-review-graph) | 9k ⭐ | Claude Code 的本地知识图谱 —— 构建代码库的持久地图 |
| [zilliztech/claude-context](https://github.com/zilliztech/claude-context) | 5.9k ⭐ | Claude Code 的代码搜索 MCP —— 将整个代码库作为任意编程 Agent 的上下文 |
| [mksglu/context-mode](https://github.com/mksglu/context-mode) | 7.1k ⭐ | AI 编程 Agent 的上下文窗口优化 —— 沙箱化工具输出，压缩率 98%，支持 12 个平台 |
| [JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman) | 22k ⭐ | 少用 Token 干大事 —— Claude Code 技能，可节省 65% Token |
| [iannuttall/claude-sessions](https://github.com/iannuttall/claude-sessions) | 1.2k ⭐ | 自定义 Slash 命令 —— 全面的开发会话追踪和文档化 |
| [peteromallet/dataclaw](https://github.com/peteromallet/dataclaw) | 2k ⭐ | Agent Harness，将 Claude Code 等工具的历史记录发布为 HuggingFace 数据集 |
| [Lum1104/Understand-Anything](https://github.com/Lum1104/Understand-Anything) | 8.2k ⭐ | 将任意代码或知识库转为交互式知识图谱 |
| [Astro-Han/karpathy-llm-wiki](https://github.com/Astro-Han/karpathy-llm-wiki) | 271 ⭐ | 兼容 Agent Skills 的 LLM Wiki，适用于 Claude Code、Cursor 和 Codex |
| [suffro/syngraphe](https://github.com/suffro/syngraphe) | 2 ⭐ | 基于 AGENTS.md 的 Git 原生仓库上下文工具，通过结构化 Markdown 为开发者和编码智能体共享项目上下文，并支持 CLAUDE.md |

---

## MCP 服务器与集成

扩展 Claude Code 工具能力的 MCP（模型上下文协议）服务器和集成。

| 仓库 | 星标 | 简介 |
|---|---|---|
| [oraios/serena](https://github.com/oraios/serena) | 22.8k ⭐ | 强大的 MCP 工具包 —— 语义检索和编辑能力（你的 Agent 的 IDE） |
| [czlonkowski/n8n-mcp](https://github.com/czlonkowski/n8n-mcp) | 18k ⭐ | 让 Claude Desktop / Claude Code / Windsurf / Cursor 构建 n8n 工作流的 MCP |
| [BeehiveInnovations/pal-mcp-server](https://github.com/BeehiveInnovations/pal-mcp-server) | 11.4k ⭐ | PAL MCP 服务器 —— 将 Claude Code 连接到 Gemini、OpenAI、OpenRouter、Azure、Grok、Ollama |
| [idosal/git-mcp](https://github.com/idosal/git-mcp) | 7.9k ⭐ | GitMCP —— 免费开源的 GitHub 项目远程 MCP 服务器，终结代码幻觉 |
| [grab/cursor-talk-to-figma-mcp](https://github.com/grab/cursor-talk-to-figma-mcp) | 6.6k ⭐ | TalkToFigma：AI Agent（Claude Code）与 Figma 之间的 MCP 集成 |
| [jau123/MeiGen-AI-Design-MCP](https://github.com/jau123/MeiGen-AI-Design-MCP) | 575 ⭐ | 将 Claude Code 变成本地 Lovart —— 本地 ComfyUI，1400+ 专业素材 |
| [Coolver/home-assistant-vibecode-agent](https://github.com/Coolver/home-assistant-vibecode-agent) | 520 ⭐ | Home Assistant MCP 服务器 —— 让 Claude Code、Cursor、VS Code 控制智能家居 |
| [Sunwood-ai-labs/draw-io-skill](https://github.com/Sunwood-ai-labs/draw-io-skill) | 31 ⭐ | 原生 draw.io 技能，含导出助手、SVG 检查，适用于 Codex 和 Claude Code |
| [teng-lin/notebooklm-py](https://github.com/teng-lin/notebooklm-py) | 10.3k ⭐ | Google NotebookLM 的非官方 Python API 和 Agentic 技能 |
| [mendixlabs/mxcli](https://github.com/mendixlabs/mxcli) | 61 ⭐ | Mendix CLI —— 无头方式操作 Mendix 项目，支持第三方 AI Agent |

---

## 技能与子智能体合集

大型技能集合、专用 Agent 和可复用 AI 行为库。

| 仓库 | 星标 | 简介 |
|---|---|---|
| [sickn33/antigravity-awesome-skills](https://github.com/sickn33/antigravity-awesome-skills) | 32.5k ⭐ | 1400+ 个可安装的 Agentic 技能，适用于 Claude Code、Cursor、Codex CLI、Gemini CLI |
| [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills) | 53.3k ⭐ | 精选 Claude Skills、资源和工具，用于自定义 Claude AI 工作流 |
| [VoltAgent/awesome-agent-skills](https://github.com/VoltAgent/awesome-agent-skills) | 15.4k ⭐ | 来自官方团队和社区的 1000+ Agent 技能精选集合 |
| [travisvn/awesome-claude-skills](https://github.com/travisvn/awesome-claude-skills) | 11.1k ⭐ | 用于自定义 Claude AI 工作流的技能、资源和工具精选列表 |
| [forrestchang/andrej-karpathy-skills](https://github.com/forrestchang/andrej-karpathy-skills) | 17.4k ⭐ | 单个 CLAUDE.md 文件改善 Claude Code 行为 —— 源自 Andrej Karpathy 的观察 |
| [Jeffallan/claude-skills](https://github.com/Jeffallan/claude-skills) | 8.1k ⭐ | 66 个专业全栈开发技能 —— 将 Claude Code 变成你的专家结对编程伙伴 |
| [slavingia/skills](https://github.com/slavingia/skills) | 7.8k ⭐ | 基于 Sahil Lavingia《极简创业者》的 Claude Code 技能 |
| [samber/cc-skills-golang](https://github.com/samber/cc-skills-golang) | 1.2k ⭐ | Claude Code 的 Golang Agentic 技能集合 |
| [jeremylongshore/claude-code-plugins-plus-skills](https://github.com/jeremylongshore/claude-code-plugins-plus-skills) | 1.9k ⭐ | 340 个插件 + 1367 个 Agent 技能，含 CCPI 包管理器 |
| [Orchestra-Research/AI-Research-SKILLs](https://github.com/Orchestra-Research/AI-Research-SKILLs) | 6.7k ⭐ | 全面的开源 AI 研究和工程技能库 |
| [runkids/skillshare](https://github.com/runkids/skillshare) | 1.4k ⭐ | 一条命令在所有 AI CLI 工具间同步技能 —— 支持 Codex、Claude Code |
| [alirezarezvani/claude-skills](https://github.com/alirezarezvani/claude-skills) | — | 232+ Claude Code 技能和 Agent 插件，支持 Claude Code、Codex、Gemini CLI、Cursor |
| [alirezarezvani/claude-code-tresor](https://github.com/alirezarezvani/claude-code-tresor) | 674 ⭐ | 世界级 Claude Code 工具合集：自主技能、专家 Agent、Slash 命令 |
| [alirezarezvani/claude-code-skill-factory](https://github.com/alirezarezvani/claude-code-skill-factory) | — | 强大的开源工具包，用于构建和部署生产级技能 |
| [refly-ai/refly](https://github.com/refly-ai/refly) | 7.2k ⭐ | 首个开源 Agent 技能构建器 —— 用 Vibe 工作流定义技能，在 Claude Code、Cursor 上运行 |
| [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) | 63.8k ⭐ | AI SKILL —— 为多平台专业 UI/UX 提供设计智能 |
| [Donchitos/Claude-Code-Game-Studios](https://github.com/Donchitos/Claude-Code-Game-Studios) | 8.7k ⭐ | 将 Claude Code 变成完整游戏开发工作室 —— 48 个 AI Agent、36 个工作流技能 |
| [htdt/godogen](https://github.com/htdt/godogen) | 2.8k ⭐ | 根据游戏描述构建完整 Godot 4 项目的 Claude Code 技能 |
| [vkehfdl1/slides-grab](https://github.com/vkehfdl1/slides-grab) | 468 ⭐ | Claude Code / Codex 中生成幻灯片的最佳 Harness + 编辑器 + Linter |
| [calesthio/OpenMontage](https://github.com/calesthio/OpenMontage) | 1.5k ⭐ | 全球首个开源 Agentic 视频制作系统 —— 11 条流水线、49 个工具、400+ Agent 技能 |
| [sangrokjung/claude-forge](https://github.com/sangrokjung/claude-forge) | 648 ⭐ | 为 Claude Code 提速 —— 11 个 AI Agent、36 个命令、15 个技能 |
| [libukai/awesome-agent-skills](https://github.com/libukai/awesome-agent-skills) | ~5k ⭐ | 精选 Agent 技能集合 |

---

## Slash 命令

Claude Code Slash 命令的集合与框架。

| 仓库 | 星标 | 简介 |
|---|---|---|
| [wshobson/commands](https://github.com/wshobson/commands) | 2.3k ⭐ | Claude Code 生产就绪 Slash 命令集合 |
| [qdhenry/Claude-Command-Suite](https://github.com/qdhenry/Claude-Command-Suite) | 1.2k ⭐ | 软件开发任务的结构化工作流，包含代码审查、功能开发等 |
| [iannuttall/claude-sessions](https://github.com/iannuttall/claude-sessions) | 1.2k ⭐ | 全面的开发会话追踪和文档化自定义 Slash 命令 |
| [alirezarezvani/claude-code-aso-skill](https://github.com/alirezarezvani/claude-code-aso-skill) | 300 ⭐ | Claude Code 的 AEO 自动化框架 —— 一键、新手友好的 GitHub 自动化 |

---

## Hooks 与自动化

用于自动化工作流、代码检查和质量保证的 Claude Code Hooks。

| 仓库 | 星标 | 简介 |
|---|---|---|
| [disler/claude-code-hooks-mastery](https://github.com/disler/claude-code-hooks-mastery) | ~5k ⭐ | Claude Code Hooks 掌握教程 —— 全面的 Hooks 学习资源 |
| [disler/claude-code-hooks-multi-agent-observability](https://github.com/disler/claude-code-hooks-multi-agent-observability) | ~3k ⭐ | 使用 Claude Code Hooks 实现多智能体可观测性 |
| [diet103/claude-code-infrastructure-showcase](https://github.com/diet103/claude-code-infrastructure-showcase) | 9.4k ⭐ | Claude Code 基础设施示例 —— 技能自动激活、Hooks 和 Agent |
| [karanb192/claude-code-hooks](https://github.com/karanb192/claude-code-hooks) | 339 ⭐ | 不断增长的实用 Claude Code Hooks 集合 —— 复制、粘贴、自定义 |
| [alexfazio/plankton](https://github.com/alexfazio/plankton) | 275 ⭐ | Claude Code 的写时代码质量执行系统 —— 每次文件编辑触发自动格式化 |
| [frankbria/ralph-claude-code](https://github.com/frankbria/ralph-claude-code) | 8.6k ⭐ | Claude Code 的自主 AI 开发循环，含智能退出检测 |
| [ruvnet/agentic-flow](https://github.com/ruvnet/agentic-flow) | 608 ⭐ | 在 Claude Code/Agent SDK 中轻松切换低成本替代 AI 模型 |
| [agent-sh/agnix](https://github.com/agent-sh/agnix) | 169 ⭐ | AI 编程助手的 Linter 和 LSP —— 验证 CLAUDE.md、AGENTS.md、SKILL.md、Hooks |
| [anthroos/claude-code-review-skill](https://github.com/anthroos/claude-code-review-skill) | 35 ⭐ | Claude Code CLI 免费 AI 代码审查技能 —— CodeRabbit 的替代品 |
| [wasintoh/toh-framework](https://github.com/wasintoh/toh-framework) | 78 ⭐ | "一次输入，全程搞定！" 面向独立开发者的 AI 编排驱动开发框架 |

---

## 模板、CLAUDE.md 与最佳实践

CLAUDE.md 模板、配置指南和 Claude Code 项目最佳实践。

| 仓库 | 星标 | 简介 |
|---|---|---|
| [shanraisshan/claude-code-best-practice](https://github.com/shanraisshan/claude-code-best-practice) | 39.3k ⭐ | Claude Code 最佳实践 —— 练习使 Claude 完美 |
| [davila7/claude-code-templates](https://github.com/davila7/claude-code-templates) | 24.5k ⭐ | 用于配置和监控 Claude Code 的 CLI 工具 |
| [Piebald-AI/claude-code-system-prompts](https://github.com/Piebald-AI/claude-code-system-prompts) | 8.6k ⭐ | Claude Code 系统提示词的所有部分、24 个内置工具描述、子 Agent 提示词 |
| [dwillitzer/claude-settings](https://github.com/dwillitzer/claude-settings) | 76 ⭐ | Claude Code 设置和权限配置参考 |
| [TheDecipherist/claude-code-mastery](https://github.com/TheDecipherist/claude-code-mastery) | 498 ⭐ | Claude Code 完整指南：CLAUDE.md、Hooks、技能、MCP 服务器和命令 |
| [zebbern/claude-code-guide](https://github.com/zebbern/claude-code-guide) | 3.9k ⭐ | Claude Code 指南 —— 设置、命令、工作流、Agent、技能和技巧，从入门到精通 |
| [claude-code-best/claude-code](https://github.com/claude-code-best/claude-code) | 15.5k ⭐ | 可运行、可构建、可调试版 Claude Code，TypeScript 类型全修复，企业级可靠性 |
| [xu-xiang/everything-claude-code-zh](https://github.com/xu-xiang/everything-claude-code-zh) | — | everything-claude-code 中文翻译项目 —— 完整的 Claude Code 配置集合 |
| [lintsinghua/claude-code-book](https://github.com/lintsinghua/claude-code-book) | — | 42 万字深度拆解 AI Agent Harness 架构 —— Claude Code 架构深度剖析，15 章 |
| [centminmod/my-claude-code-setup](https://github.com/centminmod/my-claude-code-setup) | ~2k ⭐ | 个人 Claude Code 配置方案参考 |

---

## 用量统计与监控

追踪 Claude Code Token 用量、成本和会话分析的工具。

| 仓库 | 星标 | 简介 |
|---|---|---|
| [ryoppippi/ccusage](https://github.com/ryoppippi/ccusage) | 12.8k ⭐ | 从本地 JSONL 文件分析 Claude Code / Codex CLI 用量的 CLI 工具 |
| [Maciek-roboblog/Claude-Code-Usage-Monitor](https://github.com/Maciek-roboblog/Claude-Code-Usage-Monitor) | 7.5k ⭐ | Claude Code 实时用量监控，含预测和警告 |
| [sirmalloc/ccstatusline](https://github.com/sirmalloc/ccstatusline) | 7.2k ⭐ | 精美、高度可定制的 Claude Code CLI 状态栏，支持 Powerline 主题 |
| [uppinote20/claude-dashboard](https://github.com/uppinote20/claude-dashboard) | 314 ⭐ | 全面的状态栏插件 —— 上下文用量、API 速率限制和成本追踪 |
| [phuryn/claude-usage](https://github.com/phuryn/claude-usage) | 879 ⭐ | 追踪 Claude Code Token 用量、成本和会话历史的本地看板 |
| [masorange/ClaudeUsageTracker](https://github.com/masorange/ClaudeUsageTracker) | 109 ⭐ | 从 macOS 菜单栏追踪 Claude Code API 用量，精确成本计算 |
| [soulduse/ai-token-monitor](https://github.com/soulduse/ai-token-monitor) | 132 ⭐ | 追踪 Claude Code Token 用量和成本的 macOS 菜单栏应用 |
| [tddworks/ClaudeBar](https://github.com/tddworks/ClaudeBar) | — | 监控 AI 编程助手配额的 macOS 菜单栏应用 |
| [junhoyeo/tokscale](https://github.com/junhoyeo/tokscale) | 1.8k ⭐ | 追踪 OpenCode、Claude Code、OpenClaw 等工具 Token 用量的 CLI 工具 |
| [steipete/CodexBar](https://github.com/steipete/CodexBar) | 10.6k ⭐ | 无需登录即可查看 OpenAI Codex 和 Claude Code 用量统计 |

---

## IDE 与编辑器集成

与 VS Code、Neovim、Obsidian 等编辑器和开发环境的集成。

| 仓库 | 星标 | 简介 |
|---|---|---|
| [YishenTu/claudian](https://github.com/YishenTu/claudian) | 7.6k ⭐ | Obsidian 插件 —— 将 Claude Code 作为 AI 协作者嵌入你的笔记库 |
| [mufeedvh/code2prompt](https://github.com/mufeedvh/code2prompt) | 7.3k ⭐ | CLI 工具 —— 将代码库转为单个 LLM 提示词，含源码树和提示词模板 |
| [HamedMP/CursorLens](https://github.com/HamedMP/CursorLens) | 393 ⭐ | Cursor.sh 的开源看板 —— 记录 AI 代码生成、追踪用量、控制 AI 模型 |
| [ykdojo/claude-code-tips](https://github.com/ykdojo/claude-code-tips) | 7.5k ⭐ | 45 个 Claude Code 使用技巧，从基础到进阶，含自定义状态栏 |

---

## 安全与权限管理

管理 Claude Code 安全性、权限和沙箱环境的工具。

| 仓库 | 星标 | 简介 |
|---|---|---|
| [HarmonicSecurity/claudit-sec](https://github.com/HarmonicSecurity/claudit-sec) | 107 ⭐ | Claude Desktop 和 Claude Code 的 macOS 安全审计工具 —— 一键 MCP 可见性 |
| [tintinweb/claude-code-container](https://github.com/tintinweb/claude-code-container) | 86 ⭐ | 在"危险跳过权限"模式下运行 Claude Code 的 Docker 容器 |
| [VishalJ99/claude-docker](https://github.com/VishalJ99/claude-docker) | 164 ⭐ | 以完整权限运行 Claude Code 并支持 Twilio 通知的 Docker 容器 |
| [kevinMEH/code-container](https://github.com/kevinMEH/code-container) | 213 ⭐ | 以完整权限安全运行 OpenCode、Codex、Claude Code |

---

## CI/CD 与 DevOps

与 CI/CD 流水线、GitHub Actions 和 DevOps 工作流的集成。

| 仓库 | 星标 | 简介 |
|---|---|---|
| [anthropics/claude-code-action](https://github.com/anthropics/claude-code-action) | 7k ⭐ | 将 Claude Code 集成到 CI/CD 的官方 GitHub Action |
| [openai/codex-plugin-cc](https://github.com/openai/codex-plugin-cc) | 13.8k ⭐ | 从 Claude Code 调用 Codex 审查代码或委托任务 |
| [EveryInc/compound-engineering-plugin](https://github.com/EveryInc/compound-engineering-plugin) | 14.1k ⭐ | Claude Code、Codex 等的官方 Compound Engineering 插件 |
| [glitternetwork/pinme](https://github.com/glitternetwork/pinme) | 3.2k ⭐ | 单条命令部署前端 —— 支持 Claude Code Skills |
| [fireact-dev/main](https://github.com/fireact-dev/main) | 547 ⭐ | 开源 SaaS 框架（React + Firebase + Stripe），内置 Claude Code AI 技能 |
| [wasp-lang/open-saas](https://github.com/wasp-lang/open-saas) | 14k ⭐ | 100% 免费的现代 JS SaaS 模板（React、NodeJS、Prisma）—— 完整功能，含 Claude Code 集成 |
| [JCodesMore/ai-website-cloner-template](https://github.com/JCodesMore/ai-website-cloner-template) | 10.9k ⭐ | 用 AI 编程 Agent 一条命令克隆任意网站 |
| [repowise-dev/repowise](https://github.com/repowise-dev/repowise) | 1.1k ⭐ | AI 辅助团队的代码库智能 —— 自动生成文档、git 分析、死代码检测 |
| [777genius/claude-notifications-go](https://github.com/777genius/claude-notifications-go) | 528 ⭐ | Claude Code 跨平台智能通知插件 —— 6 种类型、点击聚焦、一行安装 |

---

## 垂直领域技能

针对营销、SEO、法律、研究等特定领域的专业技能。

| 仓库 | 星标 | 简介 |
|---|---|---|
| [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills) | 20.6k ⭐ | Claude Code 的营销技能 —— CRO、文案撰写、SEO、分析和增长工程 |
| [AgriciDaniel/claude-seo](https://github.com/AgriciDaniel/claude-seo) | 4.7k ⭐ | Claude Code 通用 SEO 技能 —— 19 个子技能、12 个子 Agent、3 个扩展 |
| [AgriciDaniel/claude-ads](https://github.com/AgriciDaniel/claude-ads) | 2.3k ⭐ | Claude Code 付费广告审计和优化技能 —— 覆盖 Google、Meta 的 225+ 检查项 |
| [zubair-trabzada/ai-marketing-claude](https://github.com/zubair-trabzada/ai-marketing-claude) | 1.3k ⭐ | Claude Code 的 AI 营销套件 —— 15 个营销技能，含并行子 Agent |
| [zubair-trabzada/ai-legal-claude](https://github.com/zubair-trabzada/ai-legal-claude) | 724 ⭐ | Claude Code 的 AI 法律助手技能 —— 合同审查、风险分析、NDA 生成 |
| [blader/humanizer](https://github.com/blader/humanizer) | 13.5k ⭐ | 去除 AI 生成痕迹的 Claude Code 技能 |
| [deusyu/translate-book](https://github.com/deusyu/translate-book) | 617 ⭐ | 使用并行子 Agent 翻译整本书（PDF/DOCX/EPUB）的 Claude Code 技能 |
| [Affitor/affiliate-skills](https://github.com/Affitor/affiliate-skills) | 309 ⭐ | 50 个联盟营销 AI Agent 技能 —— 研究热门内容、撰写数据支撑的文章 |
| [CosmoBlk/email-marketing-bible](https://github.com/CosmoBlk/email-marketing-bible) | 132 ⭐ | Claude Code 邮件营销技能 —— 5.5 万字、908 个来源、19 个行业手册 |

---

## 教程与学习资源

Claude Code 的教程、操作指南、书籍和教育资源。

| 仓库 | 星标 | 简介 |
|---|---|---|
| [shareAI-lab/learn-claude-code](https://github.com/shareAI-lab/learn-claude-code) | 52.3k ⭐ | Bash 就是你需要的一切 —— 从零构建类 Claude Code 的 Agent Harness |
| [luongnv89/claude-howto](https://github.com/luongnv89/claude-howto) | 25.7k ⭐ | 可视化示例驱动的 Claude Code 指南 —— 从基础概念到高级 Agent，含可复制模板 |
| [ykdojo/claude-code-tips](https://github.com/ykdojo/claude-code-tips) | 7.5k ⭐ | 45 个 Claude Code 使用技巧，从基础到进阶，含自定义状态栏 |
| [wesammustafa/Claude-Code-Everything-You-Need-to-Know](https://github.com/wesammustafa/Claude-Code-Everything-You-Need-to-Know) | 1.6k ⭐ | 掌握 Claude Code 的终极一体化指南 —— 设置、提示工程、命令、Hooks |
| [zebbern/claude-code-guide](https://github.com/zebbern/claude-code-guide) | 3.9k ⭐ | Claude Code 指南 —— 从入门到精通 |
| [liyupi/ai-guide](https://github.com/liyupi/ai-guide) | 11.7k ⭐ | 程序员鱼皮的 AI 资源大全 + Vibe Coding 零基础教程（含 Claude Code） |
| [lintsinghua/claude-code-book](https://github.com/lintsinghua/claude-code-book) | — | 《御舆：解码 Agent Harness》—— 42 万字拆解 AI Agent 的 Harness 骨架与神经，15 章 |

---

## 提示词泄露与系统提示词

用于研究目的的逆向工程系统提示词和模型配置。

| 仓库 | 星标 | 简介 |
|---|---|---|
| [x1xhlol/system-prompts-and-models-of-ai-tools](https://github.com/x1xhlol/system-prompts-and-models-of-ai-tools) | 135k ⭐ | AI 工具完整系统提示词（含 Claude Code、Cursor、Devin AI、Kiro、Lovable、Manus） |
| [asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks) | 38.2k ⭐ | 提取自 ChatGPT（GPT-5.x、Codex）和 Claude（Opus 4.6、Sonnet 4.6）的系统提示词 |
| [Piebald-AI/claude-code-system-prompts](https://github.com/Piebald-AI/claude-code-system-prompts) | 8.6k ⭐ | Claude Code 系统提示词的所有部分 —— 24 个内置工具描述、子 Agent 提示词 |

---

## 精选合集与 Awesome 列表

汇聚 Claude Code 工具、插件和资源的精选列表。

| 仓库 | 星标 | 简介 |
|---|---|---|
| [hesreallyhim/awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code) | 38.3k ⭐ | 精选的技能、Hooks、Slash 命令、Agent 编排器、应用和插件列表 |
| [VoltAgent/awesome-claude-code-subagents](https://github.com/VoltAgent/awesome-claude-code-subagents) | 17.1k ⭐ | 100+ 个专用 Claude Code 子智能体 |
| [ComposioHQ/awesome-claude-plugins](https://github.com/ComposioHQ/awesome-claude-plugins) | 1.3k ⭐ | 精选插件列表 —— 用命令、Agent、Hooks 和 MCP 扩展 Claude Code |
| [ccplugins/awesome-claude-code-plugins](https://github.com/ccplugins/awesome-claude-code-plugins) | — | Awesome Claude Code 插件 —— Slash 命令、子 Agent、MCP 服务器和 Hooks |

---

## 贡献指南

欢迎贡献！请遵循以下规范：

1. 确认仓库与 Anthropic 的 **Claude Code 直接相关**
2. 确保仓库**活跃且在维护中**
3. 添加到最合适的分类中
4. 使用格式：`[owner/repo](URL) | 星标 | 描述`
5. 提交 Pull Request，简要说明收录理由

详细指南请参阅 [CONTRIBUTING.md](CONTRIBUTING.md)。

---

## 许可证

[![CC BY 4.0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by.svg)](https://creativecommons.org/licenses/by/4.0/)

本列表以 [知识共享署名 4.0 国际许可协议（CC BY 4.0）](https://creativecommons.org/licenses/by/4.0/deed.zh) 授权发布。

您可以自由地共享和改编本内容，但需注明出处。

---

*最后更新：2025-04 | 已收录 185+ 个仓库 | 数据来源于 GitHub 搜索，按星标数排序*
