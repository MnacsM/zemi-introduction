---
theme: neversink
# themeConfig:
  # primary: '#5d8392'
title: 村田匡輝研究室ゼミ紹介
titleTemplate: '%s'
info: false
class: text-center
# drawings:
  # persist: false
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
layout: cover
color: pink
neversink_slug: '村田匡輝研究室ゼミ紹介'
---

# <span class="font-bold">村田匡輝研究室<br>ゼミ紹介</span>

2025年度　村田 匡輝

---
layout: top-title
color: pink-light
---

:: title ::
# プロフィール

:: content ::

- 氏名：**村田　匡輝（むらた　まさき）**
- 性別：**男**
- 年齢：**40歳**
  - 1984年12月29日生まれ
- 出身：**愛知県名古屋市**
- 経歴：**名古屋大学で博士（情報科学）を取得後，豊田高専情報工学科で12年間勤務**
- 連絡先：<Email v="murata.masaki@toyota.kosen-ac.jp" />

<br>　村田の個人ページです <mdi-arrow-right-bold-circle /> https://mnacsm.github.io/

---
layout: top-title
color: pink-light
---

:: title ::
# 村田(匡)研究室では...

:: content ::
## <span v-mark.red>自然言語</span>処理に関する研究を推進

<v-click>

- 人間が普段，話したり書いたりする言葉．人間がコミュニケーションを取る最も手軽な方法の一つ

</v-click>

<v-click>

- 代表的な自然言語処理技術：

</v-click>

<v-click><img border="rounded" src="/nlp.png" width="" height="" alt="nlp"></v-click>

---
layout: statement
color: pink
---

# 自然言語処理の中でも特に，<br><span v-mark.circle.red>「音声言語」</span><br>を対象とした研究を実施

---
layout: top-title-two-cols
columns: is-8
align: l-lt-lt
color: pink-light
transition: slide-up
---

:: title ::
# 1. 人の語りを傾聴するシステムの開発

:: left ::
## 人は基本，語りたい

- でも，話を聞いてくれる人がいつもいるわけじゃない...<br> ⇨ 情報機器に聞き手になってもらう‼️

## 話を上手に聞く方法：<span class="text-pink-500">傾聴態度を示す</span>

- 適度に相槌する
- 共感する
- 褒める　etc...

<span class="bg-pink-400 text-pink-100 p-2 border-l-6 border-2 border-pink-500 rounded-lg pl-4 pr-4 font-size-7">**人間の欲求を満たすシステム**</span>

:: right ::
<img class="" src="/robot.png" alt="">

---
layout: top-title
color: pink-light
transition: slide-up
---

:: title ::
# 1. 人の語りを傾聴するシステムの開発

:: content ::
## 研究テーマ

- 傾聴応答のタイミング推定，表現生成，個人最適化，<br>マルチモーダル情報の利用，==大規模言語モデルの活用==など
  - 高齢者の語り30名分に対する聴き手11人分の**傾聴応答コーパス**を利用して研究を推進

---
layout: top-title
color: pink-light
transition: slide-up
---

:: title ::
# 傾聴応答コーパス

:: content ::

- 傾聴応答を事前に収録された語りの音声に対して作業者が付与する形で収集
  - **聴き手として傾聴応答の発声に集中，同一の語りに対し<span class="bg-yellow">複数人の多様で自然な応答を網羅的に収集</span>**

<img class="" src="/corpus.png" alt="">
<audio controls><source src="/output.wav" type="audio/wav"></audio>

---
layout: top-title
color: pink-light
transition: slide-up
---

:: title ::
# 1. 人の語りを傾聴するシステムの開発

:: content ::
## 研究テーマ

- 傾聴応答のタイミング推定，表現生成，個人最適化，<br>マルチモーダル情報の利用，==大規模言語モデルの活用==など
  - 高齢者の語り30名分に対する聴き手11人分の**傾聴応答コーパス**を利用して研究を推進

<img class="" src="/attentive_listening.png" alt="">

---
layout: top-title-two-cols
color: pink-light
---

<div class="font-size-7 text-center font-bold"><span class="bg-yellow">不同意応答タイミングの検出，表出する表現の分類が<br>一定の水準で可能であることを確認</span></div>

:: title ::
# 研究紹介：語りの傾聴において不同意を示す応答の生成

:: left ::

- 傾聴応答の基本方略：語りへの同意や肯定を示す<br>
⇨ 自虐や謙遜が含まれる場合，**同意・肯定してはいけない**
- 不同意応答生成用のコーパスを作成し，Transformer ベースのモデルで不同意応答を生成
  - 不同意応答タイミングの検出，表出する表現の分類

:: right ::
<img class="" src="/disapproval.png" alt="">

---
layout: top-title-two-cols
columns: is-8
align: l-lt-lt
color: pink-light
transition: slide-up
---

:: title ::
# 2. 読みやすい字幕を生成するシステムの開発

:: left ::
## 講演などの場では

- 高齢者・聴覚障害者の方のために字幕を提示
  - 遠隔講義の動画等でも有用

⇨ <span class="text-pink-500">**音声認識で自動生成された字幕をより読みやすくしたい‼️**</span>

<span class="bg-pink-400 text-pink-100 p-2 border-l-6 border-2 border-pink-500 rounded-lg pl-4 pr-4 font-size-7">**整形，提示方法の工夫**</span>

## 研究テーマ

- 音声と視覚情報を活用した字幕表示の最適化
- 大規模言語モデルを用いたユーザ個別最適化字幕の生成
- 発話時間と字幕の提示時間の差異を埋める字幕提示　　など…

:: right ::
<img class="" src="/transcription.png" alt="">

---
layout: top-title
color: pink-light
transition: slide-up
---

:: title ::
# 研究紹介：視線位置上への字幕提示システム

:: content ::
<img class="" src="/eyetracking.gif" alt="">

---
layout: top-title-two-cols
color: pink-light
---

:: title ::
# 研究紹介：<br>マルチタスク学習による講演テキストへの読点と改行の挿入
<!-- Automatic Insertion of Commas and Linefeeds into Lecture Transcripts based on Multi-Task Learning -->

:: left ::

- 音声認識で音声を自動的にテキスト化することが可能
- 区切りなく提示された複数行で提示されたテキストは読みにくい
- <u>改行挿入，読点挿入用の分類モデルをマルチタスク学習によって学習する手法を提案</u>
  - 改行，読点を個別に挿入するモデルよりも挿入精度が向上

# <span class="bg-yellow">字幕の可読性向上に寄与</span>

:: right ::
<img class="" src="/lf_punc.png" alt="">

---
layout: top-title
color: pink-light
transition: slide-up
---

:: title ::
# 研究室・配属について

:: content ::
# <u>新しく立ち上げる研究室となります</u>

- 先輩がいない・環境が整っていないなど，様々な点で不便を感じることがあると思いますが，<br>
最初のメンバーとして研究室を新たに作り上げていってくれる学生さんを特に歓迎したいと思っています
- もちろん，自然言語処理に興味がある学生さんも歓迎です
  - ゼミでの活動を通して自然言語処理に必要な以下の能力が身につくことが期待されます
    - 言語学や数学に関する基礎学力
    - プログラミング能力（主に Python を使用予定）
    - 既存研究を調査・理解する能力

---
layout: top-title
color: pink-light
transition: slide-up
---

:: title ::
# 研究室・配属について

:: content ::
# ゼミ・卒業研究（火曜日開講予定）

- 2年生：自然言語処理の基本的な技術，Pythonプログラミング技術（，機械学習・深層学習の技術）を<br>身に付けるための勉強会・演習を実施予定です
- 3年生：2年生に引き続き，より高度な技術を学びながら，プロジェクト演習的な研究活動の実施，<br>卒業研究テーマの決定を行いたいと思っています
- 4年生：各自で**卒業研究**に取り組んでもらう予定です

<div class="text-white bg-pink-500 p-1 pl-3 pr-3 m-1 rounded font-size-5 text-center font-bold">
卒研のテーマは，本スライドで紹介したものに限らず，<br>自然言語を扱うテーマを幅広く設定したいと思います．

また，自然言語処理は画像処理や音声処理等の他分野との融合も期待されます．

一緒に興味あるテーマを見つけていきましょう．
</div>

---
layout: top-title
color: pink-light
transition: slide-up
---

:: title ::
# 研究室・配属について

:: content ::
# 面接について

- murata.masaki@toyota.kosen-ac.jp までアポイントをお願いします
  - 氏名，研究室紹介資料・ビデオを見て興味を持ったポイント（簡単に），面接の希望日時（できれば複数）をお知らせください
- 面接可能時間：△は要調整
  - 7月1日(火) 9:00〜13:00 △
  - 7月2日(水) 9:00〜12:25 △，13:30〜16:00 ◯
  - 7月3日(木) 9:00〜10:45 ◯，10:55〜 △
- 面接はオンラインで，10分程度を予定しています．<br>僕自信分かっていない部分も多いので，色々お話しましょう
