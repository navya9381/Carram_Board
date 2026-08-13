# 🎯 Realistic 4-Player HTML5 Carrom Board Game

A lightweight, single-file 4-player Carrom Board Game simulation built with pure **HTML5 Canvas**, **CSS3**, and **Vanilla JavaScript** (No external libraries or heavy dependencies required).

It features a realistic wooden board finish, accurate 2D elastic collision physics, intuitive pull-to-aim (slingshot) controls, and an automatic turn-switching mechanism for 4 players.

---

## ✨ Features

* 🪵 **Realistic Wood Design:** Textured felt playing surface, corner pockets, and 3D-shaded acrylic carrom coins.
* 👥 **4-Player Multiplayer:** Dedicated baselines for 4 players (Bottom, Left, Top, Right).
* 🔄 **Automatic Turn Switch:** If a player fails to pocket a coin or commits a foul, the turn automatically passes to the next member ($P1 \rightarrow P2 \rightarrow P3 \rightarrow P4$).
* 🎯 **Tactile Drag & Flick Controls:** Pull back on the striker like a slingshot with visual trajectory aiming lines (works with mouse and touch devices).
* ⚙️ **Custom Physics Engine:** Realistic momentum transfer, friction deceleration, and corner pocket detection.
* 📊 **Live Scoreboard & Status:** Displays active player highlights, pocketed coins list, and score tracking.

---

## 🎮 How to Play

1. **Position the Striker:** Use the **Baseline Slide** slider or drag horizontally near your player's baseline to align your shot.
2. **Aim & Power:** Click/touch directly on the blue striker and drag **backwards** (away from the target). A red pull line and blue dashed trajectory vector will appear.
3. **Shoot:** Release your mouse or finger to flick the striker forward.
4. **Scoring:**
   * **White Coin:** 20 Points
   * **Black Coin:** 10 Points
   * **Red Queen:** 50 Points
   * **Striker Foul:** -5 Points
5. **Turn Rules:**
   * Pocketing a valid coin grants you an **extra turn**.
   * Missing all pockets or sinking the striker ends your turn and hands control to the next player.

---

## 🚀 Quick Start / Installation

Because this is built as a self-contained web app, no setup or installation commands are required!

### Option 1: Local Setup
1. Clone this repository:
   ```bash
   git clone [https://github.com/navya9381/carrom-board-game.git](https://github.com/navya9381/carrom-board-game.git)
