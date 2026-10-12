# Agent Instructions

## Google Drive Build 交付規範（所有 Agent 必須遵守）
- 每個 GitHub Repository 的 Google Drive 專案目錄固定為 `AI Project/rtk/`（AI Project folder ID `1Yhfro6Ss5TSCXCVIZIHEu5h7V1gL8b27`），名稱必須和 Repo 一致。不要在 `AI Project/` 根目錄散放檔案。
- **最新完整且已驗證 Build 直接放專案資料夾根目錄**。附 ZIP／EXE、SHA-256、所有分割 ZIP、還原工具與操作說明（依需求）；多平台可並存各自最新版。先核對成功上傳的 parent、版本、檔案大小、checksum；缺 ZIP 或只有 SHA 時不可取代完整舊版。
- **重要版本差異**（功能、架構、重大美術、相容性）才建立 `vX.Y.Z-說明/` 子資料夾保留。一般舊版非破壞性移入 `歷史封存/`，不刪除；每次例行 Build 不要另建版本資料夾。
- 新開發均提交／推送 GitHub。昂貴建置／發布 Actions 僅手動 `workflow_dispatch` 或正式 `release: published` 時觸發，不要每次 push main 就跑。未實際 Build／驗證成功，不得宣稱完成；回報 Drive 專案連結、版本和校驗結果。
**English for Codex:** Put newest complete verified build(s) directly at `AI Project/rtk/`; create version folders only for material milestones, archive routine older builds in `歷史封存/` without deleting files.
