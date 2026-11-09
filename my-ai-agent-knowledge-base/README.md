# 我的 AI Agent 實作知識庫

這是一個以繁體中文整理 AI Agent、LLM 與 LINE 會議助理開發經驗的知識網站。專案使用 GitHub Pages 與 Jekyll，文章以 Markdown 撰寫。

## 專案內容

- `AGENTS.md`：AI 維護專案時要遵守的規則。
- `index.md`：網站首頁與文章入口。
- `knowledge/`：知識文章。
- `_layouts/`、`assets/css/`：共用頁面版型與樣式。
- `_config.yml`：Jekyll 網站設定。

## 在 GitHub Pages 發布

1. 將整個專案資料夾上傳到自己的 GitHub Repository。
2. 在 Repository 開啟 **Settings → Pages**。
3. 在 **Build and deployment** 選擇 **Deploy from a branch**。
4. 選擇 `main` 分支與根目錄 `/`，再按 **Save**。
5. 等待 Pages 完成建置，使用設定頁顯示的網址瀏覽網站。

若 Repository 名稱不是 `帳號.github.io`，GitHub Pages 網址通常會包含 Repository 名稱。網站連結使用 Jekyll 的 `relative_url`，可配合這種子路徑部署。

## 新增知識文章

先閱讀 `AGENTS.md`，再於 `knowledge/` 新增 Markdown 文章，使用小寫英文 kebab-case 檔名，並遵守 Front Matter 與段落格式。完成後將文章入口加到 `index.md`。
