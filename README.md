# Karaoke Rehearsal App

A single-file local web app for karaoke and vocal rehearsal.

## Features

- 37-song rehearsal setlist
- Practice Player mode
- Search and filters
- Song status tracking: Not worked, To work, Ready
- Rehearsed toggle per song
- Editable practice notes
- Mastery star rating
- Run counter
- Practice timer with Start, Pause, Resume and Stop
- Daily practice history
- YouTube, Karaoke, Spotify and lyrics/search links
- Embedded YouTube / Spotify player with external fallback links
- Local data persistence with localStorage

## How to use

Open index.html in a browser.

For the best embedded player behavior, run a local server from the project folder:

python3 -m http.server 8000

Then open:

http://localhost:8000/index.html

The app can also be opened by double-clicking index.html, but some embedded YouTube players may not work correctly from file://.

## Data storage

All progress is stored locally in the user's browser with localStorage.

Each Mac and each browser keeps its own data.

There is no account system, no backend, no cloud sync and no database.

## Copyright note

This app does not store full song lyrics.

Music, karaoke videos and lyrics pages are accessed through external links only.
