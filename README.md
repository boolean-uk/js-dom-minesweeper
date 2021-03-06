# Minesweeper
In this exercise we're building a simplified version of the popular Minesweeper game. All user interaction should be done through the prompt, so you'll be focusing on the logic.

## Instructions
- Create a script that models a board with 10 spaces in it. You don't need to render anything to the DOM at this point, just create a way to represent a board with 10 spaces.
- Add a "mine" to one of these spaces
- Ask the user to enter an index (1-10) for the board using `prompt`
- They will keep entering indices until they either hit a mine and lose, or clear all the empty spaces and win
- When the game ends, let them know the outcome by rendering the final state of the board using the DOM. 
 - Cleared spaces should be green, unchecked spaces grey, and spaces with a hit mine red.

## Tips
- Think about how can you repeatedly ask users for input until a condition is met?

## Extension 1
- Try to think about different ways you could represent a board, and explore whether they make it easier to manage it all.

## Extension 2
- Allow the user to pick a difficulty at the start of the game. For example, they can choose between "easy", "normal" and "hard". Depending on the difficulty, add more or fewer mines to the board
- Use either `setInverval` or `setTimeout` to render the final spaces 1 at a time, with a delay of 500ms between each cell being shown.

## Extension 3
- Rather than using 'prompt', render the board state and allow the user click a cell to check if it is a mine.

