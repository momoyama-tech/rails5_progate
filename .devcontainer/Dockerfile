# ベースイメージとしてRuby 2系統を指定
FROM ruby:2.7

# 必要なツールやライブラリをインストール
RUN apt-get update && apt-get install -y \
    build-essential \
    nodejs \
    yarn \
    && apt-get clean && rm -rf /var/lib/apt/lists/*

# ワークディレクトリを設定
WORKDIR /workspace
