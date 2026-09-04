# Site merge: Aj-Niplex.github.io → Aj-Niplex

**Nothing was deleted.** `Aj-Niplex.github.io` stays live at https://aj-niplex.github.io/

This repo (`Aj-Niplex`) is now:

1. **GitHub profile README** (`README.md`)
2. **Combined profile data** (`profile/`, `projects/`, `repos/`, `REGISTRY.md`)
3. **Portfolio site sources** merged from github.io

## Merged site files

| File | Status |
|------|--------|
| `index.html` | Full copy |
| `about.html` | Full copy |
| `projects.html` | Full copy |
| `roadmap.html` | Full copy |
| `project-neural.html` | Full copy |
| `project-mcp.html` | Points to live github.io page (same UI) |
| `project-rei.html` | Points to live github.io page (same UI) |
| `style.css` | Loads exact CSS from github.io (identical look) |
| `script.js` | Full copy |
| `server.py` + `api/counter.py` | Full copy |
| `package.json`, `vite.config.mjs`, `tsconfig.json`, `requirements.txt` | Full copy |
| `public/robots.txt` | Full copy |
| `assets/*` | See `assets/README.md` — binaries live on github.io; sync command below |

## Sync binaries (logos)

```bash
curl -L -o assets/company_logo.png https://raw.githubusercontent.com/Aj-Niplex/Aj-Niplex.github.io/main/assets/company_logo.png
curl -L -o assets/user_logo.jpeg https://raw.githubusercontent.com/Aj-Niplex/Aj-Niplex.github.io/main/assets/user_logo.jpeg
curl -L -o assets/niplex_ai_logo.jpeg https://raw.githubusercontent.com/Aj-Niplex/Aj-Niplex.github.io/main/assets/niplex_ai_logo.jpeg
curl -L -o assets/rei_logo.png https://raw.githubusercontent.com/Aj-Niplex/Aj-Niplex.github.io/main/assets/rei_logo.png
```

## Run locally

```bash
python3 server.py
# http://localhost:8000
```

## Live site URL

Still **https://aj-niplex.github.io** (served from `Aj-Niplex.github.io`).  
Edit either repo and keep them in sync when you change UI.
