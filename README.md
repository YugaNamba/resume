# 職務経歴書

## 基本情報

| key      | value                               |
| -------- | ----------------------------------- |
| 氏名     | 難波 悠雅（Namba Yuga）             |
| 生年月日 | 1998/03/11                          |
| 居住地   | 大阪府                              |
| 最終学歴 | 津山工業高等専門学校 電子制御工学科 |

---

## 技術スタック

### 言語

![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Rust](https://img.shields.io/badge/rust-%23000000.svg?style=for-the-badge&logo=rust&logoColor=white)
![Go](https://img.shields.io/badge/go-%2300ADD8E.svg?style=for-the-badge&logo=go&logoColor=white)
![Swift](https://img.shields.io/badge/swift-F54A2A?style=for-the-badge&logo=swift&logoColor=white)

### フレームワーク・その他

![Vue.js](https://img.shields.io/badge/vuejs-%2335495e.svg?style=for-the-badge&logo=vuedotjs&logoColor=%234FC08D)
![Vuetify](https://img.shields.io/badge/Vuetify-1867C0?style=for-the-badge&logo=vuetify&logoColor=AEDDFF)
![Nuxtjs](https://img.shields.io/badge/Nuxt-002E3B?style=for-the-badge&logo=nuxtdotjs&logoColor=#00DC82)
![Firebase](https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase)
![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
![Google Cloud](https://img.shields.io/badge/GoogleCloud-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![GraphQL](https://img.shields.io/badge/-GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![Hono](https://img.shields.io/badge/Hono-%23000000.svg?style=for-the-badge&logo=hono&logoColor=white)

---

## 職務経歴詳細

### patternstorage 株式会社（2020/07〜現在）

#### 概要

- アパレル製造業の業務 SaaS の開発

#### 担当

- 2 人目のエンジニアとして参加
- プロダクトオーナの要望を元に仕様・設計や UI を考えながら実装
- エンジニアが増えてきたのでそのオンボーディングやサポートも行った
- フロントエンド・バックエンドを担当

#### 使用技術

- Firebase Firestore/Storage/Functions/Hosting/Authentication, Cloud SQL, Cloud Run, Cloud Build, Cloud Vision, BigQuery, Docker, GraphQL, Nuxt.js, Vuetify, SendGrid, GitHub Actions, DX Suite(Intelligent OCR, Elastic Sorter), DeepL, TypeScript, Python, FastAPI, Cloudflare Workers, Sentry

#### 取り組み

- アパレル製造業の業務 SaaS を現場の方と密に連携しながら開発
- 帳票の OCR を用いた取り込みや Excel ファイルからの取り込みによる書類確認・整理の効率化
- 作成したデータから資材発注書などの各種帳票半自動作成による業務簡略化
- ユーザーの資材マスタデータをもとに検索や変換を行う機能の提供

#### 工夫した点など

- 再利用性や可読性を意識したコーディングやコードレビューを行なった
- [プレビューチャネル](https://firebase.google.com/docs/hosting/manage-hosting-resources)を GitHub Actions で設定し、レビュー効率を上げた
- 本番・開発環境へのリリースの自動化を行なった
- コーディング規約の設定やスプリント内の各イベント内容の精査などチーム開発が上手くいくように行動した
- 複雑な計算式や様々の箇所で使うものはロジックを外に出してそれを共通で使うようにした
- TypeScript を使っておらず型チェックがないため model を通してデータを扱ったり、TypeScript を導入した
- Composition API, script setup への書き換えをおこなった
- Nuxt3 系へのリプレースをスムーズに行った
- プロダクトのリプレイスで Firestore から PostgreSQL に移行する際、既存のドメイン知識を活用してモデル設計を行った
- 既存プロダクトの資産を生かしながら、Google Cloud Vision と DeepL を用いた翻訳アプリケーションの作成を短期間で行った
- DSの方との連携を行いながらモデルの改善やマスタデータの取り込みを行った

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

#### 工夫した点など

- 複数店舗への導入を前提とした DB 設計を行なった
- マークアップの方との連携時に、ある程度コンポーネントを分けて機能を実装し、そこにスタイルなどを追加してもらうだけで済むような開発を行なった
- Functions で通知やカードの更新などバッチ処理を行なった
- デリバリーを最優先にしながらも品質を落とさないようなスコープ調整を行なった

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

#### 工夫した点など

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

#### 工夫した点など

- 従来の予約システムでは事前通知がメール受信であったため、そこを LINE 公式アカウントから行うことにより、開封率や認知率の工場につなげた。
- 次回予約を行いやすいように過去の履歴を参照し、日付の選択のみで次回予約をできるようにした。
