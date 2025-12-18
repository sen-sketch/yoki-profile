# yoki-profile

ブラウザだけで動く、1枚構成のプロフィールページです。  
HTML / CSS / JavaScript の基礎学習と、GitHub Pages 公開を目的として制作しました。

🔗 公開URL  
https://sen-sketch.github.io/yoki-profile/

---

## 概要

- ページ数：1ページ
- 外部ライブラリ：なし
- ビルド工程：なし（そのまま公開）
- モバイルファースト設計

Yoki というキャラクターを紹介するための、  
軽量でシンプルなポートフォリオページです。

---

## 主な機能

- 🌗 ライト / ダークモード切り替え（localStorage保存）
- 🖼 プロフィール画像（中央・丸型）
- 🖼 ギャラリー表示（4枚）
- 🔍 ギャラリー画像のモーダル拡大表示
- ▶ Recommend Video（YouTubeリンク・軽量）
- 📱 モバイル優先レイアウト
- ⌨ キーボード操作対応（フォーカス / Esc）

---

## ディレクトリ構成

```text
yoki-profile/
├─ index.html
├─ images/
│  ├─ yoki.jpeg
│  ├─ gallery-1.webp
│  ├─ gallery-2.webp
│  ├─ gallery-3.webp
│  ├─ gallery-4.webp
│  ├─ video-1.png
│  └─ video-2.png
└─ README.md```

## 作業ログ

- 2025-12-18
  - images フォルダへ画像を移行
  - モーダル表示の不具合を修正
  - ダークモードの可読性を改善
  - GitHub Pages（main / root）でサイトを公開
