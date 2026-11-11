# SaintMocap VRM Toolkit

VRM 角色轉換、檢視與調整工具。提供快速模式與專家模式，支援 VRM／HIK FBX 雙向轉換、骨架定義、材質與物理設定，以及 VMC 動作預覽。

A Windows toolkit for VRM / HIK FBX conversion, character inspection, materials, spring-bone physics and VMC motion preview.

## 介紹影片 / Introduction

[![觀看 SaintMocap VRM Toolkit 介紹影片](https://img.youtube.com/vi/DB7uInSvNzQ/hqdefault.jpg)](https://youtu.be/DB7uInSvNzQ)

[▶ 觀看影片 / Watch the introduction](https://youtu.be/DB7uInSvNzQ)

## 下載 / Download

**[下載 Windows x64 一般版 2.0.2 beta](https://github.com/hysaint3d/SaintMocap_VRM_Toolkit/releases/download/v2.0.2-beta/SaintMocap_VRM_Toolkit_2.0.2-beta_Windows_x64.zip)**

[所有版本與更新說明 / Releases](https://github.com/hysaint3d/SaintMocap_VRM_Toolkit/releases)

## 開始使用 / Getting started

1. 下載 ZIP 並完整解壓縮，不要只取出 exe。
2. 執行 `SaintMocap_VRM_Toolkit.exe`。
3. 選擇快速模式或專家模式，再開啟 VRM／FBX。
4. 確認骨架定義與必要模型資訊後，匯出 HIK FBX 或 VRM 1.0。

Extract the entire ZIP and run `SaintMocap_VRM_Toolkit.exe`. Keep the data folders and DLLs alongside it. No Unity Editor installation is required.

| 模式 / Mode | 用途 / Purpose |
|---|---|
| Quick | 標準角色：開檔 → 確認 → 匯出 / Open, check, export |
| Expert | 自訂骨架、材質、物理與動作預覽 / Mapping, materials, physics and motion preview |

## 版本範圍 / Edition

- 此下載適用於 **Windows x64**。/ Available for Windows x64.
- VMC 預設 UDP 39539，可自行設定。/ Configurable VMC port; default UDP 39539.
- NDI 輸出需另外安裝相容的 NDI Runtime。/ NDI output requires a separately installed compatible NDI Runtime.
- 目前沒有提供 macOS 執行檔。/ No macOS build is provided yet.
- 未包含示範模型。/ Demonstration models are not included.

## 校驗 / Verification

Release 提供 `SHA256SUMS.txt`，可核對下載 ZIP 的 SHA-256。

```powershell
Get-FileHash .\SaintMocap_VRM_Toolkit_2.0.2-beta_Windows_x64.zip -Algorithm SHA256
```

## 回報問題 / Feedback

請使用本 Repo 的 [Issues](https://github.com/hysaint3d/SaintMocap_VRM_Toolkit/issues)，附上版本、重現步驟與錯誤訊息；分享模型前請確認有權提供，避免公開私人資料。

This repository is for downloads, documentation and feedback. Source development remains in [SaintMocap_Operator / SaintMocap_VRM_Toolkit](https://github.com/hysaint3d/SaintMocap_Operator/tree/main/SaintMocap_VRM_Toolkit).

Beta 軟體：請保留原始模型，並在目標軟體確認匯出結果。模型、貼圖與其他素材權利歸原權利人所有。

Designed by Saint Hsu · SaintMocap
