# Fourier Playground

An interactive, browser-based introduction to Fourier transforms. Build signals from harmonics, draw an arbitrary periodic wave, analyze an audio file or microphone sample, and hear the result.

## Features

- Live time-domain waveform and frequency spectrum
- Harmonic presets and individual amplitude controls
- Touch- and pointer-friendly freehand signal drawing
- Local audio-file and microphone analysis
- Adjustable Fourier reconstruction with a match score
- Web Audio playback
- Responsive mobile and desktop layout
- No backend, analytics, or uploaded audio

## Run locally

Serve this directory with any static web server, then open `index.html` through that server.

```sh
python3 -m http.server 8080
```

## Deploy

Push the repository to GitHub. The included GitHub Actions workflow publishes the static files to GitHub Pages.
