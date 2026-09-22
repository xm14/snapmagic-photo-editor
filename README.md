# SnapMagic

Browser-based photo editor. Take photos directly in the browser and apply edits. No uploads, no server storage. All processing happens client-side.

## What It Does

Captures photos using the device camera through `getUserMedia`. Applies real-time manipulations: background replacement, color filters, and adjustments. The image never leaves the device. There is no backend, no storage, no account.

## Features

- In-browser camera capture using `getUserMedia`.
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

```bash
git clone https://github.com/xm14/snapmagic-photo-editor.git
cd snapmagic-photo-editor
