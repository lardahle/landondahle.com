# landondahle.com

Deployment repo for [landondahle.com](https://landondahle.com). Built from [synaptic-digital-hub](https://github.com/lardahle/synaptic-digital-hub) and served via FTP.

## To-Do

### Critical
- [ ] **Remove "Under Construction" overlays** — `/projects`, `/writing`, `/now`, and `/uses` are fully built but blocked by overlays; users can't see any content
- [ ] **Add missing nav items** — Projects, Writing, Now, and Uses are hidden from the navigation entirely (`Navigation.tsx`)

### High
- [ ] **Wire up Contact form** — currently shows a success toast but never sends anything; needs a real backend or email service (e.g. Resend, Formspree)
- [ ] **Update `/now` content** — goals still reference Q1–Q3 2024 deadlines; "Last updated: January 2024" is stale
- [ ] **Update `/uses` content** — "Last updated: January 2024" is stale

### Medium
- [ ] **Fix `/projects` demo links** — all Demo buttons link to `#`; add real URLs or remove buttons where no demo exists
