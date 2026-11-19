# AKUMU (1986)

**AKUMU** is a first-person 3D psychological horror escape room built with Three.js and WebAudio, featuring 1–4 player co-op multiplayer.

## Play Online
- **Live Game (GitHub Pages):** [https://polk730.github.io/akumu/](https://polk730.github.io/akumu/)

## Features
- **4-Player Co-op Multiplayer:** Create or join a 4-letter lobby code at the reception waiting table (or late-join a match already in progress).
- **Shared Co-op Puzzle Progression:** All locks, doors, storage terminal stages, crates, vents, and laundry/basement puzzles synchronize live across all players.
- **1986 Walkie-Talkie Proximity Radio:** Built-in WebRTC voice chat with a 1986 radio bandpass filter, squelch SFX, and proximity volume (supports Open Mic with `M` to mute or Push-to-Talk by holding `V`).
- **Smart Context Pings & Emote Wheel:** Press `B` (or `1`–`4`) to emote or point at any puzzle object in the room to spawn a 3D context label and highlight the object for teammates.
- **Co-op Squad Ending Report:** Post-escape breakdown of each player's solved puzzles, stacked crates, smart pings, emotes, and 1986 survivor titles.

## Automatic Itch.io Deployment (Optional)
This repository includes `.github/workflows/deploy-itch.yml`. To enable automatic publishing to Itch.io on every push:
1. Go to your [Itch.io API Keys settings](https://itch.io/user/settings/api-keys) and generate an API key.
2. In this GitHub repository, go to **Settings → Secrets and variables → Actions** and add:
   - Secret `BUTLER_API_KEY`: Your Itch.io API key
   - Variable `ITCH_USER`: Your Itch.io username
   - Variable `ITCH_GAME`: Your Itch.io game slug (e.g. `akumu`)
