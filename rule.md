# w010 v5

## 概要

w010 は毎週日曜日の 13:00-15:00 でアプリケーションの MINOR version を上げる取り組み。

## 目的

w010 の目的は mockmock.dev の時間 (毎週日曜日 13:00-15:00) をうまく活用できたと感じること。

- 時間の有効活用により達成感・満足感を得る
- アプリケーションを開発する能力を測る
- 「試す」挑戦によりできることを増やす
- 「使う」練習によりつくる速さを上げる
- 「つくる」定期的に成果物を上げる

NOTE: http://www.shuburi.org/ 週ぶりに通じるものがある。

## ルール

- 毎週日曜日の 13:00-15:00 でアプリケーションの MINOR version を上げる
- おおまかな流れ
  - (1) mockmock.dev に向けて計画する・ルールを見直す
  - (2) mockmock.dev のコアタイムで MINOR version を上げる
- (1) mockmock.dev に向けて計画する・ルールを見直す
  - 「やること宣言」を作成しなければならない
    - 内容制限:
      - 「試す」挑戦（まだ知らない新しいものを試すこと）を項目に含めなければならない
      - 「使う」練習（既に知っているものを使うこと）を項目に含めなければならない
      - 「つくる」つくるものの名前を項目に含めなければならない
      - w010 のルールを対象に含めてならない
    - 個数制限:
      - 最大 5 項目に絞らなければならない
      - 項目は `#N` の形で明記しなければならない
    - 回数制限:
      - 「試す」は 3 回まで「使う」は 7 回までにしなければならない
      - 回数は `(N)` の形で明記しなければならない
    - 例
      * w010 2019-W40 [w010 v5](https://blog.bouzuya.net/2019/10/01/)
        * 過去の w010 [bouzuya/w010](https://github.com/bouzuya/w010)
      * #1 試す (7) [bouzuya/create-purescript-npm-bin](https://github.com/bouzuya/create-purescript-npm-bin)
      * #2 試す (4) [bouzuya/purescript-bouzuya-command-line-option-parser](https://github.com/bouzuya/purescript-bouzuya-command-line-option-parser)
      * #3 使う (1) [purescript/purescript-newtype](https://github.com/purescript/purescript-newtype)
      * #4 使う (3) ...
      * #5 つくる create-version-module 0.1.0
  - 仕様の概要を検討しなければならない
  - コアタイムで作成するアプリケーションに必要なライブラリを作成してもよい
  - 過去の活動を踏まえてルールを見直してもよい
- (2) mockmock.dev のコアタイムで 0.1.0 を作成する
  - 「やること宣言」を投稿する
  - 集中しなければならない
  - リポジトリに MINOR version を上げたタグをつけなければならない
  - リポジトリを公開しなければならない
  - 「やったこと成果発表」を作成しなければならない
    - 内容制限:
      - 「やること宣言」の各項目の成果を項目に含めなければならない
      - w010 の目的に照らしての評価を項目に含めなければならない
      - 1.0.0 で追加する予定の機能の概要を項目に含めなければならない
  - 「やったこと成果発表」を投稿する
