# AKUMU (1986)

**AKUMU** is a first-person 3D psychological horror escape room built with Three.js and WebAudio, featuring 1–4 player co-op multiplayer.

## Play Online
- **Live Game (GitHub Pages):** [https://polk730.github.io/akumu/](https://polk730.github.io/akumu/)

## Features
- **Public & Private 4-Player Parties:** Create a **Public Party** (`"<CreatorName> Party"`, listed live in the Reception Lounge browser for one-click joining) or a **Private Party** (joinable via 4-letter lobby code, including late-joining matches in progress).
- **Reception Waiting Table Customization & Host Controls:**
  - **3D Character Customization:** Pick your 1986 Coat Color (**Obsidian**, **Crimson**, **Emerald**, **Amber**, **Violet**) and 3D Headgear (**Fedora**, **Aviator Glasses**, **Walkman Headphones**, **Survivor Bandana**, or **None**).
  - **Ready Check & Host Controls:** Guests toggle a **`READY`** stamp before the match starts; the host can promote another guest to Host (`★ HOST`) or remove guests (`✕ KICK`).
- **Shared Evidence Clipboard (`TAB`):** Pull up an animated 1986 brass-clip investigation clipboard with auto-pinned room clues and a live squad field-notes input box.
- **3D Item Pass & Swap (`G`):** Look at any nearby teammate while holding a key, wrench, hammer, wooden crate, VHS tape, washer dial knob, or coffee cup and press `G` to toss it directly into their hands (or swap items in mid-air if they're already holding one).
- **Shared Co-op Puzzle Progression:** All locks, doors, storage terminal stages, crates, vents, and laundry/basement puzzles synchronize live across all players.
- **1986 Walkie-Talkie Proximity Radio:** Built-in WebRTC voice chat with a 1986 radio bandpass filter, squelch SFX, and proximity volume (supports Open Mic with `M` to mute or Push-to-Talk by holding `V`).
- **Smart Context Pings & Emote Wheel:** Press `B` (or `1`–`4`) to emote or point at any puzzle object in the room to spawn a 3D context label and highlight the object for teammates.
- **Co-op Squad Ending Report & Former Guests Speedrun Ledger (`🏆 LEDGER`):** Post-escape breakdown of each player's stats and 1986 survivor titles, plus a persistent speedrun leaderboard on the main menu.

## Automatic Itch.io Deployment (Optional)
This repository includes `.github/workflows/deploy-itch.yml`. To enable automatic publishing to Itch.io on every push:
1. Go to your [Itch.io API Keys settings](https://itch.io/user/settings/api-keys) and generate an API key.
2. In this GitHub repository, go to **Settings → Secrets and variables → Actions** and add:
   - Secret `BUTLER_API_KEY`: Your Itch.io API key
   - Variable `ITCH_USER`: Your Itch.io username
   - Variable `ITCH_GAME`: Your Itch.io game slug (e.g. `akumu`)
