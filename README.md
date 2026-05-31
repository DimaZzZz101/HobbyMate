# HobbyMate

Root repository for the HobbyMate craft-tools site.

Live: **[dimazzzz101.github.io/HobbyMate](https://dimazzzz101.github.io/HobbyMate/)**

## Services

| Service | Repo | Description |
|---------|------|-------------|
| Paint by Numbers | [NumDraw](https://github.com/DimaZzZz101/NumDraw) | Converts any photo into a numbered SVG paint-by-numbers template (client-side TypeScript) |
|  Cross Stitch | [Cross_Stitch](https://github.com/DimaZzZz101/Cross_Stitch) | Generates cross-stitch embroidery patterns with DMC/Anchor/Cosmo/Gamma thread matching (Python via Pyodide) |

## Repository structure

```
HobbyMate/
├── index.html              — landing page
├── shared/
│   ├── theme.css           — shared design system (canonical)
│   └── shell.html          — app-shell fragment reference
├── services/
│   ├── NumDraw/            — git submodule
│   └── Cross_Stitch/       — git submodule
└── .github/workflows/
    └── deploy-pages.yml    — builds + deploys to GitHub Pages
```
