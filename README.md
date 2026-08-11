# 🐍 Snake — Smooth Edition

A single-file, dependency-free take on classic Snake with sub-cell interpolated movement, particle effects, golden apples, and full touch support. Runs entirely in the browser — no build step, no assets, no server.

**[Play it](./index.html)** by opening `index.html` in any modern browser.

## Features

- **Smooth interpolated movement** — the snake glides between grid cells via a fixed-timestep game loop, instead of the classic jerky per-cell snap
- **Golden apples** — a 15% chance per spawn, worth +3 and a bigger score/growth boost, with distinct particle burst and sound
- **Speed ramp** — pace quickens gradually as your score climbs
- **Wrap or solid walls** — toggle whether the board edges wrap around or kill you
- **Adjustable grid size, speed, and trail effects** — all changeable mid-menu via the settings panel, and remembered between sessions
- **Sound** — lightweight synthesized effects (Web Audio, no audio files) for eating, dying, pausing, and starting; toggle from the top bar or settings
- **Touch controls** — swipe anywhere on the board, or use the on-screen D-pad that appears automatically on touch devices
- **Best score persistence** — high score and all settings are saved to `localStorage`
- **Accessible & responsive** — keyboard-focus outlines, `prefers-reduced-motion` support, and a layout that adapts down to mobile

## Controls

| Action | Input |
|---|---|
| Move | Arrow keys or `WASD`, swipe, or on-screen D-pad |
| Pause / Resume | `P` or `Esc`, or the pause button |
| Start / Restart | `Space` / `Enter`, or the on-screen buttons |

## Tech

Plain HTML, CSS, and vanilla JavaScript — no frameworks, no build tools, no external dependencies beyond a Google Fonts stylesheet. The whole game lives in `index.html`.

## License

MIT — see [LICENSE](./LICENSE), or the summary below.

```
MIT License

Copyright (c) 2026 Snake — Smooth Edition contributors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
