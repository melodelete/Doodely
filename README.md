# Doodley

A drawing game where you sketch a word and model guesses what you're drawing

[Click here to play](https://melodelete.github.io/Doodely/)

## How It Works

1. A word appears
2. You draw it on the canvas
3. The AI model watches as you draw and shows its top 3 guesses with what is most likely
4. You get 30 seconds per round depending on difficulty

## Features

- AI classification
- 132 words from DoodleNet's vocabulary.
- Undo / Clear
- Timer ring
- Score and streak tracking, Your score ,Current streak, And Best streak
- Difficulty, There are 3 diffculty's,Easy,Normal, and Hard, Each one decreases the timer and must make the doodle look better (Can only be changed during celebration or Timeout)
- Skipping, You can Skip words incase it is too difficult or The AI Cant Guess it
- Advancements, There are 4 Achievments for doodeling 3/5/10 times in a row,And finishing under 10 seconds.
- Hotkeys, There is currently only one hotkey which Is S to skip a word

## Tech Stack

| Layer | What It means|
|---|---|
| **AI model** | [DoodleNet](https://learn.ml5js.org/#/reference/doodle-net) via [ml5.js](https://ml5js.org/) 0.12.2 |
| **Canvas** | HTML5 Canvas
| **Dependencies** |A webby webby browser

## License

MIT 