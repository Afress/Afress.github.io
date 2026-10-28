# 李昱翔 LEE YU HSIANG ｜ 個人履歷網站

🌐 線上網址：**https://afress.github.io/**

個人履歷展示網站，以 React + Tailwind CSS 建置，
呈現工作經驗、專案成就、專業技能、學歷與語言能力。

## 特色

- 單頁式檢視切換（主頁介紹／專業技能／工作經驗／專案成就／學歷／聯絡方式）
- 科技感淺色設計系統：自訂配色、網格線背景、發光邊框卡片
- RWD 響應式佈局（手機／平板／桌面）
- 支援 `prefers-reduced-motion` 無障礙設定
- 內容集中於單一資料檔，易於維護更新

## 技術棧

| 項目 | 技術 |
|---|---|
| 框架 | React 19 + TypeScript |
| 建置 | Vite 6 |
| 樣式 | Tailwind CSS v4 |
| 字型 | Inter / JetBrains Mono / Noto Sans TC |
| 託管 | GitHub Pages（靜態部署） |

## 本地開發

安裝依賴後啟動開發伺服器、建置靜態產物：

```bash
npm install
npm run dev        # 開發伺服器
npm run build      # 產出 dist/
```

## 部署方式

將 `dist/` 靜態產物直接 push 至本倉庫 `main` branch（無 CI）。
GitHub Pages 會自動發布。

---

© 2026 Lee Yu Hsiang
