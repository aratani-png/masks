# SegmentationMaskPainter v0.5-mod

白黒マスク出力＆影検出機能を追加した改造版です。

## インストール

### 1. リポジトリをクローン
```bash
git clone https://github.com/aratani-png/masks.git
cd masks
```

### 2. 必要なライブラリをインストール
```bash
pip install torch torchvision numpy pillow opencv-python transformers
```

## 起動方法

**`run.bat` をダブルクリック**

または:
```bash
python SegmentationMaskPainter.py
```

## 追加機能

### 白黒マスク出力 (3DGS用)
- 対象物 = 白 (255)
- 背景 = 黒 (0)
- ファイル名: `*_mask.png`

### 影マスク出力
- 地面の暗い領域を影として検出
- 輝度閾値で調整可能 (0-255)
- ファイル名: `*_shadow.png`

## ライセンス
CC0 (パブリックドメイン)
