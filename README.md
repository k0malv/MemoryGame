# Memory Game Project

This project outlines the code for the memory game, an assignment that is part of Grow with Google Developer Scholarship. This is a play on a classic memory game, whereby all the cards are hidden (laid out face down) on the board and at each turn two cards are flipped face up. The objective of the game is to find matching pair of cards. 

## How to play the game

Click on one card at a time. Flip 2 cards in a row. If the cards are a matching pair, they will remain open for the remainder of the game. However, if the pair of cards are not matching, they will be hidden within half a second. Try to concentrate and remember the placement of cards before they're hidden. Each move will be counted on the "moves" counter at the top. Also, timer will be triggered when the game begins to keep track of the time it takes to complete the game. The star ratings are based on how many turns it takes to find ALL the matching pairs. The key is to remember the placements of the cards and find the matching pairs in the least amount of moves and time!!


## Dependencies

The following libraries were used for this coding project: jQuery (https://jquery.com/), Bootstrap (https://getbootstrap.com/), Font Awesome (https://fontawesome.com/) and Easytimer (https://albert-gonzalez.github.io/easytimer.js/).


## Running the app

1. Open index.html file in your favorite browser window. This will show how the app renders on the webpage. 
2. Open index.html, app.css and app.js files in sublime text or any text editor of your choice to review the code and edit. 

## A quick overview of the programming algorithm in the js file. 

1. Set up the timer. The min.js file is in the top with the link to the github repo.
2. Create an array of deck of cards. 
3. Shuffle the cards to start the game. 
4. Set up different arrays to store opened, locked and matched cards.
5. Add event listener to start the game and reload the game.
6. Setup functions to: shuffle cards, show cards, match cards, remove cards, track moves, star ratings, display modal on game over and refresh game.

