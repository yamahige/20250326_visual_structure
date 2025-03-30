---
lang: 'ja'
title: "スライドで使う構造図をHTML+CSSで表現"
link:
  - rel: 'stylesheet'
    href: 'slide.css'
  - rel: 'stylesheet'
    href: 'logic/logic.css'
---

# スライドで使う構造図をHTML+CSSで表現 #

### 著者{.author}

yamahige

### 版{.version}

#### 版名{.version-name}

v1

#### 日付{.date}

2025-03-26


## ストレート: アイテムがフレーズ

アイテムの数は可変

<figure class="--logic-flex-inline">

1. 夜をこめて
1. 鳥の空音は はかるとも
1. よに逢阪の 関はゆるさじ

</figure>

<figure class="--logic-flex-inline-reverse">

1. 色は匂へど散りぬるを
1. 我が世誰ぞ常ならむ
1. 有為の奥山今日越えて
1. 浅き夢見し酔ひもせず

</figure>

## ストレート: アイテムの中に構造あり

<figure class="--logic-flex-inline --logic-flex-inline-box">

1. 全ての人間は死すべきものである。
    - Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
    - Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
1. ソクラテスは人間である。
    - 色は匂へど 散りぬるを
    - 我が世誰ぞ 常ならむ
    - 有為の奥山 今日越えて
    - 浅き夢見し 酔ひもせず
1. ゆえにソクラテスは死すべきものである。
    - Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
    - Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

</figure>

## 循環

アイテムの数ごとにCSSが必要…かも。この例では4個。

<figure class="--logic-cycle-4">

- 吾輩はAである
- なぜA?
- 吾輩はBである
- なぜB?

</figure>

## 循環 - オーバーラップ

アイテムの数は固定、この例では4個。

<figure class="--logic-cycle-compact-4">

- 吾輩はAである
- なぜA?
- 吾輩はBである
- なぜB?

</figure>

<!--
Web Publication (WebPub) Format
$ vivliostyle build slide.md -o web/ -f webpub
-->