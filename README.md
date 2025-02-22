Blackjack Game - README

This project is a simple Blackjack game built using HTML, CSS, and JavaScript. The game allows a player to draw cards, track the sum, and determine if they have won, lost, or can continue playing.

Project Structure

index.html: Defines the structure of the game interface.

index.css: Styles the game to give it a casino-like appearance.

script.js: Implements the game logic using JavaScript.

index.html (HTML File)

This file contains the layout of the game. It includes:

A title and a message prompting the player.

Elements to display the player's cards and sum.

Buttons to start the game and draw a new card.

A script reference to script.js.

Key Elements

<h1>Blackjack</h1>: Displays the game title.

<p id="message-el">Want to play a round?</p>: Shows game messages.

<p id="cards-el">Cards:</p>: Displays drawn cards.

<p id="sum-el">Sum:</p>: Shows the sum of the drawn cards.

<button onclick="startGame()">Start Game</button>: Starts a new round.

<button onclick="newCard()">New Card</button>: Draws a new card.

<p id="player-el"></p>: Displays player information (name and chips).

index.css (CSS File)

This file styles the game and enhances its visual appeal.

Key Styles

Body: Uses a green background (#006400) to resemble a casino table.

Container: Creates a styled box with a rounded border and shadow effect.

Buttons: Styled with orange color (#FFA500) and hover effects.

Typography: Bold text for important elements and a larger font size for readability.

script.js (JavaScript File)

This file contains the game logic and handles player interactions.

Key Variables

cards: Stores the drawn cards.

sum: Tracks the total sum of cards.

hasBlackJack: Boolean flag for a win condition.

isAlive: Tracks whether the player is still in the game.

message: Stores game messages.

player: Object containing player name and chips.

Key Functions

getRandomCard(): Returns a random card between 1 and 13 (face cards count as 10, and Ace can be 11).

startGame(): Starts a new round, resets values, and displays initial cards.

renderGame(): Updates the UI with the player's cards and game messages.

newCard(): Allows the player to draw a new card if they haven't lost or won.

How to Play

Open index.html in a web browser.

Click Start Game to begin.

The game will draw two random cards and display their sum.

If the sum is below 21, you can click New Card to draw another.

If the sum reaches exactly 21, you win!

If the sum exceeds 21, you lose the game.

Enjoy playing Blackjack! 🎰

