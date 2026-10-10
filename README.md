# Ad Overlay Studio

Batch-add headlines and CTA buttons to ad images. Runs **100% in your browser**: images are never uploaded anywhere, and brand kits (colors, fonts) are saved in your browser's localStorage on each device.

**Use it online:** https://thomasbrosch.github.io/ad-overlay-studio/

On a phone, open the link and choose **Add to Home Screen** to install it as an app. It also works offline once loaded.

## Run it on your own machine

No build step and no dependencies.

1. Download this repo (**Code → Download ZIP**) or `git clone https://github.com/thomasbrosch/ad-overlay-studio.git`.
2. Open `index.html` in a browser. (Offline install/caching needs `http://`, so for that run `python -m http.server` in the folder and visit `http://localhost:8000`.)

## Files

- `index.html`: the whole app
- `sw.js`, `manifest.webmanifest`, `icons/`: make it installable and usable offline
- `vendor/jszip.min.js`: zip export, bundled so it works offline

## Deploying changes (GitHub Pages)

Edit `index.html`, bump `VERSION` in `sw.js` so installed copies refresh, and push to `main`.

## License

MIT. Bundled JSZip is MIT/GPLv3 dual-licensed by its authors.
