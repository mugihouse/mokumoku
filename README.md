# README

## 環境構築
```
$ bundle install --without=production
$ bin/rails db:setup
$ yarn install
$ bin/webpack
$ bin/rails s
```

## 事業をエンジニアリングしよう提案編の回答は以下に記述してください

# 選択した事業側の課題
サービス登録者数の内、男性60%に対して、女性は40%。一方で、サービス内のもくもく会に参加した人の比率は、男性90%：女性10%と大きな差が出ています。もっと女性が使いやすいようなサービス設計にする必要があるのではないか？

# 提案内容
・見ず知らずの人と少人数で会うのは怖いのではないか（異性の場合は特に）
→プロフィールに性別を登録できるようにする
→もくもく会に最低人数の制限を追加する

# 実装方針
・プロフィール登録時に性別の登録を必須にする
・もくもく会の作成時に最低人数の設定を追加する
・もくもく会の検索フォームにに最低人数からでも絞り込めるようにする
