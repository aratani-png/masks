# SegmentationMaskPainter v0.5-mod

白黒マスク出力＆影検出機能を追加した改造版です。

---

## ダウンロード

### [>>> ZIPでダウンロード <<<](https://github.com/aratani-png/masks/archive/refs/heads/main.zip)

---

## インストール手順

### 1. 上のリンクからZIPをダウンロードして解凍

### 2. 必要なライブラリをインストール
コマンドプロンプトで以下を実行:
```bash
pip install torch torchvision numpy pillow opencv-python transformers
```

### 3. 起動
解凍したフォルダ内の **`run.bat`** をダブルクリック

---

## 追加機能

### 白黒マスク出力 (3DGS用)
- 対象物 = 白 (255)
- 背景 = 黒 (0)
- ファイル名: `*_mask.png`

### 影マスク出力 (人の影のみ)
- 人物の近くにある地面の暗い領域を影として検出
- 輝度閾値で調整可能 (0-255)
- ファイル名: `*_shadow.png`

---

## ライセンス
CC0 (パブリックドメイン)
