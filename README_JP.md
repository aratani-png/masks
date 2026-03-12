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
- 入力と同じファイル名で出力 (PNG形式)

### 人の影検出 (shadowクラス)
- 対象物一覧から「shadow」を選択して使用
- 人物の近くにある地面の暗い領域を影として検出
- 輝度閾値スライダーで検出感度を調整 (0-255)
- 他のクラス（建物、空など）と同様にRGBA値を設定可能

---

## ライセンス
CC0 (パブリックドメイン)
