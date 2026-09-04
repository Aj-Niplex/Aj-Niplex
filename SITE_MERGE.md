# Site merge: Aj-Niplex.github.io → Aj-Niplex

This repo now holds **both**:

1. **GitHub profile README** (`README.md`) — shown on https://github.com/Aj-Niplex
2. **Full NIPLEX portfolio site** — same files as `Aj-Niplex.github.io` (no features removed)

## What was merged (exact copies)

| Path | Role |
|------|------|
| `index.html` | Home |
| `about.html` | Vision |
| `projects.html` | Projects list |
| `roadmap.html` | Roadmap |
| `project-mcp.html` | MCP project page |
| `project-neural.html` | Neural project page |
| `project-rei.html` | Rei-kun project page |
| `style.css` | Full UI (themes, petals, layout) |
| `script.js` | Visitor counter |
| `server.py` | Python stdlib site + API server |
| `api/counter.py` | View counter logic |
| `package.json`, `vite.config.mjs`, `tsconfig.json`, `bun.lock` | Build tooling |
| `requirements.txt` | (stdlib only note) |
| `public/robots.txt` | Crawlers welcome |
| `assets/*` | Logos / images |

## Not deleted

- **`Aj-Niplex.github.io` is still live** — this was a merge *into* `Aj-Niplex`, not a delete of the Pages repo.
- Profile data folders remain: `profile/`, `projects/`, `repos/`, `REGISTRY.md`

## Run the site locally

```bash
python3 server.py
# open http://localhost:8000
```

## Pages note

User site URL `https://aj-niplex.github.io` still comes from the **`Aj-Niplex.github.io`** repo.  
This repo is the combined profile + full site source; keep both in sync when you edit UI.
