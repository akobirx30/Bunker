# ⚠️ BUNKER - Multiplayer Survival Game

A web-based multiplayer card game where players must convince others they deserve a spot in a bunker during a global catastrophe. Only 2 players will survive!

![Bunker Game](https://img.shields.io/badge/Players-4--12-yellow) ![Mobile Friendly](https://img.shields.io/badge/Mobile-Friendly-green) ![No Server Required](https://img.shields.io/badge/Server-Not%20Required-blue)

## 🎮 Features

- **Multiplayer**: 4-12 players can join from their phones
- **Room System**: Create or join rooms with 6-character codes
- **Private Cards**: Each player only sees their own cards
- **8 Card Types**: Profession, Age, Gender, Health, Skills, Traits, Baggage, Unique
- **Voting System**: Democratic elimination with automatic tie-breaking
- **6 Catastrophes**: Random disaster scenarios
- **Mobile Optimized**: Fully responsive design for phones
- **Real-time Sync**: All players see updates automatically
- **Industrial Design**: Black and yellow bunker-themed UI ⚠️

## 🚀 How to Play

1. **Setup**
   - One player creates a room and shares the code
   - Other players join using the room code
   - Everyone enters their nickname
   - Minimum 4 players required to start

2. **Round 1**
   - All players reveal their PROFESSION card
   - No voting this round

3. **Rounds 2-5**
   - Each player reveals ONE card of their choice
   - Discussion phase (use voice chat externally)
   - Vote to eliminate one player
   - Continue until 2 survivors remain

4. **Finale**
   - The 2 remaining players have survived!
   - All cards are revealed

## 💾 Installation

### Option 1: Direct Use
Simply open `bunker-website.html` in any modern web browser. No installation required!

### Option 2: Host Online
1. Upload `bunker-website.html` to any web hosting service
2. Share the URL with players
3. Everyone opens the link on their phones

### Option 3: Local Server
```bash
# Python 3
python -m http.server 8000

# Node.js
npx serve

# Then open http://localhost:8000/bunker-website.html
```

## 📱 Compatible Devices

- ✅ iPhone (Safari, Chrome)
- ✅ Android (Chrome, Firefox)
- ✅ Desktop (Chrome, Firefox, Safari, Edge)
- ✅ Tablets

## 🎯 Game Cards

### Character Cards
- **💼 Profession**: Doctor, Engineer, Soldier, Teacher, etc.
- **📅 Age**: 18-70 years old
- **👤 Gender/Status**: Single, Married, Divorced, etc.
- **❤️ Health**: Excellent Health, Diabetes, Asthma, etc.
- **⚡ Skills**: Expert Hunter, Master Gardener, Programming, etc.
- **🎭 Personality**: Natural Leader, Loyal, Quick Thinker, etc.
- **🎒 Baggage**: First Aid Kit, Solar Generator, Weapons, etc.
- **⭐ Unique**: Mutations, Phobias, Secrets, Legends

### Catastrophes
- ☢️ Nuclear World War
- 🧟 Zombie Virus Outbreak
- ☄️ Asteroid Impact Winter
- 🤖 AI Robot Uprising
- 🌋 Supervolcano Eruption
- 🦠 Deadly Pandemic

## 🎨 Design Features

- **Industrial Aesthetic**: Black background with yellow warnings
- **Hazard Stripes**: Diagonal warning pattern background
- **Retro-Future Fonts**: Share Tech Mono + Russo One
- **Glowing Effects**: Yellow shadows and borders
- **Animated Elements**: Pulsing alerts and smooth transitions
- **Mobile-First**: Touch-friendly buttons and responsive layout

## 🔧 Technical Details

- **No Backend Required**: Uses browser's persistent storage API
- **Real-time Sync**: Automatic polling every 2 seconds
- **Offline Capable**: Works without internet after initial load
- **Lightweight**: Single HTML file (~25KB)
- **Modern JavaScript**: ES6+ features
- **CSS Animations**: Smooth, performant animations

## 🎭 Recommended Voice Chat Apps

Use any voice chat app alongside the game:
- Discord
- Zoom
- Google Meet
- WhatsApp Call
- Telegram Call
- Any conference call app

## 🌐 Browser Requirements

- Modern browser with JavaScript enabled
- LocalStorage support
- CSS Grid/Flexbox support
- Recommended: Chrome 90+, Firefox 88+, Safari 14+

## 📋 Game Rules

### Round Structure
1. **Lobby**: Wait for all players (4-12)
2. **Round 1**: Reveal Profession (no voting)
3. **Round 2-5**: Reveal 1 card → Discuss → Vote → Eliminate
4. **Finale**: 2 survivors remain

### Voting Rules
- All players vote (including eliminated players)
- Player with most votes is eliminated
- Ties trigger automatic revote
- Cannot vote for yourself
- Votes are anonymous until counted

### Winning
- The 2 players who survive all rounds WIN
- All other players are eliminated

## 🤝 Contributing

Feel free to fork and improve! Some ideas:
- Add more card types
- New catastrophe scenarios
- Additional game modes
- UI themes
- Sound effects
- Chat system integration

## 📄 License

MIT License - Feel free to use and modify!

## 🎮 Credits

Based on the original "Bunker" card game concept.
Digital adaptation with multiplayer functionality.

## 🐛 Known Issues

- Players must manually refresh if disconnected
- Room codes expire if inactive for long periods
- Works best with stable internet connection

## 💡 Tips for Best Experience

1. Use voice chat for discussion (Discord recommended)
2. Play on WiFi for stable connection
3. Landscape mode on phones for better view
4. Close other browser tabs for performance
5. Keep the tab active during your turn
6. Screenshot your room code to share easily

## 📞 Support

Found a bug? Have suggestions? Open an issue on GitHub!

---

**⚠️ Remember: This is a game. Keep emotions in-game only. Have fun!**

Enjoy your survival experience! 🎮
# Bunker
