# TONEFALL

A musical falling-blocks game on a 16×16 light grid, by **Snad Industries**.

Blocks fall and lock onto the grid, while a playhead sweeps across the board and
turns whatever is lit in each column into music — row = pitch — so your stack
becomes an evolving, always-in-key loop. Clearing rows adds a chord. It's built to
be played as much for the sound as for the game.

Single self-contained HTML file. Vanilla JS + Canvas + Web Audio. No build step,
no dependencies (only Google Fonts).

## Play

Live: enable GitHub Pages for this repo (Settings -> Pages -> Branch: `main` / root),
then open the published URL.

Local: just open `index.html` in any modern browser.

## Controls

- **<- ->** move - **up** rotate - **down** soft drop - **space** hard drop
- **P** pause
- **HOLD** button - freeze the current loop, then **EXPORT** it as a `.wav`
- **1-8** pick a chord - **Presets / Custom** toggle for your own scale
- Left-hand jam keys (random but always musical): **Q W E R T - F G H V**
- XY pad - fine delay / reverb - **A/Z** reverb - **S/X** delay feedback - **D/C** delay time

## Export

Hold a loop you like, hit EXPORT, and it renders four passes (including the
delay/reverb tails) offline and downloads a WAV. Drop it straight into a DAW.

## Look

Dark brutalist shell, amber-phosphor CRT screen with scanlines, and a soft white
ambient bloom that mirrors the board behind everything.

## License

MIT - see `LICENSE`. The code is free to use and modify with attribution;
the "Snad Industries" name and branding remain the author's.
