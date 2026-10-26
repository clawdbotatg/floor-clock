# Floor Clock

A live clock in three.js. The floor slides under the clock, one tile per second. Each new digit slides in from behind and catches up. The old one drops into its hole and rides away with the floor.

A recreation of [Kitasenju Design's clock](https://x.com/kitasenjudesign/status/2114308460456329379) (@kitasenjudesign). All credit for the idea and design goes to them. This version was matched to their video frame by frame (camera, layout, timing).

## Run

It's one file. Open `index.html` in a browser, or serve the folder:

```
npx http-server .
```

Drag to look around. Shows your local time.

## Files

- `index.html`: the whole thing (three.js 0.160 from jsDelivr, digit outlines inlined).
- `tools/`: what was used to match the original frame by frame. See `tools/README.md`.

## Font

The digits come from TeX Gyre Heros Bold (GUST Font License), converted with `tools/font-to-typeface.mjs`.
