# 🐍 贪吃蛇游戏

一个使用 React + Vite 开发的贪吃蛇游戏，支持微信小程序和网页版。

## 🎮 游戏特性

- ✅ 双模式：普通模式（200分/关）和困难模式（100分/关 + 障碍物）
- ✅ 关卡系统：过关后速度提升
- ✅ 多种食物：不同大小不同分值
- ✅ 精美UI：圆形方向键控制面板
- ✅ 响应式设计：支持键盘和触屏操作

## 🚀 在线试玩

**网页版**: [点击游玩](https://your-vercel-url.vercel.app)

## 🛠️ 本地开发

### 网页版

```bash
# 安装依赖
npm install

# 启动开发服务器
npm run dev

# 构建
npm run build
```

### 微信小程序

使用微信开发者工具打开 `miniprogram` 文件夹。

## 📁 项目结构

```
.
├── src/                    # React 源码
│   ├── App.jsx            # 主组件
│   └── App.css            # 样式
├── miniprogram/           # 微信小程序
│   ├── pages/index/       # 游戏页面
│   ├── app.json           # 小程序配置
│   └── project.config.json
├── snake-game.html        # 独立HTML版本
├── package.json
└── README.md
```

## 📝 技术栈

- React 18
- Vite
- 微信小程序
- HTML5 Canvas

## 📄 许可证

MIT
