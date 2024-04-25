# Ludo Game in C

This project is a Ludo game made with the C language, it was developed as part of the final work of the Algorithms and Data Structure 1 subject in the Computer Engineering course at the State University of Minas Gerais - UEMG. The game basically follows the classic Ludo rules, offering an authentic experience to players.

## Functionalities

- **Classic Ludo Game**: It implements the traditional Ludo board game, with support for 2 to 4 players, where each player controls 4 pawns.
- **Start and Movement**: Players can only move a pawn to the start of the race, on the square of their respective color, by rolling a 6 on the die. Once the pawn has been placed at the start, the player is entitled to a new throw of the dice.
- **Three Sixes in a Row**: If a player rolls a 6 three times in a row, they must pass the turn, promoting a fair and dynamic game.
- **End of the Game**: The player must get all 4 pawns to the final square to win the game. To do this, they must roll the exact value remaining on the dice and, if successful, they will be entitled to another round on the dice.
- **Parts capture**: It is possible to capture another player's pawn when it lands on a square already occupied by an opponent's pawn. The capture forces the opposing pawn to return to its starting position off the track, providing a strategic element to the game. In addition, after a successful capture, the player can roll the dice once more.
- **Safe Points**: The board has safe squares, which are considered safe points where pawns cannot be captured.
- **Strategic Move**: The pawns must move and travel around the board until they reach the last square. With each roll of the dice, the player must move a pawn, and is not allowed to give up the move.
- **Choice of Pawn to Move**: The program allows the player to choose which of the pawns (where possible) he wants to move, offering strategic control over his pieces.

## How to Play

1. Clone this repository on your local machine.
2. Compile the program using a C compiler.
3. Run the program and follow the instructions to set the number of players, names and colors.

## License

This project is licensed under the MIT License - see the ['LICENSE'](LICENSE) file for more details.

## Contribution

Contributions are welcome! If you encounter problems or have ideas for improvements, feel free to open an issue or send a pull request.
