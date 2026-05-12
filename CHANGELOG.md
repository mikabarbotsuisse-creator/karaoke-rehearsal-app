# Changelog

## 2026-05-13 — Current app state cleanup

- Removed the user-facing runs feature:
  no visible runs on cards, overlay, or Practice Player; no run button; no undo run; no Space logging; no assisted run logging; no Songs today / Total runs in the session bar
- Kept legacy `stage-runs` data only for backward compatibility and export/import continuity
- Cleaned up documentation so it matches the current app state more accurately

## 2026-05-12 — UX and progress tracking update

- Added a Focused Song Card overlay when clicking a song card, while keeping Practice Player separate
- Added Archive / Restore with archived songs excluded from active progress and active filters
- Added Progress Backup with Export Progress / Import Progress using a single JSON file
- Added MINDSET LOCK reward state for songs that are Ready, Rehearsed, and rated 4★ or higher
- Updated Progress counters to show Locked, Ready, To work, and Not worked
- Cleaned top filters to: All, Not worked, To work, Ready, Due, Archived, and star filters
- Removed visible Easy / Medium / Hard labels from filters, song cards, and Practice Player
- Added direct clickable star ratings on song cards
- Improved the session control bar with clearer Start Session, Pause, Resume, and Stop Session hierarchy
- Simplified the header identity around `REHEARSAL STUDIO`

## v1.0.0 — Stable local version

- Added premium single-file karaoke rehearsal interface
- Added 37-song setlist
- Added Practice Player mode
- Added search and filters
- Added song status tracking
- Added Rehearsed toggle
- Added editable practice notes
- Added mastery star rating
- Added run counter
- Added practice timer with Start, Pause, Resume and Stop
- Added daily practice history
- Added YouTube, Karaoke, Spotify and lyrics/search links
- Added embedded player panel with external fallback links
- Added local data persistence with localStorage
