# Competitive Companion - Safari 移植版

[![Build Status](https://github.com/jmerle/competitive-companion/workflows/Build/badge.svg)](https://github.com/jmerle/competitive-companion/actions/workflows/build.yml)

本仓库是 [Competitive Companion](https://github.com/jmerle/competitive-companion) 的 Safari 移植版本，可将在线编程竞赛平台（如 Codeforces、AtCoder 等）的题目数据实时解析并发送到本地工具（如 CP Editor、CPH 等），支持题目/竞赛解析、测试用例提取、时空限制识别等功能。

---

## 🛠️ 安装指南

### 前置要求
1. **启用 Safari 开发者模式**：
   - 打开 Safari → 设置 (⌘+,) → 高级 → 勾选 _"显示网页开发者功能"_
2. **允许未签名扩展**：
   - 打开 Safari → 设置 (⌘+,) → 开发者 → 勾选 _"允许未签名的扩展"_
   - 或者 终端执行：
     ```bash
     defaults write com.apple.Safari AllowUnsignedExtensions -bool true
     ```

### 安装步骤
1. **下载应用包**：
   - 从 Releases 页面下载 `Competitive Companion.app`
2. **解除安全限制**：
   ```bash
   xattr -r -d com.apple.quarantine ~/Downloads/Competitive\ Companion.app
   ```
3. **安装扩展**：
   - 双击打开应用 → Safari 会提示 _"是否要启用扩展？"_ → 点击允许
   - 前往 Safari → 设置 → 扩展 → 启用 `Competitive Companion`

---

## 🔌 集成工具
- [CP Editor](https://cpeditor.org/) - 轻量级竞赛编程编辑器
- [CHelper](https://plugins.jetbrains.com/plugin/7091-chelper) - IntelliJ 系 IDE 插件
- [acmX](https://marketplace.visualstudio.com/items?itemName=marx24.acmx) - VS Code 扩展
- [支持完整工具列表](https://github.com/jmerle/competitive-companion#tools-that-use-competitive-companion)

---

## 🙏 致谢
本项目基于 [jmerle/competitive-companion](https://github.com/jmerle/competitive-companion) 进行 Safari 移植开发，保留原项目的核心功能与兼容性。
