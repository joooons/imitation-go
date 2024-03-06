# Imitation GO

Try playing [Imitation Go](https://imitation-go.onrender.com/)!

:warning: It may take a few minutes for the game to load for the first time.

This is an experimental version of Go that allows more than two players to play. It was made with `node.js` and `socket.io`. It is currently hosted on `Render`. Load the page on two or more separate browser windows to try out the multiplayer game.

## Features

- A single game can be played by two to six players.
- Two or more groups of players can play the game in different rooms, each of which has a unique name provided by the creator of the room.
- The board size can go from 5x5 to 19x19.
- The log at the bottom of the screen keeps track of whose turn it is.
- The list of players at the right top of the screen shows the number of stones lost by that player.
- The arrow next to the name indicates whose turn it is to play next.
- The `Pass` button allows you to forfeit your turn.
- `Freestyle Mode`:
  - Allows players to play out of turn
  - Allows taking back a move

## How to play

If you are new to the game of Go, check out [this video](https://www.youtube.com/watch?v=RRBjN8empIs) for an explanation of how to play the game.

- Go through the instructions
- Either create a room or join an existing room
  - To create a room, click `Add room` and type in a name for that room. Enter a number between 2 and 6 for the # of players. Enter board dimensions. The dimensions can go from 5x5 to 19x19. Check `Freestyle Mode` to allow players to play out of turn.
  - To join an existing room, click `JOIN` below the name of the room you wish to join.
- If `Freestyle Mode` is not enabled, the creator of the room must wait for the second player to join in order to make the first move.
- To skip your turn, click `Pass`.
- The game ends when all players `Pass` their turns sequentially.
