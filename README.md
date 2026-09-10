<div align="center">

# Awesome Claude Code [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<p>
  <strong>A curated list of awesome projects, tools, frameworks, extensions, and resources for Claude Code by Anthropic.</strong>
</p>

<p>
  <a href="README.md">🇺🇸 English</a> | <a href="README_CN.md">🇨🇳 中文</a>
</p>

<p>
  <img src="https://img.shields.io/badge/repos-185%2B-blue" alt="repos">
  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen" alt="PRs welcome">
  <img src="https://img.shields.io/badge/license-CC%20BY%204.0-lightgrey" alt="license">
</p>

</div>

> **Claude Code** is Anthropic's agentic coding tool that lives in your terminal, understands your codebase, and helps you code faster by executing routine tasks autonomously.
> Official site: [claude.ai/code](https://claude.ai/code) | Docs: [docs.anthropic.com/en/docs/claude-code](https://docs.anthropic.com/en/docs/claude-code)

---

## Contents

- [Official](#official)
- [Frameworks & Configurations](#frameworks--configurations)
- [Agent Orchestration](#agent-orchestration)
- [Routing & Proxies](#routing--proxies)
- [UI, Web & Desktop Apps](#ui-web--desktop-apps)
- [Memory & Context Engineering](#memory--context-engineering)
- [MCP Servers & Integrations](#mcp-servers--integrations)
- [Skills & Subagents Collections](#skills--subagents-collections)
- [Slash Commands](#slash-commands)
- [Hooks & Automation](#hooks--automation)
- [Templates, CLAUDE.md & Best Practices](#templates-claudemd--best-practices)
- [Usage Tracking & Monitoring](#usage-tracking--monitoring)
- [IDE & Editor Integrations](#ide--editor-integrations)
- [Security & Permissions](#security--permissions)
- [CI/CD & DevOps](#cicd--devops)
- [Domain-Specific Skills](#domain-specific-skills)
- [Learning & Guides](#learning--guides)
- [Prompt Leaks & System Prompts](#prompt-leaks--system-prompts)
- [Awesome Lists & Collections](#awesome-lists--collections)

---

## Official

| Repository | Stars | Description |
|---|---|---|
| [anthropics/claude-code](https://github.com/anthropics/claude-code) | 113k ⭐ | The official Claude Code — agentic coding tool that lives in your terminal, understands your codebase, and helps you code faster |
| [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official) | 16.8k ⭐ | Official, Anthropic-managed directory of high quality Claude Code Plugins |
| [anthropics/claude-code-action](https://github.com/anthropics/claude-code-action) | 7k ⭐ | Official GitHub Action for Claude Code — integrate Claude Code into your CI/CD pipelines |

---

## Frameworks & Configurations

Complete systems, frameworks, and configuration setups that extend or enhance Claude Code's core capabilities.

| Repository | Stars | Description |
|---|---|---|
| [affaan-m/everything-claude-code](https://github.com/affaan-m/everything-claude-code) | 153k ⭐ | The agent harness performance optimization system — skills, instincts, memory, security, and research-first development |
| [garrytan/gstack](https://github.com/garrytan/gstack) | 70.8k ⭐ | Garry Tan's exact Claude Code setup — 23 opinionated tools serving as CEO, Designer, Eng Manager, Release Manager, Doc Engineer, and QA |
| [code-yeongyu/oh-my-openagent](https://github.com/code-yeongyu/oh-my-openagent) | 51k ⭐ | The best agent harness (previously oh-my-opencode) |
| [gsd-build/get-shit-done](https://github.com/gsd-build/get-shit-done) | 51.4k ⭐ | A lightweight and powerful meta-prompting, context engineering and spec-driven development system for Claude Code |
| [SuperClaude-Org/SuperClaude_Framework](https://github.com/SuperClaude-Org/SuperClaude_Framework) | 22.3k ⭐ | Configuration framework enhancing Claude Code with specialized commands, cognitive personas, and development methodologies |
| [coleam00/context-engineering-intro](https://github.com/coleam00/context-engineering-intro) | 13.1k ⭐ | Context engineering — the way to make AI coding assistants actually work, centered around Claude Code |
| [coleam00/Archon](https://github.com/coleam00/Archon) | 17.1k ⭐ | The first open-source harness builder for AI coding — make AI coding deterministic and repeatable |
| [aden-hive/hive](https://github.com/aden-hive/hive) | 10.2k ⭐ | Multi-Agent Harness for Production AI |
| [e10nMa2k/cc-mini](https://github.com/e10nMa2k/cc-mini) | 776 ⭐ | Ultra-light Harness scaffolding for AI agents — a mini version of Claude Code |
| [1rgs/nanocode](https://github.com/1rgs/nanocode) | 2.3k ⭐ | Minimal Claude Code alternative — single Python file, zero dependencies, ~250 lines |
| [ProjectBarks/gopher-code](https://github.com/ProjectBarks/gopher-code) | 514 ⭐ | Claude Code rewritten from scratch in Go — zero Node.js, zero Electron, one binary |
| [dfinke/PSClaudeCode](https://github.com/dfinke/PSClaudeCode) | 77 ⭐ | A PowerShell implementation of Claude Code: agent loop + tools + permissions |
| [can1357/oh-my-pi](https://github.com/can1357/oh-my-pi) | 2.9k ⭐ | AI Coding agent for the terminal — hash-anchored edits, optimized tool harness, LSP, Python, browser |
| [vibeeval/vibecosystem](https://github.com/vibeeval/vibecosystem) | 459 ⭐ | AI software team for Claude Code — 138 agents, 295 skills, 73 hooks, self-learning multi-agent swarm |
| [keli-wen/agentic-harness-patterns-skill](https://github.com/keli-wen/agentic-harness-patterns-skill) | 204 ⭐ | Agent skill for harness engineering — memory, permissions, context engineering, multi-agent coordination |

---

## Agent Orchestration

Tools for running, managing, and coordinating multiple Claude Code agents in parallel.

| Repository | Stars | Description |
|---|---|---|
| [wshobson/agents](https://github.com/wshobson/agents) | 33.5k ⭐ | Intelligent automation and multi-agent orchestration for Claude Code |
| [ruvnet/ruflo](https://github.com/ruvnet/ruflo) | 31.5k ⭐ | The leading agent orchestration platform for Claude — deploy intelligent multi-agent swarms |
| [Yeachan-Heo/oh-my-claudecode](https://github.com/Yeachan-Heo/oh-my-claudecode) | 28.1k ⭐ | Teams-first Multi-agent orchestration for Claude Code |
| [BloopAI/vibe-kanban](https://github.com/BloopAI/vibe-kanban) | 24.9k ⭐ | Get 10X more out of Claude Code, Codex or any coding agent — kanban-style orchestration |
| [Kilo-Org/kilocode](https://github.com/Kilo-Org/kilocode) | 18k ⭐ | All-in-one agentic engineering platform — #1 coding agent on OpenRouter, 1.5M+ users |
| [VoltAgent/awesome-claude-code-subagents](https://github.com/VoltAgent/awesome-claude-code-subagents) | 17.1k ⭐ | 100+ specialized Claude Code subagents covering a wide range of development use cases |
| [smtg-ai/claude-squad](https://github.com/smtg-ai/claude-squad) | 7k ⭐ | Manage multiple AI terminal agents like Claude Code, Codex, OpenCode, and Amp |
| [yohey-w/multi-agent-shogun](https://github.com/yohey-w/multi-agent-shogun) | 1.2k ⭐ | Samurai-inspired multi-agent system for Claude Code — orchestrate parallel AI tasks via tmux |
| [Dicklesworthstone/claude_code_agent_farm](https://github.com/Dicklesworthstone/claude_code_agent_farm) | — | Orchestration framework for running 20+ Claude Code agents in parallel: automated bug fixing |
| [opslane/opslane](https://github.com/opslane/opslane) | 772 ⭐ | Run multiple Claude Code sessions in parallel |
| [stravu/crystal](https://github.com/stravu/crystal) | 3k ⭐ | Run multiple Codex and Claude Code AI sessions in parallel git worktrees |
| [ceedaragents/cyrus](https://github.com/ceedaragents/cyrus) | 513 ⭐ | Claude Code background agent for Linear, Slack, GitHub, GitLab — deploy anywhere |
| [MiniCodeMonkey/chief](https://github.com/MiniCodeMonkey/chief) | 444 ⭐ | Build big projects with Claude — breaks work into tasks and runs Claude Code in a loop until done |
| [Hainrixz/the-architect](https://github.com/Hainrixz/the-architect) | 73 ⭐ | Claude Code meta-agent that designs complete software blueprints |
| [bfly123/claude_code_bridge](https://github.com/bfly123/claude_code_bridge) | 2.2k ⭐ | Real-time multi-AI collaboration: Claude, Codex & Gemini with persistent context, minimal token overhead |
| [santifer/career-ops](https://github.com/santifer/career-ops) | 31.8k ⭐ | AI-powered job search system built on Claude Code — 14 skill modes, Go dashboard, PDF generation |

---

## Routing & Proxies

Tools for routing Claude Code requests through different models or creating compatible API proxies.

| Repository | Stars | Description |
|---|---|---|
| [musistudio/claude-code-router](https://github.com/musistudio/claude-code-router) | 32.1k ⭐ | Use Claude Code as coding infrastructure — decide how to interact with the model while enjoying Anthropic updates |
| [farion1231/cc-switch](https://github.com/farion1231/cc-switch) | 43.5k ⭐ | Cross-platform desktop All-in-One assistant tool for Claude Code, Codex, OpenCode, openclaw & Gemini CLI |
| [router-for-me/CLIProxyAPI](https://github.com/router-for-me/CLIProxyAPI) | 25.4k ⭐ | Wrap Gemini CLI, Antigravity, ChatGPT Codex, Claude Code, Qwen Code as an OpenAI/Gemini/Claude-compatible API |
| [fuergaosi233/claude-code-proxy](https://github.com/fuergaosi233/claude-code-proxy) | 2.4k ⭐ | Claude Code to OpenAI API Proxy |
| [ericc-ch/copilot-api](https://github.com/ericc-ch/copilot-api) | 3.6k ⭐ | Turn GitHub Copilot into OpenAI/Anthropic API compatible server — usable with Claude Code |
| [Wei-Shaw/claude-relay-service](https://github.com/Wei-Shaw/claude-relay-service) | 11k ⭐ | Self-hosted Claude Code mirror / relay service — unified access for Claude, OpenAI, Gemini, Droid |
| [ding113/claude-code-hub](https://github.com/ding113/claude-code-hub) | 2.4k ⭐ | Modern Claude Code & Codex API proxy — intelligent load balancing, user management, usage stats |
| [glidea/claude-worker-proxy](https://github.com/glidea/claude-worker-proxy) | — | Cloudflare Worker proxy for Claude Code — easy deploy |
| [starbaser/ccproxy](https://github.com/starbaser/ccproxy) | 197 ⭐ | Build mods for Claude Code: hook any request, modify any response, use custom models |
| [UfoMiao/zcf](https://github.com/UfoMiao/zcf) | 5.9k ⭐ | Zero-Config Code Flow for Claude Code & Codex |
| [automazeio/vibeproxy](https://github.com/automazeio/vibeproxy) | 2.4k ⭐ | Native macOS menu bar app to use Claude Code & ChatGPT subscriptions with AI coding tools |
| [heyhuynhgiabuu/proxypal](https://github.com/heyhuynhgiabuu/proxypal) | 1.1k ⭐ | Desktop app to use AI subscriptions (Claude, ChatGPT, Gemini, GitHub Copilot) with coding tools |

---

## UI, Web & Desktop Apps

Graphical interfaces, web UIs, and desktop applications for Claude Code.

| Repository | Stars | Description |
|---|---|---|
| [siteboon/claudecodeui](https://github.com/siteboon/claudecodeui) | 9.7k ⭐ | Use Claude Code on mobile and web with CloudCLI — free open source WebUI/GUI for managing sessions remotely |
| [slopus/happy](https://github.com/slopus/happy) | 17.8k ⭐ | Mobile and web client for Codex and Claude Code — realtime voice, encryption, fully featured |
| [winfunc/opcode](https://github.com/winfunc/opcode) | 21.4k ⭐ | Powerful GUI app and toolkit for Claude Code — create custom agents, manage interactive sessions |
| [iOfficeAI/AionUi](https://github.com/iOfficeAI/AionUi) | 21.6k ⭐ | Free, local, open-source 24/7 Cowork app with OpenClaw for Gemini CLI |
| [jarrodwatts/claude-hud](https://github.com/jarrodwatts/claude-hud) | 18.7k ⭐ | Claude Code plugin showing context usage, active tools, running agents and what's happening in real-time |
| [superset-sh/superset](https://github.com/superset-sh/superset) | 9.5k ⭐ | Code editor for the AI agents era — run an army of Claude Code, Codex, etc. on your machine |
| [LKbaba/Claude-code-ChatInWindows](https://github.com/LKbaba/Claude-code-ChatInWindows) | 210 ⭐ | Full-featured GUI for Claude Code CLI in VS Code — Windows (no WSL) & macOS, third-party API, MCP plugins |
| [opactorai/Claudable](https://github.com/opactorai/Claudable) | 3.9k ⭐ | Open-source web builder that leverages local CLI agents like Claude Code, Codex |
| [Gitlawb/openclaude](https://github.com/Gitlawb/openclaude) | 21k ⭐ | Open-source coding-agent CLI for OpenAI, Gemini, DeepSeek, Ollama, Codex, GitHub Models |
| [InfatoshiI/OpenSquirrel](https://github.com/Infatoshi/OpenSquirrel) | 1.3k ⭐ | Native Rust/GPUI control plane for running Claude Code, Codex, and other AI coding agents |
| [Iamshankhadeep/ccseva](https://github.com/Iamshankhadeep/ccseva) | 789 ⭐ | Beautiful macOS menu bar app for tracking Claude Code usage in real-time |
| [matt1398/claude-devtools](https://github.com/matt1398/claude-devtools) | 3.1k ⭐ | Missing DevTools for Claude Code — inspect session logs, tool calls, token usage, subagents |
| [steipete/CodexBar](https://github.com/steipete/CodexBar) | 10.6k ⭐ | Show usage stats for OpenAI Codex and Claude Code without having to login |
| [nyatinte/ccexp](https://github.com/nyatinte/ccexp) | 264 ⭐ | Interactive terminal interface for discovering, previewing, and managing Claude Code configuration |
| [kaida-palooza/ccpoke](https://github.com/kaida-palooza/ccpoke) | 97 ⭐ | Bridge between AI coding agents and your phone — notifications, 2-way chat, permissions |

---

## Memory & Context Engineering

Tools for persistent memory, context management, and intelligent context injection.

| Repository | Stars | Description |
|---|---|---|
| [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem) | 50k+ ⭐ | Claude Code plugin that automatically captures sessions, compresses with AI, and injects relevant context into future sessions |
| [OthmanAdi/planning-with-files](https://github.com/OthmanAdi/planning-with-files) | 18.6k ⭐ | Claude Code skill implementing Manus-style persistent markdown planning |
| [rohitg00/agentmemory](https://github.com/rohitg00/agentmemory) | 939 ⭐ | #1 Persistent memory for AI coding agents based on real-world benchmarks |
| [HelloRuru/claude-memory-engine](https://github.com/HelloRuru/claude-memory-engine) | 114 ⭐ | Claude Code memory system built with hooks + markdown — zero dependencies |
| [rohitg00/pro-workflow](https://github.com/rohitg00/pro-workflow) | 1.9k ⭐ | Claude Code learns from your corrections — self-correcting memory that compounds over 50+ sessions |
| [tirth8205/code-review-graph](https://github.com/tirth8205/code-review-graph) | 9k ⭐ | Local knowledge graph for Claude Code — builds a persistent map of your codebase |
| [zilliztech/claude-context](https://github.com/zilliztech/claude-context) | 5.9k ⭐ | Code search MCP for Claude Code — make entire codebase the context for any coding agent |
| [mksglu/context-mode](https://github.com/mksglu/context-mode) | 7.1k ⭐ | Context window optimization for AI coding agents — sandboxes tool output, 98% reduction, 12 platforms |
| [JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman) | 22k ⭐ | Why use many token when few token do trick — Claude Code skill that cuts 65% of tokens |
| [iannuttall/claude-sessions](https://github.com/iannuttall/claude-sessions) | 1.2k ⭐ | Custom slash commands for comprehensive development session tracking and documentation |
| [peteromallet/dataclaw](https://github.com/peteromallet/dataclaw) | 2k ⭐ | Agent harness to publish history from Claude Code et al. as Hugging Face datasets |
| [Lum1104/Understand-Anything](https://github.com/Lum1104/Understand-Anything) | 8.2k ⭐ | Turn any code or knowledge base into an interactive knowledge graph |
| [Astro-Han/karpathy-llm-wiki](https://github.com/Astro-Han/karpathy-llm-wiki) | 271 ⭐ | Agent Skills-compatible LLM wiki for Claude Code, Cursor, and Codex |
| [suffro/syngraphe](https://github.com/suffro/syngraphe) | 2 ⭐ | Git-native repository context behind AGENTS.md, with structured Markdown shared by humans and coding agents and CLAUDE.md interoperability |

---

## MCP Servers & Integrations

Model Context Protocol (MCP) servers and integrations that extend Claude Code's tool capabilities.

| Repository | Stars | Description |
|---|---|---|
| [oraios/serena](https://github.com/oraios/serena) | 22.8k ⭐ | Powerful MCP toolkit — semantic retrieval and editing capabilities (the IDE for your agent) |
| [czlonkowski/n8n-mcp](https://github.com/czlonkowski/n8n-mcp) | 18k ⭐ | MCP for Claude Desktop / Claude Code / Windsurf / Cursor to build n8n workflows |
| [BeehiveInnovations/pal-mcp-server](https://github.com/BeehiveInnovations/pal-mcp-server) | 11.4k ⭐ | PAL MCP server — connect Claude Code to Gemini, OpenAI, OpenRouter, Azure, Grok, Ollama |
| [idosal/git-mcp](https://github.com/idosal/git-mcp) | 7.9k ⭐ | GitMCP — free, open-source remote MCP server for any GitHub project (end code hallucinations) |
| [grab/cursor-talk-to-figma-mcp](https://github.com/grab/cursor-talk-to-figma-mcp) | 6.6k ⭐ | TalkToFigma: MCP integration between AI Agent (Claude Code) and Figma |
| [jau123/MeiGen-AI-Design-MCP](https://github.com/jau123/MeiGen-AI-Design-MCP) | 575 ⭐ | Turn Claude Code into your local Lovart — local ComfyUI, 1,400+ pro assets |
| [Coolver/home-assistant-vibecode-agent](https://github.com/Coolver/home-assistant-vibecode-agent) | 520 ⭐ | Home Assistant MCP server — enable Claude Code, Cursor, VS Code to control smart home |
| [Sunwood-ai-labs/draw-io-skill](https://github.com/Sunwood-ai-labs/draw-io-skill) | 31 ⭐ | Native draw.io skill with export helpers, SVG linting for Codex and Claude Code |
| [teng-lin/notebooklm-py](https://github.com/teng-lin/notebooklm-py) | 10.3k ⭐ | Unofficial Python API and agentic skill for Google NotebookLM |
| [mendixlabs/mxcli](https://github.com/mendixlabs/mxcli) | 61 ⭐ | Mendix CLI for working with Mendix projects — enables use with 3rd party AI agents |

---

## Skills & Subagents Collections

Large collections of skills, specialized agents, and reusable AI behaviors.

| Repository | Stars | Description |
|---|---|---|
| [sickn33/antigravity-awesome-skills](https://github.com/sickn33/antigravity-awesome-skills) | 32.5k ⭐ | Installable GitHub library of 1,400+ agentic skills for Claude Code, Cursor, Codex CLI, Gemini CLI |
| [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills) | 53.3k ⭐ | Curated list of awesome Claude Skills, resources, and tools for customizing Claude AI workflows |
| [VoltAgent/awesome-agent-skills](https://github.com/VoltAgent/awesome-agent-skills) | 15.4k ⭐ | Curated collection of 1000+ agent skills from official dev teams and the community |
| [travisvn/awesome-claude-skills](https://github.com/travisvn/awesome-claude-skills) | 11.1k ⭐ | Curated list of Claude Skills, resources, and tools for customizing Claude AI workflows |
| [forrestchang/andrej-karpathy-skills](https://github.com/forrestchang/andrej-karpathy-skills) | 17.4k ⭐ | Single CLAUDE.md file to improve Claude Code behavior, derived from Andrej Karpathy's observations |
| [Jeffallan/claude-skills](https://github.com/Jeffallan/claude-skills) | 8.1k ⭐ | 66 specialized skills for full-stack developers — transform Claude Code into your expert pair programmer |
| [slavingia/skills](https://github.com/slavingia/skills) | 7.8k ⭐ | Claude Code skills based on The Minimalist Entrepreneur by Sahil Lavingia |
| [samber/cc-skills-golang](https://github.com/samber/cc-skills-golang) | 1.2k ⭐ | Collection of Golang agentic skills for Claude Code |
| [jeremylongshore/claude-code-plugins-plus-skills](https://github.com/jeremylongshore/claude-code-plugins-plus-skills) | 1.9k ⭐ | 340 plugins + 1367 agent skills for Claude Code with CCPI package manager |
| [Orchestra-Research/AI-Research-SKILLs](https://github.com/Orchestra-Research/AI-Research-SKILLs) | 6.7k ⭐ | Comprehensive open-source library of AI research and engineering skills |
| [runkids/skillshare](https://github.com/runkids/skillshare) | 1.4k ⭐ | Sync skills across all AI CLI tools with one command — supports Codex, Claude Code |
| [alirezarezvani/claude-skills](https://github.com/alirezarezvani/claude-skills) | — | 232+ Claude Code skills & agent plugins for Claude Code, Codex, Gemini CLI, Cursor |
| [alirezarezvani/claude-code-tresor](https://github.com/alirezarezvani/claude-code-tresor) | 674 ⭐ | World-class collection of Claude Code utilities: autonomous skills, expert agents, slash commands |
| [alirezarezvani/claude-code-skill-factory](https://github.com/alirezarezvani/claude-code-skill-factory) | — | Powerful open-source toolkit for building and deploying production-ready skills |
| [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) | ~5k ⭐ | Scientific agent skills for Claude Code |
| [refly-ai/refly](https://github.com/refly-ai/refly) | 7.2k ⭐ | First open-source agent skills builder — define skills by vibe workflow, run on Claude Code, Cursor |
| [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) | 63.8k ⭐ | AI SKILL providing design intelligence for building professional UI/UX across multiple platforms |
| [Donchitos/Claude-Code-Game-Studios](https://github.com/Donchitos/Claude-Code-Game-Studios) | 8.7k ⭐ | Turn Claude Code into a full game dev studio — 48 AI agents, 36 workflow skills |
| [aj-geddes/claude-code-bmad-skills](https://github.com/aj-geddes/claude-code-bmad-skills) | — | BMAD Method skills for Claude Code — auto-detection, memory integration, slash commands |
| [htdt/godogen](https://github.com/htdt/godogen) | 2.8k ⭐ | Claude Code skills that build complete Godot 4 projects from a game description |
| [vkehfdl1/slides-grab](https://github.com/vkehfdl1/slides-grab) | 468 ⭐ | Best harness + editor + linter for generating slides in Claude Code / Codex |
| [calesthio/OpenMontage](https://github.com/calesthio/OpenMontage) | 1.5k ⭐ | World's first open-source agentic video production system — 11 pipelines, 49 tools, 400+ agent skills |
| [sangrokjung/claude-forge](https://github.com/sangrokjung/claude-forge) | 648 ⭐ | Supercharge Claude Code with 11 AI agents, 36 commands & 15 skills |
| [nagisanzenin/claude-code-production-grade-plugin](https://github.com/nagisanzenin/claude-code-production-grade-plugin) | 136 ⭐ | Fully autonomous production-grade SaaS pipeline — 14 bundled skills, CEO/CTO commands |
| [Aedelon/claude-code-blueprint](https://github.com/Aedelon/claude-code-blueprint) | 71 ⭐ | Production-grade Claude Code configuration: skills, agents, hooks, rules, and permissions |
| [libukai/awesome-agent-skills](https://github.com/libukai/awesome-agent-skills) | ~5k ⭐ | Curated collection of awesome agent skills |

---

## Slash Commands

Collections and frameworks for Claude Code slash commands.

| Repository | Stars | Description |
|---|---|---|
| [wshobson/commands](https://github.com/wshobson/commands) | 2.3k ⭐ | Production-ready slash commands collection for Claude Code |
| [qdhenry/Claude-Command-Suite](https://github.com/qdhenry/Claude-Command-Suite) | 1.2k ⭐ | Structured workflows for software development tasks including code review, feature development |
| [iannuttall/claude-sessions](https://github.com/iannuttall/claude-sessions) | 1.2k ⭐ | Custom slash commands for comprehensive development session tracking and documentation |
| [alirezarezvani/claude-code-aso-skill](https://github.com/alirezarezvani/claude-code-aso-skill) | 300 ⭐ | AEO Automation Framework for Claude Code — one-click, beginner-friendly GitHub automation |

---

## Hooks & Automation

Claude Code hooks for automated workflows, linting, and quality enforcement.

| Repository | Stars | Description |
|---|---|---|
| [disler/claude-code-hooks-mastery](https://github.com/disler/claude-code-hooks-mastery) | ~5k ⭐ | Master Claude Code Hooks — comprehensive hooks learning resource |
| [disler/claude-code-hooks-multi-agent-observability](https://github.com/disler/claude-code-hooks-multi-agent-observability) | ~3k ⭐ | Multi-agent observability using Claude Code hooks |
| [diet103/claude-code-infrastructure-showcase](https://github.com/diet103/claude-code-infrastructure-showcase) | 9.4k ⭐ | Examples of Claude Code infrastructure with skill auto-activation, hooks, and agents |
| [karanb192/claude-code-hooks](https://github.com/karanb192/claude-code-hooks) | 339 ⭐ | Growing collection of useful Claude Code hooks — copy, paste, customize |
| [alexfazio/plankton](https://github.com/alexfazio/plankton) | 275 ⭐ | Write-time code quality enforcement system for Claude Code — every file edit triggers automated formatting |
| [frankbria/ralph-claude-code](https://github.com/frankbria/ralph-claude-code) | 8.6k ⭐ | Autonomous AI development loop for Claude Code with intelligent exit detection |
| [bejranonda/LLM-Autonomous-Agent-Plugin-for-Claude](https://github.com/bejranonda/LLM-Autonomous-Agent-Plugin-for-Claude) | 21 ⭐ | Autonomous self-learning Agent Plugin for Claude Code — automatic learning, real-time dashboard |
| [ruvnet/agentic-flow](https://github.com/ruvnet/agentic-flow) | 608 ⭐ | Switch between alternative low-cost AI models in Claude Code/Agent SDK |
| [Piebald-AI/splitrail](https://github.com/Piebald-AI/splitrail) | — | Fast, cross-platform real-time token usage tracker for Gemini CLI / Claude Code |
| [KenKaiii/minimal-claude](https://github.com/KenKaiii/minimal-claude) | 18 ⭐ | Intelligent Claude Code plugin that auto-configures linting, typechecking, and parallel agent-based builds |
| [carlrannaberg/cclint](https://github.com/carlrannaberg/cclint) | 16 ⭐ | Linter for Claude Code project files |
| [agent-sh/agnix](https://github.com/agent-sh/agnix) | 169 ⭐ | Missing linter and LSP for AI coding assistants — validate CLAUDE.md, AGENTS.md, SKILL.md, hooks |
| [anthroos/claude-code-review-skill](https://github.com/anthroos/claude-code-review-skill) | 35 ⭐ | Free AI-powered code review skill for Claude Code CLI — alternative to CodeRabbit |
| [wasintoh/toh-framework](https://github.com/wasintoh/toh-framework) | 78 ⭐ | "Type Once, Have it all!" AI-Orchestration Driven Development framework for solo developers |

---

## Templates, CLAUDE.md & Best Practices

CLAUDE.md templates, configuration guides, and best practices for setting up Claude Code projects.

| Repository | Stars | Description |
|---|---|---|
| [shanraisshan/claude-code-best-practice](https://github.com/shanraisshan/claude-code-best-practice) | 39.3k ⭐ | Best practices for Claude Code — practice made claude perfect |
| [davila7/claude-code-templates](https://github.com/davila7/claude-code-templates) | 24.5k ⭐ | CLI tool for configuring and monitoring Claude Code |
| [Piebald-AI/claude-code-system-prompts](https://github.com/Piebald-AI/claude-code-system-prompts) | 8.6k ⭐ | All parts of Claude Code's system prompt, 24 builtin tool descriptions, sub-agent prompts |
| [dwillitzer/claude-settings](https://github.com/dwillitzer/claude-settings) | 76 ⭐ | Claude Code settings and permissions configuration |
| [centminmod/my-claude-code-setup](https://github.com/centminmod/my-claude-code-setup) | ~2k ⭐ | Personal Claude Code setup and configuration reference |
| [TheDecipherist/claude-code-mastery](https://github.com/TheDecipherist/claude-code-mastery) | 498 ⭐ | Complete guide to Claude Code: CLAUDE.md, hooks, skills, MCP servers, and commands |
| [zebbern/claude-code-guide](https://github.com/zebbern/claude-code-guide) | 3.9k ⭐ | Claude Code Guide — setup, commands, workflows, agents, skills & tips from beginner to pro |
| [claude-code-best/claude-code](https://github.com/claude-code-best/claude-code) | 15.5k ⭐ | Runnable, buildable, debuggable Claude Code with full TypeScript type fixes and enterprise reliability |
| [xu-xiang/everything-claude-code-zh](https://github.com/xu-xiang/everything-claude-code-zh) | — | Chinese translation of everything-claude-code — complete Claude Code config collection |
| [lintsinghua/claude-code-book](https://github.com/lintsinghua/claude-code-book) | — | 420k-word deep dive into AI Agent Harness architecture — Claude Code internals, 15 chapters |

---

## Usage Tracking & Monitoring

Tools for monitoring Claude Code token usage, costs, and session analytics.

| Repository | Stars | Description |
|---|---|---|
| [ryoppippi/ccusage](https://github.com/ryoppippi/ccusage) | 12.8k ⭐ | CLI tool for analyzing Claude Code/Codex CLI usage from local JSONL files |
| [Maciek-roboblog/Claude-Code-Usage-Monitor](https://github.com/Maciek-roboblog/Claude-Code-Usage-Monitor) | 7.5k ⭐ | Real-time Claude Code usage monitor with predictions and warnings |
| [sirmalloc/ccstatusline](https://github.com/sirmalloc/ccstatusline) | 7.2k ⭐ | Beautiful, highly customizable statusline for Claude Code CLI with powerline support and themes |
| [uppinote20/claude-dashboard](https://github.com/uppinote20/claude-dashboard) | 314 ⭐ | Comprehensive status line plugin with context usage, API rate limits, and cost tracking |
| [phuryn/claude-usage](https://github.com/phuryn/claude-usage) | 879 ⭐ | Local dashboard for tracking Claude Code token usage, costs, and session history |
| [masorange/ClaudeUsageTracker](https://github.com/masorange/ClaudeUsageTracker) | 109 ⭐ | Track Claude Code API usage from your macOS menu bar with accurate cost calculations |
| [soulduse/ai-token-monitor](https://github.com/soulduse/ai-token-monitor) | 132 ⭐ | macOS menu bar app for tracking Claude Code token usage and costs |
| [tddworks/ClaudeBar](https://github.com/tddworks/ClaudeBar) | — | macOS menu bar app that monitors AI coding assistant usage quotas |
| [junhoyeo/tokscale](https://github.com/junhoyeo/tokscale) | 1.8k ⭐ | CLI tool for tracking token usage from OpenCode, Claude Code, OpenClaw, and more |
| [steipete/CodexBar](https://github.com/steipete/CodexBar) | 10.6k ⭐ | Show usage stats for OpenAI Codex and Claude Code without having to login |

---

## IDE & Editor Integrations

Integrations with editors like VS Code, Neovim, Obsidian, and other development environments.

| Repository | Stars | Description |
|---|---|---|
| [YishenTu/claudian](https://github.com/YishenTu/claudian) | 7.6k ⭐ | Obsidian plugin that embeds Claude Code as an AI collaborator in your vault |
| [mufeedvh/code2prompt](https://github.com/mufeedvh/code2prompt) | 7.3k ⭐ | CLI tool to convert your codebase into a single LLM prompt with source tree and templating |
| [HamedMP/CursorLens](https://github.com/HamedMP/CursorLens) | 393 ⭐ | Open-source dashboard for Cursor.sh IDE — log AI code generations, track usage, control AI models |
| [AgentEra/Agently](https://github.com/AgentEra/Agently) | 1.5k ⭐ | GenAI Application Development Framework — build GenAI application quick and easy |
| [ykdojo/claude-code-tips](https://github.com/ykdojo/claude-code-tips) | 7.5k ⭐ | 45 tips for getting the most out of Claude Code, from basics to advanced |

---

## Security & Permissions

Tools for managing Claude Code security, permissions, and running in sandboxed environments.

| Repository | Stars | Description |
|---|---|---|
| [HarmonicSecurity/claudit-sec](https://github.com/HarmonicSecurity/claudit-sec) | 107 ⭐ | Security audit tool for Claude Desktop and Claude Code on macOS — single-command MCP visibility |
| [tintinweb/claude-code-container](https://github.com/tintinweb/claude-code-container) | 86 ⭐ | Docker container for running Claude Code in "dangerously skip permissions" mode |
| [VishalJ99/claude-docker](https://github.com/VishalJ99/claude-docker) | 164 ⭐ | Docker container for running Claude Code with full permissions and Twilio notifications |
| [kevinMEH/code-container](https://github.com/kevinMEH/code-container) | 213 ⭐ | Safely run OpenCode, Codex, Claude Code with full permissions |
| [dwillitzer/claude-settings](https://github.com/dwillitzer/claude-settings) | 76 ⭐ | Claude Code settings and permissions configuration reference |

---

## CI/CD & DevOps

Integrations with CI/CD pipelines, GitHub Actions, and DevOps workflows.

| Repository | Stars | Description |
|---|---|---|
| [anthropics/claude-code-action](https://github.com/anthropics/claude-code-action) | 7k ⭐ | Official GitHub Action for integrating Claude Code into CI/CD |
| [openai/codex-plugin-cc](https://github.com/openai/codex-plugin-cc) | 13.8k ⭐ | Use Codex from Claude Code to review code or delegate tasks |
| [EveryInc/compound-engineering-plugin](https://github.com/EveryInc/compound-engineering-plugin) | 14.1k ⭐ | Official Compound Engineering plugin for Claude Code, Codex, and more |
| [glitternetwork/pinme](https://github.com/glitternetwork/pinme) | 3.2k ⭐ | Deploy your frontend in a single command — Claude Code Skills supported |
| [fireact-dev/main](https://github.com/fireact-dev/main) | 547 ⭐ | Open-source SaaS framework (React + Firebase + Stripe) with built-in Claude Code AI skills |
| [wasp-lang/open-saas](https://github.com/wasp-lang/open-saas) | 14k ⭐ | 100% free modern JS SaaS boilerplate (React, NodeJS, Prisma) — full-featured with Claude Code integration |
| [JCodesMore/ai-website-cloner-template](https://github.com/JCodesMore/ai-website-cloner-template) | 10.9k ⭐ | Clone any website with one command using AI coding agents |
| [repowise-dev/repowise](https://github.com/repowise-dev/repowise) | 1.1k ⭐ | Codebase intelligence for AI-assisted teams — auto-generated docs, git analytics, dead code |
| [777genius/claude-notifications-go](https://github.com/777genius/claude-notifications-go) | 528 ⭐ | Cross-platform smart notifications plugin for Claude Code — 6 types, click-to-focus, 1-line install |
| [komunite/tezgah](https://github.com/komunite/tezgah) | 84 ⭐ | Production-ready SaaS with Claude Code — skill set for solopreneurs |
| [whawkinsiv/solo-founder-superpowers](https://github.com/whawkinsiv/solo-founder-superpowers) | 158 ⭐ | Skillset for solo, bootstrapped, non-technical founders building SaaS with Claude Code |

---

## Domain-Specific Skills

Specialized skills for specific domains like marketing, SEO, legal, research, and more.

| Repository | Stars | Description |
|---|---|---|
| [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills) | 20.6k ⭐ | Marketing skills for Claude Code — CRO, copywriting, SEO, analytics, growth engineering |
| [AgriciDaniel/claude-seo](https://github.com/AgriciDaniel/claude-seo) | 4.7k ⭐ | Universal SEO skill for Claude Code — 19 sub-skills, 12 subagents, 3 extensions |
| [AgriciDaniel/claude-ads](https://github.com/AgriciDaniel/claude-ads) | 2.3k ⭐ | Paid advertising audit & optimization skill for Claude Code — 225+ checks across Google, Meta |
| [zubair-trabzada/ai-marketing-claude](https://github.com/zubair-trabzada/ai-marketing-claude) | 1.3k ⭐ | AI Marketing Suite for Claude Code — 15 marketing skills with parallel subagents |
| [zubair-trabzada/ai-legal-claude](https://github.com/zubair-trabzada/ai-legal-claude) | 724 ⭐ | AI Legal Assistant skill for Claude Code — contract review, risk analysis, NDA generation |
| [blader/humanizer](https://github.com/blader/humanizer) | 13.5k ⭐ | Claude Code skill that removes signs of AI-generated writing from text |
| [deusyu/translate-book](https://github.com/deusyu/translate-book) | 617 ⭐ | Claude Code skill that translates entire books (PDF/DOCX/EPUB) using parallel subagents |
| [Affitor/affiliate-skills](https://github.com/Affitor/affiliate-skills) | 309 ⭐ | 50 AI agent skills for affiliate marketing — research trending content, write data-backed posts |
| [CosmoBlk/email-marketing-bible](https://github.com/CosmoBlk/email-marketing-bible) | 132 ⭐ | Email marketing skill for Claude Code — 55K words, 908 sources, 19 industry playbooks |

---

## Learning & Guides

Tutorials, how-to guides, books, and educational resources for Claude Code.

| Repository | Stars | Description |
|---|---|---|
| [shareAI-lab/learn-claude-code](https://github.com/shareAI-lab/learn-claude-code) | 52.3k ⭐ | Bash is all you need — build a nano claude code-like agent harness from 0 to 1 |
| [luongnv89/claude-howto](https://github.com/luongnv89/claude-howto) | 25.7k ⭐ | Visual, example-driven guide to Claude Code — from basic concepts to advanced agents with copy-paste templates |
| [ykdojo/claude-code-tips](https://github.com/ykdojo/claude-code-tips) | 7.5k ⭐ | 45 tips for getting the most out of Claude Code, from basics to advanced, with custom status bar |
| [wesammustafa/Claude-Code-Everything-You-Need-to-Know](https://github.com/wesammustafa/Claude-Code-Everything-You-Need-to-Know) | 1.6k ⭐ | Ultimate all-in-one guide to mastering Claude Code — setup, prompt engineering, commands, hooks |
| [zebbern/claude-code-guide](https://github.com/zebbern/claude-code-guide) | 3.9k ⭐ | Claude Code Guide — from beginner to pro |
| [liyupi/ai-guide](https://github.com/liyupi/ai-guide) | 11.7k ⭐ | Programmer's AI resource guide + Vibe Coding tutorial (includes Claude Code) |
| [lintsinghua/claude-code-book](https://github.com/lintsinghua/claude-code-book) | — | 420k-word deep dive into AI Agent Harness architecture — Claude Code internals, 15 chapters |
| [davila7/claude-code-templates](https://github.com/davila7/claude-code-templates) | 24.5k ⭐ | CLI tool for configuring and monitoring Claude Code |

---

## Prompt Leaks & System Prompts

Reverse-engineered system prompts and model configurations for research purposes.

| Repository | Stars | Description |
|---|---|---|
| [x1xhlol/system-prompts-and-models-of-ai-tools](https://github.com/x1xhlol/system-prompts-and-models-of-ai-tools) | 135k ⭐ | Full system prompts of AI tools including Claude Code, Cursor, Devin AI, Kiro, Lovable, Manus |
| [asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks) | 38.2k ⭐ | Extracted system prompts from ChatGPT (GPT-5.x, Codex), Claude (Opus 4.6, Sonnet 4.6) |
| [Piebald-AI/claude-code-system-prompts](https://github.com/Piebald-AI/claude-code-system-prompts) | 8.6k ⭐ | All parts of Claude Code's system prompt — 24 builtin tool descriptions, sub-agent prompts |

---

## Awesome Lists & Collections

Curated lists aggregating Claude Code tools, plugins, and resources.

| Repository | Stars | Description |
|---|---|---|
| [hesreallyhim/awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code) | 38.3k ⭐ | Curated list of skills, hooks, slash-commands, agent orchestrators, apps, and plugins for Claude Code |
| [VoltAgent/awesome-claude-code-subagents](https://github.com/VoltAgent/awesome-claude-code-subagents) | 17.1k ⭐ | 100+ specialized Claude Code subagents for development use cases |
| [ComposioHQ/awesome-claude-plugins](https://github.com/ComposioHQ/awesome-claude-plugins) | 1.3k ⭐ | Curated list of plugins extending Claude Code with commands, agents, hooks, and MCP |
| [ccplugins/awesome-claude-code-plugins](https://github.com/ccplugins/awesome-claude-code-plugins) | — | Awesome Claude Code plugins — slash commands, subagents, MCP servers, and hooks |

---

## Contributing

Contributions welcome! Please:

1. Verify the repository is **directly related to Claude Code** by Anthropic
2. Ensure the repository is **active and maintained**
3. Add to the most appropriate category
4. Use the format: `[owner/repo](URL) | Stars | Description`
5. Submit a Pull Request with a brief reason for inclusion

See [CONTRIBUTING.md](CONTRIBUTING.md) for detailed guidelines.

---

## License

[![CC BY 4.0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by.svg)](https://creativecommons.org/licenses/by/4.0/)

This list is licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

You are free to share and adapt this material for any purpose, as long as you give appropriate credit.

---

*Last updated: 2025-04 | 185+ repositories indexed | Data sourced from GitHub search sorted by stars*
