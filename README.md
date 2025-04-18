# Pig Game - JavaScript

This is a simple two-player dice game where players take turns rolling a dice, accumulating scores, and trying to reach 100 points to win. It is built using vanilla JavaScript, HTML, and CSS.

## Game Rules

1. Each player takes turns rolling a dice.
2. On each roll, the dice shows a number between 1 and 6.
3. The player adds the number rolled to their "current score".
4. If a player rolls a 1, their current score is reset to 0, and the turn passes to the other player.
5. After each turn, the player can choose to "Hold", which means they add their current score to their overall score.
6. If a player's overall score reaches 100 or more, they win the game.
7. A new game can be started by clicking the "New Game" button.

## Features

- **Rolling Dice:** Players can roll the dice and see the result.
- **Current Score:** The current score is displayed for each player during their turn.
- **Overall Score:** Players' overall scores are updated as they hold their current score.
- **Winner:** When a player's score reaches or exceeds 100, they are declared the winner and the game ends.
- **Active Player:** The active player is highlighted, and the turn automatically switches when a player rolls a 1 or holds their score.
- **New Game:** A new game can be started by clicking the "New Game" button.

## How to Play

1. Click the **"Roll Dice"** button to roll the dice. If the result is 1, your turn will end, and the next player will be up. If it's any other number, it will be added to your current score.
2. Click the **"Hold"** button to add your current score to your overall score and pass the turn to the other player.
3. The first player to reach 100 points wins the game. The winner will be highlighted.
4. To start a new game, click the **"New Game"** button.

## Getting Started

To run the game on your local machine:

1. Clone this repository to your local machine using `git clone`.
2. Open the `index.html` file in your browser.
3. Play and enjoy the game!

## Technologies Used

- HTML
- CSS
- JavaScript (Vanilla)

## License

This project is open-source and available under the [MIT License].
