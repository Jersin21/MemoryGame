## Memory Card Game - README

This is a memory card game developed in React using Vite and styled with Tailwind CSS. The game consists of a grid of cards with images of Pokémon obtained through the PokeAPI. The objective of the game is to click on the cards randomly without repeating the same card, while keeping a score. If the player repeats a card, the score resets, and a "You Lost" message is displayed. The game continues until the player repeats a card.

### Game Features

- The card grid is 3x3 and contains 9 cards.
- The card images are random Pokémon obtained from the PokeAPI.
- The score increases each time the player clicks on a card that has not been repeated.
- If the player repeats a card, the score resets, and a "You Lost" message is displayed.
- Each time the player clicks on a card, the cards are randomly rearranged to change their position in the grid.

### Project Structure

The project consists of the following files:

- `App.js`: The main component that contains the `ContainerCards` component and the game state management.
- `ContainerCards.js`: The component that displays the card grid and the score.
- `Cards.js`: The individual card component that shows the image of a Pokémon.
- `index.css`: Global CSS file with custom styles for the game.
- `index.html`: Base HTML file for the React application.
- `vite.config.js`: Vite configuration for the project.

### Running the Game

To run the game, make sure you have Node.js and npm installed on your system. Then follow these steps:

1. Clone the project repository.
2. Navigate to the project directory in your terminal.
3. Run the following command to install the dependencies:

npm install


4. Once the dependencies are installed, run the following command to start the development server:

npm run dev

5. Open your browser and go to `http://localhost:3000` to see the game in action.

Have fun playing the Pokémon Memory Card Game! If you have any questions or comments, feel free to let me know.

