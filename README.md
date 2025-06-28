# Phase 10 Scorecard

This project is a simple website for keeping score while playing the
**Phase 10** card game. It uses [Tailwind CSS](https://tailwindcss.com)
via CDN and does not require any build steps.

## Features

- Add any number of players.
- Display each player's current phase and total score.
- Show the required card combination for the player whose turn it is.
- Record points left in a player's hand after each round.
- Advance a player to the next phase when they complete the current one.
- Rotate turn order automatically.

The phases follow the standard Phase 10 rules:

1. 2 sets of 3
2. 1 set of 3 + 1 run of 4
3. 1 set of 4 + 1 run of 4
4. 1 run of 7
5. 1 run of 8
6. 1 run of 9
7. 2 sets of 4
8. 7 cards of one color
9. 1 set of 5 + 1 set of 2
10. 1 set of 5 + 1 set of 3

## Usage

Open `index.html` in your browser. No additional dependencies are
required. Add players, enter the points they have remaining after each
round, and use the buttons to advance turns and phases.

The winner is the player who completes all phases with the lowest total
score.
