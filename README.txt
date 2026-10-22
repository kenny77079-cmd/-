無盡弓域 V25｜固定中央透明虛擬搖桿版 iPhone 部署包

部署方式（沿用 GitHub Pages）：
1. 解壓縮本 ZIP。
2. 將 index.html、manifest.json、service-worker.js、icons 資料夾上傳到 GitHub 遊戲儲存庫的根目錄（與 Pages 設定的 main / (root) 相同）。
3. GitHub 儲存庫 → Settings → Pages，確認 Branch 為 main、資料夾為 /(root)，儲存。
4. 等待 Pages 部署完成，使用 iPhone 的 Safari 開啟網站 HTTPS 網址。
5. 點 Safari「分享」→「加入主畫面」→ 加入。從主畫面圖示開啟，即可像 App 一樣使用。

注意：本包已加入 PWA manifest、主畫面圖示與離線快取設定，但尚未替你上傳到 GitHub。若遊戲原本還有外部素材網址，首次載入時仍需網路；離線可用程度需在實機測試。更新後若仍顯示舊版，可先從主畫面關閉再開，或清除網站資料。
