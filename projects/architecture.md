# NIPLEX Stack Architecture

## High-level flow

```
┌─────────────────────┐
│  AI Client          │  (Claude, other MCP-capable clients)
│  Discord / Telegram │  (Neural-Chat)  ← social apps as UI
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│     Niplex-MCP      │  47+ tools in one MCP server (Python)
│  GitHub · Google    │
│  Workspace · SFTP   │
│  Sandboxes · Web    │
│  YouTube · Neural   │
└──────────┬──────────┘
           │ ask_neural / log_to_neural
           ▼
┌─────────────────────┐
│     Neural-MCP      │  Memory / context sub-agent (Python)
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│  Adarshs-Stack      │  Durable wiki / memory store
│  Adarsh-Jaiswal     │  Obsidian vault (remote sync)
└─────────────────────┘
```

## Build style (current)

- **Language:** Python only
- **Focus:** Backend and agents
- **UI:** Discord / Telegram (social apps as the interface)
- Full-stack and other languages later when websites/apps are in scope

## Key components

### Niplex-MCP
Custom Model Context Protocol server. One connection gives any MCP client access to:
- Full GitHub (repos, files, PRs, issues)
- Google Workspace (Gmail read/draft, Calendar, Drive, Docs)
- HidenCloud production server (SFTP file access)
- Multiple sandboxes (E2B, Horizon, local subprocess)
- Web search + page scrape
- YouTube Data API
- Neural memory bridge

### Neural-MCP
Separate sub-agent with its own memory. Backed by a plain GitHub repo acting as a human-readable knowledge store. Scoped fine-grained PAT. Tools: `ask_neural`, `log_to_neural`.

### Neural-Chat
Discord + Telegram front-end:
- **Capture mode** — file thoughts into Neural
- **Chat mode** — full Niplex-MCP tool access

Hosted on HidenCloud (phone-first friendly).

### Obsidian layer
- **Niplex-obsidian-Research-AI** — autonomous research agent with bounded vault context (community plugin)
- **niplex-obsidian-helper** + **Niplex-Obsidian-skills** — skill marketplace and catalogue
- **Adarsh-Jaiswal** vault — identity, goals, study state, project notes

### Portfolio
**Aj-Niplex.github.io** — public face (Vision, Projects, Roadmap).

## Design principles

- AI tools are deliberate parts of the process (debugging, review, planning) — judgment and shipping stay with Adarsh
- Mobile-first / free-host friendly where possible
- Memory is durable, human-readable, and versioned in Git
- No credentials in memory or profile repos
