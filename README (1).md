# सही English — Production Tracker (Dark Edition)

A branded dark-theme dashboard with neon accents to track live lesson deployment across Hindi, Telugu, Tamil, Kannada + AI Riya practice.

## Deploy on Netlify (30 seconds)

1. Go to https://app.netlify.com/drop
2. Drag this folder into the browser
3. Live URL ready instantly

Everything (logo, AI Riya image, CSS, JS) is bundled into `index.html` — no broken links.

## Features

- **Dark neon theme** — deep purple gradient background, glowing KPI numbers, glassmorphism cards, floating owl mascot
- **6 views** — Dashboard, Lessons, AI Riya, Languages, Deployments, Assets
- **Status dots per language** — click to cycle: empty → 🟢 Live → 🟡 In Review → empty
- **Search + filter** (All / Live / Pending)
- **Auto-save** to browser localStorage
- **Export / Import JSON** to back up or move between devices

## Pre-seeded

- L1 M1 — all 5 lessons live in Hindi
- L1 M3 — lessons 1–4 live in Hindi (lesson 5 pending)

## Note

Data is stored per-browser (localStorage). For a shared team tracker with live sync, a backend (Supabase / Firebase free tier) can be added later.
