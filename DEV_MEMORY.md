# 小教室簡易版（8 頁三欄實戰版）開發與維護記憶

> 專屬 GitHub 儲存庫：`https://github.com/snowsepch/workshop-generator-simple.git`
> 專屬線上 Pages 網址：`https://snowsepch.github.io/workshop-generator-simple/`
> 本地目錄：`/Users/sep/Library/Mobile Documents/com~apple~CloudDocs/小教室簡易版`

---

## 核心定位與規格
- **版型架構**：8 頁投影片 · 三欄工作台（左欄主題庫 68 門課、中欄投影片縮圖、右欄大畫面預覽與演講者備忘錄）。
- **特有功能**：
  1. 課前 3 分鐘速覽卡。
  2. 雙主題海報（規劃兩堂課）。
  3. **AI 海報指令轉換器（Gemini ✕ ChatGPT ✕ Claude ✕ Midjourney）**。
  4. PPTX 演講者備忘稿匯出。
- **頁面 Title**：`<title>Apple Shop 小教室專案 · 簡易版</title>`
- **導覽列識別**：`Apple Shop 小教室專案 簡易版 v2.6 官方校正版`

---

## 絕對維護鐵律
1. **本目錄專屬推送 `workshop-generator-simple`**，嚴禁跨目錄推播至其他儲存庫。
2. 每次推送前執行 pre-flight check：
   ```bash
   git remote -v
   grep "<title>" index.html
   ```
3. 嚴禁在未備份的情況下執行外部 force-push。
