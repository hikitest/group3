# 2014研修会グループ3 サーバーサイドアプリ



## ローカル実行方法

事前に[Git](http://msysgit.github.io/)、[Node.js](http://nodejs.org/)と[npm](https://www.npmjs.org/)がインストールされていることを確認してください。

```sh
$ git clone http://172.16.30.71:10080/2014-kensyukai-group3/server.git
$ cd g3-server-2
$ npm install
$ npm start
```

[localhost:5000](http://localhost:5000/)でアクセスできます。

## 本番環境へのデプロイ方法

SSHの公開鍵が必要です。

```
$ git push heroku master
$ heroku open
```

## テスト用緯度/経度サンプル

35.384304/139.470192

35.383679/139.469473

35.382704/139.469838