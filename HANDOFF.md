# Portfolio Handoff Note

## 目前進度
作品集網站框架已完成，等待填入真實內容。

## 啟動方式
```bash
cd "Elaine Portfolio"
node serve.mjs
# 開啟 http://localhost:3000
```

## 唯一需要做的事：填入 index.html 底部 <script> 裡的資料

### 1. Hero Demoreel
```js
const DEMOREEL_ID = 'YOUR_DEMOREEL_VIMEO_ID';
// 改成你的 Vimeo ID，例如：'123456789'
```

### 2. 6 個作品（projects 陣列）
每個作品填入：
- `vimeoId` — Vimeo 影片 ID
- `title` — 作品名稱
- `type` — 類型 + 年份，例如 `Motion Graphics · 2024`
- `desc` — 作品概述
- `specs` — 工具、時長等
- `process[].src` — 創作過程圖片路徑（moodboard / storyboard / styleframe）

### 3. LinkedIn
搜尋 `YOUR_LINKEDIN`，換成你的 LinkedIn 帳號名稱。

## 設計資訊
- 字型：Anton（標題）+ IBM Plex Mono（內文）
- 主色：#e33e3e
- 風格：大膽 editorial，全黑背景
- 頭像：brand_assets/Elaine Chen.jpg（已套用）

## 給桌機的 Claude
告訴 Claude：「我在繼續做 Elaine Chen 的 Motion Designer 作品集，請讀取這份 HANDOFF.md 了解目前進度。」
