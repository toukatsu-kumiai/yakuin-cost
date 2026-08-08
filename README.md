# 役員行動費かんたん入力PWA

協同組合の役員行動費をスマホで入力し、20日締めの行動費明細PDFや集計用データを作成するためのPWAです。

## 使い方

GitHub Pagesで公開する場合は、このリポジトリのルートに以下のファイルを置いてください。

```text
index.html
manifest.webmanifest
service-worker.js
icons/icon.svg
```

## 注意

入力データは外部サーバーへ送信されず、利用者のブラウザ内に保存されます。  
スマホの初期化、ブラウザデータ削除、キャッシュ削除、機種変更などで保存データが消える場合があります。  
必要に応じてバックアップ保存を行ってください。

## 更新時

修正版をアップロードする場合は、原則として以下を上書きしてください。

```text
index.html
manifest.webmanifest
service-worker.js
icons/icon.svg
```
