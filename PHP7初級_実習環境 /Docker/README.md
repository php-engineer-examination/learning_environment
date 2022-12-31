# PHP8技術者認定初級試験 Docker 実習環境

PHP8初級試験の Docker 実習環境です。

## 環境

「独習PHP 第4版」より動作確認環境を参考に選出しました。

* PHP 8.0.3
* Apache 2.4.46
* MariaDB 10.4.18

## 実習環境

* Docker
  * PHP 8.0.3
  * Apache 2.4.46
  * MariaDB 10.4.18

## 実習環境の準備

1. Docker Desktop のインストール
2. Docker Desktop の起動
3. 環境変数の設定

### Docker Desktop のインストール

[Docker Desktop](https://www.docker.com/products/docker-desktop/) をダウンロードしてインストールしてください。


### Docker Desktop の起動

Docker Desktop を起動しておいてください。

### 環境変数を設定

こちらは通常は必要のない作業です。
必要に応じて書き換えてください。

環境変数は `.env` ファイルに書かれています。
初期値は下記のとおりです。

```.env
COMPOSE_PROJECT_NAME=php7elexam
DB_HOST=mariadb
DB_DATABASE=sample
DB_USER=docker
DB_PASSWORD=password
TZ=Asia/Tokyo
FORWARD_HTTP_PORT=80
FORWARD_DB_PORT=3306
FORWARD_PMA_PORT=8080
```

## 実習環境の実行

## Docker Compose から起動

Docker Compose でコンテナを一式起動します。

```sh
docker compose up -d
```
