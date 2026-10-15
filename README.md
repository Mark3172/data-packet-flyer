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

- **Endless Cyber Gauntlet**: Fly continuously through the infinite cyber mainframe without arbitrary stop limits. Track your lifetime best and firewalls cleared in real time!
- **3-Life Data Integrity System**: No unfair instant deaths! The packet has 3 Integrity points. Hitting an obstacle deducts 1 integrity and grants a generous ~1.4-second invulnerability grace flicker.
- **Rare Magnetic Data Nodes**: Glowing green Data Nodes now spawn rarely (~18% chance, ~1 in 5 firewalls), rewarding skilled navigation. Proximity magnetism draws them to your packet when within 90px.
- **High-Value Repair & Breaker Shield**: Each rare node awards +50 points. Harvesting 3 Data Nodes restores +1 Integrity life and charges a **5.0-second Breaker Shield** allowing you to smash straight through firewalls!
- **Feather-Light Thrust**: Press <kbd>Space</kbd>, <kbd>↑</kbd>, <kbd>W</kbd>, <kbd>J</kbd>, or **Click / Tap** to give the packet an effortless, nimble upward lift against gentle gravity.
- **Selectable Pacing / Difficulty**: Choose between **Relaxed (0.8x)**, **Standard (1.0x)**, and **Overclock (1.3x)** to match your preferred flow.
- **Dynamic Phase Escalation (Harder at 10+)**: 
  - **Walls 1–9 (Infiltration)**: Accessible runway with wide 215px gates and static firewalls to build combo and gather momentum.
  - **Wall 10+ (Security Level 2 Lockdown)**: Sudden +30% speed surge, alarm alert, tighter 184px gaps, closer obstacle spacing (340px), and dynamic **Moving Firewalls** that oscillate vertically (marked with glowing amber chevrons and ▲▼ motion arrows)!
  - **Wall 20+ (Deep Core Overclock)**: High-tension endless overclock (+50% speed, 75% moving firewalls, continuous rhythmic escalation).

---

## 🕹️ Controls & Mechanics

| <kbd>Space</kbd> / <kbd>↑</kbd> / <kbd>W</kbd> / **Left Click** | **Vertical Thrust** | Feather-light upward impulse with responsive, smooth tilting. |
| <kbd>ESC</kbd> | **Pause & Settings Menu** | Pause the game mid-run to change difficulty pace (0.8x / 1.0x / 1.3x), toggle audio, edit call sign, restart, or return to the main menu. |
| <kbd>L</kbd> | **Squad Leaderboard** | Open the 35/65 Hall of Fame modal to view rankings, name your squad, and invite friends. |
| <kbd>Q</kbd> | **Leave Run / Main Menu** | Return to the Title screen when dead or paused, or click **Leave Game** to exit session. |
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

- **Pure Endless Gauntlet**: Seamless endless flight where your distance and score scale indefinitely with deep-core speed milestones at 10 and 20+ firewalls.
- **3-Life Data Integrity System**: High tolerance gameplay with 3 HP and visual glitch/flicker grace periods, preventing frustrating one-hit game overs.
- **Rare Powerup Nodes & Breaker Shield**: Strategic powerups appearing ~1 in 5 firewalls that reward players with +50 points, +1 HP repair, and high-impact firewall smashing.
- **Tuned, Balanced Physics**: Accessible learning curve with wider firewall gates (215px+), spacious obstacle spacing (410px+), and forgiving near-miss hitboxes (5.5px).
- **Full In-Game Pause & Settings Menu (<kbd>ESC</kbd>)**:
  - **Mid-Flight Pacing Control**: Switch between Relaxed (0.8x), Standard (1.0x), and Overclock (1.3x) on the fly during a run.
  - **Audio & Profile Controls**: Toggle procedural Web Audio sound FX and edit Pilot Call Sign anytime.
  - **Quick Run Restarts & Clean Exits**: One-click restart, squad leaderboard check, or return to the main menu.
- **35/65 Split Grid Menus**: Modern split-card start, pause, leaderboard, and game-over modals displaying live telemetry, controls, and run statistics.
- **Translucent Frosted Glass HUD**: Sleek floating cards powered by `backdrop-filter: blur(16px)` housing scores, Integrity health pips, real-time firewalls cleared counter, clock speed, and segmented combo meters.
- **Visual FX & Screen Shake**: Luminescent particle trails, shattering firewall voxels, and a 22px screen shake when smashing through obstacles.
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
