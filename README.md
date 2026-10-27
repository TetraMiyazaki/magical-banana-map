# 🍌 マジカルバナナマップ

「亀戸といえばホルモン」「下北沢といえばカレー」みたいな、東京の街の「〜といえば」をまとめたスマホ向けの1ページマップです。

- 地図のピンをタップすると「〇〇といえば…」が出ます
- 「🎲 〜といえば？」ボタンでランダム出題（答えはタップで表示）
- 下のリストから検索もできます

## 追加のしかた

`index.html` の `SPOTS` 配列に1行足すだけです。緯度経度はだいたいでOK（Googleマップで右クリックするとコピーできます）。

```js
{ area: "亀戸", keyword: "ホルモン", emoji: "🥩", lat: 35.6974, lng: 139.8263, note: "ひとこと説明" },
```

## 公開（GitHub Pages）

1. リポジトリの Settings → Pages を開く
2. Source を「Deploy from a branch」、Branch を `main` / `/ (root)` にして Save
3. 数分後に `https://tetramiyazaki.github.io/magical-banana-map/` で見られます

ビルドは不要です（`index.html` 1枚だけ）。
