# 你的片單，你的時間表。

批量場次整理與 Google 日曆匯入工具。程式碼以 GitHub 版控，網站使用 Firebase Hosting。

## 功能

- 批量解析多行或單行場次資訊
- 編輯日期、時長、座位與開演前預留時間（預設 10 分鐘）
- 批次刪除與復原、重疊提示、匯出 ICS
- 台北時區；資料僅在瀏覽器處理，不會上傳或自動儲存

## 本機使用

以瀏覽器開啟 index.html。

## 部署

安裝官方 Firebase CLI，執行 firebase login，再以 firebase use --add 選擇專案，執行 firebase deploy --only hosting。
