# PawCauldron

[PawCauldron](https://www.curseforge.com/wow/addons/pawcauldron) 是一款整合多種實用功能的輕量化魔獸世界介面插件。這個 repo 放打包好的版本，目前主要是**還沒正式發布的測試版**，給願意幫忙測試、回報問題的玩家下載。

> ⚠️ 標著 **Pre-release** 的是測試版：可能還有問題，也可能多了測試用的按鈕或功能。只想正常使用的話，請裝 CurseForge 上的正式版。

## 下載

到 [Releases](../../releases) 下載：

- `PawCauldron_<版本>-installer.zip`：附「安裝.bat」「還原.bat」，雙擊就能安裝（建議）
- `PawCauldron_<版本>.zip`：只有插件本身，自己解壓到 `World of Warcraft\_retail_\Interface\AddOns\`

每一版的說明裡都有檔案的 SHA-256，可以用來確認下載的檔案沒有被改過。

## 安裝（installer 版）

1. 完全關閉魔獸世界。
2. 在 zip 上按右鍵 →「全部解壓縮」。
3. 打開解壓出來的資料夾，雙擊「安裝.bat」，照視窗說明操作。
   Windows 若顯示「Windows 已保護您的電腦」，按「其他資訊」→「仍要執行」。

原本裝的 PawCauldron 會先備份到 `_retail_\Interface\PawCauldron_backups`；設定與存檔（WTF 資料夾）不會動。
要換回原本的版本：關閉遊戲後雙擊「還原.bat」。

如果你用 CurseForge App 管理插件，測試期間先不要更新 PawCauldron，否則可能會被換回正式版。

## 回報問題

- 遊戲裡：PawCauldron 設定 → 快捷 → 訊息提示 →「複製錯誤回報」，按 Ctrl+C 複製後，傳給提供你測試版的人。
- 紀錄要在 `/reload` 或正常登出時才會存檔；遊戲閃退的那一場記不到。

## 授權

這個 repo 只放打包好的版本，不含開發紀錄。插件以 MIT 授權發布（見壓縮檔內的 `LICENSE`）。

---

**English**: Packaged builds of the PawCauldron World of Warcraft addon — currently mostly pre-release test builds. Download from [Releases](../../releases); releases marked **Pre-release** are test builds. The `-installer.zip` contains `安裝.bat` (install) and `還原.bat` (restore); close the game, extract the zip, and double-click. Your previous PawCauldron is backed up to `_retail_\Interface\PawCauldron_backups`; settings (WTF) are not touched. For normal use, install the release version from CurseForge.
