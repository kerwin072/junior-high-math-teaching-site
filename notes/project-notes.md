# 專案筆記

## 已完成

- 建立靜態網站首頁與基本樣式。
- 建立 GitHub Pages 部署工作流程。
- 建立 GitHub 儲存庫並完成公開 GitHub Pages 部署。
- 網站網址：https://kerwin072.github.io/junior-high-math-teaching-site/
- 驗證 NotebookLM 讀取與筆記本清單功能。
- 設定並驗證 Codex 可透過 MCPVault 唯讀存取 Obsidian vault。

## 下一步

1. 決定第一個上線單元與目標年級。
2. 撰寫單元的概念說明、例題與練習。
3. 在桌面與手機版檢查第一份教材頁面的可讀性。

## 踩坑筆記

- 私有 GitHub repository 在目前帳號方案無法使用 GitHub Pages；為完成公開教學網站部署，repository 已改為公開。
- GitHub CLI 推送 Actions workflow 前需具備 `workflow` scope。
- Windows 的 TOML 路徑需使用 literal string 或跳脫反斜線；PowerShell 5.1 產生的 UTF-8 BOM 也會使 Python TOML 驗證失敗。
