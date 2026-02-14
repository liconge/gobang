# 🎮 3D Gomoku (五子棋)

A beautiful 3D Gomoku (Five in a Row) game that runs entirely in your browser. Play locally against AI or challenge friends online with **zero installation** - just a single HTML file!

[中文说明](#中文说明) | [English](#english)

---

## 📖 English

### ✨ Features

- 🎨 **Stunning 3D Graphics**: Built with Three.js featuring realistic lighting, shadows, and smooth animations
- 🤖 **AI Opponent**: Three difficulty levels (Easy, Medium, Hard) with intelligent move evaluation
- 🌐 **Online Multiplayer**: Play with friends on different computers using WebRTC peer-to-peer connection
- 👥 **Local Multiplayer**: Two players on the same computer
- 🎯 **Smart Features**:
  - Hover preview before placing pieces
  - Undo moves
  - Win detection with animation
  - Responsive design

### 🎮 How to Play

1. **Download** the `gomoku-3d.html` file
2. **Double-click** to open in any modern browser
3. **Choose Game Mode**:
  - 👥 **Two Players**: Local multiplayer on same computer
  - 🤖 **vs AI**: Play against computer with 3 difficulty levels
  - 🌐 **Online**: Play with friends over the internet

### 🕹️ Controls

| Action | Control |
| --- | --- |
| Place Piece | Left Click on board intersection |
| Rotate View | Drag with mouse |
| Zoom | Mouse wheel |
| Undo | Click "悔棋" button |
| Restart | Click "重新开始" button |

### 🌐 Online Multiplayer Guide

1. Click the mode button until it shows **"联机对战"** (Online)
2. **Host**:
  - Copy the 6-character room ID
  - Share it with your friend
  - Wait for connection
3. **Guest**:
  - Switch to online mode
  - Enter the room ID
  - Click "加入" (Join)
4. Start playing! Host plays as Black, Guest as White

### 🎯 AI Difficulty Levels

- **Easy**: Basic defense and random offense
- **Medium**: Pattern recognition and position evaluation
- **Hard**: Advanced strategy with extended search range

### 💻 Technical Details

- **Engine**: Three.js r128
- **Networking**: PeerJS (WebRTC)
- **Board Size**: 15×15 (Standard)
- **File Size**: ~49KB (single HTML file)
- **No Dependencies**: All libraries loaded from CDN

### 🖥️ Browser Support

- ✅ Chrome / Edge (Recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Opera

---

## 中文说明

### ✨ 功能特点

- 🎨 **精美3D画面**: 基于Three.js开发，真实光影效果和流畅动画
- 🤖 **AI对手**: 三种难度级别（简单、中等、困难），智能评估系统
- 🌐 **在线对战**: 使用WebRTC技术，无需服务器即可联机对战
- 👥 **本地双人对战**: 同一台电脑上两人对战
- 🎯 **智能功能**:
  - 落子前预览
  - 悔棋功能
  - 胜负判定动画
  - 响应式设计

### 🎮 游戏玩法

1. **下载** `gomoku-3d.html` 文件
2. **双击**用浏览器打开
3. **选择游戏模式**:
  - 👥 **双人对战**: 本地双人同机对战
  - 🤖 **人机对战**: 与电脑AI对战，三种难度
  - 🌐 **联机对战**: 与远方朋友在线对战

### 🕹️ 操作说明

| 操作  | 控制方式 |
| --- | --- |
| 落子  | 左键点击棋盘交叉点 |
| 旋转视角 | 鼠标拖拽 |
| 缩放  | 鼠标滚轮 |
| 悔棋  | 点击"悔棋"按钮 |
| 重新开始 | 点击"重新开始"按钮 |

### 🌐 联机对战指南

1. 点击模式按钮切换到 **"联机对战"**
2. **房主**:
  - 复制6位房间号
  - 分享给朋友
  - 等待连接
3. **加入者**:
  - 切换到联机模式
  - 输入房间号
  - 点击"加入"
4. 开始对战！房主执黑棋，加入者执白棋

### 🎯 AI难度说明

- **简单**: 基础防守 + 随机进攻
- **中等**: 棋型识别 + 位置评估
- **困难**: 高级策略 + 扩大搜索范围

### 💻 技术细节

- **引擎**: Three.js r128
- **网络**: PeerJS (WebRTC)
- **棋盘**: 15×15 标准规格
- **文件大小**: 约49KB（单个HTML文件）
- **零依赖**: 所有库从CDN加载

### 🖥️ 浏览器支持

- ✅ Chrome / Edge (推荐)
- ✅ Firefox
- ✅ Safari
- ✅ Opera

---

## 📸 Screenshots

*Coming soon - Add your screenshots here*

```
[Screenshot 1: Game Board]
[Screenshot 2: AI Mode]
[Screenshot 3: Online Multiplayer]
```

## 🚀 Quick Start

### Option 1: Direct Download

1. Download `gomoku-3d.html`
2. Open in browser
3. Play immediately!

### Option 2: Clone Repository

```bash
git clone https://github.com/yourusername/gomoku-3d.git
cd gomoku-3d
# Open gomoku-3d.html in browser
```

### Option 3: Web Server (for development)

```bash
# Python 3
python -m http.server 8000

# Node.js
npx serve

# PHP
php -S localhost:8000
```

Then open `http://localhost:8000/gomoku-3d.html`

## 🎯 Game Rules

Standard Gomoku (Five in a Row) rules:

1. Black plays first
2. Players alternate placing stones on board intersections
3. First player to get 5 stones in a row (horizontally, vertically, or diagonally) wins
4. Game ends when a player wins or board is full

## 🔧 Customization

You can easily modify the game by editing the HTML file:

```javascript
// Change board size (default: 15)
const BOARD_SIZE = 19; // for 19×19 board

// Adjust AI difficulty
const aiDifficulty = 3; // 1=Easy, 2=Medium, 3=Hard

// Modify colors
const BOARD_COLOR = 0xDEB887; // Wood color
```

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### 📝 TODO List

- [ ] Add sound effects
- [ ] Add game timer
- [ ] Add move history/replay
- [ ] Support for different board sizes
- [ ] Mobile touch controls optimization
- [ ] Save/Load game state

## 🐛 Troubleshooting

### Online Mode Issues

**Problem**: Cannot connect to opponent

- ✅ Check internet connection
- ✅ Ensure both players use the same game version
- ✅ Try refreshing and rejoining
- ✅ Disable VPN if using one

**Problem**: Room ID not working

- ✅ Room ID is case-sensitive
- ✅ Must be exactly 6 characters
- ✅ Host must stay on the game page

### Performance Issues

**Problem**: Game runs slowly

- ✅ Close other browser tabs
- ✅ Use Chrome or Edge for best performance
- ✅ Update graphics drivers
- ✅ Disable browser extensions

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Three.js](https://threejs.org/) - 3D graphics library
- [PeerJS](https://peerjs.com/) - WebRTC peer-to-peer library
- Inspired by traditional Gomoku games

## 📧 Contact

- **Author**: Your Name
- **Email**: your.email@example.com
- **GitHub**: [@yourusername](https://github.com/yourusername)

---

## 🌟 Star History

[](https://star-history.com/#yourusername/gomoku-3d&Date)

---

<div align="center">

**Enjoy the game! 🎮**

If you like this project, please give it a ⭐️ Star!

[Report Bug](../../issues) · [Request Feature](../../issues)

</div>

---

*Last updated: February 2026*
