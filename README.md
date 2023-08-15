# README

選択した事業側の課題
 サービス登録者数の内、男性60%に対して、女性は40%。一方で、サービス内のもくもく会に参加した人の比率は、男性90%：女性10%と大きな差が出ています。もっと女性が使いやすいようなサービス設計にする必要があるのではないか？

提案内容
 ユーザの性別を設定できるようにし、公開する。参加者の項目だけでなく、興味ありの項目も作る。参加者、興味ありの人の性別が他のユーザからわかるようにする。
⇨現状ユーザは性別を設定できず、もくもく会の情報からも男女比が伝わらないため、女性は参加しづらい。知り合いがいない状態で、女性1人、残りは全て男性だと過ごしづらい。また、いきなり参加ボタンを押すのは迷いが生じやすいので、興味ありの項目があると、検討が進みやすい。性別が他のユーザからわかることで、女性が他にもいるもくもく会なら参加してみよう、という気持ちになる。

実装方針
・マイページのプロフィール画面でユーザの性別を設定できるようにする。
・もくもく会の詳細画面に興味がある人用に興味ありのユーザ名と性別が表示される項目を作る
・もくもく会の詳細画面の参加者の項目も性別が表示されるようにする。

実装方針
## 環境構築
```
$ bundle install --without=production
$ bin/rails db:setup
$ yarn install
$ bin/webpack
$ bin/rails s
```

## 事業をエンジニアリングしよう提案編の回答は以下に記述してください
