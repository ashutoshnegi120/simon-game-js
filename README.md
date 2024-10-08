# Simon Game

A web-based version of the classic Simon game built with HTML, CSS, and JavaScript. The game challenges players to repeat a sequence of colors generated by the game. The sequence becomes progressively longer, and the game ends if the player makes a mistake.

## Getting Started

### Prerequisites

- A web browser (e.g., Chrome, Firefox)

### Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/simon-game-js.git
2. **Navigate to the Project Directory**
   ```bash
   cd simon-game-js
3. **Open the Project**
   - Open index.html in your web browser.
  
### How to Play

1. **Start the Game**
 - Press 'A' key to start the game.
   
3. **Play the Game**
  - Watch and listen as the game shows a sequence of colors.
  - Click on the colored buttons in the same order as shown.
  - If you match the sequence correctly, the game will add another color to the sequence.
    
3. **Game Over**
  - The game ends if you click the wrong color.
  - Press any key to restart the game.

## Files
- index.html – The main HTML file that structures the game.
- styles.css – The CSS file that styles the game.
- index.js – The JavaScript file that contains the game logic.

## JavaScript Functions
- nextSequence(): Starts the next sequence in the game.
- playSequence(): Animates the sequence for the player to follow.
- checkAnswer(currentLevel): Checks if the player's input matches the sequence.
- animatePress(currentColor): Animates button presses.
- playSound(name): Plays sound effects for each color.
- startOver(): Resets the game state for a new round.

