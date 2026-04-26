# Solitaire ♠

A touch-friendly Klondike solitaire game built for seniors — large cards, high contrast, and simple tap-to-play controls. Works on phones, tablets, and desktop browsers.

[Play now →](https://solitaire-gules.vercel.app)

## Features

- **Tap to play** — tap a card to select (glows gold), tap where to place it
- **Double-tap** — auto-moves a card to its foundation pile if valid
- **Drag support** — drag cards on touch screens and mouse
- **Large cards** — 115–125px wide, bold rank labels at 1.6rem+
- **High contrast** — dark green felt background, white cards, red/black suits
- **No time pressure** — play at your own pace
- **Undo** — unlimited undo
- **Auto-complete** — sends all ready cards to foundations
- **Keyboard shortcuts** — D=Draw, U=Undo, A=Auto, N=New, Esc=Deselect

## Deploy

Single HTML file — drop on any static host:

| Platform | Instructions |
|----------|-------------|
| **Vercel** | `vercel deploy` |
| **GitHub Pages** | Enable in repo Settings → Pages → main branch |
| **Netlify** | Drag-and-drop the folder |
| **Any server** | Serve `index.html` with any HTTP server |

## Tech

Zero dependencies, no framework, no build step. Pure HTML/CSS/JS. ~32KB.

## License

MIT
