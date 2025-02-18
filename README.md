# InnomaticesreachlabProject2-Memory-match-game-

## Part 1: Setting Up the Game

1)HTML Structure:
Create the basic structure of the page, including the landing page with buttons for selecting the category (Fruits, Emojis, Animals, Planets).
Ensure that the HTML has the necessary divs for the game container, cards, score, and timer.

2) CSS Design:
Style the landing page with a header, buttons, and a centered layout.
Design the game container to display the cards in a grid-like structure.
Ensure that the layout is responsive. Make sure the game adjusts for smaller screen sizes (such as on mobile devices).

## Part 2: Game Logic Implementation

1)JavaScript - Game Initialization:
Implement a startGame function that dynamically displays a grid of cards based on the selected category.
Each category should consist of 8 pairs of matching items (e.g., fruits, emojis, animals, planets).
Create an array for each category and ensure the cards are shuffled randomly before being displayed.

2)Card Flip Logic:
Implement a handleCardClick function that flips the cards when clicked.
Ensure that the cards remain flipped for 1 second, allowing the player to see them, and then either hide them or leave them visible if they form a matching pair.

3)Matching Logic:
If two cards match, they should stay flipped and have a distinct style (e.g., a green background).
If the cards don’t match, they should flip back after a short delay.
Track the number of matches and update the score accordingly. Award points for each match.

4)Timer Functionality:
Add a countdown timer that starts when the game begins and counts down from 30 seconds.
If the time runs out, the game should display a “Game Over” message and stop the game.

## Part 3: Enhancements

1)Add New Categories:
Add a new category (e.g., Flags of Countries or Famous Landmarks) with at least 8 pairs.
Integrate this new category into the game, ensuring the player can choose it from the landing page.

2)Scoreboard and Timer:
Display the player’s current score and the remaining time during the game.
Once the game ends (either through a win or by running out of time), display the final score along with a win or lose message.

3)Responsive Design:
Make sure the game works on different devices, including mobile phones, tablets, and desktops. Ensure the game’s layout adjusts properly for various screen sizes.

## Part 4: Bonus Features (Optional)

1)Sound Effects:
Add sound effects when the player flips a card, matches two cards, or when the game ends (either win or lose).
Use Audio() to trigger sound effects, and ensure the sounds are pleasant and non-intrusive.

2)Save Game State:
Implement a feature that allows the player to save their game state in local storage. When the page is reloaded, the player should be able to resume the game from where they left off.

3)Animations and Transitions:
Add animations or transitions to improve the user experience. For instance, animate the cards when they flip or use a fade effect for the score and timer updates.
