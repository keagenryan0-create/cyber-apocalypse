# 🤖 Cyber Apocalypse - Robot Survival Game & World Clock

Welcome to the ultimate web experience! This project includes two amazing applications:

## 🎮 **Game Mode - Cyber Apocalypse**

A cyberpunk-themed bullet-hell survival game where you battle robots in a digital apocalypse.

### How to Play
- **WASD** - Move your ship
- **SPACEBAR** - Shoot  
- **Touch Screen** - Tap to shoot (mobile)

### Features
- ✅ Intense survival gameplay
- ✅ Progressive weapon leveling
- ✅ Boss encounters (10% spawn rate)
- ✅ Health/healing system
- ✅ Sound effects & visuals
- ✅ Mobile-friendly controls

---

## 🕐 **Clock Mode - World Clock**

Real-time digital clock displaying the current time across 8 major cities around the globe.

### Cities Displayed
- 🗽 **New York** - America/New_York
- 🇬🇧 **London** - Europe/London
- 🗼 **Tokyo** - Asia/Tokyo
- 🇦🇺 **Sydney** - Australia/Sydney
- 🕌 **Dubai** - Asia/Dubai
- 🇸🇬 **Singapore** - Asia/Singapore
- 🇮🇳 **Mumbai** - Asia/Kolkata
- 🇧🇷 **São Paulo** - America/Sao_Paulo

### Features
- ✅ Real-time updates (every second)
- ✅ Displays time, date, and timezone
- ✅ Beautiful gradient UI
- ✅ Responsive design
- ✅ Hover effects

---

## 🚀 **Getting Started**

### Play Online
Visit the deployed site at: **[https://keagenryan0-create.github.io/cyber-apocalypse/](https://keagenryan0-create.github.io/cyber-apocalypse/)**

### Run Locally

```bash
# Clone the repository
git clone https://github.com/keagenryan0-create/cyber-apocalypse.git
cd cyber-apocalypse

# Install dependencies
npm install

# Start development server
npm start
```

The app will open at `http://localhost:3000`

### Build & Deploy

```bash
# Build for production
npm run build

# Deploy to GitHub Pages
npm run deploy
```

---

## 🛠 **Technologies Used**

- **React 18** - Modern UI framework
- **Tailwind CSS** - Utility-first styling
- **HTML5 Canvas** - Game graphics
- **Web Audio API** - Sound effects
- **GitHub Pages** - Hosting

---

## 📁 **Project Structure**

```
cyber-apocalypse/
├── public/
│   └── index.html              # HTML entry point
├── src/
│   ├── index.js                # React root
│   ├── Home.js                 # App switcher
│   ├── App.js                  # Game component
│   └── DigitalClock.js         # Clock component
├── package.json                # Dependencies
├── README.md                   # This file
└── .gitignore                  # Git ignore rules
```

---

## 🎯 **Features & Controls**

### Game Controls
| Key | Action |
|-----|--------|
| **W** | Move Up |
| **A** | Move Left |
| **S** | Move Down |
| **D** | Move Right |
| **SPACE** | Shoot |
| **Touch** | Shoot (Mobile) |

### Gameplay Mechanics
- Enemies spawn continuously from the top
- Boss enemies (magenta) appear randomly (10% chance)
- Collect green health pickups to restore HP
- Weapon levels increase every 100 points
- Game ends when health reaches 0

---

## 📊 **Scoring System**

- **Enemy Kill** - +10 points
- **Weapon Upgrade** - Every 100 points
- **Health Restore** - +20 HP (max 100)
- **Damage** - -10 HP per collision

---

## 🔧 **Configuration**

### GitHub Pages Settings
The site is configured to deploy from the `gh-pages` branch automatically when you run `npm run deploy`.

### Custom Domain (Optional)
To use a custom domain:
1. Go to Repository Settings → Pages
2. Select your custom domain
3. Follow GitHub's verification steps

---

## 📝 **License**

MIT License - Feel free to use and modify!

---

## 👨‍💻 **Author**

Created by **keagenryan0-create**

---

## 🐛 **Found a Bug?**

Report issues on the [GitHub Issues](https://github.com/keagenryan0-create/cyber-apocalypse/issues) page.

---

## 🌟 **Support**

If you enjoy this project, please give it a star! ⭐

Made with ❤️ and lots of cyan lasers 🔫✨
