# Rya McKinnon · Game Portfolio

Playable browser games. Live at **https://ryaskye.github.io**

| Game | Genre | Play |
|---|---|---|
| Last Bus Home | Narrative driving | [Play](https://ryaskye.github.io/games/last-bus-home/) |
| Low Tide Café | Cozy cooking | [Play](https://ryaskye.github.io/games/low-tide-cafe/) |
| Grandma's Kitchen | Cozy cooking | [Play](https://ryaskye.github.io/games/grandmas-kitchen/) |
| Pixel Rally | Volleyball | [Play](https://ryaskye.github.io/games/pixel-rally/) |
| Lane Eight | Track meet | [Play](https://ryaskye.github.io/games/lane-eight/) |
| Rec Six | Volleyball diorama | [Play](https://ryaskye.github.io/games/rec-six/) |
| Park Fours | Volleyball diorama | [Play](https://ryaskye.github.io/games/park-fours/) |

## Structure

```
index.html          portfolio landing page
images/             card thumbnails
games/<name>/       each game, self-contained (index.html + any assets)
```

Each game is plain HTML, CSS and JavaScript with no build step. The 3D games load three.js from a CDN.

## Adding a game

1. Make a folder in `games/` and put the game's `index.html` (and assets) inside.
2. Add a screenshot to `images/` (16:9).
3. Copy one of the cards in `index.html` and update the link, image, title, text and tags.
