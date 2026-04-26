# 🏀 HOOPS: 1 ON 1

A fast-paced, fully-featured basketball 1v1 game built entirely in vanilla JavaScript with procedurally generated music and sound effects. No external assets—pure Web Audio synthesis.

**[🎮 PLAY THE GAME HERE](https://astrophyd.github.io/basketball-1v1/)** ← Click to play!

![Game Preview](https://img.shields.io/badge/Play%20Now-Live-brightgreen?style=for-the-badge&logo=github)

---

## 🎮 Features

### Three Game Modes
- **🎓 Career Mode** - Progress through 5 stages with 30 challenging levels
- **🏀 Free Play** - Quick 1v1 matches with 4 difficulty levels (Rookie → Legend)
- **🏆 Tournament** - 8-team single-elimination bracket (first to 7)

### Gameplay Mechanics
- ⚙️ **Realistic Physics** - Gravity, ball drag, and collision detection
- 🤖 **Adaptive AI** - CPU opponents react to difficulty levels
- 📊 **Shot Meter** - Release in the green zone for a swish
- 🎯 **Multiple Skills** - Shooting, stealing, defending, dunking, layups
- 🎪 **6 Unique Characters** - Unlock new players with different stats
- 💾 **Career Persistence** - Your progress saves automatically

### Audio & Visuals
- 🎵 **Procedurally Generated Music** - Glam rock menu theme + hip-hop game beat
- 🔊 **15+ Dynamic Sound Effects** - All synthesized, no files needed
- 🎨 **Polished UI** - Neon theme, animations, and effects
- 👥 **Stadium Crowd** - Generated crowd of 380 spectators

---

## 🎮 Controls

| Action | Key |
|--------|-----|
| Move | `A` / `D` |
| Jump | `W` |
| Crouch | `S` |
| Sprint | `Shift` |
| Shoot | `Space` (hold & release) |
| Steal | `E` |
| Dunk | `Q` (free-throw line only, 50/50 chance) |

**Tip:** Release your shot in the **green zone** on the meter for a guaranteed make!

---

## 🚀 Getting Started

### Play Online
Simply visit: **https://astrophyd.github.io/basketball-1v1/**

### Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/Astrophyd/basketball-1v1.git
   cd basketball-1v1
   ```

2. Open `index.html` in your browser:
   ```bash
   # Mac/Linux
   open index.html
   
   # Windows
   start index.html
   ```

Or use a local server:
```bash
python -m http.server 8000
# Then visit http://localhost:8000
```

---

## 🎯 Game Modes Explained

### Career Mode 🎓
Progress through a structured career with increasingly difficult opponents:
- **Stage 1: Fundamentals** - Learn the basics (scoring, defense, steals)
- **Stage 2: Rising Star** - Master mid-range and 3-point shots
- **Stage 3: All-Star** - Elite timing and clutch performance
- **Stage 4: Pro League** - Isolation plays and late-game execution
- **Stage 5: Championship** - Win a 7-game series to become champion

Each stage has 6 levels with specific challenges and tips.

### Free Play 🏀
Quick 1v1 matches against 4 difficulty levels:
- **Rookie** ★☆☆☆ - Great for learning
- **Pro** ★★☆☆ - Moderate challenge
- **All-Star** ★★★☆ - Hard difficulty
- **Legend** ★★★★ - Extreme challenge

First to 11 wins using street rules.

### Tournament 🏆
8-team single-elimination bracket featuring legendary players:
1. **YOU** (your player)
2. **DEREK** (Rookie level)
3. **MARCUS** (Pro level)
4. **KENNY** (All-Star level)
5. **TONY** (Elite)
6. **SAM** (Elite+)
7. **RAY** (Legend)
8. **THE KING** (Ultimate boss - 97% accuracy!)

Win the tournament to prove you're the best!

---

## 🎭 Playable Characters

Unlock new characters by completing career stages. Each has unique stats:

| Character | Unlock | Speed | Jump | Shooting | Stealing |
|-----------|--------|-------|------|----------|----------|
| **Rookie** | Start | 1.0x | 1.0x | 1.0x | 1.0x |
| **John Curry** 🟡 | Stage 1 | 1.0x | 0.9x | 1.55x | 0.70x |
| **Jordan James** 🔴 | Stage 2 | 1.15x | 1.35x | 1.10x | 1.20x |
| **Grant Gryant** 🟣 | Stage 3 | 1.30x | 1.10x | 0.85x | 1.55x |
| **Larry Eagle** 🩵 | Stage 4 | 0.80x | 0.85x | 1.65x | 1.0x |
| **Mr. Hooper** 🟠 | Stage 5 | 0.70x | 1.65x | 0.90x | 1.45x |

---

## 🔧 Technical Stack

- **Language:** Vanilla JavaScript (ES6+)
- **Graphics:** HTML5 Canvas
- **Audio:** Web Audio API (procedural synthesis)
- **Storage:** LocalStorage for career progression
- **Size:** Single HTML file (~132KB)
- **No Dependencies:** 100% self-contained

### Architecture Highlights
- **Game Loop:** 60 FPS render + physics update
- **Physics:** Gravity, collision detection, ball trajectory
- **AI System:** 4 difficulty tiers with reactive decision-making
- **Audio Synthesis:** 
  - Kick, snare, hi-hats, bass, guitar chords, lead synth
  - Pentatonic scales and dynamic filtering
  - Full BPM-locked music scheduling

---

## 📈 Tips & Tricks

1. **Master the Green Zone** - The sweet spot on the shot meter determines makes/misses
2. **Create Space** - Sprint past defenders before shooting for easier shots
3. **Defensive Positioning** - Stay between your opponent and the hoop
4. **Use Steals** - Press `E` to take the ball from the CPU
5. **Dunk Power** - Attempt dunks from the free-throw line (50/50 success rate)
6. **Career Tips** - Each level has a specific tip shown in the level select

---

## 🐛 Known Limitations

- Single-file implementation means large file size
- No mobile touch controls (keyboard only)
- No multiplayer (CPU only)
- Career progress tied to browser storage (clears if cache is emptied)

---

## 🎨 Credits

**Game Design & Development:** ASTROPHYD

Created with ❤️ as a complete web game experience.

---

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

## 🌟 Support

- ⭐ Star this repo if you enjoyed the game!
- 🐛 Found a bug? Open an issue
- 💡 Have ideas? Feel free to discuss in issues
- 🔄 Want to contribute? Fork and submit a PR

---

**Enjoy the game and dominate the court! 🏀**
