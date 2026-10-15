# ⚡ DATA // PACKET — Cyber Flyer

> A highly polished, single-button endless flyer game built in pure HTML5 Canvas, CSS3, and JavaScript with zero external dependencies.

![HTML5 Canvas](https://img.shields.io/badge/HTML5-Canvas-00f3ff?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/Vanilla-JavaScript-f7df1e?style=for-the-badge&logo=javascript&logoColor=black)
![CSS3 Glassmorphism](https://img.shields.io/badge/CSS3-Frosted%20Glass-b545ff?style=for-the-badge&logo=css3&logoColor=white)
![Web Audio API](https://img.shields.io/badge/Audio-Web%20Audio%20API-00ffaa?style=for-the-badge)

---

- **Live Demo**: [Play on GitHub Pages](https://mark3172.github.io/data-packet-flyer/)

---

## 🎮 Gameplay Overview

Take control of a high-frequency **Data Packet** infiltrating the root mainframe in cyberspace.

- **Winnable 20-Firewall Mission**: Reach and breach the Mainframe by successfully clearing 20 firewalls to trigger a **VICTORY SCREEN**! Players can celebrate victory or continue into Endless Mode for high scores.
- **3-Life Data Integrity System**: No unfair instant deaths! The packet has 3 Integrity points. Hitting an obstacle deducts 1 integrity and grants a generous ~1.4-second invulnerability grace flicker.
- **Magnetic Data Nodes**: Glowing green Data Nodes are magnetically drawn toward your packet when within proximity (90px), ensuring rewarding pickups.
- **Repair & Breaker Shield**: Collecting 3 Data Nodes restores +1 Integrity and activates a **5.0-second Breaker Shield** to smash directly through firewalls!
- **Feather-Light Thrust**: Press <kbd>Space</kbd>, <kbd>↑</kbd>, <kbd>W</kbd>, <kbd>J</kbd>, or **Click / Tap** to give the packet an effortless, nimble upward lift against gentle gravity.
- **Selectable Pacing / Difficulty**: Choose between **Relaxed (0.8x)**, **Standard (1.0x)**, and **Overclock (1.3x)** to match your preferred flow.
- **Dynamic Phase Escalation (Harder at 10+)**: 
  - **Walls 1–9 (Infiltration)**: Accessible runway with wide 215px gates and static firewalls to build combo and gather momentum.
  - **Wall 10+ (Security Level 2 Lockdown)**: Sudden +30% speed surge, alarm alert, tighter 184px gaps, closer obstacle spacing (340px), and dynamic **Moving Firewalls** that oscillate vertically (marked with glowing amber chevrons and ▲▼ motion arrows)!
  - **Wall 20+ (Deep Core Overclock)**: High-tension endless overclock (+50% speed, 75% moving firewalls, rapid rhythm).

---

## 🕹️ Controls & Mechanics

| <kbd>Space</kbd> / <kbd>↑</kbd> / <kbd>W</kbd> / **Left Click** | **Vertical Thrust** | Feather-light upward impulse with responsive, smooth tilting. |
| <kbd>L</kbd> | **Squad Leaderboard** | Open the 35/65 Hall of Fame modal to view rankings, name your squad, and invite friends. |
| <kbd>ESC</kbd> | **Boss Stealth Key** | Instantly hides the game behind an authentic corporate **Windows System Update** screen. Press <kbd>ESC</kbd> or click the sleek **[ ↩ Return to Game ]** button to exit safely. |
| <kbd>M</kbd> | **Audio Toggle** | Toggle procedural Web Audio sound FX (muted by default for office safety). |

---

## 🏆 Squad Leaderboards & Friend Invites

- **Custom Call Signs**: Name your agent pilot (e.g. `MARK_01`, `ALEX`, `GHOST`) directly from the start screen or leaderboard hub.
- **Custom Squad / Leaderboard Names**: Name your squad leaderboard (e.g. `CYBER_SQUAD`, `TITAN_CREW`).
- **🔗 1-Click Friend Invite Link**: Click **Invite Friend Link** to copy a smart URL containing your squad and top scores. When friends open the link, they automatically join your named squad board!
- **📋 Squad Codes**: Copy and import portable squad codes across browsers and group chats (Discord, WhatsApp, Telegram).
- **🤖 Cyber Rivals Benchmark**: Compare your flight scores against legendary AI hacker benchmarks (`ROOT_DAEMON`, `ZERO_COOL`, `GHOST_NET`).

---

## ✨ Features

- **Winnable Mainframe Mission**: Defeat 20 firewalls to trigger the Root Mainframe Breached victory modal, complete with triumphant procedural synth chords.
- **3-Life Data Integrity System**: High tolerance gameplay with 3 HP and visual glitch/flicker grace periods, preventing frustrating one-hit game overs.
- **Magnetic Node Collection & Repair**: Gentle magnetic attraction draws nearby nodes into your path, granting points, repairs, and breaker shields.
- **Tuned, Balanced Physics**: Accessible learning curve with wider firewall gates (215px+), spacious obstacle spacing (410px+), and forgiving near-miss hitboxes (5.5px).
- **Interactive Pace Selector**: Seamlessly switch between Relaxed (0.8x), Standard (1.0x), and Overclock (1.3x) right on the start menu.
- **35/65 Split Grid Menus**: Modern split-card start, victory, and game-over modals displaying live telemetry, controls, and run statistics.
- **Translucent Frosted Glass HUD**: Sleek floating cards powered by `backdrop-filter: blur(16px)` housing scores, Integrity health pips, mission progress bar, clock speed, and segmented combo meters.
- **Visual FX & Screen Shake**: Luminescent particle trails, shattering firewall voxels, and a 22px screen shake when smashing through obstacles.
- **Office Stealth Mode**:
  - **Mute by default**: Procedural synth audio powered by Web Audio API without external audio files.
  - **Authentic Windows Update Boss Screen**: Realistic Segoe UI circular dot spinner and incrementing update percentage ticker that camouflages your gameplay, with an accessible **[ ↩ Return to Game ]** button or <kbd>ESC</kbd> shortcut.
- **Zero Dependencies**: 100% self-contained in a single, lightweight HTML file.

---

## 🚀 How to Run

Simply open `index.html` in any modern web browser (Chrome, Edge, Firefox, Safari). No build tools, servers, or npm packages required!

```bash
# Clone the repository
git clone https://github.com/Mark3172/data-packet-flyer.git

# Open in browser
cd data-packet-flyer
start index.html # On Windows
```

---

## 📄 License

MIT License. Free to use, modify, and distribute.
