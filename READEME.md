# 職務経歴書

## 基本情報

| key      | value                               |
| -------- | ----------------------------------- |
| 氏名     | 難波 悠雅（Namba Yuga）             |
| 生年月日 | 1998/03/11                          |
| 居住地   | 岡山県                              |
| 最終学歴 | 津山工業高等専門学校 電子制御工学科 |

---

## 技術スタック

### 言語

![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)

### フレームワーク・その他

![Vue.js](https://img.shields.io/badge/vuejs-%2335495e.svg?style=for-the-badge&logo=vuedotjs&logoColor=%234FC08D)
![Vuetify](https://img.shields.io/badge/Vuetify-1867C0?style=for-the-badge&logo=vuetify&logoColor=AEDDFF)
![Nuxtjs](https://img.shields.io/badge/Nuxt-002E3B?style=for-the-badge&logo=nuxtdotjs&logoColor=#00DC82)
![Firebase](https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase)
![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)

---

## 職務経歴詳細

### patternstorage 株式会社（2020/07〜現在）

#### 概要

- 0 ⇨1 フェーズにおけるアパレル製造業の業務 SaaS の開発

#### 担当

- 2 人目のフロントエンジニアとして参加
- プロダクトオーナの要望を元に仕様・設計や UI を考えながら実装
- エンジニアが増えてきたのでそのサポートも

#### 使用技術

- Firebase Firestore/Storage/Functions/Hosting, Nuxt.js, Vuetify, SendGrid, GitHub Actions, DX Suite(Intelligent OCR, Elastic Sorter)

#### 取り組み

- アパレル製造業の業務 SaaS を現場の方と密に連携しながら開発
- 帳票の OCR を用いた取り込みや Excel ファイルからの取り込みによる書類確認・整理の効率化
- 作成したデータから資材発注書などの各種帳票半自動作成による業務簡略化

#### 工夫した点

- OCR 取り込みは最低でも 3~4 分ほどかかっていた、そこで Excel ファイル取り込みを実装し、ファイルの読み取り速度を 5 秒以下に短縮することができた
- フォーマット用 Excel ファイルを用意することで様々な帳票の吐き出しを可能にした
- 再利用性や可読性を意識したコーディングやコードレビューを行なった
- [プレビューチャネル](https://firebase.google.com/docs/hosting/manage-hosting-resources)を GitHub Actions で設定し、レビュー効率を上げた
- 本番・開発環境へのリリースの自動化を行なった
- コーディング規約の設定やスプリント内の各イベント内容の精査などチーム開発が上手くいくように行動した
- 複雑な計算式や様々の箇所で使うものはロジックを外に出してそれを共通で使うようにした
- TypeScript を使っておらず型チェックがないため model を通してデータを扱ったり、TypeScript を部分的に導入した
- Composition API, script setup への書き換えをおこなった

### 顧客・卓管理＆ミニゲームアプリ（2020/10〜2021/03）

#### 概要

- 0 ⇨1 フェーズにおける[LIFF](https://developers.line.biz/ja/docs/liff/overview/)を用いた顧客・卓管理＆ミニゲームアプリの開発

#### 担当

- リードエンジニアとして参加 マークアップ 1 人・フロント 2 人(自分含め)
- プロダクトオーナの要望を元に仕様・設計や UI を考えながら実装
- 各エンジニアのマネジメント

#### 使用技術

- Firebase Firestore/Storage/Functions/Hosting, Nuxt.js, Vuetify, LIFF

#### 取り組み

- 店舗で行うビンゴゲームの開発とそれに紐づく顧客管理・卓管理アプリの開発
- 以前は卓管理をその日入っている人がメモなどを使いながらフロントの人に直接に伝えていた。それを解消するためのアプリを管理側と閲覧者側で用意しスマホを確認するだけで全体の状況把握をできるようにした。

#### 工夫した点

- 複数店舗への導入を前提とした DB 設計を行なった
- マークアップの方との連携時に、ある程度コンポーネントを分けて機能を実装し、そこにスタイルなどを追加してもらうだけで済むような開発を行なった
- Functions で通知やカードの更新などバッチ処理を行なった
- デリバリーを最優先にしながらも
  品質を落とさないようなスコープ調整を行なった

### 介護人材マッチングアプリ(2020/04~2021/03)

#### 概要

- 0 ⇨1 フェーズにおける[LIFF](https://developers.line.biz/ja/docs/liff/overview/)を用いた介護人材マッチングアプリの開発

#### 担当

- エンジニアとして 1 人で全て開発
- プロダクトオーナの要望を元に仕様・設計や UI を考えながら実装

#### 使用技術

- Firebase Firestore/Storage/Functions/Hosting, Nuxt.js, Vuetify, LIFF, Google Maps API

#### 取り組み

- 介護士人材と介護施設をマッチングさせるアプリとその管理画面の開発
- 介護士側の空き時間を掲載し施設がスカウト(施設側が求人を出してそこに介護士が応募)したあとにチャット機能でやりとりしてもらい条件などが合えば成立後勤務できる

#### 工夫した点

- 履歴書に必要な項目埋めてもらうと、履歴書の閲覧・DL・印刷をできるようにした
- チャット機能では Functions を TypeScript で記述し開発効率を上げつつ型チェックを行なった
- 利用者の年齢が 4,50 代が多いということもあり、フォントサイズ・分かりやすい UI や説明など、ユーザーフレンドリーなアプリになるように開発した
- 初期は検証段階ということもあり一時的に別機能を追加したり、UI などの変更が多くなることが予想されたので、そこを意識した開発を行なった
- プロダクトオーナは初めてのプロダクト開発だったので、仕様の確認や提案・改善などを密にしながら開発を行なった

### 美容院予約管理アプリ(2020/04~2021/03)

#### 概要

- 0 ⇨1 フェーズにおける[LIFF](https://developers.line.biz/ja/docs/liff/overview/)を用いた美容院予約管理アプリの開発

#### 担当

- フロントエンドエンジニアの 2 人目のメンバー
- プロダクトオーナの要望を元に仕様・設計や UI を考えながら実装

#### 使用技術

- Firebase Firestore/Storage/Functions/Hosting, Nuxt.js, Vuetify, LIFF, puppeteer

#### 取り組み

- 美容院や美容サロンの予約を LINE 公式アカウントから行えるアプリの開発。
- 別の予約システムを導入している店舗はその連携も行なった。

#### 工夫した点

- 従来の予約システムでは事前通知がメール受信であったため、そこを LINE 公式アカウントから行うことにより、開封率や認知率の工場につなげた。
- 次回予約を行いやすいように過去の履歴を参照し、日付の選択のみで次回予約をできるようにした。
