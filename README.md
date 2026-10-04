# Eelgrass AR

Standalone AR image trigger using MindAR. No Twine or narrative system—just image detection with custom callbacks.

## Setup

1. Add your compiled `targets.mind` file to this repo (use [MindAR's compiler](https://hiukim.github.io/mind-ar-js-doc/tools/compile))
2. Place trigger images in `/images/` folder
3. Open `index.html` on a device with camera access (HTTPS or localhost)

## Usage

Edit the `onTargetFound()` and `onTargetLost()` callbacks in `index.html` to trigger your custom logic.

## Tech Stack

- [MindAR](https://github.com/hiukim/mind-ar-js) - Web AR image tracking
- Three.js - Optional 3D rendering
