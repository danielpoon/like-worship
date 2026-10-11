# Like Worship — 敬拜鋼琴課程

一個簡單的鋼琴學習網站，專為 **iPhone、iPad 及電腦** 設計。  
選擇難度，點選課堂，YouTube 影片直接在頁面內播放。  
無需登入，無需帳號。在任何裝置上都能流暢使用。

🌐 **網站：** [like-worship.danielpoon.com](https://like-worship.danielpoon.com)

---

## 功能簡介

- 按難度瀏覽課堂 — **初級**、**中級**、**高級**、**詩歌示範**
- 直接在頁面內觀看 YouTube 教學影片
- 按歌名或頻道搜尋課堂
- 點 ⭐ 星星儲存喜歡的課堂，隨時重溫
- 切換 **英文** 與 **繁體中文** 介面
- 可加入 iPhone 或 iPad 主畫面，像 App 一樣使用

---

## 課堂數量

### 繁體中文

| 程度 | 課堂數 |
|------|--------|
| 初級 | 9 |
| 中級 | 17 |
| 高級 | 9 |
| 詩歌示範 | 11 |
| **合計** | **46** |

### 英文 English

| 程度 | 課堂數 |
|------|--------|
| 初級 Easy | 36 |
| 中級 Moderate | 39 |
| 高級 Hard | 17 |
| 詩歌教學 Song Tutorials | 14 |
| **合計** | **106** |

---

## 主要功能說明

| 功能 | 說明 |
|------|------|
| ⭐ 儲存課堂 | 點課堂標題旁的星星即可儲存。點右上角星星圖示查看所有已儲存課堂。資料存在瀏覽器，不需伺服器。 |
| 🔍 搜尋 | 按歌名、頻道或模組名稱搜尋 |
| 🌙 主題顏色 | 藍色（預設）、深色、粉紅色，在設定中更換 |
| 📱 加入主畫面 | 點頂部分享圖示，依指示加入 iPhone 或 iPad 主畫面 |
| ❓ 說明 | 點 **?** 查看 YouTube 播放控制說明（手機顯示觸控手勢，電腦顯示鍵盤快捷鍵）|
| 🌐 雙語 | 完整英文及繁體中文內容 |

---

## 如何加入 iPhone / iPad 主畫面

1. 在 **Safari** 打開 [like-worship.danielpoon.com](https://like-worship.danielpoon.com)（不是 Chrome）。
2. 點 **分享** 按鈕（方框加向上箭頭）。
3. 點 **加入主畫面**。
4. 點 **加入**。主畫面會出現 Like Worship 圖示。

---

## 授權

本專案採用 [Creative Commons 姓名標示 4.0 國際授權條款 (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/deed.zh-hant) 授權。

您可以自由使用、修改及分享，但須註明作者：**Daniel Poon** 及原始網站 [like-worship.danielpoon.com](https://like-worship.danielpoon.com)。

---

---

# Like Worship — Worship Piano Lessons

A simple web app for learning worship piano, designed to work on **iPhone, iPad, and desktop**.  
Pick a difficulty, tap a lesson, and watch the YouTube tutorial right inside the page.  
No login. No account. Works great on any device.

🌐 **Live site:** [like-worship.danielpoon.com](https://like-worship.danielpoon.com)

---

## What it does

- Browse lessons by difficulty — **Easy**, **Moderate**, **Hard**, and **Song Tutorials**
- Watch YouTube videos without leaving the page
- Search lessons by title or channel
- Save lessons with a ⭐ star and review them later
- Switch between **English** and **Traditional Chinese (繁體中文)**
- Add to your iPhone or iPad Home Screen like an app

---

## Lessons

### Chinese 繁體中文 🇭🇰 🇹🇼

| Level | Lessons |
|-------|---------|
| 初級 Easy | 9 |
| 中級 Moderate | 17 |
| 高級 Hard | 9 |
| 詩歌示範 Song Tutorials | 11 |
| **Total** | **46** |

### English 🇺🇸 🇨🇦

| Level | Lessons |
|-------|---------|
| Easy | 36 |
| Moderate | 39 |
| Hard | 17 |
| Song Tutorials | 14 |
| **Total** | **106** |

---

## Features

| Feature | Details |
|---------|---------|
| ⭐ Saved Lessons | Click the star next to any lesson title to save it. View all saved lessons from the star button top right. Stored in your browser — no server needed. |
| 🔍 Search | Search by song title, channel, or module name |
| 🌙 Themes | Blue (default), Dark, and Pink — pick in Settings |
| 📱 Home Screen | Tap the share icon on the top bar for instructions to add Like Worship to your iPhone or iPad Home Screen |
| ❓ Help | Tap **?** for YouTube player controls — shows touch gestures on phone, keyboard shortcuts on desktop |
| 🌐 Bilingual | Full English and Traditional Chinese content |

---

## How to use on iPhone / iPad

1. Open [like-worship.danielpoon.com](https://like-worship.danielpoon.com) in **Safari**.
2. Tap the **Share** button (square with arrow up).
3. Tap **Add to Home Screen**.
4. Tap **Add**. The app icon appears on your Home Screen.

---

## Running locally

No build step needed. It is a plain HTML file.

```bash
git clone https://github.com/danielpoon/like-worship.git
cd like-worship
open index.html        # macOS
# or drag index.html into any browser
```

For the lessons data (`lessons.json`) to load, serve it from a local web server:

```bash
python3 -m http.server 8080
# then open http://localhost:8080
```

---

## License

This project is licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

You are free to use, modify, and share this project, as long as you give credit to **Daniel Poon** and link back to [like-worship.danielpoon.com](https://like-worship.danielpoon.com).
