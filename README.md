# Connect Four Game
Check out my profile: https://hyperskill.org/profile/405752989

This is a simple implementation of the classic Connect Four game in Java.

## Game Description

Connect Four is a two-player connection board game, in which the players choose a color and then take turns dropping coloured discs into a seven-column, six-row vertically suspended grid. The pieces fall straight down, occupying the lowest available space within the column. The objective of the game is to be the first to form a horizontal, vertical, or diagonal line of four of one's own discs.

## Features

- Two-player game: Player X and Player O.
- Player X's discs are represented with a pink color and Player O's discs are represented with a green color.
- The game board is a grid of 6 rows and 7 columns.
- A 'Reset' button is provided to reset the game at any point.

## How to Run

This project uses Gradle for build and dependency management. You can run the game by executing the `ApplicationRunner` class which contains the main method.

```bash
javac ApplicationRunner.java
java ApplicationRunner
```

## Game Rules

1. Players take turns dropping one of their discs into any of the slots in the top of the grid.
2. The game ends when there is a 4-in-a-row horizontally, vertically, or diagonally. The player who forms this 4-in-a-row is the winner.
3. If the game board is filled completely and no player has a 4-in-a-row, then the game is a draw.

## Implementation Details

The game is implemented using Java Swing for the GUI. The `ConnectFour` class is the main class representing the game. It contains a grid of `ConnectFourField` objects, each representing a cell on the game board. The `Turn` class is used to keep track of the current player's turn.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)

Check out my profile: https://hyperskill.org/profile/405752989
