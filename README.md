# Simon Game

A browser-based memory game built with HTML, CSS, JavaScript, and
jQuery. The player repeats an increasingly long sequence of colored
buttons and tries to remember the pattern.

This project was completed as part of the **Complete Web Development
Bootcamp by Dr. Angela Yu on Udemy**. It gave me practice working with
JavaScript logic, user interactions, event handling, and DOM
manipulation.

## Live Demo

https://ashkanhussaini.github.io/Simon-game/

## How to Play

1.  Press any keyboard key to start the game.
2.  Watch the color that flashes and listen to its sound.
3.  Click the matching colored button.
4.  Each new level adds another color to the sequence.
5.  Repeat the full sequence in the correct order.
6.  If you click the wrong color, the game ends. Press any key to start
    a new game.

## Built With

-   HTML5
-   CSS3
-   JavaScript
-   jQuery
-   Google Fonts

## Features

-   Randomly generated color sequences.
-   Four interactive colored buttons.
-   Sound effects for each color.
-   Visual feedback when a button is pressed.
-   Level progression with an increasingly difficult sequence.
-   Game-over feedback and restart functionality.

## What I Practised

-   Using JavaScript arrays to store and compare sequences.
-   Generating random values with `Math.random()`.
-   Handling keyboard and mouse events.
-   Selecting and updating HTML elements with jQuery.
-   Using timers with `setTimeout()`.
-   Creating visual effects with jQuery animations and CSS classes.
-   Organizing game logic into reusable functions.

## Run Locally

1.  Clone this repository:

    ``` bash
    git clone https://github.com/ashkanhussaini/Simon-game
    ```

2.  Open the project folder.

3.  Open `index.html` in your browser.

The project loads jQuery from its CDN, so an internet connection is
required for that dependency. Keep the `sounds` folder in the same
project directory as `game.js`.

## Project Structure

``` text
simon-game/
├── index.html
├── styles.css
├── game.js
├── sounds/
│   ├── green.mp3
│   ├── red.mp3
│   ├── yellow.mp3
│   ├── blue.mp3
│   └── wrong.mp3
└── README.md
```

Make sure the filenames and folder structure match the paths used in the
code.

## Possible Improvements

-   Add a visible Start/Restart button for touch-screen users.
-   Improve the layout for mobile screens.
-   Add a high-score tracker.
-   Refactor the game logic using modern JavaScript syntax.

## Contact

-   **Email:** ashkanhosseini122@gmail.com
-   **LinkedIn:** Add your own LinkedIn profile URL

------------------------------------------------------------------------

Thanks for checking out my project!
