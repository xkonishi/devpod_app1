FROM node:20-slim

RUN apt-get update && apt-get install -y \
    git \
    curl \
    && rm -rf /var/lib/apt/lists/*

WORKDIR /workspace

# 非rootユーザーを作成（オプション）
ARG USERNAME=node
RUN chown -R $USERNAME:$USERNAME /workspace

USER $USERNAME
