# goバージョン
FROM golang:1.16.3-alpine
# アップデート＆gitインストール
RUN apk add --update &&  apk add git
# ディレクトリの作成
RUN mkdir /go/src/app
# ワーキングディレクトリの設定
WORKDIR /go/src/app
# ホストのファイルをコンテナの作業ディレクトリに移行
ADD . /go/src/app
