# soda-roulette.html
## *don't pick the spicy soda!! Oh no! BOOM!*

A minimalist, high-tension browser game of chance. Built with pure HTML, CSS, and JavaScript.
The Concept

Soda Roulette is a game of luck and suspense, stripped down to its bare essentials. The aesthetic is intentionally minimal, using only a black, white, and red color palette, a standard monospace font, and emoji icons. The experience is designed to be focused and tense, with no distractions.

The game is entirely self-contained in a single index.html file and requires no installation or setup.
How to Play

The objective is to find all five "safe" sodas without picking the single "spicy" one.

- Start the Game: Open the index.html file in any modern web browser.
- Pick a Soda: You will be presented with six sodas. Click on one to make your choice.
- The Reveal: After a 3-second suspenseful pause, the result is revealed.
    - Safe: If the soda is safe, the screen will flash white, and the chosen soda will turn white. You can then pick another soda.
    - Spicy: If you pick the spicy soda, the screen will flash red, a "click" sound will play, and the game ends. The screen will turn red with the text "you lost."
- Winning: If you successfully select all five safe sodas, the screen will flash white and then turn white with the text "you win."
- Play Again: To play a new round, simply refresh the browser page. The position of the spicy soda is randomized every time.

## Technology

Intentionally simple, using fundamental web technologies:

    - HTML: Provides the basic structure of the application.
    - CSS: Styles the application, using CSS variables for the strict color palette and keyframe animations for visual feedback.
    - JavaScript: Contains all game logic, from setup and event handling to the win/loss conditions.
    - Tone.js: A lightweight library imported via CDN to generate the single "click" sound effect on loss, avoiding the need for external audio files. 
