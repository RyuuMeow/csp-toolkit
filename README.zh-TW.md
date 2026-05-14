# csp-toolkit

<p align="center">
  <a href="README.md">English</a> |
  <a href="README.zh-TW.md">繁體中文</a> |
  <a href="README.zh-CN.md">简体中文</a> |
  <a href="README.ja-JP.md">日本語</a>
</p>

這是一個 Clip Studio Paint 工具集入口，整理我開發的工具，以及其他由不同開發者製作、我發現有趣或實用的工具。

我開發的每個工具都有獨立的專案倉庫；這個 repo 則作為輕量索引，集中放置工具簡介、預覽圖與安裝說明連結。我也會在這裡整理一些自己發現、覺得有趣或實用的其他 CSP 工具。

## 工具列表

### [GoPieMenu](https://github.com/RyuuMeow/GoPieMenu)

一個以游標為中心的圓形選單，可以把大量 Clip Studio Paint 快捷鍵集中到同一個 PieMenu 中，並支援分類與階層式選單。不需要再記住一整套複雜快捷鍵，只要一個快捷鍵，就能直接在筆尖附近完成操作。

適合用在：

- 將大量 CSP 工具、動作與指令整理成清楚分類。
- 為大型或專門流程建立階層式快捷選單。
- 用單一快捷鍵呼叫所有常用操作，不必離開繪圖區。

<p align="center">
  <img src="demo/GoPieMenu_Demo.gif" alt="GoPieMenu demo">
</p>

---

### [ClipStudioPaint-Grayscale-Viewer](https://github.com/RyuuMeow/ClipStudioPaint-Grayscale-Viewer)

一個不干擾工作流程的 Clip Studio Paint 灰階預覽覆蓋工具。它會覆蓋在 CSP app 上方，不需要另外開視窗預覽；透過快捷鍵即可達成類似 Photoshop 的灰階預覽體驗。

適合用在：

- 在不離開 CSP 畫布的情況下切換灰階預覽。
- 不改動圖層、色彩設定或工作檔，也能檢查明度關係。
- 不必再建立臨時顏色圖層、鋪底色，並反覆開關圖層來預覽明度。
- 在 CSP 中取得接近 Photoshop 的灰階預覽流程。

<p align="center">
  <img src="demo/ClipStudioPaint-Grayscale-Viewer_Demo.gif" alt="ClipStudioPaint-Grayscale-Viewer demo">
</p>

## 我發現的其他 CSP 工具

一些由其他創作者製作、我覺得有用或有趣的 Clip Studio Paint 相關工具。

> 這些專案由各自的作者維護。安裝方式、相容性、支援與授權資訊，請以各專案倉庫中的說明為準。

- [ClipStudioPaint-Smooth-Color-Adjustment](https://github.com/MMmmmoko/ClipStudioPaint-Smooth-Color-Adjustment) - 透過 CSP 修改與外掛改善調色、常用模糊功能的預覽流暢度，也提供縮時攝影匯出選項等工作流程輔助功能。
- [clip_to_psd](https://github.com/dobrokot/clip_to_psd) - 將 Clip Studio Paint `.clip` 檔轉換為 PSD 檔的 Python 腳本。
- [CSPBrushExtract](https://github.com/MorrowShore/CSPBrushExtract) - 從 Clip Studio Paint `.sut` 筆刷檔提取參數與筆尖點陣圖。
- [Brush-Converter](https://github.com/tohsakrat/Brush-Converter) - 可從 Photoshop `.abr`、Procreate `.brushset`、Clip Studio Paint `.sut` 等筆刷格式中拆出素材圖片與參數的腳本。

## 開始使用

1. 從上方工具列表選擇想使用的工具。
2. 前往該工具的獨立專案倉庫。
3. 下載最新版本，並依照該專案的安裝說明進行設定。

由於每個工具的功能、需求與發布節奏不同，詳細安裝與使用方式會放在各自的專案倉庫中維護。

## 專案結構

```text
csp-toolkit/
├── demo/             # README 使用的預覽 GIF
├── README.md         # English project index
├── README.zh-TW.md   # 繁體中文說明
├── README.zh-CN.md   # 简体中文说明
└── README.ja-JP.md   # 日本語說明
```

## 回饋

歡迎提供錯誤回報、功能想法或工作流程建議。若問題與特定工具有關，請到該工具的專案倉庫開 issue，方便讓討論與程式碼維持在同一個地方。

## 授權

每個連結工具可能使用不同授權條款。使用、修改或散布程式碼前，請先查看各工具倉庫中的授權資訊。
