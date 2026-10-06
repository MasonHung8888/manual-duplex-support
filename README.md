# PDF 手動雙面列印官方網站

這是「PDF 手動雙面列印」iPhone、iPad 與 Mac 版本的官方產品、客服支援與隱私權網站。

## 網站頁面

- `dist/index.html`：產品介紹與跨平台功能
- `dist/support.html`：客服方式與常見問題
- `dist/privacy.html`：iPhone、iPad 與 Mac 共用隱私權政策
- `dist/assets/mac-app-interface.jpg`：Mac 版實際操作介面
- `dist/assets/ios-home.png`：iPhone／iPad 版首頁
- `dist/assets/ios-tutorial.png`：iPhone／iPad 版手動雙面列印教學
- `dist/assets/ios-file-picker.png`：iOS 系統檔案選擇器
- `dist/assets/ios-support-privacy.png`：手機版客服、隱私與版本資訊
- `dist/assets/ios-lifetime-unlock.png`：免費試印與終身解鎖畫面

## iPhone／iPad 版說明

手機版會先透過 AirPrint 送出正面。待正面全部印完後，依 App 的校正提示整疊翻紙，再按「開啟系統背面列印選單」，於 iOS 系統選單中再次選擇「列印」並確認同一台印表機，送出背面工作。這是 iOS 版的正常操作流程。

每份 PDF 的原始前 8 頁可免費試印；一次買斷後可列印第 9 頁以後與整份 PDF，並可使用同一 Apple ID 恢復購買。

客服聯絡人：Mason Hung  
Email：taijia1025@gmail.com

## GitHub Pages

推送到 `main` 分支後，GitHub Actions 會自動將 `dist` 資料夾部署到 GitHub Pages。

第一次使用時，請到儲存庫的 `Settings → Pages`，將來源選為 `GitHub Actions`。
