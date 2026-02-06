# Quick Search Switcher (Custom Search Engine)

[中文](README.md) | [English](README_EN.md)

A lightweight Chrome/Edge extension: select text and switch search engines instantly, reducing the interruption caused by digging through long context menus.

![Floating toolbar](assets/截屏.png)

## Features
- **Floating toolbar on text selection (default shows top 3, configurable)**
- **One‑click copy for selected text**
- **Floating position (above/below)**
- **New tab position (next to current tab / end of window)**
- **Translate button: Google / Baidu / Bing, auto EN↔ZH**
- **Auto‑hide floating toolbar: configurable timeout, pause on hover, auto‑hide 3s after returning to page**
- **“More” dropdown to access additional engines and Settings**
- **Context‑menu search entries**
- **Custom engines + ordering (drag / move up/down)**
- **Auto‑save + language/theme switch**
- **Quick‑add common engines**

## Install (Developer Mode)
1. Open `chrome://extensions`
2. Enable “Developer mode”
3. Click “Load unpacked”
4. Select this project folder

You can also refer to this (Chinese) install tutorial:  
https://www.7longwen.com/d/zen-me-zai-chrome-shang-an-zhuang-cha-jian.html

## Usage
1. Select text on a webpage
2. The floating toolbar appears
3. Click an engine button to search in a new tab

## Settings
- Floating buttons count & position
- Translate provider (Google / Baidu / Bing)
- Auto target language: Chinese → English, English → Chinese
- Auto‑hide timeout (seconds)
- Engine list add/remove/reorder
- Quick‑add common engines

## Default / Quick‑add Engines
Google, Bing, Wikipedia, Zhihu, Bilibili, GitHub, Taobao, JD, Twitter, YouTube, Google Scholar, Douyin

## File Structure
- `manifest.json` Extension manifest
- `background.js` Context menus & tab opening
- `content.js` Selection floating toolbar
- `content.css` Floating toolbar styles
- `options.html` / `options.js` / `options.css` Settings page
- `assets/` Images (QR codes, screenshots, icons)

## Permissions
- `contextMenus`: context menu entries
- `storage`: save engines and settings

## License
Add an open‑source license if needed (e.g., MIT).
