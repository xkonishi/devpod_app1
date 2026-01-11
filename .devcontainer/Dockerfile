# FROM node:20-slim
FROM mcr.microsoft.com/devcontainers/typescript-node:24

# RUN apt-get update && apt-get install -y \
#     git \
#     curl \
#     && rm -rf /var/lib/apt/lists/*

WORKDIR /workspace

# # 非rootユーザーを作成（オプション）
# ARG USERNAME=node
# RUN chown -R $USERNAME:$USERNAME /workspace
RUN chown -R node:node /workspace

# USER $USERNAME
