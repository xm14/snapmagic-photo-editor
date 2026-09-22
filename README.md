# SnapMagic

Browser-based photo editor. Take photos directly in the browser and apply edits. No uploads, no server storage. All processing happens client-side.

## What It Does

Captures photos using the device camera through getUserMedia. Applies real-time manipulations: background replacement, color filters, and adjustments. The image never leaves the device. There is no backend, no storage, no account.

## Features

- In-browser camera capture using getUserMedia.
- Real-time photo manipulation: background swap, filters, adjustments.
- Zero server storage. All processing client-side.
- No signup, no ads.
- Open source.

## Stack

- HTML5
- CSS3
- JavaScript
- Canvas API for image processing

Optional: TensorFlow.js for AI-based background removal.

## Running Locally

Clone the repository and open index.html in a browser. No build step required. Camera access requires HTTPS or localhost.

## Live Demo

https://xm14.github.io/snapmagic-photo-editor/

## Notes

Camera access through getUserMedia requires a secure context. The demo on GitHub Pages runs over HTTPS, so it works. If you run the project locally over plain HTTP, the browser will block camera access. Use localhost or a local HTTPS server.

Background removal with TensorFlow.js is optional and adds a significant payload. If you do not need it, the editor works without it.

## License

MIT. Use, modify, distribute.

## Contact

Email: martinrlab@gmail.com
I try to respond quickly.
