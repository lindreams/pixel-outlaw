# Pixel Outlaw

一个网页可玩的西部牛仔像素风俯视角射击小游戏。边移动、边射击，在一波波敌人中活下来。

**[在线试玩](https://lingmeng-658.github.io/pixel-outlaw/)**

## 怎么玩

| 操作 | 按键 |
| --- | --- |
| 移动 | WASD |
| 射击 | 方向键（支持斜向） |
| 开始新游戏 | Space 或点击 Start |
| 继续已有存档 | C（存在存档时） |
| 暂停 / 返回游戏 | Esc |
| 暂停时重新开始当前关卡 | R |
| 暂停时保存并退出 | S |

## 现在有什么

- 从第一关的基础移动、射击和敌人波次开始，逐步加入关卡推进。
- 咖啡、血瓶、护盾等道具，以及后续关卡的战斗与拾取机制。
- 不同敌人行为、击杀反馈、分数和生命值。
- 暂停与存档继续功能。

目前仍是持续迭代的小游戏，关卡、数值和表现都可能继续调整。

## 本地运行

需要 Node.js 和 npm。

```bash
npm ci
npm run dev
```

构建静态页面：

```bash
npm run build
```

项目使用 **Phaser、TypeScript 和 Vite**。GitHub Pages 部署流程见 [deploy.yml](.github/workflows/deploy.yml)。

开发过程和下一步想法保存在 [TODO.md](TODO.md) 及 [PROJECT_CONTEXT.md](PROJECT_CONTEXT.md)。

## 关于这个项目

玩法最初受到《草原大王的冒险》的启发，项目使用自己的名称、素材和设定。
