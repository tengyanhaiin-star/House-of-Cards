# House of Cards

An interactive 3D house of cards built with Three.js. Watch all 52 cards fly one by one from a deck and assemble into a three-story pyramid — then rotate around it freely.

## Demo

Visit [House of Cards](https://tengyanhaiin-star.github.io/House-of-Cards/)

## Features

- **52-card animation** — cards fly one at a time from a shuffled deck and land precisely into a three-layer pyramid structure
- **Randomised deck** — cards are shuffled on every Build and Reset, so each run looks different
- **Real SVG card faces** — powered by [SVG-cards](https://github.com/htdebeer/SVG-cards) by Huub de Beer
- **3D orbit controls** — drag to rotate, scroll to zoom, centred on the house of cards
- **iOS compatible** — safe area insets, Retina pixel ratio, touch gesture handling
- **Noticia Text typography** — card numerals and UI buttons use [Noticia Text](https://fonts.google.com/specimen/Noticia+Text) via Google Fonts

## File Structure

```
.
├── house_of_cards.html       # Main application (single-file)
├── svg-cards.svg             # SVG playing card sprite (see attribution)
├── NoticiaText-Regular.woff2 # Noticia Text font (latin subset)
└── README.md
```

## Usage

Because the app fetches `svg-cards.svg` and `NoticiaText-Regular.woff2` at runtime, it must be served over HTTP — opening the HTML file directly via `file://` will not work.

## Controls

| Input | Action |
|---|---|
| Drag | Orbit around the house of cards |
| Scroll / Pinch | Zoom in and out |
| ▶ Build | Shuffle the deck and animate the build |
| ↺ Reset | Return all cards to the deck |

## Dependencies

| Library | License |
|---|---|
| [Three.js](https://threejs.org) | MIT |
| [SVG-cards](https://github.com/htdebeer/SVG-cards) | LGPL-2.1 |
| [Noticia Text](https://fonts.google.com/specimen/Noticia+Text) | OFL-1.1 |
| [Courier Prime](https://fonts.google.com/specimen/Courier+Prime) | OFL-1.1 |

## License

This project is licensed under the **GNU Lesser General Public License v2.1 (LGPL-2.1)**, in accordance with the license of the SVG-cards library on which it depends.

See the [LGPL-2.1 license text](https://www.gnu.org/licenses/old-licenses/lgpl-2.1.html) for details.

### Attribution

Playing card graphics from [SVG-cards](https://github.com/htdebeer/SVG-cards) by Huub de Beer, originally created by David Bellot. Licensed under LGPL-2.1.
