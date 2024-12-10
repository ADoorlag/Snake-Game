
# Snake Game

A modern browser-based implementation of the classic Snake game. This project showcases a clean, modular approach to creating interactive web experiences using core web technologies.

## Interesting Techniques

- **CSS Grid**: Used for creating a responsive game grid. See [CSS Grid on MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout) for details.
- **Dynamic DOM Manipulation**: The game dynamically creates and updates elements for the snake and food using JavaScript.
- **Event Handling**: Utilizes `keydown` events for responsive user interaction. Learn more about [KeyboardEvent](https://developer.mozilla.org/en-US/docs/Web/API/KeyboardEvent).
- **Game Speed Adjustment**: The game dynamically adjusts speed based on performance using `setInterval`, enhancing gameplay difficulty.
- **Collision Detection**: Implements boundary and self-collision checks for game over logic.

## Libraries and External Resources

- **Font: VT323** - A retro-style monospace font loaded from [Google Fonts](https://fonts.google.com/specimen/VT323).
- **Preconnect Optimization**: The `link rel="preconnect"` tag reduces latency when loading fonts from external sources. See [Preconnect on MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Link_types/preconnect).

## Project Structure

```plaintext
.
├── index.html      # Main HTML structure
├── style.css       # Styling for the game
├── script.js       # Game logic
├── assets/
│   ├── Snake_Game_Logo.png   # Logo image displayed on the start screen
└── README.md       # Project documentation
```

### Notable Directories

- **`assets/`**: Contains images and other static assets used in the game.

## Features

### Game Design
- **Responsive Layout**: Adjusts to the screen size using `flexbox` for centering and `CSS Grid` for the game board.
- **Custom Borders**: Multi-layered borders for a visually appealing game board design using `box-shadow` and border-radius.

### Game Mechanics
- **Randomized Food Placement**: Food spawns at random positions within the grid. 
- **Scoring System**: Keeps track of current and high scores, displayed with leading zeros.
- **Adaptive Speed**: The snake’s speed increases progressively as the game continues.

### Interaction
- **Keyboard Controls**: Arrow keys control the snake's movement; the spacebar starts the game.
- **Reset and Restart**: Implements game reset logic for a seamless user experience.
