# 株式会社 侍友 — コーポレートサイト

## ファイル構成

```
ziu-HP/
├── index.html    # メインページ（全セクション）
├── style.css     # スタイルシート
├── favicon.svg   # SVGファビコン（葉モチーフ）
├── _headers      # Cloudflare Pages セキュリティヘッダー
├── _redirects    # www リダイレクト設定
└── ogp.png       # OGP画像（別途用意: 1200×630px）
```

## Cloudflare Pages デプロイ手順

1. GitHub Organization `Conippo-works` にリポジトリ `ziu-HP` を作成
2. このフォルダの全ファイルをプッシュ
3. Cloudflare Dashboard → Pages → 「新しいプロジェクトを作成」
4. GitHub リポジトリ `Conippo-works/ziu-HP` を連携
5. ビルド設定：
   - フレームワーク: なし（静的HTML）
   - ビルドコマンド: 空欄
   - ビルド出力ディレクトリ: `/`（ルート）
6. カスタムドメインを追加（取得済みの場合）

## OGP画像について

`ogp.png`（1200×630px）を別途作成してルートに配置してください。
- 背景: ダークグリーン（#1b4332）グラデーション
- テキスト: 「大地の恵みを、まっすぐ食卓へ。」+ 株式会社 侍友
