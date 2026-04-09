<div align="center">

# 🃏 百家乐模拟器 Baccarat Simulator

[![GitHub Pages](https://img.shields.io/badge/Play%20Now-GitHub%20Pages-brightgreen?style=for-the-badge&logo=github)](https://raymond1030.github.io/baccarat-simulator/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](index.html)
[![PWA](https://img.shields.io/badge/PWA-Supported-5A0FC8?style=for-the-badge&logo=pwa&logoColor=white)](sw.js)

网页端百家乐模拟器，真实赌场风格，纯前端零依赖，支持移动端和离线使用。

[**▶️ 在线体验**](https://raymond1030.github.io/baccarat-simulator/)

</div>

---

## ✨ 功能特性

| 功能 | 说明 |
|------|------|
| 🎰 **标准百家乐规则** | 8 副牌，庄/闲/和/庄对/闲对下注，庄赢 5% 佣金 |
| 📊 **完整五路路单** | 大路、大眼仔、小路、蟑螂路、珠盘路 |
| 📈 **统计面板** | 胜率、连胜记录、盈亏追踪、对子统计 |
| 🎲 **多桌系统** | 3 张独立桌子，可同时对比不同策略 |
| 💾 **数据持久化** | localStorage 自动保存，关闭浏览器不丢失 |
| 📱 **响应式设计** | 桌面端并排布局，移动端 Tab 切换 |
| 📶 **PWA 支持** | 可添加到主屏幕，离线可用 |

## 🚀 快速开始

### 在线使用

访问 **https://raymond1030.github.io/baccarat-simulator/** 即可开始。

### 本地使用

```bash
git clone https://github.com/Raymond1030/baccarat-simulator.git
cd baccarat-simulator
open index.html   # macOS
# 或直接用浏览器打开 index.html
```

## 🎮 操作指南

### 基本操作

1. 🪙 选择筹码面额（10 / 50 / 100 / 500 / 1K）
2. 👆 点击下注区域放置筹码（可叠加）
3. 🃏 点击「发牌」查看结果
4. ↩️ 右键点击下注区域可撤回

### ⌨️ 键盘快捷键

| 按键 | 功能 |
|:----:|------|
| `1` - `5` | 选择筹码面额 |
| `P` | 下注闲 |
| `B` | 下注庄 |
| `T` | 下注和 |
| `Space` | 发牌 |

## 📊 路单说明

| 路单 | 英文 | 说明 |
|------|------|------|
| 大路 | Big Road | 主路单，记录庄闲结果走势 |
| 大眼仔 | Big Eye Boy | 基于大路推导，判断走势齐整度 |
| 小路 | Small Road | 跳一列比较的齐整度分析 |
| 蟑螂路 | Cockroach Pig | 跳两列比较的齐整度分析 |
| 珠盘路 | Bead Plate | 逐局顺序记录，最直观 |

## 🛠️ 技术栈

```
📄 index.html  — 全部游戏代码（HTML + CSS + JS）
📄 sw.js       — Service Worker（离线缓存）
```

- 纯前端单文件，无框架、无构建、无依赖
- Canvas 路单渲染
- localStorage 数据持久化
- 响应式 CSS（断点 768px）

## 📄 License

[MIT](LICENSE)
