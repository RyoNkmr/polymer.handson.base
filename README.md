# Polymer Handson Base

このリポジトリは [Polymer.co-edo](https://polymercoedo.doorkeeper.jp/) で実施するハンズオンのベースになるリポジトリです。
ハンズオンの実施者は、このリポジトリを fork して利用してください。

## 前提事項

以下のソフトウェアが必要になります。

- Node.js 6.0以上
- NPM 3.0以上

## インストール

GitHubからリポジトリのコードをcloneまたはダウンロードしてください。

以下のコマンドを実行し、必要な依存関係をダウンロードします。

```sh
$ npm install
```

インストールが完了したら、動作確認をしておきます。

```sh
$ npm run polymer serve
```

正常に起動すると、以下のように表示されます。

```sh
> polymer.handson.base@1.0.0 postinstall /home/user/polymer.co-edo/polymer.handson.base
> bower install

user$ npm run polymer serve

> polymer.handson.base@1.0.0 polymer /home/user/polymer.co-edo/polymer.handson.base
> polymer "serve"

Starting Polyserve...
    serving on port: 8080
    from root: /home/user/polymer.co-edo/polymer.handson.base
  
Files in this directory are available under the following URLs
    applications: http://localhost:8080
    reusable components: http://localhost:8080/components/polymer.handson.base/
```

起動したらブラウザを開いてページが表示されることを確認します。

## Web Components のインストール

`npm run bower install` が利用可能になっています。
