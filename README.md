# Ailes Track Club Webサイト

埼玉・東京・千葉を中心に活動する走り方教室・アスリート育成クラブ「Ailes Track Club（エールズトラッククラブ）」の1ページ完結型ランディングページです。

## ファイル構成

```text
.
├── index.html
├── styles.css
├── script.js
├── README.md
├── coach-photo.jpg
├── hero-sprint-school.png
└── assets/
    ├── coach-photo.jpg
    └── hero-sprint-school.png
```

## 編集しやすい場所

- 申込フォームのリンク：`index.html`内の `https://forms.gle/7rFG9adoMvdD8aaG7`
- LINEのリンク：`index.html`内の `https://lin.ee/XRpvNZC`
- Instagramのリンク：`index.html`内の `https://www.instagram.com/h18_.aru?igsh=MXN0c2FvM2psMmV0dg%3D%3D&utm_source=qr`
- メイン写真：`hero-sprint-school.png` を同じ名前の画像に差し替え
- コーチ写真：`coach-photo.jpg` を同じ名前の画像に差し替え
- 色：`styles.css` の最上部にある `:root` 内の色指定
- コース紹介：`index.html` の `id="courses"` セクション
- 料金案内：`index.html` の `id="price"` セクション
- オンライン指導：`index.html` の `id="online"` セクション
- 活動エリア：`index.html` の `id="place"` セクション

## 公開方法

静的サイトなので、`index.html`、`styles.css`、`script.js`、画像ファイルをそのままGitHub Pages、Netlify、Vercelなどにアップロードすれば公開できます。
