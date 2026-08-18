# 🌼 Genda Phool HQ

A three-stage birthday page for a friend who loves marigolds.

1. **Cake** — tap anywhere on the cake, one puff blows out all three candles
2. **Hero** — the smoke clears and "Happy Birthday Shraddha Shristy" lands letter by letter
3. **Gift** — a ribboned card unwraps to photos and a rotating set of wishes

Single self-contained `index.html` — no build step, no dependencies, no external requests.

## Adding photos

Open `index.html` and find the `PHOTOS` array near the bottom:

```js
var PHOTOS = [
  { src:"", caption:"Exhibit A — muskurate hue pakdi gayi" },
  ...
];
```

Put an image path (e.g. `"img/one.jpg"`) or a `data:` URI in `src`. An empty
`src` renders a placeholder frame instead. Add or remove entries freely — the
strip scrolls sideways.

## Local preview

```sh
python3 -m http.server 8000
# then open http://localhost:8000
```
