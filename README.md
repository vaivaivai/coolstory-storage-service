# RESTful API server for Telegram Bot 'CoolStory'

## Endpoints

### /api/games
- GET (returns game state)

### /api/game
- POST (creates state, returns gameHashId)

### /api/game/:gameHashId
- GET (returns game state)
- PUT (updates game state, returns game state)
- DELETE (removes game state, returns success message)

### /api/characters
- GET (returns character state)

### /api/character
- POST (creates state, returns characterHashId)

### /api/character/:characterHashId
- GET (returns character state)
- PUT (updates character state, returns character state)
- DELETE (removes character state, returns success message)

## Usage

### Start node server
- ```npm install```
- ```npm start```

### Share a web service on your local development machine
- ```npm install -g localtunnel```
- ```lt --port 3000```

### Launch MongoDB
- ```brew install mongodb```
- ```mongo```
