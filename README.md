# ⚡ 小赫的每日任務 Checklist

小學二年級學生的每日任務追蹤網站，寶可夢風格設計。

🔗 **網站連結**
- [小赫的任務頁面](https://dada3c.github.io/htctors-check-list/)
- [爸媽 Dashboard](https://dada3c.github.io/htctors-check-list/dashboard.html)

---

## 功能

**小赫的頁面**
- 13 個每日任務，分 4 個區塊（回家後 / 作業與閱讀 / 睡前準備 / 睡覺前）
- Pokéball 打勾動畫
- 每完成 3 項觸發寶可夢慶祝彈窗 + 彩帶動畫
- 全部完成顯示大獎盃慶祝

**爸媽 Dashboard**
- 今日完成率即時顯示
- 每個任務的完成狀態
- 最近 7 天完成率趨勢圖
- 新增 / 刪除任務

**資料同步**
- Firebase Firestore 雲端儲存
- 任何裝置開啟資料都同步

---

## 技術架構

| 項目 | 技術 |
|------|------|
| 前端 | HTML / CSS / JavaScript（原生） |
| 資料庫 | Firebase Firestore |
| 部署 | GitHub Pages |

---

## 本地開發

```bash
npx serve . --listen 3000
```

開啟 http://localhost:3000

---

## Firebase 專案

- Project ID：`htctors-check-list`
- Firestore 集合：`checklist`（每日紀錄）、`config`（任務設定）
