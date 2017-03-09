# php開発者のためのHeroku入門

## セミナー概要

開発したアプリケーションを迅速に提供できるインフラは常に求められています。
クラウドによって仮想環境の調達は容易になりましたが、アプリケーションを動かすためのミドルウェアやデータベースの設計、導入には依然として時間がかかります。
Herokuでは、必要なミドルウェアは自動的に判断され、データベースはワンクリックで作成できるため、開発したアプリケーションをいますぐに公開することが可能です。

本Webセミナーでは、PHP開発者の方々を対象に、Hello World を表示する方法や、Composer や Pipeline と連携してHerokuへデプロイする方法を、デモを交えて説明します。

## 当Githubサイトのご案内

Webセミナー内で使用したサンプルプログラムを公開しています。

## 使い方

### 前提条件

1. `git` コマンドが利用可能なこと
2. Heroku アカウントを有しており、かつ [Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli)が導入され、利用可能なこと

### 利用手順(CLIのケース)

1. 事前に Heroku login を済ませておくこと
2. `git clone https://github.com/tabesfdc/heroku_php_0309.git` を実行する
3. `cd heroku_php_0309` により、カレントディレクトリを変更する
4. `heroku login` にて、Heroku へログインを済ませる
5. `heroku create` により、Heroku へ新たにアプリのデプロイ環境を作成する
7. `git push heroku master` で、作成した Heroku へアプリケーションをデプロイ
8. `heroku open` でデプロイしたアプリケーションの稼働確認ができます
9. ログを確認する場合には `heroku logs` を利用ください

## もっとかんたんな使い方

### Heroku buttonを使おう

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)


# 注意事項

- Macでのみ実行の確認をしています
