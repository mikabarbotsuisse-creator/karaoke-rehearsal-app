# Karaoke Rehearsal App

A static single-file web app for karaoke and vocal rehearsal.

Live site:
https://mikabarbotsuisse-creator.github.io/karaoke-rehearsal-app/

## Features

- 37-song rehearsal setlist
- Practice Player mode
- Focused Song Card overlay for immersive song review
- Search and cleaned top filters:
  All, Not worked, To work, Ready, Due, and star filters
- Song status tracking: Not worked, To work, Ready
- MINDSET LOCK reward state:
  Ready + Rehearsed + 4★ or higher
- Rehearsed toggle per song
- Clickable mastery star rating directly on song cards
- Editable practice notes
- Run counter
- Progress panel counters:
  Locked, Ready, To work, Not worked
- Practice timer with improved Start Session, Pause, Resume, and Stop Session controls
- Daily practice history
- Progress Backup:
  Export Progress / Import Progress with a single JSON file
- YouTube, Karaoke, Spotify and lyrics/search links
- Embedded YouTube / Spotify player with external fallback links
- Local data persistence with localStorage

## How to use

Use the live site:

https://mikabarbotsuisse-creator.github.io/karaoke-rehearsal-app/

For local testing or development, open `index.html` in a browser.

For the best embedded player behavior, run a local server from the project folder:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000/index.html
```

The app can also be opened by double-clicking `index.html`, but some embedded YouTube players may not work correctly from `file://`.

## Data storage

All progress is stored locally in the user's browser with `localStorage`.

Each browser on each device keeps its own saved progress.

There is no backend, no account system, no cloud sync, and no database.

Use Export Progress and Import Progress to move local progress between browsers or devices with a single JSON backup file.

## Notes

- The app is static and built around one main file: `index.html`.
- Full song lyrics are not stored in the app.
- Music, karaoke videos, and lyrics pages are accessed through external links only.
- Easy / Medium / Hard difficulty data still exists internally for song data, but those labels are no longer shown in filters, song cards, or the Practice Player.
