# 國中數學教材網站

提供國中數學主題教材、練習與互動學習資源的靜態網站。

## 本機預覽

直接用瀏覽器開啟 `index.html`，或使用任一靜態網站伺服器預覽。

## 部署

推送到 `main` 後，GitHub Actions 會部署到 GitHub Pages。第一次部署前，請到 GitHub 儲存庫的 **Settings → Pages**，將 Source 設為 **GitHub Actions**。

> 私有儲存庫是否能使用 GitHub Pages 取決於帳號或組織方案；若 GitHub 顯示限制，可改為公開儲存庫或選用其他部署服務。

## 專案結構

- `index.html`：網站首頁
- `styles.css`：網站樣式
- `.github/workflows/deploy-pages.yml`：GitHub Pages 部署流程
- `notes/project-notes.md`：專案筆記與待辦事項
