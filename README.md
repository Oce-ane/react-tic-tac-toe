# Tic Tac Toe Game in React

This project is an exercise to create a basic Tic Tac Toe game using React without the use of Webpack or other build tools. The goal is to understand how to set up a React project with minimal configuration and dependencies.

<h3>Setup and Instructions</h3>

1. **Prerequisites**: Ensure you have a modern web browser installed (e.g., Chrome, Firefox, Safari).

2. **Project Files**:

- **index.html:** The main HTML file that includes the necessary scripts and styles.
- **index.jsx:** The React component file containing the logic for the Tic Tac Toe game.

3. **How to Run:**

- Simply open the `index.html` file in your web browser. The Tic Tac Toe game will be displayed, and you can start playing immediately.

<h3>Project Structure</h3>

- **index.html:** Contains the HTML structure and links to React, ReactDOM, Babel, and the custom React component.
- **index.jsx:** Contains the React components (Square, Board, Game) and the game logic, including the calculateWinner function and the reset functionality.

<h3>Key Features</h3>

- **React Components:** The game is built using basic React components.
- **No Build Tools:** No Webpack, Babel CLI, or other build tools are used. Babel is included via a CDN to transform JSX on the fly.
- **Reset Button:** A reset button is provided to restart the game at any point.

<h3>How It Works</h3>

1. **index.html:**

- Includes scripts for React, ReactDOM, and Babel.
- Contains a div with id="container" where the React app will be rendered.
- Styles for the Tic Tac Toe board and squares.

2. **index.jsx:**

- **Square Component:** Represents a single square on the board.
- **Board Component:** Manages the state of the game, renders squares, and includes the reset functionality.
- **Game Component:** The main component that renders the Board.
- **calculateWinner Function:** Determines the winner of the game.

<h3>Additional Information</h3>

This project is a basic example to demonstrate the creation of a simple React application without the need for complex build setups. It is suitable for beginners who are learning React and want to understand the fundamental concepts without the overhead of additional tooling.

<h3>License</h3>

This project is open-source and available under the MIT License.
