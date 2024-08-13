# Pygame Chess

A simple chess game built using Python and Pygame. The game features basic chess rules, including piece movement, pawn promotion, and check/checkmate detection.

## Features

- **Piece Movement**: Supports all standard chess piece movements (King, Queen, Rook, Bishop, Knight, and Pawn).
- **Pawn Promotion**: Automatically promotes pawns to queens upon reaching the opponent's back rank.
- **Check and Checkmate Detection**: The game detects and notifies when a player is in check or checkmate.
- **Turn-based Play**: Players take turns, with visual indicators for the current player.
- **Basic GUI**: Displays the board, pieces, and highlights selected pieces and valid moves.

## Getting Started

### Prerequisites

- Python 3.x
- Pygame library

### Installation

1. **Clone the Repository**

    ```sh
    git clone https://github.com/yourusername/pygame-chess.git
    cd pygame-chess
    ```

2. **Install Dependencies**

    Ensure you have Pygame installed:

    ```sh
    pip install pygame
    ```

3. **Run the Game**

    ```sh
    python chess_game.py
    ```

## How to Play

- **Start the Game**: The game will start immediately upon running the script.
- **Select a Piece**: Click on the piece you want to move. Valid moves will be highlighted.
- **Make a Move**: Click on a valid square to move the selected piece.
- **Turn-based Play**: Players alternate turns, with Red starting first.
- **Winning the Game**: The game ends when a player checkmates their opponent's king.

## Known Issues

- **Castling**: Castling is not yet implemented.
- **En Passant**: Special pawn capture move "en passant" is not yet implemented.
- **Pawn Promotion Options**: Currently, pawns are automatically promoted to queens. No option for other pieces (Rook, Bishop, Knight).

## Future Improvements

- Implement castling and en passant.
- Add a pawn promotion choice.
- Include a save/load game feature.
- Implement a basic AI for single-player mode.
- Improve the GUI with piece images and additional visual feedback.


