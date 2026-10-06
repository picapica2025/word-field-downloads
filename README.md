# 野外詞語採集 v0.42.0

本次候選為 Windows x64 便攜版。解壓後執行 `app/WordField.exe`；需要 Microsoft Edge WebView2 Evergreen Runtime，不需 Node.js 或網路伺服器。存檔保存在 `%LOCALAPPDATA%\WordField\WebView2`，與瀏覽器版分開。完整操作和遷移方式見 ZIP 內 `START_HERE.md`。

## 本版內容

- 單一 IELTS 備考詞書，6,550 個詞條與 12,840 條例句記錄。
- 詞庫不是官方 IELTS 詞表；所有詞條仍待獨立人工語言審校。
- 遊戲已有本機存檔、營地、採集與學習循環、複習、圖鑑、筆記、成就和桌面存檔遷移入口。

## 驗收

- 自動測試：249 通過、0 失敗。
- 程式語法檢查：通過。
- Windows 桌面 smoke test：營地主畫面渲染、刷新後本機存檔回讀通過。
- 測試範圍不代表已在多種實體電腦上完成相容性測試；目前尚未簽署，也不是安裝程式或商店版。

## 授權與第三方內容

ZIP 內包含 ECDICT、Tatoeba、OpenCC 衍生檢索資料的來源聲明及相關許可文本。請依包內 `app/wwwroot/THIRD_PARTY_NOTICES.md` 保留逐句署名及來源資訊。專案自身程式碼與原創素材尚未設定公開許可，故不提供修改、再散佈或商用授權聲明。

## 附件

- `WordField-Windows-x64-v0.42.0.zip`：Windows x64 便攜包。
- `preview-night-camp.png`：實際桌面 smoke test 畫面。
- `RELEASE_NOTES_v0.42.0.md`：此版本記錄。
- `SHA256SUMS.txt`：ZIP 與預覽圖校驗值。

