---
theme: seriph
background: https://cover.sli.dev
title: Alfred と Raycast を併用したら便利だった話
class: text-center
highlighter: shiki
transition: slide-left
mdc: true
export:
  dark: true
hideInToc: true
---


# Alfred と Raycast を併用したら便利だった話

2024-06-27 社内 LT 大会

<p class="absolute bottom-10 right-10 font-700">
  mitani24
</p>

---
hideInToc: true
---

# 目次

<Toc />

---

# [Alfred](https://www.alfredapp.com/) の特徴

- macOS で使えるランチャーアプリの定番
  - Mac 標準の Spotlight の上位互換
- 高機能
  - アプリ・ファイル・ブックマーク・ウェブページの検索
  - OS 機能の操作
  - クリップボード履歴
  - Workflow（公式やサードパーティが開発した拡張機能）
  - Snippets
- 価格
  - 有料版は買い切り £34 (¥6,800)
  - 無料版では Workflow などの強力な機能が使えないので基本課金する人が多いはず

---

# [Raycast](https://www.raycast.com/) の特徴

- Alfred の対抗馬の新生ランチャーアプリ
  - こちらも macOS のみ
- モダンな UI/UX
  - 串刺し検索できる Alfred に対して Raycast はモーダル的
- 地味に便利なツールが入っている
  - e.g. Floating Notes, Calculator
- サードパーティによる Extension 開発が活発
  - ニッチなサービスと連携する Extension も割とある
- 価格
  - 有料版は $8/month (¥1,250/月)
  - 無料版で十分な人が多そう

---

# Alfred と Raycast の使い分け

- 原則 Alfred を使用する (⌘ + Space)
  - やはり串刺し検索できる Alfred の方が効率的
  - Raycast には (⌥ + Space) を割り当てる
- Hotkey に登録する使用頻度の高い機能は Raycast を使用する
  - Hotkey ならモーダル的でもほぼ気にならない
  - e.g.
    - Floating Notes
    - Apple Music の Toggle Play/Pause
    - Philips Hue のシーン変更
- Alfred にない機能は Raycast を使用する
  - e.g. Calculator の単位変換

---

# まとめ

それぞれいいところがあるので併用することでより便利になった

| 特徴         |    Alfred    |  Raycast  |
| ------------ |:------------:|:---------:|
| 機能         |      ◎       |     ◎     |
| UI           | ややレガシー |  モダン   |
| 効率性       |      ◎       |     △     |
| サードパーティによる開発の活発さ |      △       |     ◎     |
| 有料版の価格 |    ¥6,800    | ¥1,250/月 |
