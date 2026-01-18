# 🔐 Hacker Terminal - Security Grid Breach

![Version](https://img.shields.io/badge/version-1.0.0-green)
![License](https://img.shields.io/badge/license-MIT-blue)
![Status](https://img.shields.io/badge/status-active-success)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

An immersive hacker-themed memory matching game with retro terminal aesthetics, featuring a warning system, boot sequence, and competitive leaderboard.

<p align="center">
  <img src="https://img.shields.io/badge/Game-Hacker%20Terminal-brightgreen?style=for-the-badge&logo=gnuprivacyguard" alt="Game Badge">
</p>

---

## 📸 Screenshots

```
⚠️  WARNING SCREEN → 💻 BOOT SEQUENCE → 📋 INSTRUCTIONS → 🎮 GAME → 🏆 RESULTS
```

## 🎮 Overview

**Hacker Terminal - Security Grid Breach** is a browser-based memory matching game where you play as an elite operative infiltrating a classified system. Your mission: decrypt the security grid by matching 12 pairs of code symbols before time runs out.

**🎯 Play Now:** Just download and open `index.html` in your browser!

---

---

## 🚀 Quick Start

### Method 1: Download and Play Locally
```bash
# Clone the repository
git clone https://github.com/mprshark/hacker-terminal-game.git

# Navigate to the directory
cd hacker-terminal-game

# Open in browser
open index.html
# or double-click index.html
```

### Method 2: GitHub Pages (Live Demo)
Visit: `https://mprshark.github.io/hacker-terminal-game/`

### Method 3: Download ZIP
1. Click the green "Code" button above
2. Select "Download ZIP"
3. Extract and open `index.html`

**That's it!** No installation, no dependencies, no server required. 🎉

---

## ✨ Features

### 🎯 Core Gameplay
- **Memory Matching Game**: Match 12 pairs (24 blocks) of identical symbols
- **60-Second Timer**: Race against the clock to complete your mission
- **Random Symbol Generation**: Each game features randomized symbols from a pool of 20+ options
- **Dynamic Difficulty**: Symbols and positions randomize every playthrough

### 🖥️ Interface & Design
- **Retro Terminal Aesthetic**: Authentic CRT monitor effect with scanlines
- **Neon Green Matrix Theme**: Classic hacker color palette
- **Warning Screen**: Immersive "play at your own risk" disclaimer
- **Boot Sequence**: Realistic system initialization with progress bar
- **Mission Briefing**: Clear instructions in terminal format

### 🏆 Leaderboard System
- **Top 10 Best Penetrators**: Competitive ranking by completion time
- **Persistent Storage**: Scores saved in browser localStorage
- **Submit Your Score**: Enter your operative name after winning
- **Real-time Updates**: Leaderboard updates instantly with new scores

### 🎨 Visual Effects
- **CRT Scanlines**: Authentic retro monitor effect
- **Glowing Text**: Neon text shadows and animations
- **Pulse Animations**: Warning indicators and time-critical alerts
- **Smooth Transitions**: Polished screen transitions and card flips
- **Responsive Design**: Works on desktop, tablet, and mobile

## 📋 Game Flow

```
1. ⚠️  WARNING SCREEN
   └─> Accept risks & legal disclaimer

2. 💻 BOOT SEQUENCE  
   └─> System initialization & loading

3. 📋 TERMINAL INSTRUCTIONS
   └─> Mission briefing & leaderboard
   
4. 🎮 GAMEPLAY
   └─> Match 12 pairs in 60 seconds
   
5. 🏆 GAME OVER
   └─> Success/Failure + Score submission
```

## 🎯 How to Play

### Objective
Match all 12 pairs of identical symbols before the 60-second timer expires.

### Controls
1. **Click any block** to reveal its symbol
2. **Click a second block** to reveal another symbol
3. **Match found** → Both blocks stay revealed (green glow)
4. **No match** → Both blocks flip back (red shake)
5. **Win condition** → All 12 pairs matched before timer expires
6. **Lose condition** → Timer reaches zero before all pairs are matched

### Tips for Success
- 🧠 **Memorize positions** of symbols you've seen
- ⚡ **Work systematically** - don't click randomly
- 🎯 **Stay focused** - time pressure increases mistakes
- 💡 **Start with corners** for easier tracking
- ⏱️ **Manage time** - you have 60 seconds total

## 🚀 Getting Started

### Installation

#### Option 1: Clone Repository (Recommended)
```bash
git clone https://github.com/mprshark/hacker-terminal-game.git
cd hacker-terminal-game
open index.html  # macOS
start index.html # Windows
xdg-open index.html # Linux
```

#### Option 2: Download ZIP
1. Click the green **"Code"** button on this repository
2. Select **"Download ZIP"**
3. Extract the ZIP file
4. Open `index.html` in your browser

#### Option 3: Fork and Deploy
1. Fork this repository
2. Go to Settings → Pages
3. Select main branch as source
4. Your game will be live at `https://yourusername.github.io/hacker-terminal-game/`

### Browser Compatibility

✅ **Recommended Browsers:**
- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Opera 76+

### System Requirements
- Any modern device (PC, Mac, tablet, smartphone)
- JavaScript enabled
- Minimum 1024x768 screen resolution (responsive to all sizes)

## 📁 File Structure

```
hacker-terminal-game/
│
├── index.html              # Main game file (standalone)
├── README.md              # This file
└── LICENSE                # MIT License
```

**Note:** All game code (HTML, CSS, JavaScript) is contained in a single `index.html` file for easy deployment and portability.

---

## 🛠️ Tech Stack

- **Frontend:** Vanilla HTML5, CSS3, JavaScript (ES6+)
- **Fonts:** Google Fonts (VT323, Share Tech Mono)
- **Storage:** Browser localStorage API
- **Dependencies:** None! Pure vanilla code
- **Size:** ~35KB total

---

## 🏆 Leaderboard

The game features a **Best Penetrators** leaderboard that tracks the top 10 fastest completion times (displays top 5 in-game).

### Default Leaderboard (Can be beaten!)

| Rank | Operative Name   | Time | Date       |
|------|-----------------|------|------------|
| 🥇 1 | GHOST_PROTOCOL  | 28s  | 2026-01-15 |
| 🥈 2 | CIPHER_QUEEN    | 31s  | 2026-01-14 |
| 🥉 3 | SHADOW_BYTE     | 34s  | 2026-01-13 |
| 4    | NEON_HACKER     | 37s  | 2026-01-12 |
| 5    | ZERO_DAY        | 39s  | 2026-01-11 |

*Top 5 shown in-game, top 10 tracked in localStorage*

### How Leaderboard Works
- **Automatic Saving**: Scores stored in browser's localStorage
- **Top 10 Only**: Only the best 10 times are displayed
- **Persistent**: Scores persist across browser sessions
- **Per Browser**: Leaderboard is local to each browser/device
- **Reset Option**: Clear browser data to reset leaderboard

## 🎨 Customization

### Modify Symbols
Edit the `symbolPool` array in the JavaScript section:
```javascript
const symbolPool = ['◈', '◊', '◆', '◉', '◎', '●', ...];
```

### Change Timer Duration
Modify the `timeLeft` variable:
```javascript
let timeLeft = 60; // Change to desired seconds
```

### Adjust Number of Pairs
Change the `totalPairs` variable:
```javascript
let totalPairs = 12; // Must have enough symbols!
```

### Color Scheme
Modify CSS variables at the top of the `<style>` section:
```css
:root {
    --neon-green: #00ff41;    /* Main theme color */
    --dark-green: #003b00;    /* Dark accents */
    --warning-red: #ff0000;   /* Warnings/errors */
    --warning-yellow: #ffff00; /* Highlights */
}
```

## 🐛 Troubleshooting

### Leaderboard Not Saving
- Ensure browser allows localStorage
- Check if browser is in private/incognito mode
- Try a different browser

### Game Not Starting
- Ensure JavaScript is enabled
- Clear browser cache and reload
- Check browser console for errors (F12)

### Visual Glitches
- Update your browser to the latest version
- Disable browser extensions temporarily
- Try a different browser

### Performance Issues
- Close other browser tabs
- Reduce browser zoom level
- Ensure hardware acceleration is enabled

---

## 🌐 Deploy on GitHub Pages

Want to host your own version? Follow these steps:

1. **Fork this repository**
   - Click the "Fork" button at the top right

2. **Enable GitHub Pages**
   - Go to your fork's Settings
   - Navigate to "Pages" in the left sidebar
   - Under "Source", select "main" branch
   - Click "Save"

3. **Access your game**
   - Your game will be live at: `https://yourusername.github.io/hacker-terminal-game/`
   - It may take a few minutes to deploy

4. **Share your link**
   - Share your custom game URL with friends!
   - Challenge them to beat your leaderboard

---

## 🔒 Privacy & Data

- **No Server Communication**: Game runs entirely in your browser
- **No User Tracking**: No analytics or tracking scripts
- **Local Storage Only**: Scores stored locally on your device
- **No Personal Data**: Only operative names (player-chosen) are stored

## 📜 License

This project is licensed under the MIT License - see below for details:

```
MIT License

Copyright (c) 2026 Hacker Terminal Game

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

### How to Contribute

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **Make your changes**
4. **Commit your changes**
   ```bash
   git commit -m "Add some amazing feature"
   ```
5. **Push to the branch**
   ```bash
   git push origin feature/amazing-feature
   ```
6. **Open a Pull Request**

### Contribution Ideas

- 🐛 Report bugs
- 💡 Suggest new features
- 🎨 Improve design/UI
- 📝 Fix typos in documentation
- 🔊 Add sound effects
- 🎮 Create new game modes
- ⭐ Star this repository

### Code Style

- Use clear, descriptive variable names
- Comment complex logic
- Test in multiple browsers
- Keep files organized

## 🎓 Credits

### Fonts
- **VT323** - Google Fonts (terminal display)
- **Share Tech Mono** - Google Fonts (body text)

### Design Inspiration
- Classic terminal/command-line interfaces
- 1980s cyberpunk aesthetic
- The Matrix movie series
- Retro CRT monitors

### Created By
**mprshark** - [github.com/mprshark](https://github.com/mprshark)

## 📞 Support

Having issues or questions? 

- 🐛 [Open an issue](https://github.com/mprshark/hacker-terminal-game/issues)
- 💬 [Check existing issues](https://github.com/mprshark/hacker-terminal-game/issues)
- ⭐ [Star the repository](https://github.com/mprshark/hacker-terminal-game)
- 🍴 [Fork and improve](https://github.com/mprshark/hacker-terminal-game/fork)

## 🎮 Future Features (Roadmap)

- [ ] Multiple difficulty levels (Easy/Medium/Hard)
- [ ] Sound effects and background music
- [ ] Additional game modes (Time Attack, Endless)
- [ ] Global online leaderboard
- [ ] Achievements system
- [ ] Custom symbol sets
- [ ] Dark/Light theme toggle
- [ ] Mobile app version
- [ ] Multiplayer mode

## 📊 Statistics

- **Lines of Code**: ~1000
- **File Size**: ~35KB
- **Load Time**: < 1 second
- **Dependencies**: 0 (vanilla JavaScript)

## 🌟 Show Your Support

If you enjoyed this game, please:
- ⭐ Star the repository
- 🍴 Fork and customize it
- 🐦 Share with friends
- 💬 Leave feedback

---

**⚠️ WARNING**: This is a game. No actual hacking occurs. Play responsibly and enjoy! 🎮

**Made with 💚 by the hacker community**

*Version 1.0.0 - January 2026*
# CodeBreaker
