# 银河指尖 · Galaxy Bloom 3D

> 🤖 **AI 生成声明 / AI-Generated**
> 本项目的全部代码、文案与设计均由 **AI 生成**，人类仅提出需求与验收标准。
> This project is entirely **AI-Generated**.

摄像头手势驱动的 3D 粒子银河 —— 基于 **Three.js**（WebGL 粒子渲染）与 **MediaPipe Hands**（手势识别）。

✊ 握拳坍缩成星核 · ✋ 张掌绽放星河 · 🖐 左手旋转/拨动 · 👌 右手定位/捏合缩放 · 💧 水波纹从中心扩散

## ✨ 功能特性

| 特性 | 说明 |
| --- | --- |
| 🌀 旋臂银河 | 对数螺旋旋臂、恒星团、尘埃带，双密度波流动感 |
| ✊ 手势控制 | 握拳坍缩 / 张掌绽放 / 双手分工（右手定位缩放、左手旋转拨动） |
| 💧 水波纹 | 从银河中心向外扩散的环形波，左手拨动触发，闲置时自动泛出 |
| 🌌 粒子规模 | 最高 420,000 粒子（移动端自动降档） |
| 📷 纯浏览器 | 单文件 HTML，无需构建；摄像头手势识别实时驱动 |

## 🚀 运行方式

> ⚠️ 必须通过本地 HTTP 服务打开（`file://` 协议下浏览器会拒绝摄像头权限）。

```bash
# 在项目目录下启动一个静态服务器
python3 -m http.server 8123

# 浏览器访问
# http://localhost:8123/gesture-bloom.html
```

## 🎮 操作说明

| 手势 | 效果 |
| --- | --- |
| 右手移动 | 银河中心跟随掌心定位 |
| 右手捏合 | 收缩 / 放大星系 |
| 左手旋转 / 拨动 | 旋转银河，并激起水波纹 |
| 握拳 | 坍缩成星核 |
| 张开手掌 | 银河绽放 |

## 🛠 技术栈

- [Three.js](https://threejs.org/) — WebGL 粒子渲染（ES Module + importmap）
- [MediaPipe Hands](https://developers.google.com/mediapipe) — 摄像头手势识别
- 原生 JavaScript / HTML / CSS — 单文件实现（`gesture-bloom.html`）

## 📄 声明

- 本项目为 **AI 生成内容（AI-Generated）**，仅供学习、研究与演示使用。
- 图形与手势识别依赖浏览器 WebGL / 摄像头能力，建议使用最新版 Chrome / Edge / Safari。

---

*Generated with ❤️ by AI — 银河指尖 · Galaxy Bloom 3D*
