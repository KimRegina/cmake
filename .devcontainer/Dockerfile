FROM mcr.microsoft.com/devcontainers/cpp:1-debian-11

#安装MySQL服务器
RUN apt-get update && apt-get install -y default-mysql-server

#サーバーを起動
CMD service mysql start && tail -f /dev/null

WORKDIR /workspace