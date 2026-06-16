# 奇門問卦

## 設定 Google Sheet

1. 建立 Google Sheet，欄位順序：
   `symbol | subtitle | color | overview | advice_work | advice_wealth | advice_love | advice_misc`

2. 發佈到網路：檔案 → 共用 → 發佈到網路 → 工作表1 → CSV → 複製網址

3. 將網址貼入 index.html 的 `SHEET_CSV_URL` 變數

## 設定 LINE@ 連結

`index.html` 的 `contactLine()` 函式中 `LINE_URL` 目前是佔位符，Peter 之後會提供 LINE@ 連結再替換。

解籤結果頁面下方新增「結語引導」文字段落，引導使用者加入 LINE@，與「重新問卦」並列顯示。

## 部署到 Vercel

```bash
vercel deploy
```
