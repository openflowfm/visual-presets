# visual[flow] presets

The full preset library that [visual[flow]](https://github.com/openflowfm/visuals) downloads:
9,795 MilkDrop presets in their style folders, with `index.json` (each preset's style,
authors, colours, brightness, speed and intensity) and `thumbnails/` (a WebP picture of each
preset, named by its content hash), so the library arrives grouped and with pictures.

The app downloads this repo's archive at a pinned commit
(`https://github.com/openflowfm/visual-presets/archive/<commit>.tar.gz`); there are no
releases.

## Credits and licence

The presets are projectM's
[Cream of the Crop](https://github.com/projectM-visualizer/presets-cream-of-the-crop),
curated and sorted by ISOSCELES, as they are. Every preset belongs to its author, named in
its file name and in `index.json`; thank you to all of them. The licence is projectM's, in
[`LICENSE.md`](LICENSE.md).

## How it's built

[`docs/pack.md`](https://github.com/openflowfm/visuals/blob/main/docs/pack.md) in
openflowfm/visuals: the presets at a pinned projectM commit, drawn by the engine's `index`
bin for the index and thumbnails, copied here, committed and pushed; then the app's pinned
commit is moved to it.

## Takedown

If you made a preset here and want it removed, open an issue in this repo naming it, and
it will be taken out of the next commit the app downloads.
