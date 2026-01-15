```
  ██╗  ██╗  ██████╗   ██╗   ██╗  ███████╗  ██████╗
  ██║ ██╔╝  ██╔══██╗  ╚██╗ ██╔╝  ██╔════╝  ██╔══██╗
  █████╔╝   ██████╔╝   ╚████╔╝   ███████╗  ██║  ██║
  ██╔═██╗   ██╔══██╗    ╚██╔╝    ╚════██║  ██║  ██║
  ██║  ██╗  ██║  ██║     ██║     ███████║  ██████╔╝
  ╚═╝  ╚═╝  ╚═╝  ╚═╝     ╚═╝     ╚══════╝  ╚═════╝
                      白 河 愁
```

# SnapPlus v1.0.0

> Build: 2026-01-15 22:42:24

---

## Introduction

SnapPlus is a lightweight Windows system tray tool designed for AI chat applications like Claude Desktop. After taking a screenshot, simply press the hotkey to automatically save the clipboard image as a PNG file and paste the file path at the current cursor position.

## 紹介

SnapPlus は Claude Desktop などの AI チャットアプリ向けに設計された軽量な Windows システムトレイツールです。スクリーンショットを撮った後、ホットキーを押すだけで、クリップボードの画像を PNG ファイルとして自動保存し、ファイルパスを現在のカーソル位置に貼り付けます。

## 简介

SnapPlus 是一款轻量级的 Windows 系统托盘工具，专为 Claude Desktop 等 AI 对话应用设计。当您截图后，只需按下快捷键，即可将剪贴板中的图片自动保存为 PNG 文件，并将文件路径粘贴到当前光标位置，方便直接在对话框中引用图片。

## 簡介

SnapPlus 是一款輕量級的 Windows 系統托盤工具，專為 Claude Desktop 等 AI 對話應用設計。當您截圖後，只需按下快捷鍵，即可將剪貼簿中的圖片自動儲存為 PNG 檔案，並將檔案路徑貼上到目前游標位置，方便直接在對話框中引用圖片。

---

## Usage

1. Run SnapPlus.exe, the program minimizes to system tray
2. Take a screenshot using any tool (e.g., Win+Shift+S, Snipaste)
3. Place cursor where you want to paste the path (e.g., Claude chat box)
4. Press the hotkey (default: `Ctrl+Alt+V`)
5. Screenshot is saved and file path is automatically pasted

## 使い方

1. SnapPlus.exe を実行すると、システムトレイに最小化されます
2. 任意のツールでスクリーンショットを撮ります（Win+Shift+S、Snipaste など）
3. パスを貼り付けたい場所にカーソルを置きます（Claude チャットボックスなど）
4. ホットキーを押します（デフォルト：`Ctrl+Alt+V`）
5. スクリーンショットが保存され、ファイルパスが自動的に貼り付けられます

## 使用方法（简体中文）

1. 运行 SnapPlus.exe，程序会最小化到系统托盘
2. 使用任意截图工具截图（如 Win+Shift+S、Snipaste 等）
3. 将光标放在需要粘贴路径的位置（如 Claude 对话框）
4. 按下快捷键（默认 `Ctrl+Alt+V`）
5. 截图自动保存，文件路径自动粘贴到光标位置

## 使用方法（繁體中文）

1. 執行 SnapPlus.exe，程式會最小化到系統托盤
2. 使用任意截圖工具截圖（如 Win+Shift+S、Snipaste 等）
3. 將游標放在需要貼上路徑的位置（如 Claude 對話框）
4. 按下快捷鍵（預設 `Ctrl+Alt+V`）
5. 截圖自動儲存，檔案路徑自動貼上到游標位置

---

## Tray Menu

| Menu Item | Description |
|-----------|-------------|
| Hotkey: Ctrl+Alt+V | Click to change hotkey |
| Open Save Folder | Open screenshot save directory |
| Language | Switch interface language |
| About | Visit author's homepage |
| Exit | Exit program |

## トレイメニュー

| メニュー項目 | 説明 |
|-------------|------|
| ホットキー: Ctrl+Alt+V | クリックでホットキーを変更 |
| 保存フォルダを開く | スクリーンショット保存ディレクトリを開く |
| 言語 | インターフェース言語を切り替え |
| バージョン情報 | 作者のホームページにアクセス |
| 終了 | プログラムを終了 |

## 托盘菜单

| 菜单项 | 说明 |
|--------|------|
| 快捷键: Ctrl+Alt+V | 点击可修改快捷键 |
| 打开保存文件夹 | 打开截图保存目录 |
| 语言 | 切换界面语言 |
| 关于 | 访问作者主页 |
| 退出 | 退出程序 |

## 托盤選單

| 選單項目 | 說明 |
|----------|------|
| 快捷鍵: Ctrl+Alt+V | 點擊可修改快捷鍵 |
| 開啟儲存資料夾 | 開啟截圖儲存目錄 |
| 語言 | 切換介面語言 |
| 關於 | 訪問作者主頁 |
| 結束 | 結束程式 |

---

## Save Location / 保存場所 / 保存位置 / 儲存位置

Screenshots are saved in the program directory, organized by date:

```
SnapPlus.exe
└── 2024-01-15/
    ├── 20240115_143052.png
    ├── 20240115_143108.png
    └── ...
```

---

## Configuration / 設定ファイル / 配置文件 / 設定檔

`SnapPlus.ini`

```ini
[General]
Language=0          ; 0=Auto, 1=English, 2=日本語, 3=简体中文, 4=繁體中文

[Hotkey]
Modifiers=3         ; Modifier keys / 修飾キー / 修饰键 / 修飾鍵
VirtualKey=86       ; Key code / キーコード / 按键码 / 按鍵碼 (86='V')
```

---

## System Requirements / システム要件 / 系统要求 / 系統需求

- Windows 7 / 8 / 10 / 11
- No installation required, single executable
- インストール不要、単一実行ファイル
- 无需安装，单文件运行
- 無需安裝，單檔案執行

---

**Author / 作者:** 白河愁 (Kryso)

**Homepage / ホームページ / 主页 / 主頁:** [http://www.ff18.com](http://www.ff18.com)
