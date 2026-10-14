# darshakpatel5.github.io

Personal CV / portfolio site for **Darshak Patel** — built with [Hugo](https://gohugo.io/) and the [Toha](https://github.com/hugo-toha/toha) theme, deployed to GitHub Pages.

## Edit content

All content lives in YAML data files (no Markdown pages needed):

- `data/en/author.yaml` — name, avatar, contact, taglines
- `data/en/site.yaml` — copyright, meta/OpenGraph
- `data/en/sections/about.yaml` — summary, social links, résumé button
- `data/en/sections/skills.yaml` — skills (logos in `assets/images/sections/skills/`)
- `data/en/sections/experiences.yaml` — work history
- `data/en/sections/accomplishments.yaml` — certifications & awards
- `data/en/sections/education.yaml` — education

Replace the avatar at `assets/images/author/darshak.png` and the résumé at `static/files/resume.pdf` with your own.

## Run locally

```bash
npm install
hugo server
```

Then open http://localhost:1313.

## Deploy

Every push to `main` builds and deploys via GitHub Actions (`.github/workflows/deploy.yml`). Enable it once under **Settings → Pages → Build and deployment → Source: GitHub Actions**.
