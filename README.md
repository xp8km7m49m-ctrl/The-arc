# The Arc — Personal Basketball Training Program

A React app for a weekly basketball training program built around a tight,
real-world schedule: three 2-hour sessions (location varies week to week —
full gym, court only, or weight room) plus a 45-minute home session every
day using just bands and dumbbells (no hoop at home).

Focus areas: shooting, strength & conditioning, and freer movement patterns.

## Features
- 10 session cards across the week (Mon–Sun)
- Tue/Wed/Thu sessions adapt to whatever's available that day: Full Gym,
  Court Only, or Weight Room
- Checklist-style exercise tracking with sets/reps and coaching cues
- A shot-arc SVG that fills in as sessions get checked off
- Progress persists between visits

## Running it
This component was built as a Claude.ai artifact and uses Claude's
in-artifact `window.storage` API for saving progress, so it runs as-is
inside Claude.ai.

To run it as a standalone web app (e.g. Vite, Create React App, Next.js),
you'll need to:
1. Install `react` and `lucide-react`
2. Replace the `window.storage.get/set` calls with `localStorage` (or any
   backend of your choice)

## File
- `the-arc-training-app.jsx` — the full app (single file, default export)
