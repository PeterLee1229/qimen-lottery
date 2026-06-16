# 奇門問卦

## 設定 Google Sheet

1. 建立 Google Sheet，欄位順序：
   `symbol | subtitle | color | overview | advice_work | advice_wealth | advice_love | advice_misc`

2. 發佈到網路：檔案 → 共用 → 發佈到網路 → 工作表1 → CSV → 複製網址

3. 將網址貼入 index.html 的 `SHEET_CSV_URL` 變數

## 部署到 Vercel

```bash
vercel deploy
```
