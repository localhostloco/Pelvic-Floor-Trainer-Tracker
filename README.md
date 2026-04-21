# Pelvic Floor Trainer

A single-file, mobile-first pelvic floor training web app. Open the HTML file in any modern browser — no build, no install, no backend.

## Features

**Training**
- Animated ring timer with hold / rest / release phases
- Slow holds, quick flicks, full release work, and pulse patterns
- Auto-advance through reps → rest → next set
- 3-2-1 prep countdown before each session
- Block transitions for multi-protocol sessions
- Breathing pacer (visual inhale/exhale guide)

**12-Week Sexual Function Plan**
- 3 sessions per day (morning / midday / evening)
- 6 phases: Foundation → Build → Strength → Power & Control → Endurance + Pulse → Mastery → Maintenance
- Position progression (lying → sitting → standing → functional) baked into the schedule
- Stays under the 100-rep/day clinical safety cap
- Auto-tracks daily/weekly completion

**Persistence & Insights**
- All data in `localStorage` — no account, no backend
- Session history with hold-time trend chart
- Weekly summary (sessions, reps, avg hold)
- Daily streak tracker
- Export / import JSON for backup
- Resume interrupted sessions

**Mobile UX**
- Screen Wake Lock + silent-audio fallback (keeps screen on)
- Elapsed workout timer (pauses when you pause)
- Audio beeps, voice cues (Web Speech API), and haptic feedback — all toggleable
- Light / dark / auto theme

**Standalone Programs (off-plan)**
- Beginner, Intermediate, Advanced, Quick Flicks, PT Standard, Custom
- Per-program progression levels with "struggled" detection
- Progressive overload suggestions

## Usage

Download `pelvic-floor-trainer.html` and open it in any browser. On mobile, "Add to Home Screen" gives you a near-native experience.

## Evidence base

The plan structure follows guidance from:
- Mayo Clinic — position progression (lying → sitting → standing)
- Memorial Sloan Kettering / UNC / Cleveland Clinic — 5s holds building to 10s
- Frontiers in Public Health (2026) — 6-week neuromuscular activity studies in men
- Physiopedia — daily training with mixed slow/quick contractions and release work
- Newman et al. clinical regimen — 3 sets × 8–12 reps × 8–10s, 2–5 sessions/day

## Privacy

Everything stays on your device. No analytics, no tracking, no network calls (except loading Google Fonts on first open — Tailwind/JS frameworks are not used).

## License

MIT — see `LICENSE`.
