# Duolingo Landing Page Clone

Duolingo風のデザインを参考に作成した、レスポンシブ対応のランディングページです。

> ※ 学習・ポートフォリオ目的のサンプルサイトです。Duolingo公式とは関係ありません。

---

## デモ

ブラウザで `index.html` を開くだけで動作します。

---

## 使用技術

- HTML5
- Tailwind CSS (CDN)
- Google Fonts (Noto Sans JP)
- SVG
- レスポンシブデザイン

---

## 主な機能

- レスポンシブ対応
- 固定ナビゲーション
- ヒーローセクション
- 特徴紹介
- 学習方法紹介
- 利用者レビュー
- CTA(Call To Action)
- フッター

---

## ディレクトリ構成

```
project/
│
├── index.html
└── README.md
```

---

## セクション一覧

- Navigation
- Hero
- Statistics
- Features
- Learning Method
- Reviews
- CTA
- Footer

---

## デザイン

Duolingoをイメージした

- グリーンを基調とした配色
- 大きなボタン
- 丸みのあるカード
- シンプルで見やすいUI

を採用しています。

---

## カスタマイズ

### ロゴ

SVGを変更することで自由に変更できます。

### レビュー画像

現在は絵文字を使用しています。

例

```html
<div class="w-12 h-12 bg-green-100 rounded-full mr-4 flex items-center justify-center text-2xl">
👩🏻
</div>
```

画像に変更する場合は

```html
<img
    src="keiko.jpg"
    class="w-12 h-12 rounded-full mr-4 object-cover"
>
```

のように変更してください。

---

## 実行方法

1. このリポジトリをクローン

```bash
git clone https://github.com/yourname/duolingo-landing-page.git
```

2. フォルダへ移動

```bash
cd duolingo-landing-page
```

3. `index.html` をブラウザで開く

サーバーは不要です。

---

## ライセンス

このプロジェクトは学習・ポートフォリオ用途を目的としたサンプルです。

Duolingoの名称・ロゴ・デザインに関する権利はそれぞれの権利者に帰属します。

商用利用や公式サイトとしての公開は行わないでください。

---

## 作者

GitHub: https://github.com/tt7516902mura-maker

---

## スクリーンショット

完成後のスクリーンショットを `images/` フォルダに保存し、以下のように表示できます。

```markdown
![Screenshot](images/screenshot.png)
```
