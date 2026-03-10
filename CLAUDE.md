# CV Portfolio Site — Yevhenii Hladkykh

## Project Overview
Personal CV/portfolio website deployed via GitHub Pages.
Single-page static site (HTML/CSS/JS) — no build tools, no frameworks.

## Architecture
- `index.html` — the live site (served by GitHub Pages from root)
- `CV_Yevhenii_Hladkykh_Detailed.md` — source of truth for all CV content
- `CV_Yevhenii_Hladkykh_Compact.md` — short version for quick reference
- `Site/` — drafts, experiments, old theme explorations (not deployed)

## Design Direction
- Theme: "Ember" — dark monospace aesthetic with orange accent (#ff6b2b)
- Fonts: Bebas Neue (headings) + DM Mono (body)
- Dark/light theme toggle
- Mobile responsive
- No generic AI aesthetics — bold, intentional, memorable

## Content Sections
1. Hero — name, role, key stats
2. Ticker — scrolling skills banner
3. About / Summary
4. Work Experience timeline
5. Technical Skills
6. Projects (accordion with preview)
7. Education
8. Contact + social links

## Key Rules
- CV markdown files are living documents — updated regularly
- Site content should be easy to update when CV changes
- Keep everything in a single index.html (inline CSS/JS) for simplicity
- GitHub Pages deployment from `main` branch root
- No external dependencies beyond Google Fonts CDN

## Git & Deploy
- Repo: GitHub Pages site
- Branch: `main`
- Deploy: push to main → auto-deployed by GitHub Pages
- Use `/commit` and `/commit-push-pr` plugin commands for git workflow

## Contacts (for site)
- Email: kaskat250@gmail.com
- Telegram: @Kaskat
- Phone: +380989384514
- Location: Lviv, Ukraine
- Format: Remote only
