# library_management
シェルスクリプトマガジン Vol.56 サンプルプログラム

## 前提条件

当サンプルプログラムは、次の環境での実行を確認しています。

- node.js 10.10.0 / 8.11.4
- sqlite3 v4.0.2 (ローカルで実行する場合に必要です)
- postgresql v10.4 (本番環境としてローカルかHerokuで実行する場合に必要です)
- macOS High Sierra 10.13.6
- Heroku-16 Stack (Ubuntu 16.04)

# 当サンプルプログラムの使い方

## ローカルで実行する場合

1. git clone https://github.com/40node/node003.git
2. cd node003
3. npm install
4. npm run build
5. npm start
6. [ローカルホスト](http://localhost:3000/books/)へアクセス

## Heroku へデプロイする場合

1. git clone https://github.com/40node/node003.git
2. cd node003
3. heroku create
4. git push heroku master
5. heroku open

※ 直接 Herokuへデプロイする場合は、次の [Heroku Button] も利用できます

## 実行可能なコマンド

次の定義されたコマンドが実行可能です

### npm start

起動します

### npm run migrate

データベースのマイグレーションを実行します

### npm run seed

データベースへ、テストデータを準備します

### npm run build

マイグレーションとテストデータの準備を一括で実行します

### npm clean

データベース内のデータをクリアします

# Heroku Button

Heroku へ直接でプロイするには、次のボタンをクリックしてください。

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)
