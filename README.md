# Loredle

Guess the video game from six pieces of lore. One daily puzzle, plus free play with era, platform, and genre filters, a hard mode, and an archive of past dailies.

Play it at **https://ethdmiller.github.io/Loredle/** (once Pages is enabled).

## How it works

- Six clues per game, revealed one at a time, from oblique to obvious. Each tier has two variants, so a repeat game plays as a different puzzle.
- Six guesses. A miss tells you whether the answer is earlier or later than your guess and whether the genre or developer match. Hard mode turns those hints off and adds deeper cuts to the pool.
- Everything (streaks, stats, flags, archive results) lives in your browser's local storage. There is no server.

## Running it

It's a single `index.html`. Open it in a browser, or host it anywhere static (GitHub Pages works: Settings → Pages → Deploy from branch → `main` / root).

## Flagging a bad clue

After a round ends, each clue has a 👎. Flagged clues collect under Stats with a "Copy list" button. Paste the list into an issue.

## Credits

Inspired by [Doctordle](https://doctordle.org/) and [Wordle](https://www.nytimes.com/games/wordle). Not affiliated with either.

## License

Code is licensed under AGPL-3.0 (see `LICENSE`). The clue text and game data are licensed [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).
