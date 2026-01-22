# 🐍 Snake Game - 贪吃蛇游戏

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Canvas](https://img.shields.io/badge/Canvas-000000?logo=html5&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)

**A classic snake game recreation with smooth animations and elegant design**

经典贪吃蛇游戏复刻，流畅动画与精美设计

[在线体验](https://jgzuo.github.io/snake/) · [关于](#关于) · [报告问题](../../issues)

</div>

---

## Language / 语言

<button onclick="toggleLanguage('en')" style="padding: 8px 16px; margin-right: 10px; border: 1px solid #ddd; background: white; cursor: pointer; border-radius: 5px;">🇬🇧 English</button>
<button onclick="toggleLanguage('zh')" style="padding: 8px 16px; border: 1px solid #ddd; background: white; cursor: pointer; border-radius: 5px;">🇨🇳 中文</button>

---

<div id="en-content">

## English

### ✨ Features

- **🎮 Classic Gameplay**: Perfect recreation of the classic Snake game
- **⚡ Smooth Controls**: Responsive arrow key and WASD controls
- **🎨 Elegant Design**: Pale colors with smooth animations
- **🎵 Sound Effects**: Eat, move, and game over audio feedback
- **📊 Score System**: Track your score and beat your high score
- **🚀 Progressive Difficulty**: Game speeds up as you score more
- **💾 High Score Storage**: Persistent high score using localStorage
- **📱 Responsive Design**: Works on desktop and mobile devices
- **🎯 Touch Controls**: Swipe gestures for mobile play

### 🎮 Controls

| Action | Keyboard | Mobile |
|--------|----------|--------|
| Move Up | ↑ or W | Swipe Up |
| Move Down | ↓ or S | Swipe Down |
| Move Left | ← or A | Swipe Left |
| Move Right | → or D | Swipe Right |
| Start/Restart | Space | Tap Start Button |
| Pause/Resume | Space | Tap Pause Button |

### 🎯 Game Mechanics

- **Grid Movement**: Snake moves on a 20x20 grid
- **Food System**: Eat food to grow longer and earn points
- **Progressive Speed**: Every 50 points, the game speeds up
- **Collision Detection**: Game ends if you hit walls or yourself
- **High Score**: Your best score is saved locally

### 🚀 Quick Start

#### Play Online
Visit [GitHub Pages](https://jgzuo.github.io/snake/) to play instantly.

#### Run Locally
```bash
# Clone repository
git clone https://github.com/jgzuo/snake.git

# Enter project directory
cd snake

# Open index.html in browser
```

### 🛠️ Tech Stack

- **HTML5 Canvas** - Game rendering
- **Vanilla JavaScript** - Game logic
- **Web Audio API** - Sound effects
- **CSS3** - UI styling and animations
- **LocalStorage** - High score persistence

### 🎨 Technical Highlights

#### Game Engine
- Grid-based movement system (20x20 grid)
- Smooth 60fps rendering with requestAnimationFrame
- Dynamic speed adjustment (150ms to 50ms intervals)
- Responsive canvas scaling

#### Visual Effects
- Gradient snake coloring (head to tail)
- Pulsing food animation
- Subtle grid overlay
- Snake eyes that follow direction
- Smooth rounded corners on snake segments

#### Audio System
- Procedural sound generation using Web Audio API
- Eat sound (dual-tone ascending)
- Move sound (subtle click)
- Game over sound (descending tones)

### 📊 Project Stats

| Item | Value |
|------|-------|
| Lines of Code | 600+ |
| Files | 1 single file |
| Dependencies | 0 |
| Game Elements | Snake, food, grid |

### 📝 Changelog

- **v1.0.0** (2026-01-22)
  - Initial release
  - Complete Snake game implementation
  - Sound effects and animations
  - GitHub Pages deployment

### 🤝 Contributing

Issues and Pull Requests are welcome!

### 📄 License

This project is licensed under the [MIT License](LICENSE).

### 🙏 Acknowledgments

- Inspired by the classic Snake game
- Built with pure web technologies as a tribute to the classic

</div>

<div id="zh-content" style="display: none;">

## 中文

### ✨ 特性

- **🎮 经典玩法**：完美复刻经典贪吃蛇游戏
- **⚡ 流畅操控**：响应灵敏的方向键和WASD控制
- **🎨 精美设计**：淡雅配色与流畅动画
- **🎵 完整音效**：进食、移动、游戏结束音效
- **📊 计分系统**：追踪分数，挑战最高分
- **🚀 难度递进**：分数越高，速度越快
- **💾 高分保存**：使用localStorage本地保存最高分
- **📱 响应式设计**：支持桌面和移动设备
- **🎯 触摸控制**：支持滑动手势操作

### 🎮 游戏操作

| 操作 | 键盘 | 移动端 |
|------|------|--------|
| 向上移动 | ↑ 或 W | 上滑 |
| 向下移动 | ↓ 或 S | 下滑 |
| 向左移动 | ← 或 A | 左滑 |
| 向右移动 | → 或 D | 右滑 |
| 开始/重开 | 空格键 | 点击开始按钮 |
| 暂停/继续 | 空格键 | 点击暂停按钮 |

### 🎯 游戏机制

- **网格移动**：蛇在20x20的网格上移动
- **食物系统**：吃掉食物来增长身体并获得分数
- **速度递增**：每获得50分，游戏速度提升
- **碰撞检测**：撞墙或撞到自己身体游戏结束
- **最高分记录**：你的最佳分数会被保存到本地

### 🚀 快速开始

#### 在线体验
访问 [GitHub Pages](https://jgzuo.github.io/snake/) 即可立即游玩。

#### 本地运行
```bash
# 克隆仓库
git clone https://github.com/jgzuo/snake.git

# 进入项目目录
cd snake

# 用浏览器打开 index.html
```

### 🛠️ 技术栈

- **HTML5 Canvas** - 游戏渲染
- **Vanilla JavaScript** - 游戏逻辑
- **Web Audio API** - 音效系统
- **CSS3** - 界面样式和动画
- **LocalStorage** - 最高分持久化

### 🎨 技术亮点

#### 游戏引擎
- 基于网格的移动系统（20x20网格）
- 60fps流畅渲染（requestAnimationFrame）
- 动态速度调整（150ms至50ms间隔）
- 响应式画布缩放

#### 视觉效果
- 渐变色蛇身（从头到尾）
- 食物脉动动画
- 细微网格叠加
- 蛇眼跟随移动方向
- 圆润的蛇身段

#### 音频系统
- 使用Web Audio API程序化生成音效
- 进食音效（双音上升）
- 移动音效（轻微点击）
- 游戏结束音效（下降音调）

### 📊 项目数据

| 项目 | 数值 |
|------|------|
| 代码行数 | 600+ |
| 文件数量 | 1个单文件 |
| 依赖项 | 0 |
| 游戏元素 | 蛇、食物、网格 |

### 📝 更新日志

- **v1.0.0** (2026-01-22)
  - 初始版本发布
  - 完整贪吃蛇游戏实现
  - 音效和动画系统
  - GitHub Pages部署

### 🤝 贡献

欢迎提交 Issue 和 Pull Request！

### 📄 许可证

本项目采用 [MIT License](LICENSE) 开源协议。

### 🙏 致谢

- 灵感来源于经典的贪吃蛇游戏
- 使用纯Web技术实现，致敬经典

</div>

---

<div align="center">

**如果喜欢这个项目，请给一个 ⭐️ Star！**

**If you like this project, please give it a ⭐️ Star!**

Made with ❤️ by [jgzuo](https://github.com/jgzuo)

</div>

<script>
function toggleLanguage(lang) {
    const enContent = document.getElementById('en-content');
    const zhContent = document.getElementById('zh-content');

    if (lang === 'en') {
        enContent.style.display = 'block';
        zhContent.style.display = 'none';
        localStorage.setItem('preferredLang', 'en');
    } else {
        enContent.style.display = 'none';
        zhContent.style.display = 'block';
        localStorage.setItem('preferredLang', 'zh');
    }
}

// Auto-detect or load saved language preference
document.addEventListener('DOMContentLoaded', () => {
    const savedLang = localStorage.getItem('preferredLang');
    if (savedLang) {
        toggleLanguage(savedLang);
    } else {
        // Auto-detect based on browser language
        const browserLang = navigator.language || navigator.userLanguage;
        if (browserLang.startsWith('zh')) {
            toggleLanguage('zh');
        } else {
            toggleLanguage('en');
        }
    }
});
</script>
