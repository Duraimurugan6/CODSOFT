# Rock Paper Scissors - Python Game

## Overview

This is a simple Rock-Paper-Scissors game built using Python. The game is played against the computer, where both the player and the computer make a choice from Rock, Paper, or Scissors. The game then compares both choices to determine the winner based on the classic rules of Rock-Paper-Scissors.

## Features

- **Simple Gameplay**: Classic rock, paper, scissors rules.
- **Play against the Computer**: Randomized computer choices.
- **Score Tracking**: Keep track of wins, losses, and draws.
- **Replayable**: After each game, the player is given the option to play again or quit.

## Prerequisites

Make sure you have Python installed on your system. You can download it from [python.org](https://www.python.org/).

## How to Run

1. Clone the repository or download the script to your local machine:
    ```bash
    git clone https://github.com/yourusername/rock-paper-scissors-python.git
    cd rock-paper-scissors-python
    ```

2. Run the Python script:
    ```bash
    python rock_paper_scissors.py
    ```

3. Follow the prompts to play the game.

## Usage

Once you run the application, you'll be prompted to make your choice from Rock, Paper, or Scissors:

```
Choose:
1. Rock
2. Paper
3. Scissors
Enter your choice (1/2/3): 1
```

The computer will then make its choice, and the result of the game will be displayed.

### Example Gameplay

```
Choose:
1. Rock
2. Paper
3. Scissors
Enter your choice (1/2/3): 2
You chose Paper.
Computer chose Rock.
You win!

Play again? (y/n): y
```

## Game Rules

- **Rock beats Scissors**
- **Scissors beat Paper**
- **Paper beats Rock**
- If both the player and the computer choose the same option, the result is a draw.

## File Structure

- `rock_paper_scissors.py`: The main script containing the logic for the Rock-Paper-Scissors game.

## Future Improvements

- Add more rounds with a scoring system for best out of 3 or 5.
- Implement different game modes, such as multiplayer.
- Create a graphical user interface (GUI) using libraries like Tkinter or Pygame.
- Add animations and sound effects for a more interactive experience.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributions

Feel free to fork this repository and submit pull requests for any improvements or bug fixes!
