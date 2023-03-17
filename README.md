# Azure Logic App Templates for LINE Bot

LINE Bot 用バックエンドを作成するための Azure Logic App をデプロイします。

「Deploy to Azure」ボタンを押して Azure にサインイン後、

- サブスクリプション
- リソースグループ
- リージョン
- Logic App 名
- LINE Messaging API のチャネル ID
- LINE Messaging API のチャネルシークレット

を入力してデプロイを開始してください。

## リプライ
### テキストのオウム返し

ユーザーから送られたテキスト内容をそのまま返信するオウム返しです。また、スタンプが送られた場合は固定のスタンプを返します。

メッセージイベントのみに反応させるための制御（条件）、メッセージ種別ごとに処理を分けるための制御（スイッチ）をフローに含みます。

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fhimanago%2Fazure-logicapp-linebot-templates%2Fmaster%2Ftemplates%2Freply-echo-text.json)

## プッシュその他
### ブロードキャスト

友だち追加されているユーザー全体へのメッセージ送信を行います。

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fhimanago%2Fazure-logicapp-linebot-templates%2Fmaster%2Ftemplates%2Fbroadcast-simple.json)
