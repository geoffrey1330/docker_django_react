# A dockerized version of the multiplayer realtime Tic Tac Toe game

# [Play game](https://jedah.netlify.app/) 

A full stack multiplayer Tic Tac Toe game built with React, Django framework,django channels and redis.

### Features
- 3x3 game grid
- Persistent scoreboard (data stored in SQL database)
- multiplayer with django channels and websockets
- Two human players with different device

### Prerequisites:
- [Python 3](https://www.python.org) (>=3.7)
- [pip](https://pip.pypa.io/en/stable/installing/) (included in Python 3 >=3.4 )
- [pipenv](https://docs.pipenv.org/en/latest/)

In oder to start the game, do the following:

### 1) Make sure you have docker installed in your machine(windows,mac,linux)

### then run the following command on the terminal
```
git clone https://github.com/geoffrey1330/docker_django_react.git
cd docker_django_react

docker-compose -f docker-compose.yml up -d

```

### 2) Start application (default on localhost:3000) on the browser


