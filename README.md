# Bingo plugin

A Minecraft plugin inspired by Bingo minigame.

Each player is given a set of instruments and a card with a grid of items. The items are the same for all players.
Depending on a game mode, participants either have to collect 5 items in a row in a 5x5 grid, collect items as fast as possible or collect all items in a 3x3 grid.

Any number of players is supported.

## Installation

Requires Spigot/Paper server for Minecraft 1.19.

Put built plugin file into the plugins folder and start the server.

## Usage

All the commands can be accessed with "/bingo help" command.

For a quick start with all players, execute "/bingo quickstart [mode] [difficulty]". Tab completer will show all the available options for mode and difficulty.

To access the item grid, right click with the Bingo card. If you have a necessary item in your inventory, left click on it in the item grid.

There are 3 game modes:
- **default**: Players have to collect 5 items in one row, column or main diagonal in a 5x5 grid. When everyone except for 1 player finishes, the game ends, and the players get scores respectively to their place.
- **butfast**: Players have to collect any items in a 5x5 grid as quickly as possible. First one to collect an items gets the most points for it, the second one gets a bit less, etc. The game ends in a time fixed for each difficulty level.
- **collectall**: Players are given a 3x3 grid and have to collect all items from it as fast as possible. When everyone except for 1 player finishes, the game ends, and the players get scores respectively to their place.

After the game finishes, the host can either finish it by running "/bingo end" or start another round with the same players, mode and difficulty by running "/bingo start".

## Example
