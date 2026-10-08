<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&duration=2800&pause=900&color=22D3EE&center=true&vCenter=true&width=900&height=50&lines=Hey%2C+I'm+Adarsh+Jaiswal+%F0%9F%91%8B;AJ+NiPlex+%C2%B7+AI+Agents+%C2%B7+MCP+%C2%B7+Backend;Main+products%3A+NiPlex-Harness+%26+NiPlex-MCP;Never+Stop+Imagining" alt="Typing SVG" />

<img src="https://komarev.com/ghpvc/?username=Aj-Niplex&label=Profile+Views&color=0ea5e9&style=flat" alt="Profile views" />

<br/>

```text
░▒█▀▄ █▀█ █░█ █   █ ██▀ █▀▀ █▀█ █▀▄ █▀▀ █▀█  ▁ ▂ ▄ ▅ ▆ ▇ █
░▒█▄▀ █▄█ ▀▄▀ █▄▄ █ ▄█  ██▄ █▄█ █▄▀ ██▄ █▀▄  █ ▇ ▆ ▅ ▄ ▂ ▁
```

```bash
> boot sequence initiated .......... [ OK ]
> loading  niplex.agents ........... [ OK ]
> mounting  harness + mcp .......... [ OK ]
> syncing   tools + memory ......... [ OK ]
> signal locked :: AJ-NIPLEX ....... [ LIVE ]
```

<br/>

[![Portfolio](https://img.shields.io/badge/-Portfolio-0ea5e9?style=flat-square&logo=github&logoColor=white)](https://aj-niplex.github.io/)
[![Python](https://img.shields.io/badge/-Python_3.13-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![MCP](https://img.shields.io/badge/-MCP_Protocol-7C3AED?style=flat-square&logo=graphql&logoColor=white)](https://modelcontextprotocol.io/)
[![Discord.py](https://img.shields.io/badge/-Discord.py-5865F2?style=flat-square&logo=discord&logoColor=white)](https://discordpy.readthedocs.io/)
[![Linux](https://img.shields.io/badge/-Linux_VPS-FCC624?style=flat-square&logo=linux&logoColor=black)](https://www.linux.org/)

</div>

---

### Main Products

#### 1. NiPlex-Harness (Public)
**Personal AI agent harness** controlled from Discord or Telegram.  
Built for people on free hosts (HidenCloud etc.) without a PC — phone is the control panel.

- Discord (recommended) or Telegram gateway  
- `/setup` → provider → API key → models from API  
- Built-in Python sandbox + **approval buttons**  
- `vault/` — Obsidian-ready Markdown  
- Memory, files, skills, web search, terminal  
- Allow-list only

**Repo:** [NiPlex-Harness](https://github.com/Aj-Niplex/NiPlex-Harness)  
**Private dev:** `dev-NiPlex-Harness`

#### 2. NiPlex-MCP (Private · Core)
**Production Model Context Protocol server** — one AI agent’s full toolkit behind a single MCP connection.

- **47+ tools**  
- GitHub (full repo/file/branch/issue/PR access)  
- Sandboxes (Daytona / E2B / Horizon)  
- HidenCloud (live production server, file-only)  
- Web search + YouTube  
- Neural memory sub-agent  
- Google Workspace (Gmail draft, Calendar, Drive, Docs)

Paired with **Neural** (memory sub-agent) backed by a durable GitHub knowledge store.  
Security-reviewed, allow-list dispatch, no email-send, no auto-merge.

---

### Architecture

```mermaid
flowchart TB
    subgraph Clients
        A[Discord / Telegram]
        B[Any MCP Client]
    end

    subgraph "NiPlex-Harness"
        H[Harness Gateway]
        S[Python Sandbox + Approvals]
        V[vault/ · Memory · Skills]
    end

    subgraph "NiPlex-MCP"
        M[MCP Server · 47+ tools]
        G[GitHub]
        SB[Sandboxes]
        HC[HidenCloud]
        W[Web / YouTube]
        GW[Google Workspace]
    end

    subgraph Memory
        N[Neural Sub-agent]
        K[Durable Knowledge Store]
    end

    A --> H
    B --> M
    H --> S
    H --> V
    H --> M
    M --> G
    M --> SB
    M --> HC
    M --> W
    M --> GW
    M --> N
    N --> K
```

---

### Other Public Projects

| Project | What it is |
|---------|------------|
| **[Rei-kun-Bot](https://github.com/Aj-Niplex/Rei-kun-Bot)** | Live Discord AI orchestrator — multi-model fallback, persistent persona, resource hub |
| **[Niplex-obsidian-Research-AI](https://github.com/Aj-Niplex/Niplex-obsidian-Research-AI)** | Mobile-first Obsidian research agent (bounded context + approved edits) |
| **[niplex-obsidian-helper](https://github.com/Aj-Niplex/niplex-obsidian-helper)** + **[Niplex-Obsidian-skills](https://github.com/Aj-Niplex/Niplex-Obsidian-skills)** | Safe skill marketplace + instruction-only skills for Obsidian |
| **[Aj-Niplex.github.io](https://aj-niplex.github.io/)** | Public portfolio site |

<p align="center">
  <a href="https://github.com/Aj-Niplex/NiPlex-Harness">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Aj-Niplex&repo=NiPlex-Harness&theme=tokyonight&hide_border=true" alt="NiPlex-Harness" />
  </a>
  <a href="https://github.com/Aj-Niplex/Rei-kun-Bot">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Aj-Niplex&repo=Rei-kun-Bot&theme=tokyonight&hide_border=true" alt="Rei-kun-Bot" />
  </a>
</p>

---

### Tools & AI Agents I use

| Role | Tool |
|------|------|
| **Main developer** | Claude |
| **Bug hunter & secondary dev** | Grok |
| **3rd / random tasks** | Mistral Vibe |
| **Research (sometimes)** | ChatGPT |
| **Custom agent (sometimes)** | My own customized Hermes |
| **Google-connected work** | Gemini |

### AI Providers I love & use

- **Gemini** (Google APIs)
- **Agnes AI** by Sepians

---

### Stack

```text
Python 3.13          MCP Protocol         Discord.py
aiohttp / REST       Obsidian plugins     Linux VPS
Mobile-first UX      Sandbox isolation    Agent memory layers
```

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![MCP](https://img.shields.io/badge/-MCP-7C3AED?style=flat-square&logo=graphql&logoColor=white)
![Discord](https://img.shields.io/badge/-Discord.py-5865F2?style=flat-square&logo=discord&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Obsidian](https://img.shields.io/badge/-Obsidian-7C3AED?style=flat-square&logo=obsidian&logoColor=white)

---

### How I work

- Backend & agents first  
- Ship real running systems, then improve them  
- Social apps (Discord / Telegram) as the primary UI  
- Transparent prompts, bounded context, explicit approvals  
- Mobile-first development whenever possible

---

### 📊 GitHub Stats (auto-updating)

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Aj-Niplex&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="165" alt="GitHub Stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Aj-Niplex&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" height="165" alt="Top Languages" />

<br/>

<img src="https://streak-stats.demolab.com/?user=Aj-Niplex&theme=tokyonight&hide_border=true" alt="GitHub Streak" />

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Aj-Niplex&theme=tokyo-night&hide_border=true&area=true" alt="Contribution Graph" width="100%" />

<br/>

<img src="https://github-profile-trophy.vercel.app/?username=Aj-Niplex&theme=tokyonight&no-frame=true&no-bg=true&column=7&margin-w=15" alt="Trophies" />

</div>

---

<div align="center">

**Never Stop Imagining.**

[Portfolio](https://aj-niplex.github.io/) · [NiPlex-Harness](https://github.com/Aj-Niplex/NiPlex-Harness) · [GitHub](https://github.com/Aj-Niplex)

</div>
