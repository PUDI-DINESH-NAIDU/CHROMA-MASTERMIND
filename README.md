# CHROMA-MASTERMIND
**Chroma Mastermind: RGB Color Guessing Game**

## Overview

**Chroma Mastermind** is an RGB color guessing game implemented in HTML, CSS, and JavaScript. The game challenges players to identify the correct RGB color code from a set of options. The difficulty level can be adjusted, and players are rewarded for correct guesses.

## Mechanism

1. **HTML Structure:**
   - The game is built within an HTML structure that includes a title, difficulty selection dropdown, color display area, color options container, result display, and a "New Game" button.

2. **CSS Styling:**
   - The styling is set up using CSS to create a visually appealing and responsive interface. The game container is centered on the page with a background color of #f0f0f0.

3. **JavaScript Functions:**

   - **`getRandomInt(min, max)` Function:**
     - Generates a random integer within a specified range.

   - **`generateRandomColor()` Function:**
     - Creates a random RGB color code.

   - **`generateOptions(numOptions)` Function:**
     - Generates an array of random color options based on the selected difficulty level.

   - **`newGame()` Function:**
     - Sets up a new game by determining difficulty, generating a correct color, creating options, and displaying them.

   - **`displayColor(color)` Function:**
     - Displays the RGB color code to be guessed.

   - **`displayOptions(options)` Function:**
     - Populates the options container with color boxes based on the generated color options.

   - **`checkAnswer(selectedColor)` Function:**
     - Compares the selected color with the correct color and updates the result display accordingly.

4. **Game Initialization:**
   - The `newGame()` function is called initially to set up the first game.

## Uses and Benefits

- **Educational Purpose:**
  - Chroma Mastermind serves as an educational tool to help users improve their understanding of RGB color codes.

- **Entertainment:**
  - Provides an engaging and fun activity for users to test their color perception skills.

- **Customizable Difficulty:**
  - Users can choose between easy, medium, and hard difficulty levels, allowing for a gradual increase in complexity.

- **Visual Appeal:**
  - The use of color boxes and dynamic updates enhances the visual appeal of the game.

- **Responsive Design:**
  - The game is designed to be responsive, ensuring a seamless experience on various devices.

- **Randomization:**
  - The game leverages randomization to create a unique experience in each playthrough, keeping it interesting for users.

- **Instant Feedback:**
  - Provides immediate feedback on the correctness of the user's guess, fostering a responsive and interactive environment.

## How to Play

1. Choose a difficulty level from the dropdown menu.
2. The RGB color code to be guessed is displayed.
3. Click on the color box that you think corresponds to the displayed RGB color.
4. Receive instant feedback on the correctness of your guess.
5. Click the "New Game" button to start a new round with a different color.

Enjoy playing Chroma Mastermind and test your RGB color recognition skills!
