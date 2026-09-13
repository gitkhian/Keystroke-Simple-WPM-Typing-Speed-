# Keystroke

A minimalist typing speed test with a typewriter-inspired design — tracks WPM, accuracy, and time in real time.

Type the passage as it appears, and Keystroke tracks your words-per-minute, accuracy, and elapsed time live as you go. Every run pulls a fresh, randomized passage, so no two tests are the same. No sign-up, no backend — just open it and start typing.

*by Githian*

## Features

- **Live WPM tracking** — updates as you type, calculated from characters typed over elapsed time
- **Live accuracy tracking** — compares each typed character against the target passage
- **Randomized passages** — pulled from a bank of common words, different every run
- **Three passage lengths** — short (12 words), medium (40 words), long (80 words)
- **Keyboard shortcut** — press `Esc` to restart instantly, no mouse needed
- **Typewriter-inspired design** — paper, ink, and ribbon-red visuals instead of a generic dashboard look

## Running it

No install, no build step, no dependencies.

1. Download `index.html`
2. Open it in any browser (double-click it, or drag it into a browser tab)

That's it. Everything runs client-side.

## Tech

Plain HTML, CSS, and JavaScript — one file, no framework, no backend. Fonts (`Special Elite`, `Courier Prime`) are loaded from Google Fonts over a CDN link; everything else is self-contained.

## Ideas to extend

- Persist run history (e.g. `localStorage`) to chart WPM improvement over time
- Word-level error handling so a single mistyped character doesn't misalign the rest of the passage
- A custom word-count option instead of fixed short/medium/long presets
- A race mode where two people type the same passage against each other

## License

MIT — free to use, modify, and share.
