BhekOS 6.0 - Modern Web-Based Operating System

https://img.shields.io/badge/BhekOS-6.0-blue
https://img.shields.io/badge/license-MIT-green
https://img.shields.io/badge/platform-Web-brightgreen
https://img.shields.io/badge/PWA-✓-success

BhekOS 6.0 is a fully functional, web-based operating system that runs directly in your browser. Built with modern web technologies, it provides a desktop-like experience with window management, applications, games, and security features.

🌟 Features

🖥️ Core System

· Full Desktop Environment - Complete with taskbar, start menu, and desktop icons
· Window Management - Drag, resize, minimize, maximize, and close windows
· Multi-App Support - Run multiple applications simultaneously
· File Explorer - Virtual file system with folder navigation
· Settings Panel - Customizable system preferences

🎮 Built-in Applications

1. File Explorer - Browse and manage virtual files
2. Terminal - Command-line interface with commands
3. Web Browser - Built-in browser for web navigation
4. Media Player - Audio/video playback
5. Game Center - Collection of 6 built-in games
6. AI Chat - Interactive AI assistant
7. Notepad - Text editing
8. Calculator - Basic and scientific calculations
9. Paint - Drawing application
10. Settings - System customization

🕹️ Game Center (6 Complete Games)

· 🐍 Snake - Classic snake game with score tracking
· 🐦 Flappy Bird - Physics-based bird game
· 🧠 Memory Match - Card matching memory game
· 🧮 2048 - Number sliding puzzle
· 🧩 Puzzle - Slide puzzle game
· ⭕ Tic Tac Toe - Play against AI opponent

🔒 Security Features

· Password Protection - App-level security
· Auto-Lock - Inactivity timer
· Clipboard Protection - Secure clipboard management
· Encrypted Storage - Local data encryption
· Session Security - Protected game sessions

🎨 Customization

· Icon Customization - Change emojis, colors, sizes
· Desktop Layout - Drag-and-drop icon positioning
· Wallpaper - Custom background images
· Theme Settings - Dark/light mode, accent colors
· Security Settings - Configure protection levels

📱 Cross-Platform

· Progressive Web App (PWA) - Install as native app
· Responsive Design - Works on desktop and mobile
· Touch Support - Optimized for touch devices
· Offline Capable - Works without internet

🚀 Quick Start

Option 1: Direct Use

1. Save the HTML file as index.html
2. Open it in any modern browser (Chrome, Edge, Firefox, Safari)
3. No installation required!

Option 2: PWA Installation

1. Open BhekOS in Chrome/Edge
2. Click the install icon in the address bar (or ⋮ → "Install BhekOS")
3. App will install with custom icon to desktop/home screen

📦 Installation

Simple Method (One File)

```bash
# Download the single HTML file
wget https://raw.githubusercontent.com/[username]/bhekos/main/index.html

# Open in browser
open index.html  # macOS
start index.html # Windows
xdg-open index.html # Linux
```

Complete PWA Setup

1. Create project folder:

```bash
mkdir bhekos
cd bhekos
```

1. Create the following files:

· index.html - Main HTML file with BhekOS code
· manifest.json - PWA manifest
· sw.js - Service worker
· icons/ folder with icon files

1. Folder structure:

```
bhekos/
├── index.html
├── manifest.json
├── sw.js
└── icons/
    ├── icon-72.png
    ├── icon-96.png
    ├── icon-128.png
    ├── icon-144.png
    ├── icon-152.png
    ├── icon-192.png
    ├── icon-384.png
    └── icon-512.png
```

🎮 Games Included

1. Snake Game

· Controls: Arrow keys
· Objective: Eat food, grow longer, avoid walls and yourself
· Features: High score tracking, pause/resume

2. Flappy Bird

· Controls: Click/Spacebar
· Objective: Navigate through pipes
· Features: Progressive difficulty, score system

3. Memory Match

· Controls: Click cards
· Objective: Find matching pairs
· Features: Move counter, timer, encrypted scores

4. 2048

· Controls: Arrow keys (swipe on mobile)
· Objective: Combine tiles to reach 2048
· Features: Undo move, best score tracking

5. Puzzle Game

· Controls: Click adjacent tiles
· Objective: Arrange numbers 1-8 in order
· Features: Move counter, timer

6. Tic Tac Toe

· Controls: Click cells
· Objective: Get three in a row
· Features: AI opponent, win statistics

⚙️ System Requirements

Minimum:

· Browser: Chrome 80+, Firefox 75+, Safari 13+, Edge 80+
· RAM: 512MB minimum
· Storage: 5MB free space
· Screen: 1024x768 resolution

Recommended:

· Browser: Latest Chrome/Edge/Firefox
· RAM: 1GB+
· Storage: 10MB+ for cached data
· Screen: 1920x1080 or higher

🔧 Development

Technologies Used:

· HTML5 - Structure and semantics
· CSS3 - Styling with modern features (CSS Grid, Flexbox, Variables)
· JavaScript (ES6+) - Core functionality with classes
· Canvas API - Game graphics rendering
· LocalStorage - Persistent data storage
· Service Workers - PWA and offline functionality
· Web App Manifest - Installation metadata

File Structure:

```
bhekos/
├── index.html              # Main application (all-in-one)
├── manifest.json           # PWA manifest
├── sw.js                   # Service worker
├── icons/                  # App icons (multiple sizes)
│   ├── icon-72.png
│   ├── icon-96.png
│   ├── icon-128.png
│   ├── icon-144.png
│   ├── icon-152.png
│   ├── icon-192.png
│   ├── icon-384.png
│   └── icon-512.png
└── README.md              # This file
```

Key Components:

1. BhekOS Class - Main operating system controller
2. Window Manager - Handles app windows and taskbar
3. App Loaders - Individual application UIs
4. Game Engine - Canvas-based game systems
5. Security Module - Password and encryption handling
6. PWA Manager - Installation and service worker

📱 Platform Support

Desktop:

· Windows (Chrome, Edge, Firefox) - Full support
· macOS (Safari, Chrome) - Full support
· Linux (Chrome, Firefox) - Full support

Mobile:

· Android (Chrome) - PWA installable, touch optimized
· iOS (Safari) - PWA installable, touch optimized

Installation Methods:

1. Chrome/Edge: Click install prompt or ⋮ menu → "Install BhekOS"
2. Safari: Share button → "Add to Home Screen"
3. Firefox: Settings → "Install"
4. Android Chrome: ⋮ menu → "Add to Home screen"

🛡️ Security

Built-in Security:

1. App Passwords - Optional password for sensitive apps
2. Auto-Lock - System locks after inactivity
3. Encrypted Storage - Local data encryption
4. Clipboard Protection - Secure clipboard handling
5. Session Security - Protected game sessions

Privacy:

· No Tracking - No analytics or telemetry
· Local Storage - All data stays on your device
· No Server Communication - Completely offline-capable
· Open Source - Transparent codebase

🎨 Customization Options

Icon Settings:

· Emoji Selection - Change app icons
· Color Customization - Pick custom colors
· Size Adjustment - Scale icon sizes
· Background Opacity - Control transparency

Desktop:

· Wallpaper - Custom background images
· Icon Layout - Drag-and-drop positioning
· Grid Snap - 20px grid alignment
· Theme - Dark/light mode

System:

· Accent Color - Change system highlight color
· Transparency - Enable/disable glass effects
· Animation Speed - Control UI animations
· Security Settings - Configure protection levels

🚀 Performance Tips

For Best Experience:

1. Use Latest Browser - Chrome/Edge recommended
2. Enable Hardware Acceleration - Improves canvas performance
3. Close Other Tabs - Frees up memory for games
4. Use Desktop - Larger screen improves usability
5. Regular Refresh - Clear cache if performance slows

Known Limitations:

· Large Games: May slow on older devices
· Memory: Multiple apps open can increase RAM usage
· Storage: LocalStorage limited to ~5-10MB
· Offline: Some features require initial internet for images

🔄 Updates

Version History:

· 6.0.0 - Initial release with full feature set
· 6.0.1 - Bug fixes and performance improvements
· Future - Planned: More apps, cloud sync, multiplayer games

Update Process:

1. Download latest index.html
2. Replace existing file
3. Refresh browser
4. Clear cache if needed (Ctrl+Shift+R)

🤝 Contributing

How to Contribute:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit pull request

Areas Needing Help:

· New Applications - Create more built-in apps
· Game Development - Add more games
· UI/UX Improvements - Enhance user experience
· Performance - Optimize for slower devices
· Documentation - Improve docs and tutorials

📄 License

MIT License - See LICENSE file for details.

Permissions:

· ✅ Commercial use
· ✅ Modification
· ✅ Distribution
· ✅ Private use

Conditions:

· © Include original copyright notice
· © Include license copy

🌐 Links

· Live Demo: [Coming Soon]
· GitHub Repository: [Your Repo Link]
· Issue Tracker: [GitHub Issues]
· Documentation: [GitHub Wiki]

🙏 Acknowledgments

Built With:

· Unsplash - Wallpaper images
· Google Fonts - Typography
· MDN Web Docs - Documentation
· Can I Use - Browser compatibility data

Inspiration:

· Windows 11 - UI design inspiration
· macOS - Smooth animations
· Chrome OS - Web-first approach
· Classic Games - Retro game designs

📞 Support: +233533989053

Getting Help:fireplus969@gmail.com 

1. Check FAQ - Common questions and solutions
2. GitHub Issues - Report bugs or request features
3. Documentation - Detailed usage guides

Common Issues:

· Games not loading: Try clearing browser cache
· Slow performance: Close other tabs/apps
· Installation failed: Check browser PWA support
· Password not working: Reset in settings

---

BhekOS 6.0 - Redefining what's possible in a web browser. Experience desktop computing, reimagined for the web. 🚀

Last Updated: Version 6.0.0 | Build 22000.556
