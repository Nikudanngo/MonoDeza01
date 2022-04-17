---
# try also 'default' to start simple
theme: seriph
download: true
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
# background: https://source.unsplash.com/collection/94734566/1920x1080
background: false
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# persist drawings in exports and build
drawings:
  persist: false

---

  # 時間割確認サイト
  **920017 遠藤 哲**
---
layout: center
---
  # **次の授業って何だっけ?**

---

  # **現状の解決策**
  - ### 友だちに聞く
  - ### 授業時間割表やポータルで確認する
  - ### 予め自分で作って置いた時間割表を確認する
  - ### サボる
---
layout: center

---
  # **新しい解決策**

---
layout: two-cols
---

  # **仮UI**
  <ul class="image">
    <li class="noColum"><img src="/img/SOMEONE.png" class=" w-400px " /></li>

    <li class="noColum"><img src="/img/HOME.png" class=" w-400px " /></li>
  </ul>

  <style>
    .image {
      display: flex;
      justify-content: center;
    }

    .noColum {
      list-style: none;
    }

    li:nth-child(2) {
      margin: 0 21px;
    }
  </style>

  ::right::
  # **授業確認アプリ**
  - ### アクセスすると次の授業や一週間の授業が確認できる**webアプリ**
  - ### LOGINすると自分の履修内容に編集できるor自動で自分の履修内容を確認できる
  - ### LOGINで留年にも対応
  - ### 梅田キャンパスのみ対応
---
layout: two-cols
---
  # **仮UI**
  <ul class="image">
    <li class="noColum"><img src="/img/SOMEONE.png" class=" w-400px " /></li>

    <li class="noColum"><img src="/img/HOME.png" class=" w-400px " /></li>
  </ul>

  <style>
    .image {
      display: flex;
      justify-content: center;
    }

    .noColum {
      list-style: none;
    }

    li:nth-child(2) {
      margin: 0 21px;
    }
  </style>

  ::right::
  # **そんなサービス作れるのか?**
  - ### 梅田キャンパスの学生は履修内容がほどんど同じ!
  - ### 各教室にある出席管理システムの情報が取れれば最高
  - ### バックエンド側,認証周りの処理はFirebaseで実装
---

  # Diagrams
---
layout: center
---

# **END**

<!-- [Documentations](https://sli.dev) · [GitHub](https://github.com/slidevjs/slidev) · [Showcases](https://sli.dev/showcases.html) -->
