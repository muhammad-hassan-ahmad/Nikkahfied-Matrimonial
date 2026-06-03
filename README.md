# Nikkahfied

A halal Muslim matrimonial app — clickable **UI prototype** (HTML/CSS/JS) built to validate the design with the client before the Flutter build.

## What's here
A single self-contained file, `index.html`, that renders the app inside a phone frame and is fully navigable:

- **Onboarding** — 3-slide intro (verified profiles / Wali / marriage-intent)
- **Auth** — login + sign up (with "Continue with Wali")
- **Discover** — swipe deck (drag or buttons): **right = interest, down = pass, up = super interest**
- **Browse** — search + filter chips + biodata grid, with photo-privacy blur
- **Profile detail** — biodata (profession, education, faith, salah, marital status, family), about, interests
- **Matches** — new matches + conversation list
- **Chat** — with Chaperone (Wali oversight) mode banner
- **My profile** — profile strength, Gold upgrade, guardian, photo privacy, preferences

### Design
Romantic rose primary with gold accents, Fraunces + Outfit fonts. Photos in `assets/` are free Pexels stock (commercial use, no attribution) — replace with real photos later.

## How to view
Open `index.html` in any modern browser (Chrome recommended). No build step or server required. Use browser zoom to fit it to your screen.

## Roadmap
1. Polish design with client feedback
2. Convert approved screens to **Flutter** (Android first; iOS later via Mac/cloud build)
3. Wire up backend (auth, profiles, matching, chat)

---
Internal prototype — InnovatorSolution.
