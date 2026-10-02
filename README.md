# Digital Clock

A live digital clock displayed over a looping, full-screen video of beach waves. Built with plain HTML, CSS and JavaScript, with no libraries or build step.

## Features

- Shows the current time as `HH:MM:SS` and updates every second
- Full-screen background video that loops silently and scales to any window size
- Large monospace clock centred on the page

## Running it

1. Clone the repository:
   ```bash
   git clone https://github.com/alp-isik/digital-clock.git
   ```
2. Open `index.html` in your browser.

The background video is about 80 MB, so the clone takes a moment.

## Project structure

| File | Purpose |
| --- | --- |
| `index.html` | Page markup: the video background and the clock |
| `styles.css` | Layout, video sizing and clock styling |
| `script.js` | Reads the current time and refreshes the clock every second |
| `video/beach-waves.mp4` | Background video |
