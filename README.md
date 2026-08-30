# SamTrack Dashboard Validation & Review

Two self-contained static pages covering the Cacao & Co dashboard UX/UI work — no build step, drop them in and go.

## Pages

- **`index.html`** — the full Validation & UI Audit Plan: user-validation research topics plus the complete Cacao & Co dashboard audit (layout reasoning, accessibility, aesthetics, font implementation) with screenshots.
  Live: https://claude.ai/code/artifact/e1e66a1e-8971-4274-ac65-2e4f2d2ce34b

- **`slides.html`** — a presentable slide deck version of the same audit's four categories (layout & hierarchy, accessibility, aesthetic, font implementation), each split into what's working and what needs improvement. Built for walking a team through live — arrow keys / space / swipe to navigate.
  Live: https://claude.ai/code/artifact/b623a218-2262-4a7e-a9a7-053b974650ae

## Deploying

**GitHub Pages:** Settings → Pages → Deploy from branch → `main` / root.
- `index.html` → `https://<user>.github.io/dashboard-audit/`
- `slides.html` → `https://<user>.github.io/dashboard-audit/slides.html`

**Vercel / Netlify:** point either at this repo with no framework preset; both serve static files as-is, so both pages are reachable the same way.

## Source

Companion to the main SamTrack UX Audit. Last updated 2026-08-30.
