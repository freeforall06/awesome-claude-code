<div align="center">

# Awesome Claude Code

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Curated list of tools, skills, plugins, and MCP servers for [Claude Code](https://github.com/anthropics/claude-code) — Anthropic's agentic coding tool that lives in your terminal.

Only repositories with **1,000+ stars** are listed. PRs are always welcome!

</div>

## Contents

- [Official](#official)
- [Configuration & Rules](#configuration--rules)
- [Skills & Plugins](#skills--plugins)
- [Agent Orchestration](#agent-orchestration)
- [GUI & IDE](#gui--ide)
- [Monitoring & Analytics](#monitoring--analytics)
- [Learning & Reference](#learning--reference)
- [MCP Ecosystem](#mcp-ecosystem)
  - [Core & Frameworks](#core--frameworks)
  - [Servers](#servers)

---

## Official

| Repository | Stars | Description |
|:-----------|:-----:|:------------|
| [anthropics/claude-code](https://github.com/anthropics/claude-code) | ![](https://img.shields.io/github/stars/anthropics/claude-code?style=flat-square&logo=github) | Agentic coding CLI for terminals and IDEs with codebase understanding and git workflows |
| [anthropics/skills](https://github.com/anthropics/skills) | ![](https://img.shields.io/github/stars/anthropics/skills?style=flat-square&logo=github) | Dynamic instruction folders that teach Claude specialized tasks like doc creation and data analysis |
| [anthropics/claude-code-action](https://github.com/anthropics/claude-code-action) | ![](https://img.shields.io/github/stars/anthropics/claude-code-action?style=flat-square&logo=github) | GitHub Action for PR reviews, code changes, and issue triage via @claude mentions |
| [anthropics/claude-code-security-review](https://github.com/anthropics/claude-code-security-review) | ![](https://img.shields.io/github/stars/anthropics/claude-code-security-review?style=flat-square&logo=github) | GitHub Action that detects security vulnerabilities in PR diffs using semantic analysis |
| [anthropics/claude-agent-sdk-python](https://github.com/anthropics/claude-agent-sdk-python) | ![](https://img.shields.io/github/stars/anthropics/claude-agent-sdk-python?style=flat-square&logo=github) | Python SDK to build autonomous agents with file editing, command execution, and tool use |
| [anthropics/claude-agent-sdk-typescript](https://github.com/anthropics/claude-agent-sdk-typescript) | ![](https://img.shields.io/github/stars/anthropics/claude-agent-sdk-typescript?style=flat-square&logo=github) | TypeScript SDK to build autonomous agents with Claude Code's agentic capabilities |
| [anthropics/anthropic-sdk-python](https://github.com/anthropics/anthropic-sdk-python) | ![](https://img.shields.io/github/stars/anthropics/anthropic-sdk-python?style=flat-square&logo=github) | Typed Python client for the Claude REST API with sync and async support |
| [anthropics/claude-cookbooks](https://github.com/anthropics/claude-cookbooks) | ![](https://img.shields.io/github/stars/anthropics/claude-cookbooks?style=flat-square&logo=github) | Copy-paste notebooks for RAG, tool use, vision, classification, and Claude integrations |

## Configuration & Rules

| Repository | Stars | Description |
|:-----------|:-----:|:------------|
| [affaan-m/everything-claude-code](https://github.com/affaan-m/everything-claude-code) | ![](https://img.shields.io/github/stars/affaan-m/everything-claude-code?style=flat-square&logo=github) | Battle-tested Claude Code configs: agents, skills, hooks, commands, rules, and MCPs |
| [hesreallyhim/awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code) | ![](https://img.shields.io/github/stars/hesreallyhim/awesome-claude-code?style=flat-square&logo=github) | Curated list of skills, hooks, slash-commands, tools, and plugins for Claude Code |
| [SuperClaude-Org/SuperClaude_Framework](https://github.com/SuperClaude-Org/SuperClaude_Framework) | ![](https://img.shields.io/github/stars/SuperClaude-Org/SuperClaude_Framework?style=flat-square&logo=github) | 30 slash commands, 16 agents, and 7 behavioral modes for Claude Code development |
| [davila7/claude-code-templates](https://github.com/davila7/claude-code-templates) | ![](https://img.shields.io/github/stars/davila7/claude-code-templates?style=flat-square&logo=github) | CLI + web catalog to browse and install 100+ agents, commands, hooks, and MCPs |
| [Yeachan-Heo/oh-my-claudecode](https://github.com/Yeachan-Heo/oh-my-claudecode) | ![](https://img.shields.io/github/stars/Yeachan-Heo/oh-my-claudecode?style=flat-square&logo=github) | Multi-agent orchestration with 5 execution modes and automatic parallelization |
| [steipete/agent-rules](https://github.com/steipete/agent-rules) | ![](https://img.shields.io/github/stars/steipete/agent-rules?style=flat-square&logo=github) | Shared guardrail rules and helper scripts for Claude Code and Cursor agents |
| [diet103/claude-code-infrastructure-showcase](https://github.com/diet103/claude-code-infrastructure-showcase) | ![](https://img.shields.io/github/stars/diet103/claude-code-infrastructure-showcase?style=flat-square&logo=github) | Reference library for auto-activating skills, modular skill patterns, and hook systems |
| [ChrisWiles/claude-code-showcase](https://github.com/ChrisWiles/claude-code-showcase) | ![](https://img.shields.io/github/stars/ChrisWiles/claude-code-showcase?style=flat-square&logo=github) | Full project config example with skill auto-activation, CI workflows, and JIRA integration |

## Skills & Plugins

| Repository | Stars | Description |
|:-----------|:-----:|:------------|
| [vercel-labs/agent-skills](https://github.com/vercel-labs/agent-skills) | ![](https://img.shields.io/github/stars/vercel-labs/agent-skills?style=flat-square&logo=github) | React, Next.js, and web design best-practice rules for AI coding agents |
| [vercel-labs/skills](https://github.com/vercel-labs/skills) | ![](https://img.shields.io/github/stars/vercel-labs/skills?style=flat-square&logo=github) | CLI tool to install agent skills across 35+ coding agents via `npx skills add` |
| [vercel-labs/agent-browser](https://github.com/vercel-labs/agent-browser) | ![](https://img.shields.io/github/stars/vercel-labs/agent-browser?style=flat-square&logo=github) | Headless browser automation CLI for AI agents with Rust backend and Playwright |
| [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills) | ![](https://img.shields.io/github/stars/ComposioHQ/awesome-claude-skills?style=flat-square&logo=github) | Curated skills list + Composio plugin connecting Claude to 500+ external apps |
| [VoltAgent/awesome-agent-skills](https://github.com/VoltAgent/awesome-agent-skills) | ![](https://img.shields.io/github/stars/VoltAgent/awesome-agent-skills?style=flat-square&logo=github) | 200+ agent skills from official dev teams, compatible with 10+ coding agents |
| [travisvn/awesome-claude-skills](https://github.com/travisvn/awesome-claude-skills) | ![](https://img.shields.io/github/stars/travisvn/awesome-claude-skills?style=flat-square&logo=github) | Curated Claude Skills list with progressive-disclosure architecture explained |
| [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) | ![](https://img.shields.io/github/stars/nextlevelbuilder/ui-ux-pro-max-skill?style=flat-square&logo=github) | Design intelligence skill with 100 reasoning rules and 67 UI style presets |
| [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem) | ![](https://img.shields.io/github/stars/thedotmack/claude-mem?style=flat-square&logo=github) | Plugin that captures session history, compresses it with AI, and injects context |
| [OthmanAdi/planning-with-files](https://github.com/OthmanAdi/planning-with-files) | ![](https://img.shields.io/github/stars/OthmanAdi/planning-with-files?style=flat-square&logo=github) | Manus-style persistent markdown planning skill with session recovery |
| [EveryInc/compound-engineering-plugin](https://github.com/EveryInc/compound-engineering-plugin) | ![](https://img.shields.io/github/stars/EveryInc/compound-engineering-plugin?style=flat-square&logo=github) | Plan-work-review-compound loop plugin with worktrees and multi-agent review |
| [obra/superpowers](https://github.com/obra/superpowers) | ![](https://img.shields.io/github/stars/obra/superpowers?style=flat-square&logo=github) | Full dev workflow skill: spec elicitation, TDD planning, and subagent execution |
| [agentskills/agentskills](https://github.com/agentskills/agentskills) | ![](https://img.shields.io/github/stars/agentskills/agentskills?style=flat-square&logo=github) | Open spec and SDK for the Agent Skills format maintained by Anthropic |
| [supabase/agent-skills](https://github.com/supabase/agent-skills) | ![](https://img.shields.io/github/stars/supabase/agent-skills?style=flat-square&logo=github) | Postgres and Supabase best-practice skills for schema, RLS, and query tuning |
| [hesreallyhim/a-list-of-claude-code-agents](https://github.com/hesreallyhim/a-list-of-claude-code-agents) | ![](https://img.shields.io/github/stars/hesreallyhim/a-list-of-claude-code-agents?style=flat-square&logo=github) | Community-submitted collection of Claude Code sub-agent prompts and frameworks |

## Agent Orchestration

| Repository | Stars | Description |
|:-----------|:-----:|:------------|
| [smtg-ai/claude-squad](https://github.com/smtg-ai/claude-squad) | ![](https://img.shields.io/github/stars/smtg-ai/claude-squad?style=flat-square&logo=github) | Terminal multiplexer to run and manage multiple AI coding agents in parallel |
| [ruvnet/claude-flow](https://github.com/ruvnet/claude-flow) | ![](https://img.shields.io/github/stars/ruvnet/claude-flow?style=flat-square&logo=github) | Multi-agent orchestration framework with swarm coordination and self-learning |
| [wshobson/agents](https://github.com/wshobson/agents) | ![](https://img.shields.io/github/stars/wshobson/agents?style=flat-square&logo=github) | 73 plugins with 112 specialized agents, 146 skills, and 79 dev tools for Claude Code |
| [VoltAgent/awesome-claude-code-subagents](https://github.com/VoltAgent/awesome-claude-code-subagents) | ![](https://img.shields.io/github/stars/VoltAgent/awesome-claude-code-subagents?style=flat-square&logo=github) | Curated collection of 126+ ready-to-install specialized Claude Code subagents |
| [vercel-labs/coding-agent-template](https://github.com/vercel-labs/coding-agent-template) | ![](https://img.shields.io/github/stars/vercel-labs/coding-agent-template?style=flat-square&logo=github) | Deploy multi-agent coding tasks in Vercel Sandbox with GitHub integration |
| [coder/agentapi](https://github.com/coder/agentapi) | ![](https://img.shields.io/github/stars/coder/agentapi?style=flat-square&logo=github) | HTTP API to control Claude Code, Aider, Codex, Goose, and other coding agents |
| [frankbria/ralph-claude-code](https://github.com/frankbria/ralph-claude-code) | ![](https://img.shields.io/github/stars/frankbria/ralph-claude-code?style=flat-square&logo=github) | Autonomous dev loop with intelligent exit detection, rate limiting, and circuit breaker |
| [UfoMiao/zcf](https://github.com/UfoMiao/zcf) | ![](https://img.shields.io/github/stars/UfoMiao/zcf?style=flat-square&logo=github) | Zero-config CLI to set up Claude Code & Codex with providers, MCPs, and workflows |

## GUI & IDE

| Repository | Stars | Description |
|:-----------|:-----:|:------------|
| [21st-dev/1code](https://github.com/21st-dev/1code) | ![](https://img.shields.io/github/stars/21st-dev/1code?style=flat-square&logo=github) | Desktop UI for Claude Code with git worktree isolation and parallel agent execution |
| [siteboon/claudecodeui](https://github.com/siteboon/claudecodeui) | ![](https://img.shields.io/github/stars/siteboon/claudecodeui?style=flat-square&logo=github) | Web and mobile UI to manage Claude Code, Cursor CLI, and Codex sessions remotely |
| [coder/claudecode.nvim](https://github.com/coder/claudecode.nvim) | ![](https://img.shields.io/github/stars/coder/claudecode.nvim?style=flat-square&logo=github) | Neovim plugin implementing Claude Code's WebSocket MCP protocol in pure Lua |
| [musistudio/claude-code-router](https://github.com/musistudio/claude-code-router) | ![](https://img.shields.io/github/stars/musistudio/claude-code-router?style=flat-square&logo=github) | Route Claude Code requests to different LLM providers with dynamic model switching |
| [BloopAI/vibe-kanban](https://github.com/BloopAI/vibe-kanban) | ![](https://img.shields.io/github/stars/BloopAI/vibe-kanban?style=flat-square&logo=github) | Kanban board to orchestrate and track multiple coding agents in parallel |
| [farion1231/cc-switch](https://github.com/farion1231/cc-switch) | ![](https://img.shields.io/github/stars/farion1231/cc-switch?style=flat-square&logo=github) | Desktop app to manage API providers, MCPs, and configs for Claude Code and Codex |
| [slopus/happy](https://github.com/slopus/happy) | ![](https://img.shields.io/github/stars/slopus/happy?style=flat-square&logo=github) | Mobile and web client for Claude Code and Codex with E2E encryption and push alerts |

## Monitoring & Analytics

| Repository | Stars | Description |
|:-----------|:-----:|:------------|
| [Maciek-roboblog/Claude-Code-Usage-Monitor](https://github.com/Maciek-roboblog/Claude-Code-Usage-Monitor) | ![](https://img.shields.io/github/stars/Maciek-roboblog/Claude-Code-Usage-Monitor?style=flat-square&logo=github) | Real-time terminal dashboard for token usage tracking with ML-based predictions |
| [chiphuyen/sniffly](https://github.com/chiphuyen/sniffly) | ![](https://img.shields.io/github/stars/chiphuyen/sniffly?style=flat-square&logo=github) | Analytics dashboard for Claude Code logs with usage stats and error breakdowns |
| [ryoppippi/ccusage](https://github.com/ryoppippi/ccusage) | ![](https://img.shields.io/github/stars/ryoppippi/ccusage?style=flat-square&logo=github) | Fast CLI to analyze Claude Code/Codex token usage and costs from local JSONL logs |
| [steipete/CodexBar](https://github.com/steipete/CodexBar) | ![](https://img.shields.io/github/stars/steipete/CodexBar?style=flat-square&logo=github) | macOS menu bar app showing usage limits for Codex, Claude, Cursor, and 10+ providers |

## Learning & Reference

| Repository | Stars | Description |
|:-----------|:-----:|:------------|
| [Piebald-AI/claude-code-system-prompts](https://github.com/Piebald-AI/claude-code-system-prompts) | ![](https://img.shields.io/github/stars/Piebald-AI/claude-code-system-prompts?style=flat-square&logo=github) | Extracted and versioned system prompts for every Claude Code release |
| [shareAI-lab/learn-claude-code](https://github.com/shareAI-lab/learn-claude-code) | ![](https://img.shields.io/github/stars/shareAI-lab/learn-claude-code?style=flat-square&logo=github) | Build-from-scratch tutorial teaching AI agent patterns in 50–550 lines of Python |

---

## MCP Ecosystem

MCP servers extend Claude Code with external tools and data. Configure via `claude mcp add` or `~/.claude/settings.json`.

### Core & Frameworks

| Repository | Stars | Description |
|:-----------|:-----:|:------------|
| [modelcontextprotocol/modelcontextprotocol](https://github.com/modelcontextprotocol/modelcontextprotocol) | ![](https://img.shields.io/github/stars/modelcontextprotocol/modelcontextprotocol?style=flat-square&logo=github) | Official MCP specification, protocol schema, and documentation |
| [modelcontextprotocol/python-sdk](https://github.com/modelcontextprotocol/python-sdk) | ![](https://img.shields.io/github/stars/modelcontextprotocol/python-sdk?style=flat-square&logo=github) | Official Python SDK for building MCP servers and clients |
| [modelcontextprotocol/typescript-sdk](https://github.com/modelcontextprotocol/typescript-sdk) | ![](https://img.shields.io/github/stars/modelcontextprotocol/typescript-sdk?style=flat-square&logo=github) | Official TypeScript SDK for building MCP servers and clients |
| [modelcontextprotocol/inspector](https://github.com/modelcontextprotocol/inspector) | ![](https://img.shields.io/github/stars/modelcontextprotocol/inspector?style=flat-square&logo=github) | Visual developer tool for testing and debugging MCP servers in the browser |
| [modelcontextprotocol/registry](https://github.com/modelcontextprotocol/registry) | ![](https://img.shields.io/github/stars/modelcontextprotocol/registry?style=flat-square&logo=github) | Community-driven app-store-style registry for discovering MCP servers |
| [jlowin/fastmcp](https://github.com/jlowin/fastmcp) | ![](https://img.shields.io/github/stars/jlowin/fastmcp?style=flat-square&logo=github) | Pythonic framework for building MCP servers with tools, resources, and transforms |
| [mcp-use/mcp-use](https://github.com/mcp-use/mcp-use) | ![](https://img.shields.io/github/stars/mcp-use/mcp-use?style=flat-square&logo=github) | Connect any LLM to MCP servers with agents, clients, and inspector in 6 lines |
| [IBM/mcp-context-forge](https://github.com/IBM/mcp-context-forge) | ![](https://img.shields.io/github/stars/IBM/mcp-context-forge?style=flat-square&logo=github) | MCP gateway that federates REST, MCP, and A2A services with auth and admin UI |
| [metorial/metorial](https://github.com/metorial/metorial) | ![](https://img.shields.io/github/stars/metorial/metorial?style=flat-square&logo=github) | Integration platform connecting AI models to 600+ APIs via MCP with one-liner SDKs |
| [metatool-ai/metamcp](https://github.com/metatool-ai/metamcp) | ![](https://img.shields.io/github/stars/metatool-ai/metamcp?style=flat-square&logo=github) | MCP proxy aggregating multiple servers into one unified endpoint with middleware |

### Servers

| Repository | Stars | Description |
|:-----------|:-----:|:------------|
| [github/github-mcp-server](https://github.com/github/github-mcp-server) | ![](https://img.shields.io/github/stars/github/github-mcp-server?style=flat-square&logo=github) | Official GitHub MCP server for managing repos, issues, PRs, and Actions via AI |
| [upstash/context7](https://github.com/upstash/context7) | ![](https://img.shields.io/github/stars/upstash/context7?style=flat-square&logo=github) | Injects up-to-date, version-specific library docs and code examples into LLM prompts |
| [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp) | ![](https://img.shields.io/github/stars/microsoft/playwright-mcp?style=flat-square&logo=github) | Browser automation via accessibility snapshots, no vision models needed |
| [oraios/serena](https://github.com/oraios/serena) | ![](https://img.shields.io/github/stars/oraios/serena?style=flat-square&logo=github) | IDE-like semantic code retrieval and symbol-level editing tools for any LLM |
| [GLips/Figma-Context-MCP](https://github.com/GLips/Figma-Context-MCP) | ![](https://img.shields.io/github/stars/GLips/Figma-Context-MCP?style=flat-square&logo=github) | Feeds Figma layout and styling data to AI coding agents for one-shot UI builds |
| [21st-dev/magic-mcp](https://github.com/21st-dev/magic-mcp) | ![](https://img.shields.io/github/stars/21st-dev/magic-mcp?style=flat-square&logo=github) | AI-powered UI component generation from natural language using 21st.dev library |
| [Jpisnice/shadcn-ui-mcp-server](https://github.com/Jpisnice/shadcn-ui-mcp-server) | ![](https://img.shields.io/github/stars/Jpisnice/shadcn-ui-mcp-server?style=flat-square&logo=github) | Serves shadcn/ui v4 component source, demos, and blocks for React/Vue/Svelte |
| [idosal/git-mcp](https://github.com/idosal/git-mcp) | ![](https://img.shields.io/github/stars/idosal/git-mcp?style=flat-square&logo=github) | Zero-setup remote MCP server that turns any GitHub repo into an LLM doc hub |
| [hangwin/mcp-chrome](https://github.com/hangwin/mcp-chrome) | ![](https://img.shields.io/github/stars/hangwin/mcp-chrome?style=flat-square&logo=github) | Chrome extension MCP server reusing your browser sessions, logins, and tabs |
| [executeautomation/mcp-playwright](https://github.com/executeautomation/mcp-playwright) | ![](https://img.shields.io/github/stars/executeautomation/mcp-playwright?style=flat-square&logo=github) | Browser and API automation with screenshots, scraping, and device emulation |
| [browserbase/mcp-server-browserbase](https://github.com/browserbase/mcp-server-browserbase) | ![](https://img.shields.io/github/stars/browserbase/mcp-server-browserbase?style=flat-square&logo=github) | Cloud browser automation with Stagehand v3 for extraction and interaction |
| [wonderwhy-er/DesktopCommanderMCP](https://github.com/wonderwhy-er/DesktopCommanderMCP) | ![](https://img.shields.io/github/stars/wonderwhy-er/DesktopCommanderMCP?style=flat-square&logo=github) | Terminal control, file search, diff editing, and code execution from AI chat |
| [czlonkowski/n8n-mcp](https://github.com/czlonkowski/n8n-mcp) | ![](https://img.shields.io/github/stars/czlonkowski/n8n-mcp?style=flat-square&logo=github) | Gives AI assistants full knowledge of 1,084 n8n nodes, templates, and docs |
| [googleapis/genai-toolbox](https://github.com/googleapis/genai-toolbox) | ![](https://img.shields.io/github/stars/googleapis/genai-toolbox?style=flat-square&logo=github) | Open-source MCP server for databases with pooling, auth, and observability |
| [BeehiveInnovations/pal-mcp-server](https://github.com/BeehiveInnovations/pal-mcp-server) | ![](https://img.shields.io/github/stars/BeehiveInnovations/pal-mcp-server?style=flat-square&logo=github) | Multi-model orchestration layer letting your CLI coordinate 50+ AI providers |
| [crystaldba/postgres-mcp](https://github.com/crystaldba/postgres-mcp) | ![](https://img.shields.io/github/stars/crystaldba/postgres-mcp?style=flat-square&logo=github) | Postgres index tuning, explain plans, health checks, and safe SQL execution |
| [supabase-community/supabase-mcp](https://github.com/supabase-community/supabase-mcp) | ![](https://img.shields.io/github/stars/supabase-community/supabase-mcp?style=flat-square&logo=github) | Connect AI assistants to Supabase for schema, queries, and project management |
| [bytebase/dbhub](https://github.com/bytebase/dbhub) | ![](https://img.shields.io/github/stars/bytebase/dbhub?style=flat-square&logo=github) | Zero-dependency MCP gateway for Postgres, MySQL, SQL Server, MariaDB, SQLite |
| [julien040/anyquery](https://github.com/julien040/anyquery) | ![](https://img.shields.io/github/stars/julien040/anyquery?style=flat-square&logo=github) | SQL query engine for 40+ apps (Notion, GitHub, Chrome) with MCP and MySQL modes |
| [haris-musa/excel-mcp-server](https://github.com/haris-musa/excel-mcp-server) | ![](https://img.shields.io/github/stars/haris-musa/excel-mcp-server?style=flat-square&logo=github) | Create, read, and modify Excel workbooks with charts, pivots, and formatting |
| [awslabs/mcp](https://github.com/awslabs/mcp) | ![](https://img.shields.io/github/stars/awslabs/mcp?style=flat-square&logo=github) | Suite of 20+ specialized MCP servers spanning AWS compute, data, AI, and DevOps |
| [cloudflare/mcp-server-cloudflare](https://github.com/cloudflare/mcp-server-cloudflare) | ![](https://img.shields.io/github/stars/cloudflare/mcp-server-cloudflare?style=flat-square&logo=github) | Remote MCP servers for Workers, Radar, DNS, observability, and 10+ CF services |
| [hashicorp/terraform-mcp-server](https://github.com/hashicorp/terraform-mcp-server) | ![](https://img.shields.io/github/stars/hashicorp/terraform-mcp-server?style=flat-square&logo=github) | Manage Terraform Registry, HCP workspaces, and IaC automation via MCP |
| [containers/kubernetes-mcp-server](https://github.com/containers/kubernetes-mcp-server) | ![](https://img.shields.io/github/stars/containers/kubernetes-mcp-server?style=flat-square&logo=github) | Native Go server for K8s/OpenShift CRUD, Helm, pod exec, and multi-cluster ops |
| [grafana/mcp-grafana](https://github.com/grafana/mcp-grafana) | ![](https://img.shields.io/github/stars/grafana/mcp-grafana?style=flat-square&logo=github) | Query dashboards, Prometheus, Loki, and manage alerts and incidents via MCP |
| [dagger/container-use](https://github.com/dagger/container-use) | ![](https://img.shields.io/github/stars/dagger/container-use?style=flat-square&logo=github) | Isolated containerized dev environments for parallel coding agents via MCP |
| [makenotion/notion-mcp-server](https://github.com/makenotion/notion-mcp-server) | ![](https://img.shields.io/github/stars/makenotion/notion-mcp-server?style=flat-square&logo=github) | Official Notion API integration for pages, databases, search, and content editing |
| [sooperset/mcp-atlassian](https://github.com/sooperset/mcp-atlassian) | ![](https://img.shields.io/github/stars/sooperset/mcp-atlassian?style=flat-square&logo=github) | Confluence and Jira integration supporting both Cloud and Server/Data Center |
| [taylorwilsdon/google_workspace_mcp](https://github.com/taylorwilsdon/google_workspace_mcp) | ![](https://img.shields.io/github/stars/taylorwilsdon/google_workspace_mcp?style=flat-square&logo=github) | Control Gmail, Calendar, Drive, Docs, Sheets, and 6+ Google services via MCP |
| [korotovsky/slack-mcp-server](https://github.com/korotovsky/slack-mcp-server) | ![](https://img.shields.io/github/stars/korotovsky/slack-mcp-server?style=flat-square&logo=github) | Slack workspace access with stealth mode, DMs, threads, and smart history fetch |
| [lharries/whatsapp-mcp](https://github.com/lharries/whatsapp-mcp) | ![](https://img.shields.io/github/stars/lharries/whatsapp-mcp?style=flat-square&logo=github) | Read, search, and send personal WhatsApp messages including media via MCP |
| [MarkusPfundstein/mcp-obsidian](https://github.com/MarkusPfundstein/mcp-obsidian) | ![](https://img.shields.io/github/stars/MarkusPfundstein/mcp-obsidian?style=flat-square&logo=github) | Read, search, and edit Obsidian vault notes via the Local REST API plugin |
| [firecrawl/firecrawl-mcp-server](https://github.com/firecrawl/firecrawl-mcp-server) | ![](https://img.shields.io/github/stars/firecrawl/firecrawl-mcp-server?style=flat-square&logo=github) | Web scraping, crawling, search, and deep research with auto-retry and batching |
| [exa-labs/exa-mcp-server](https://github.com/exa-labs/exa-mcp-server) | ![](https://img.shields.io/github/stars/exa-labs/exa-mcp-server?style=flat-square&logo=github) | Exa-powered semantic web search, code search, and company research for AI agents |
| [luminati-io/brightdata-mcp](https://github.com/luminati-io/brightdata-mcp) | ![](https://img.shields.io/github/stars/luminati-io/brightdata-mcp?style=flat-square&logo=github) | Real-time web access and scraping for LLMs with anti-blocking via Bright Data |
| [zcaceres/markdownify-mcp](https://github.com/zcaceres/markdownify-mcp) | ![](https://img.shields.io/github/stars/zcaceres/markdownify-mcp?style=flat-square&logo=github) | Convert PDFs, DOCX, images, audio, YouTube, and web pages to Markdown |
| [blazickjp/arxiv-mcp-server](https://github.com/blazickjp/arxiv-mcp-server) | ![](https://img.shields.io/github/stars/blazickjp/arxiv-mcp-server?style=flat-square&logo=github) | Search, download, and analyze arXiv papers with local storage and caching |
| [antvis/mcp-server-chart](https://github.com/antvis/mcp-server-chart) | ![](https://img.shields.io/github/stars/antvis/mcp-server-chart?style=flat-square&logo=github) | Generate 26+ chart types for data visualization and analysis using AntV |
| [LaurieWired/GhidraMCP](https://github.com/LaurieWired/GhidraMCP) | ![](https://img.shields.io/github/stars/LaurieWired/GhidraMCP?style=flat-square&logo=github) | LLM-driven binary reverse engineering with Ghidra decompilation and analysis |
| [mrexodia/ida-pro-mcp](https://github.com/mrexodia/ida-pro-mcp) | ![](https://img.shields.io/github/stars/mrexodia/ida-pro-mcp?style=flat-square&logo=github) | Bridge IDA Pro disassembler to LLMs for AI-assisted reverse engineering |
| [ahujasid/blender-mcp](https://github.com/ahujasid/blender-mcp) | ![](https://img.shields.io/github/stars/ahujasid/blender-mcp?style=flat-square&logo=github) | Control Blender 3D modeling, materials, and scene creation from Claude via MCP |
| [mobile-next/mobile-mcp](https://github.com/mobile-next/mobile-mcp) | ![](https://img.shields.io/github/stars/mobile-next/mobile-mcp?style=flat-square&logo=github) | Platform-agnostic iOS and Android automation on emulators, simulators, and devices |
| [doobidoo/mcp-memory-service](https://github.com/doobidoo/mcp-memory-service) | ![](https://img.shields.io/github/stars/doobidoo/mcp-memory-service?style=flat-square&logo=github) | Persistent context memory across AI sessions using semantic search and embeddings |
| [cjo4m06/mcp-shrimp-task-manager](https://github.com/cjo4m06/mcp-shrimp-task-manager) | ![](https://img.shields.io/github/stars/cjo4m06/mcp-shrimp-task-manager?style=flat-square&logo=github) | Structured task decomposition with dependency tracking and chain-of-thought for AI |

---

## Contributing

Found a missing repo? Open an issue or submit a PR! Only repositories with **1,000+ stars** are listed.

## License

[CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/)
