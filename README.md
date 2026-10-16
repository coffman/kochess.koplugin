# ♟ Kochess.koplugin  
**Play real chess on your e-reader — powered by Stockfish**

Turn your KOReader device into a focused, distraction-free chessboard.  
Kochess brings a full UCI chess engine, PGN support, clocks and analysis straight to your e-ink device.

No ads. No cloud. Just chess.

---

## Introduction

**Kochess — Chess Plugin for KOReader**
**Actively maintained Kochess plugin for KOReader**, designed for e-ink devices including Kobo, Kindle and other compatible readers.
Kochess lets you play chess against Stockfish, review PGN games, explore openings and analyze positions — entirely offline.
**Project status:** Actively maintained by Coffman.
**KOReader integration:** Available through KOReader Community Plugins.
Originally developed by bateast. This fork continues its development with new features, fixes and improvements.

---

## 🚀 Features

- ♞ Play against **Stockfish 11** (UCI engine)  
- ♛ Play against a friend in the same device
- 📖 Load and save games in **PGN** format  
- ⏳ Built-in **chess clocks** (time + increment)  
- 🔁 **Undo / Redo** full game history  
- 🧠 Shows **opening name** and **engine evaluation**  
- 👤 Configure **Human vs Engine** per color  
- 📂 File browser to load your own chess games  
- ✏️ Supports **comments and headers** from PGN  
- 🪶 Optimized for **e-ink devices** (Kobo, reMarkable)  
- ⚡ Works fully **offline**

---

## 📦 Installation

1. Copy the plugin folder to:
```
koreader/plugins/kochess.koplugin
```

2. Icons will be installed automatically into:

```
koreader/resources/icons/chess
```

3. Restart KOReader.  
4. Enable Kochess from:

```
Tools → More tools → Plugin management
```

---

## ♟ Launching Kochess

From KOReader:

```
Tools → Chess Game
```

A new game starts automatically with Stockfish ready.

You will see:

- The **chessboard**  
- The **PGN move list**  
- The **clocks and engine status**  
- The **opening name and evaluation**

---

## 📱 Interface Overview

Kochess is designed for clarity and e-ink readability.  
The screen is divided into four functional areas:

**Title Bar (Top)**  
Shows the plugin name and quick access buttons (menu, settings, actions).

**Chess Board (Center)**  
The main board where all moves are played.  
Tap pieces and squares to move.

**PGN Log and Toolbar (Below the board)**  
The left side shows the move list in standard algebraic notation.  
The right side contains the main control buttons (undo, redo, save, load).

**Status Bar (Bottom)**  
Displays:
- Player to move  
- Remaining time for both sides  
- Game state (playing, paused, finished)

Below the status bar, Kochess also shows:
- The detected opening  
- The engine evaluation of the current position


---

## 🕹️ Playing a Game

### Making a Move

1. Tap a piece  
2. Tap the destination square  
3. The move is executed and logged  
4. Stockfish replies when it is its turn  

### Pawn Promotion

When a pawn reaches the last rank, a dialog appears.  
Choose **Queen, Rook, Bishop or Knight**.

---

## ⏳ Game Clocks

Each side has a real chess clock.

- Time starts after the first move  
- Supports **time + increment**  
- Displayed in the **status bar**

Status icons:

- ⤆ White to move  
- ⤇ Black to move  
- ⤊ Paused or reset  

---

## 📜 PGN System

Kochess is built around real chess files.

### 💾 Save a Game  
Tap the **bookmark icon**  
Choose folder and filename (`.pgn` added automatically)

### 📂 Load a Game  
Tap the **file icon**  
Select any `.pgn` file  

Supported:

- Move history (SAN)  
- Headers (Event, Date, White, Black…)  
- Comments  
- Variations  

---

## 🧰 Toolbar

| Button | Action |
|--------|--------|
| ⬅ Undo | Tap: undo one move · Hold: rewind to start |
| ➡ Redo | Tap: redo one move · Hold: go to last |
| 🔖 Save | Save the current game to PGN |
| 📂 Load | Load a PGN file |

---

## ⚙️ Settings

Kochess allows full control of the game:

- Who plays **White** and **Black** (Human or Engine)  
- **Engine strength**  
- **Initial time**  
- **Time increment**

Settings are stored per game.

---

## 🧠 Chess Engine

Kochess uses **Stockfish 11** via UCI.

Optimized builds are provided for:

- Kobo  
- reMarkable  

Installed in:

```
koreader/plugins/kochess.koplugin/engines
```

---

## 📁 Game Storage

By default PGN games are saved in:

```
koreader/plugins/kochess.koplugin/Games
```

You can use any folder on your device.

---

## 🎬 Demo

See the demo video in the latest GitHub Release:

[**Kochess.4.Koreader.by.Coffmanv2.mp4**](https://github.com/user-attachments/assets/2d4b052f-0c1b-4174-9478-ad99800003a5)

---

## 🤝 Contributing

Pull requests, bug reports and feature ideas are welcome.  
If you improve UI, engine integration or PGN handling, please contribute.

---

## 📄 License and Credits

**Kochess**  
© Victor Fariña  
GPL-3.0 or later  

Based on the original **kochess** by Baptiste Fouques  
(continued after long inactivity)

Chess logic provided by:  
https://github.com/arizati/chess.lua  

Icons derived from:  
Colin M. L. Burnett (GPLv2+)

---

## ♟ Why Kochess?

Because e-readers are perfect for chess.

No glare.  
No notifications.  
No distractions.  

Just you, Stockfish and the board.
