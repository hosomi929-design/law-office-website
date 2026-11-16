# 法律事務所ホームページ (Astro)

```
npm install
npm run dev      # http://localhost:4321
npm run build    # dist/ に静的ファイルを出力
```

## 差し替えるもの
- `public/images/slide1.jpg`, `slide2.jpg` … トップのスライド画像（金沢駅鼓門の写真など）
- `src/pages/index.astro` … 取扱分野・プロフィール・連絡先などの文言
- `src/components/Hero.astro` … スライドの見出し・ボタン
- `src/layouts/Layout.astro` … 事務所名・meta description
