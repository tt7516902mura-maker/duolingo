# Duolingo Landing Page Clone

Duolingo風のデザインを参考に作成した、レスポンシブ対応のランディングページです。

> ※ 学習・ポートフォリオ目的のサンプルサイトです。Duolingo公式とは関係ありません。

---

## デモ

**GitHub Repository**

https://github.com/tt7516902mura-maker/duolingo

---

## 使用技術

* HTML5
* Tailwind CSS (CDN)
* Google Fonts (Noto Sans JP)
* SVG
* レスポンシブデザイン

---

## 特徴

* レスポンシブ対応
* 固定ナビゲーションバー
* ヒーローセクション
* 特徴紹介セクション
* 学習方法紹介
* 利用者レビュー
* CTA（Call To Action）
* フッター

---

## ディレクトリ構成

```text
duolingo/
├── index.html
└── README.md
```

---

## デザインコンセプト

Duolingoをイメージした

* グリーンを基調とした配色
* 丸みのあるカードデザイン
* 見やすいタイポグラフィ
* シンプルで親しみやすいUI

を採用しています。

---

## カスタマイズ

### ロゴ

SVGを変更することで自由に変更できます。

### レビュー画像

現在は絵文字を使用しています。

```html
<div class="w-12 h-12 bg-green-100 rounded-full mr-4 flex items-center justify-center text-2xl">
👩🏻
</div>
```

画像を使用する場合は、

```html
<img src="keiko.jpg" class="w-12 h-12 rounded-full mr-4 object-cover">
```

へ変更してください。

---

## 実行方法

リポジトリをクローンします。

```bash
git clone https://github.com/tt7516902mura-maker/duolingo.git
```

フォルダへ移動します。

```bash
cd duolingo
```

その後、`index.html` をブラウザで開くだけで閲覧できます。

サーバーの構築は不要です。

---

## ライセンス

このプロジェクトは学習・ポートフォリオ用途を目的としたサンプルです。

Duolingoの名称・ロゴ・デザイン等の権利は、それぞれの権利者に帰属します。

商用利用や公式サービスとしての公開は行わないでください。

---

## 作者

GitHub

https://github.com/tt7516902mura-maker

---

## スクリーンショット

スクリーンショットを `images/` フォルダへ保存し、以下のように表示できます。

```markdown
![Screenshot](images/screenshot.png)
```
