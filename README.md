# Mastermind

Mastermind is a code-breaking game for two players. The modern game with pegs was invented in 1970 by Mordecai Meirowitz, an Israeli postmaster and telecommunications expert. It resembles an earlier pencil and paper game called Bulls and Cows that may date back a century or more.

## Installing

Clone the repository to your local machine:

- [https://github.com/t0nn1x/mastermind.git]

## Prerequisites
You will need Python 3.7 installed on your system to run this game.

## Running the Game
To run the game, open the folder with game.py file and use the following command: 

$ python game.py

## How to play

The code-maker chooses a pattern of four code pegs. Duplicates are allowed, so the player could even choose four code pegs of the same color. The code-breaker tries to guess the pattern, in both order and color, within twelve turns. Each guess is made by placing a row of code pegs on the decoding board. Once placed, the codemaker provides feedback by placing from zero to four key pegs in the small holes of the row with the guess. A colored or black key peg is placed for each code peg from the guess which is correct in both color and position. A white key peg indicates the existence of a correct color code peg placed in the wrong position.

## Example

The code-maker chooses a pattern of four code pegs: blue, green, yellow, and red. The code-breaker makes a guess of: yellow, blue, red, green. The codemaker provides feedback by placing two colored key pegs in the small holes of the row with the guess: one red for the yellow peg, and one green for the green peg. The codemaker also places a white key peg for the blue peg, to indicate that it is the correct color but in the wrong position.

## Rules

- The code consists of four colors, each of which can be one of the following:
- Colors: R, G, B, Y, W, O
- The code is case insensitive, so you can guess 'R G B Y' or 'r g b y'.
- You have 10 tries to guess the code.
- Correct Positions: The number of colors in the correct position.
- Incorrect Positions: The number of colors in the incorrect position.

## References

- [Mastermind (board game)](https://en.wikipedia.org/wiki/Mastermind_(board_game))
- [Mastermind (video game)](https://en.wikipedia.org/wiki/Mastermind_(video_game))
- [Mastermind (board game) - How to play](https://www.wikihow.com/Play-Mastermind-(Board-Game))
- [Mastermind (video game) - How to play](https://www.wikihow.com/Play-Mastermind-(Video-Game))

