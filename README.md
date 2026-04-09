# PediAid Status

Single-page live status dashboard for the PediAid platform.

**Live URL:** https://mulgundsunil1918.github.io/pediaid-status/

## What it shows

- **Live checks** (60 s auto-refresh) for the backend API, React frontend, and Flutter web build — with response time and last-checked timestamp
- **Hosting & deployment** — Render, GitHub Pages targets, Play Store / App Store status
- **Database & storage** — Neon PostgreSQL, local dev disk
- **Backend stack** — Node/Fastify, TypeScript, JWT, bcrypt, Sharp
- **Frontend stack** — React 18, Tailwind, React Query, React Router, Zustand
- **Mobile** — Flutter
- **Email & notifications** — Gmail SMTP, Resend (future), in-app bell
- **Dev tools** — Claude Code, Claude.ai, Codespaces, Notion
- **GitHub repos** — direct links to pediaid-flutter / pediaid-frontend / pediaid-backend
- **Pending checklist** — localStorage-backed todo list for launch tasks

## Tech

Plain static HTML + CSS + JS. No build step. Deploys via the `deploy.yml`
workflow in `.github/workflows/`.

## Local preview

Just open `index.html` in a browser. The live checks run from the browser
so nothing needs to be running locally.
