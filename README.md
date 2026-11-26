# Wordle — CS Edition

A five-letter word puzzle with vocabulary from an English for Academic Purposes course. Built with HTML, CSS, and vanilla JavaScript.

![A solved round showing SLATE, ROUND, CHIMP, and the winning guess ELUDE](wordle-gameplay.jpg)

## How to play

Find the hidden word in six guesses. The tiles and keyboard show what each guess tells you.

- 🟩 **Green** — correct letter and position
- 🟨 **Yellow** — correct letter in a different position
- ⬛ **Gray** — no remaining match for that letter

Use your keyboard or the on-screen keys. Select **New Game** for a fresh round, or press **Enter** once a round ends.

## Run locally

Open [`index.html`](index.html) in your browser. If you prefer a local server, run this from the repository folder and open [http://localhost:8000](http://localhost:8000).

```bash
python -m http.server 8000
```

## Change the words

Edit the `WORDS` array in [`script.js`](script.js). The game uses entries that are exactly five characters long and converts them to lowercase.

Made by **Davoud and Hosna** for a Fall 2025 course project at the University of Isfahan.
