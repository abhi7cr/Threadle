# Threadle

A Wordle x Zip hybrid word puzzle game.

## How it plays

- 6x6 letter grid, five sequential rounds
- Each round: one 5-letter word, crossword-style clue, 6 guesses
- Guesses are traced as orthogonal paths (Zip-style drag)
- Win a round to bank a gold letter and lock its trail as a wall
- Finale: one continuous thread through all 5 gold letters in order (strict Zip, no backtracking)
- 365 boards, daily puzzle with weekly difficulty ramp (Thursday easiest → Wednesday hardest)

## Tech

Static single-page app. No build step, no backend. Open `index.html` in a browser.
