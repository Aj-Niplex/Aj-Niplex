# Adarsh Jaiswal — Combined Profile & Projects Registry

**Single source of truth** combining:
- Profile / identity data from the `Adarsh-Jaiswal` vault
- Full project & repository inventory across the Aj-Niplex account
- Current state, goals, and architecture notes

> Mission: **Never Stop Imagining.**  
> GitHub: [Aj-Niplex](https://github.com/Aj-Niplex)  
> Site: [aj-niplex.github.io](https://aj-niplex.github.io/)

---

## Quick Identity

| Field | Value |
|-------|--------|
| **Preferred name** | Adarsh |
| **Full name** | Adarsh Jaiswal |
| **GitHub** | [`Aj-Niplex`](https://github.com/Aj-Niplex) |
| **Founder of** | **NIPLEX** — *Never Stop Imagining* |
| **Real DOB** | 3 September 2009 |
| **Official DOB** | 3 September 2010 |
| **Location** | Gorakhpur, Uttar Pradesh, India |
| **School** | Woodland Academy (Class 12 CBSE PCM) |
| **Long-term** | Independent AI-assisted builder → eventually a company |

**Enduring interests:** AI/ML, software development, developer tools, useful applications, Japan & Japanese language (route still open).

**Communication style:** Informal, direct, clear correction. Tough-love allowed when procrastinating. Prefers a second-brain style assistant: honest about uncertainty, practical, initiative-taking.

---

## Current Goals (priority order)

1. Recover academically and target ~80% in CBSE Class 12.
2. Learn Japanese and keep the Japan pathway open (MEXT 2028 target, language school, Kosen/university options).
3. Build a substantial GitHub project that demonstrates real engineering / AI usefulness.
4. Clarify best career direction (AI/ML vs CS vs Software Engineering vs Robotics).
5. Develop NIPLEX as useful resources and a future company, not feature-chasing.

---

## Architecture Snapshot

```
AI Client (Claude / others)
        │
        ▼
   Niplex-MCP  ──────► sandboxes, GitHub, Google Workspace, HidenCloud, YouTube, web
        │
        ▼
   Neural-MCP  ──────► ask_neural / log_to_neural
        │
        ▼
   Adarshs-Stack (memory wiki) + Adarsh-Jaiswal (Obsidian vault)
```

**Neural-Chat** = Discord + Telegram capture/chat bot wired into the same pipeline.

---

## Full Project & Repo Inventory

### Active / Continuously Upgrading

| Project | Repo | Description |
|---------|------|-------------|
| **Niplex-MCP** | [`niplex-mcp`](https://github.com/Aj-Niplex/niplex-mcp) | Custom MCP server — 47+ tools (GitHub, Google Workspace, HidenCloud/SFTP, sandboxes, YouTube, web search, Neural). Horizon auto-deploy. |
| **Neural (Neural-MCP)** | [`Neural`](https://github.com/Aj-Niplex/Neural) | Memory sub-agent between Niplex-MCP and Adarshs-Stack. Tools: `ask_neural` / `log_to_neural`. |
| **Neural-Chat** | [`neural-chat`](https://github.com/Aj-Niplex/neural-chat) | Discord + Telegram bot (capture mode + full tool access). Hosted on HidenCloud. |
| **Niplex Research AI** | [`Niplex-obsidian-Research-AI`](https://github.com/Aj-Niplex/Niplex-obsidian-Research-AI) (public) / `Dev-obsidian-agentic-research` (private) | Mobile-first Obsidian community plugin — autonomous research agent with bounded vault context. Passed community review. |
| **Niplex Skills Helper** | [`niplex-obsidian-helper`](https://github.com/Aj-Niplex/niplex-obsidian-helper) | Companion plugin — skill marketplace lookup/install. |
| **Niplex Obsidian Skills** | [`Niplex-Obsidian-skills`](https://github.com/Aj-Niplex/Niplex-Obsidian-skills) | Public catalogue of research skills (RSH01–RSH09). |
| **Sandbox** | [`Sandbox`](https://github.com/Aj-Niplex/Sandbox) | Minimal free code-runner MCP (subprocess), cheapest sandbox tier for Niplex-MCP. |
| **Portfolio Site** | [`Aj-Niplex.github.io`](https://github.com/Aj-Niplex/Aj-Niplex.github.io) | Public NIPLEX showcase — vision, projects, roadmap. Python backend + Vite frontend. |

### Mature / Lower Activity

| Project | Repo | Description |
|---------|------|-------------|
| **Rei-kun-Bot** | [`Rei-kun-Bot`](https://github.com/Aj-Niplex/Rei-kun-Bot) | High-performance AI Discord orchestrator with persistent persona, multi-model intelligence, resource hub. |
| **NiPlex-Harness** | [`NiPlex-Harness`](https://github.com/Aj-Niplex/NiPlex-Harness) | Public personal AI agent harness (Discord/Telegram, /setup, sandbox). Built for phone-first / free hosts. |
| **dev-NiPlex-Harness** | [`dev-NiPlex-Harness`](https://github.com/Aj-Niplex/dev-NiPlex-Harness) | Dev/experiments branch of the harness. |

### Planned / Private

| Project | Status |
|---------|--------|
| **Niplex Agent** | Planned private agent — not yet scoped for public release. |
| **Niplex-Computer-MCP / Computer-Use-MCP / Computer-Runtime** | Computer-use related MCP experiments. |

### Infrastructure & Memory

| Repo | Role |
|------|------|
| **Adarsh-Jaiswal** | Obsidian remote-sync vault (identity, goals, current-state, project notes). |
| **Adarsh-Profile** (this repo) | Combined public-facing profile + full project registry. |
| **Hermes-backup** | Disaster-recovery snapshot. |
| **Niplex-bot** | Predecessor to Neural-Chat (superseded). |
| **Temp** | Scratch / manager file dump. |
| **Neural_OS** | Archived second-brain web app experiment ("Graphene Daily"). |
| **Niplex-Research-Brain / Niplex-Writing-Insights** | Research & writing support repos. |
| **Niplex-Obsidian-skills** | Skills catalogue (also listed under active). |

### Other

| Repo | Notes |
|------|-------|
| **Hermes-backup** | Single-commit recovery snapshot. |
| **Sandbox** | Code-runner MCP. |
| **Computer-*** family | Computer-use / runtime MCP experiments. |

---

## File Map in This Repo

| File | Purpose |
|------|--------|
| `README.md` | This overview |
| `profile/identity.md` | Stable identity & durable preferences |
| `profile/current-state.md` | Living current situation |
| `profile/goals.md` | Current goals & priority order |
| `projects/registry.md` | Full project status table |
| `projects/architecture.md` | How the NIPLEX stack fits together |
| `repos/inventory.md` | Complete list of Aj-Niplex repositories |

---

## Privacy & Update Rules

- No passwords, API keys, tokens, or recovery codes live here.
- Newest direct statement from Adarsh wins over older files.
- Project status changes should update both the registry and the relevant project note.
- This repo is the **combined public profile + project view**. Detailed daily notes and study state remain in the private `Adarsh-Jaiswal` vault.

---

*Last assembled from Adarsh-Jaiswal vault + Neural memory + live GitHub inventory — September 2026.*
