# Storage Monitoring Dashboard

A single-file HTML dashboard that shows storage capacity, per-volume usage, a usage trend chart and threshold alerts. It has no dependencies and no build step.

The data is simulated in the browser. To use real metrics, replace the body of `tick()` in `index.html` with a `fetch()` to your metrics API.

## Run locally

Open `index.html` in a browser.

## Deploy

GitHub Pages serves this repository from the `main` branch root.
