# Solace AI

An AI mental-wellness companion — a mobile-first web app built for the
**Humanity Founders solo 48-hour hackathon** (Nov 2026).

**Live demo:** https://muse.ai/s/solace-ai-xhi6b8xqxnoxueh/569ZEfGUJ-c4FuedXkHZ-zmZQM-yuONdVtNDsetWSkg

## What it does

Solace AI is a calm, private space for checking in with yourself. It has
seven screens:

1. **Home** — "Hey Sasi, how are you feeling today?" greeting, quick mood
   check-in, recent activity and conversations.
2. **AI Chat** — an adaptive companion that detects the feeling behind your
   words (anxiety, stress, sadness, sleep, anger, work pressure), responds
   supportively, and suggests a fitting activity. Crisis mentions surface
   Indian mental-health helplines (KIRAN, iCall, Vandrevala, AASRA) and 112.
3. **Mood Check-in & Tracking** — 1–10 slider, mood tags, journal notes,
   and a 7/14-day trends chart with history.
4. **Guided Activities** — breathing timer (Calm 4·4·6, Box 4·4·4·4,
   Sleep 4·7·8), meditation timer with chime, 5-4-3-2-1 grounding, and
   guided journaling prompts.
5. **Health Insights** — personalised recommendations from your own mood
   trends, check-in streaks, milestones, and a daily wellness report.
6. **Profile & Settings** — name, light/dark calm themes, reminders,
   privacy controls, export and erase your data.
7. **Notifications & Reminders** — daily check-in, evening wind-down and
   weekly reflection reminders, with browser notifications and streaks.

## How to run

No build step, no backend, no sign-in. Just open `index.html` in any
modern browser — or visit the live demo link above.

## Technology

- React with TypeScript, Tailwind CSS (single self-contained `index.html`)
- On-device storage (localStorage) — your data never leaves your browser
- Built with Muse AI; the in-app companion is an adaptive,
  rules-based engine with feeling detection and personalised recommendations

## Privacy

Everything stays on the device. No account, no server, no tracking.
Export or erase your data anytime from Profile & Settings.
