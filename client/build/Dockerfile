#ベースイメージを指定
FROM node:11.12.0-stretch-slim

#コンテナ作者の情報
MAINTAINER koki <yamakoh.dev@gmail.com>

#docker runを実行した時に表示されるメッセージ
RUN echo "now building, please wait..."

#RUNでコマンドを実行
RUN apt clean &&\
    apt get install -y vim less

#指定したポートを解放
EXPOSE 80