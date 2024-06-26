---
theme: seriph
background: top.jpg
title: Alfred vs Raycast
class: text-center
highlighter: shiki
transition: slide-left
mdc: true
export:
  dark: true
hideInToc: true
---

# Alfred vs Raycast

2024-06-27 社内 LT 大会

<p class="absolute bottom-10 right-10 font-700">
  mitani24
</p>

---

# [Alfred](https://www.alfredapp.com/) と [Raycast](https://www.raycast.com/)

- どちらも macOS で使えるランチャーアプリ
  - macOS 標準の Spotlight 機能をより強力にしたもの

|   | Alfred | Raycast |
|---| ------ | ------- |
| Initial Release | (2010) | (2020) |
| Stable Release | v5.5 (2024) | v1.77.0 (2024) |
| 有料版 | £34 (¥6,891) | $8/month (¥1,278/月) |

<div class="mt-4 text-right text-xs text-gray">
※ 価格は 2024-06-26 時点の為替レート (1 USD = 159.78 JPY, 1 GBP = 202.69 JPY) に基づいて換算しています
</div>

---
layout: fact
---

# Alfred のデモ

⌥ Option + Space

<!--
- 検索
  - アプリ (e.g. Notion)
  - ファイル (e.g. Download)
  - ブックマーク (e.g. Cateras)
  - ウェブ検索 (e.g. 新宿のうどん屋)
- OS の操作 (e.g. sleep, restart)
- 計算機
- Workflow
  - ChatGPT
  - apb
-->

---
layout: fact
---

# Raycast のデモ

⌘ Command + Space

<!-- 
- 検索
  - アプリ (e.g. Notion)
  - ファイル (e.g. Search File => Download)
  - ブックマーク (e.g. Search Browser Bookmarks => Cateras)
  - ウェブ検索 (e.g. Search Google => 新宿のうどん屋)
- OS の操作 (e.g. sleep, restart)
- 計算機
  - sqrt, abs
  - 単位変換 (e.g. $10, 10rem, 10inch)
- Extension
  - ChatGPT
  - Philips Hue
  - Unsplash
-->

---

# Alfred の優位性

- 串刺し検索
- ビジュアル・プログラミングによる拡張機能開発

<div class="mt-8" />

# Raycast の優位性

- 無料版でより多くのことを行うことができる
- リッチなインターフェース
- 豊富な拡張機能
- React + TypeScript による拡張機能開発

---
layout: image-right
image: top.jpg
backgroundSize: contain
---

# 結論

- ランチャーアプリ超便利
- まず試すなら Raycast 👑
  - わざわざ Alfred 有料版を購入するほどの優位性はない
- Alfred 有料版購入者なら併用するとよいかも
  - どっちかにしかない拡張機能がある
