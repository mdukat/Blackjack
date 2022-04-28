# Blackjack

![Game Screenshot](https://i.ibb.co/S3vjPCX/blackjack-background.jpg)

## Description
[Blackjack-Game-Multiplayer](https://blackjack-multiplayer.herokuapp.com) is a free online multiplayer casino game. It's an online version of the traditional blackjack played at real casinos. You can choose to play alone or play in a private room with your friends. The goal of the game is to beat the dealer and win as much money as possible.

## Installation
1. Clone the project
```
git clone https://github.com/mdukat/Blackjack.git
```
2. Install all the modules
```
npm install
```
3. Start server
```
node index.js
```

## Docker
1. Build docker image
```
docker build . -t mdukat/blackjack
```
2. Run docker container
```
docker run -p 127.0.0.1:3000:3000 -d mdukat/blackjack
```

## Docker-compose
1. Build docker image
```
docker build . -t mdukat/blackjack
```
2. Run docker-compose
```
docker-compose up -d
```

