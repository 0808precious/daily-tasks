<div align="center">
  <img src="icon-192.png" width="84" alt="Daily" />

  <h1>每日任务 · Daily</h1>

  <p>A minimal, modern daily task list. Jot down today's tasks; past days are archived automatically for easy review.<br/>
  一个极简、现代的每日任务清单。记录当天要做的事，往日清单自动归档，随时回看。</p>

  <p><em>Pure frontend · Zero dependencies · Local-only data · Installable as a desktop / mobile app</em></p>

  <p><a href="#english">English</a> · <a href="#中文">中文</a></p>
</div>

---

<a name="english"></a>

## English

### ✦ Overview

**Daily** is a lightweight to-do app: each day opens to a fresh page where you write down what you want to get done. The next day, the previous day's list is automatically tucked into **History**, so you can always look back at what you accomplished.

It's a single-page web app — no installation required, no online account, no backend server. Every task is stored locally in your own browser.

### ✦ Features

- **Today's tasks** — Add, check off, and delete items, with a live progress bar at the top.
- **History archive** — Each day's list is saved automatically by date; click any day in the sidebar to view it (past entries are read-only to prevent accidental edits).
- **Automatic paging** — Lists are archived by the real calendar date; a new day starts on its own, no manual action needed.
- **Four themes** — Graphite, Cobalt, Coral, and Sand. Switch with one tap in the top-right corner; your choice is remembered.
- **Installable** — Works as a PWA you can install to your Mac desktop or iPhone home screen, with its own window and app icon.
- **Works offline** — Once installed, it opens and runs without an internet connection.

### ✦ Use online

After deploying to GitHub Pages, just visit your URL:

```
https://<your-username>.github.io/<repo-name>/
```

### ✦ Run locally

No build step needed. Keep all files in one folder and double-click `index.html` to open it in your browser.

> Note: When opened as a local file (`file://`), offline caching and "Install as app" won't work — those require accessing it through the deployed URL below.

### ✦ Deploy to GitHub Pages

1. Create a **Public** repository.
2. Upload all project files to the repository **root** (make sure `index.html` is at the top level).
3. Go to `Settings → Pages`, set Branch to `main` and folder to `/ (root)`, then save.
4. Wait about a minute; your URL will appear at the top of the page.

### ✦ Install as an app

Once deployed and you have the URL:

- **Mac (Chrome / Edge):** Open the URL and click the install icon on the right side of the address bar, or "Install Daily" in the menu.
- **iPhone (Safari):** Open the URL → Share button → "Add to Home Screen".
- **Android (Chrome):** Open the URL → menu → "Install app".

### ✦ Data & privacy

- All task data is stored only in **your current device's browser storage (localStorage)**. It is never uploaded to any server, and it does **not** appear in this public repository.
- Only the app's code is public — none of your task content is.
- Clearing your browser data or switching device/browser will lose the local records.

### ✦ Tech

Plain HTML / CSS / vanilla JavaScript — no frameworks, no third-party dependencies. Fonts use Saira and Hanken Grotesk from Google Fonts (falling back to system fonts when offline).

### ✦ File structure

```
.
├── index.html       Main page and all logic
├── manifest.json    PWA manifest
├── sw.js            Service worker (offline cache)
├── icon-192.png     App icon
├── icon-512.png     App icon
└── README.md
```

### ✦ License

[MIT](LICENSE) © 2026

---

<a name="中文"></a>

## 中文

### ✦ 简介

「每日任务」是一个轻量的待办应用：每天打开就是崭新的一页，写下今天要做的事；到了第二天，前一天的清单会自动收进「历史记录」里归档保存，方便你随时翻看自己每天完成了什么。

它是一个单页网页应用，不需要安装、不需要联网账号、没有任何后端服务器——所有任务都保存在你自己浏览器的本地存储里。

### ✦ 功能

- **今日任务** — 添加、勾选完成、删除，顶部实时显示完成进度。
- **历史归档** — 每一天的清单自动按日期保存，侧栏点选即可查看（往日记录只读，避免误改）。
- **自动翻页** — 按真实日期归档，无需手动操作，新的一天自动开始。
- **四套主题** — Graphite（深灰）、Cobalt（钴蓝）、Coral（珊瑚）、Sand（暖砂），右上角一键切换，选择会被记住。
- **可安装** — 支持作为 PWA 安装到 Mac 桌面、iPhone 主屏，拥有独立窗口与应用图标。
- **离线可用** — 安装后断网也能打开使用。

### ✦ 在线使用

部署到 GitHub Pages 后，直接访问你的网址即可：

```
https://<你的用户名>.github.io/<仓库名>/
```

### ✦ 本地运行

无需任何构建步骤。把项目文件放在同一文件夹下，双击 `index.html` 用浏览器打开即可使用。

> 注：以本地文件（`file://`）方式打开时，离线缓存与「安装为应用」不会生效，需通过下方部署后的网址访问才支持。

### ✦ 部署到 GitHub Pages

1. 新建一个 **Public（公开）** 仓库。
2. 将本项目所有文件上传到仓库**根目录**（确保 `index.html` 在最外层）。
3. 进入 `Settings → Pages`，将 Branch 设为 `main`、目录设为 `/ (root)`，保存。
4. 等待约 1 分钟，页面顶部会显示你的访问网址。

### ✦ 安装为应用

部署完成、拿到网址后：

- **Mac（Chrome / Edge）**：打开网址，点击地址栏右侧的安装图标，或菜单中的「安装 每日任务」。
- **iPhone（Safari）**：打开网址 → 分享按钮 → 「添加到主屏幕」。
- **Android（Chrome）**：打开网址 → 菜单 → 「安装应用」。

### ✦ 数据与隐私

- 所有任务数据仅保存在**你当前设备的浏览器本地存储（localStorage）**中，不会上传到任何服务器，也**不会**出现在这个公开仓库里。
- 公开的只是应用的代码，不包含你的任何任务内容。
- 清除浏览器数据或更换设备/浏览器，本地任务记录将无法找回。

### ✦ 技术

纯 HTML / CSS / 原生 JavaScript，无框架、无第三方依赖。字体使用 Google Fonts 的 Saira 与 Hanken Grotesk（离线时自动回退到系统字体）。

### ✦ 文件结构

```
.
├── index.html       主页面与全部逻辑
├── manifest.json    PWA 应用清单
├── sw.js            Service Worker（离线缓存）
├── icon-192.png     应用图标
├── icon-512.png     应用图标
└── README.md
```

### ✦ 许可证

[MIT](LICENSE) © 2026
