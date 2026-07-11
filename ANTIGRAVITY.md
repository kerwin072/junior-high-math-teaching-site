# 專案工作規則

## 專案目標

建立一個提供國中數學教材與互動學習資源的教學網站，部署到 GitHub Pages。

## 開發原則

- 網站維持純靜態 HTML、CSS 與 JavaScript，優先確保 GitHub Pages 可直接部署。
- 教材內容使用繁體中文；發布前確認題目、解答與公式正確。
- 不將學生姓名、成績或其他個人資料提交到儲存庫。
- 每次變更後，以瀏覽器檢查桌面與手機版面。

## 常用指令

```powershell
git status
```

GitHub Pages 由 `.github/workflows/deploy-pages.yml` 在推送到 `main` 後部署。
