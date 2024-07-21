# Docker_rocketchat
Rocketchatデプロイツール

# demo

# Requirement
## Environment
* rocketchat:latest
* mongo:4.4
* mongo:4.4(replica)
## Device
* Device: MacBook Air (2020)
* Operating System: macOS Sonoma 14.5
* Browser: Google chrome Version 126.0.6478.127

# Installation
## Deploy
1. git clone https://github.com/makoto-kamimura/docker_rocketchat.git
2. cd ./docker_rocketchat/
3. sudo docker-compose down -v && sudo docker-compose build && sudo docker-compose up -d
4. "localhost:3000" をブラウザにて入力/実行