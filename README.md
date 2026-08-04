# brink

add clean borders to your photos for instagram, stories and tiktok. everything runs in your browser, your photos never leave your device.

**[use it here](https://sergiopaniego.github.io/brink/)**

![brink](screenshot.jpg)

## features

- exact ratios for every format: post 4:5, square 1:1, wide 1.91:1, story/reel/tiktok 9:16, or keep the ratio as shot
- fit keeps the whole photo and fills the ratio with the border color, fill crops to the ratio instead
- pixels are never resampled: fit pads, fill is a pure crop, the photo stays at native resolution
- drag the photo to reframe, zoom for a tighter crop (zooming past x1 is the only thing that resamples, and the readout says so)
- collage: 2x1, 1x2, 3x1 and 2x2 templates, place any photo in any cell, leave cells empty, reframe each cell on its own
- border size and color are configurable, defaults to a small white border
- batch: load several photos, tweak once, save all
- exports jpeg (quality 97) or png, output size always visible
- works on your phone from the same url

## develop

the whole app is a single `index.html`. no build step, no dependencies, no server.

```
git clone https://github.com/sergiopaniego/brink
open brink/index.html
```

any static server also works, for example `python3 -m http.server`.

built with ai assistance.
