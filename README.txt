北市勤務排程 B 全覽模式 v1

檔案內容
1. index.html              主程式
2. manifest.webmanifest    PWA 設定
3. sw.js                   離線快取 / App 化
4. icon-192.png            App 圖示
5. icon-512.png            App 圖示
6. README.txt              本說明

部署到 GitHub Pages
1. 建立一個新的 GitHub repository，例如：beishi-schedule
2. 將這 6 個檔案全部上傳到 repository 根目錄
3. Repository → Settings → Pages
4. Build and deployment 選 Deploy from a branch
5. Branch 選 main，資料夾選 /(root)，按 Save
6. 等待約 1～3 分鐘，GitHub 會產生 Pages 網址

目前版本說明
- 這版已可直接部署及手機瀏覽。
- 勤務資料目前仍寫在 index.html 內，屬於「實際資料展示版」。
- 下一階段會改成從 Google Sheet 自動讀取，不必重複維護資料。
- 等先用真實網址在手機上確認版面後，再調整字級、密度、人員方塊、欄位顯示方式。
