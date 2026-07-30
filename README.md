# Doodley

An drawing game where you sketch a word and model guesses what you're drawing

## Play
[Click here to play](https://melodelete.github.io/Doodely/)


## How It Works

1. A **target word** appears
2. You draw it on the canvas
3. The AI model watches as you draw and shows its **top 3 guesses** with what is most likely
4. You get **30 seconds** per round — score a point if one of the model's top 3 guesses matches the target word

## Features

- **AI classification** — the model runs every 400ms as you draw
- **132 words** from DoodleNet's vocabulary, shuffled each session
- **Undo / Clear** — undo up to 25 strokes, or clear the canvas entirely
- **Timer ring** — a circular progress indicator that changes color as time runs out
- **Score & streak tracking** — your score and current streak 
- **Difficulty** - There are 3 modes,Easy,Normal, and Hard, Each one decreases the timer and must make the doodle look better (Can only be changed during celebration or Timeout)
- **Skipping** You can Skip words incase it is too difficult or The AI Cant Guess it
- **Advancements** There are 3 Achievments for doodeling 3/5/10 times in a row

## Tech Stack

| Layer | What It means|
|---|---|
| **AI model** | [DoodleNet](https://learn.ml5js.org/#/reference/doodle-net) via [ml5.js](https://ml5js.org/) 0.12.2 |
| **Canvas** | HTML5 Canvas
| **Fonts** | [Inter](https://fonts.google.com/specimen/Inter) via Google Fonts |
| **Dependencies** |A webby webby browser

## Word List / Credits

The game uses a curated subset of **132 words** from DoodleNet's.

## License

MIT 