# retropuzz
Retropuzz is a jigsaw puzzle game built with HTML.

## About
- This is a little browser-based jigsaw puzzle game with a retro pixel-art look. Upload any photo; it gets sliced into a grid, shuffled, and you drag the pieces back into place. That's basically it; no backend, no build step, no accounts. Just open the HTML file and play.
- This is mostly made for fun and to mess around with drag-and-drop stuff.

## What it does?
- Upload any image; it auto-guesses a decent grid size based on the aspect ratio, or pick 4×4 / 5×5 / 6×6, or type in a custom size
- Drag pieces around freely - swap two pieces
- Timer & move counter, starts once you hit Start (not the second you touch a piece)
- Confetti & a random "you did it" quote on win (there's like 120+ of these, all different, none of them say "Congratulations!" because that's boring, lol)
- A "show it off" button that generates a downloadable screenshot of your solved puzzle + your time — built with plain canvas, no screenshot library, so it doesn't depend on anything external. Everything's local. Your image never leaves your browser.

## Running it
- There is nothing to install!
- Just open retropuzz.html (here in the repo) or click [here!](retropuzz.html)
- That's it!

## Tech
Single HTML file. JS, no frameworks, no npm, no build tooling. CSS does the pixel-art look (custom properties & image-rendering: pixelated + a chunky retro font from Google Fonts). Everything's self-contained on purpose.

## Known quirks
- Very tall or very wide images get grid sizes that work fine but might not look perfectly square-cropped — best results come from roughly 1:1 images
- No mobile-native touch polish yet; touch dragging works but could feel smoother
- Custom grid sizes above ~12 get fiddly to actually solve (that's on you, not a bug!)

## Stuff I might add later- maybe never :(
- Highest Score
- Rotated pieces
- Toggles for ghost mode
- Sound effects

## Notes:
- not trying to reinvent the jigsaw puzzle here, just wanted something that felt fun actually to use
- this was my very first software game i built, as i am more of a hardware guy
- make sure see my other projects [cookie cutters](https://github.com/vd-sh/cookie-cutters), [key rings](https://github.com/vd-sh/key-rings), [mp3 player](https://github.com/vd-sh/mp3-player) i did until now or visit my [profile](https://github.com/vd-sh) to see all projects :)