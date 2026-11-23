# 紙頁 PDF工具

[下載 Windows 分享包（約 184 MB）](https://github.com/evatsai0108-dev/paperdesk-downloads/releases/download/windows-v1.0.0-beta.4/Paperdesk-1.0.0-beta.4-Windows-x64-Share.zip)

版本：1.0.0-beta.4，Windows x64 測試版。

## 安裝與使用

下載 ZIP 並解壓縮，執行資料夾中的 `Paperdesk-1.0.0-beta.4-Windows-x64-Setup.exe`，依畫面完成安裝。之後從桌面「紙頁 PDF工具」捷徑開啟，拖入 PDF 即可轉成 Word；其他轉檔、合併、切割、旋轉、編輯及浮水印功能可從左側選單選擇。

分享包包含安裝程式、安裝與使用說明、驗收報告及校驗碼。轉檔在本機執行，使用者不需帳號、API 金鑰、Node.js 或 Python；開啟產生的 Office 檔案需要相容的編輯軟體。

## 簽名與自訂圖片

在「PDF 編輯」按「選擇簽名／圖片」，選 PNG 或 JPEG 後在頁面點一下放置。透明 PNG 可保留透明背景，支援移動、等比例縮放、刪除、復原及另存後繼續編輯。

## JPG／JPEG 轉 Word 與 PDF 加密

選「JPG 轉 Word」，拖入圖片即可批次辨識文字與表格，另存可編輯 Word。手機照片方向會自動套用，原圖與既有結果保留。

選「PDF 加密」，加入 PDF、輸入並確認開啟密碼，以 AES-256 另存新檔。App 不會儲存密碼，請自行保存。

## 圖片表格編輯修正

圖片與少量文字層混合的 PDF 會辨識圖片內的表格文字，並保留原有文字且避免重複。表格以 Word 儲存格輸出，空白格可輸入文字，確認的格內斜線以原生框線儲存。

## 驗收與使用範圍

同一份安裝包已通過 Windows Server 2025 x64 與 Windows 11 ARM64 的 x64 相容模式驗收。每個環境各通過 24 項核心案例、18 組桌面流程，以及實際安裝、桌面與開始功能表捷徑啟動、解除安裝。詳細內容見 [驗收結果](VALIDATION.md)。

Windows 10 與 Intel／AMD 的 Windows 11 尚未另做實機驗收。低解析掃描、小字、注音及複雜版面仍需核對原稿。此版尚未使用發行者憑證數位簽章，Windows 可能顯示發行者未驗證提示。

## 下載與校驗

- [直接下載 Windows 分享包](https://github.com/evatsai0108-dev/paperdesk-downloads/releases/download/windows-v1.0.0-beta.4/Paperdesk-1.0.0-beta.4-Windows-x64-Share.zip)
- [版本下載頁](https://github.com/evatsai0108-dev/paperdesk-downloads/releases/tag/windows-v1.0.0-beta.4)
- [安裝與使用說明](INSTALL.txt)
- [SHA-256 校驗碼](SHA256SUMS.txt)

第三方元件的授權與聲明保留在完整安裝目錄內。本倉庫提供安裝包下載與公開使用說明。
