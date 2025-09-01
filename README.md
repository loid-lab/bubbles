# Bubbles

This project is a simple interactive animation that displays text as a collection of bubbles. The bubbles repel the mouse cursor, and the user can change the displayed text.

## How to use

1. Open `index.html` in your browser.
2. To change the displayed text, open `index.js` and modify the string in the `drawName()` function call.

## How it works

The text is rendered on a canvas element. Each letter is composed of a collection of points, which are rendered as bubbles. The bubbles are animated to repel the mouse cursor.

The `alphabet.js` file contains the data for the letters. Each letter is defined by a set of points. The `bubbles.js` file contains the code for the bubble animation. The `index.js` file contains the code that initializes the animation.

## Deployment

This project is hosted on GitHub Pages. You can view the live version at `https://loid-lab.github.io/bubbles/`