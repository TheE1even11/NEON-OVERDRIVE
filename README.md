# 🏎️⚡ NEON OVERDRIVE // Cyber Typing Racer

[![Version](https://img.shields.io/badge/Version-1.0-00f0ff?style=for-the-badge&logo=semver&logoColor=black)](https://github.com/Thee1even11/NEON-OVERDRIVE)
[![Status](https://img.shields.io/badge/Status-Live-39ff14?style=for-the-badge)](https://thee1even11.github.io/NEON-OVERDRIVE/)
[![Platform](https://img.shields.io/badge/Platform-Web%20%7C%20Mobile%20%7C%20Desktop-ff0077?style=for-the-badge)](#controls)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-ffe600?style=for-the-badge)](https://www.gnu.org/licenses/gpl-3.0)

> **Burn rubber across a synthwave cyberspace highway. Type the decryption phrases hovering above rival drones to trigger Nitro Overdrive and outrun the grid.**

🎮 **Play Instantly in Browser:** [https://thee1even11.github.io/NEON-OVERDRIVE/](https://thee1even11.github.io/NEON-OVERDRIVE/)

---

## 🕹️ Gameplay & Core Loop

**NEON OVERDRIVE** blends high-octane 80s arcade racing with precision touch and keyboard typing mechanics. Rival drones cruise down the digital grid; match and type their hovering code-strings to blast past them. Chaining error-free words unleashes maximum nitro speed and scales your multiplier up to **x4.0**.

### 🌟 Key Features

- **Pseudo-3D Perspective Engine:** Custom-built hardware-accelerated Canvas renderer creating dynamic highway depth, banking turns, and animated grid bands without heavy 3D frameworks.
- **Pure Synthesized Web Audio:** Zero external audio files to download or break. Dynamic polyphonic chimes, thruster blasts, impact rumbles, and typo alerts generated procedurally in real-time.
- **Dual Control Scheme (Desktop & Mobile):**
  - **Desktop:** Physical keyboard targeting with auto-lock, backspace support, and quick hotkeys (`Space`, `Esc`, `R`).
  - **Mobile / Tablet:** Dedicated, non-dismissing cyber input field for native OS keyboards + an optional on-screen virtual cyber keypad.
- **Juicy Feedback:** Trauma-based camera shake, nitro exhaust plumes, and exploding neon debris shards on word completion.
- **Strict Drone Pacing & Anti-Lag Optimization:** Intelligent lane distribution and pacing distance buffers that prevent traffic jams and maintain a solid 60 FPS on low-power mobile devices.
- **Complete Menu Lifecycle:** Interactive Start Screen, Pause Menu, "How to Play" Guide, Game Over statistics, and local high-score persistence via `localStorage`.

---

## ⌨️ Controls

### Desktop Controls
| Key | Action |
| :--- | :--- |
| **A – Z** | Type matching characters of the target drone |
| **Backspace** | Undo mistyped characters |
| **Space / Enter** | Start game from Main Menu |
| **Esc** | Pause / Resume race |
| **R** | Quick restart (from Pause or Game Over screens) |

### Mobile Controls
- **Tap Input Bar:** Opens device native keyboard (stays docked without accidental dismissals).
- **Keyboard Toggle:** Switch between device keyboard mode and on-screen cyberpunk virtual keypad.
- **Touch Navigation:** Tap UI buttons directly for instant menu access.

---

## 📦 Versioning Scheme

This project follows a strict two-tier release and single hotfix convention:

- **`X.Y`** — Major & feature releases (e.g., `1.0`, `1.1`, `1.2`).
- **`X.Y1`** — The single designated hotfix release for that version (e.g., `1.01` for `1.0`, `1.11` for `1.1`, `1.21` for `1.2`).

Current Version: **`1.0`**

---

## 🛠️ Technology Stack

- **Markup & Styling:** Semantic HTML5, CSS3 Variables, Responsive Flexbox/Grid, CRT Scanline shader simulation.
- **Rendering:** HTML5 2D Canvas API with optimized vector drawing primitives.
- **Audio:** Web Audio API (`AudioContext`, `OscillatorNode`, `GainNode`).
- **Persistence:** Client-side HTML5 `localStorage`.
- **Dependencies:** **Zero.** (Vanilla JS, single-file deployable, 100% compatible with GitHub Pages).

---

## 🗺️ Roadmap & Upcoming Releases

- [ ] **v1.01 (Hotfix):** Mobile touch threshold polish and additional vocabulary sets.
- [ ] **v1.1:** Audio volume sliders, new vehicle skins, and customizable road synth palettes.
- [ ] **v1.11 (Hotfix):** Dedicated hotfix for v1.1.
- [ ] **v1.2:** Global online leaderboard integration via serverless database.

---

## 📄 License

This project is licensed under the **GNU General Public License v3.0 (GPL-3.0)**. See the [LICENSE](LICENSE) file for details.
