# Humanoid peg insertion — project page

A static GitHub Pages showcase. This repository contains only the page, selected evaluation data, and two videos; no simulation or training source.

Platform: https://github.com/WATonomous/pioneer_humanoid/tree/main

## Preview

Run `python3 -m http.server 8000` here, then open http://localhost:8000.

## Provenance

- Normal video: seed 1008, ACT 150k, temporal ensembling 0.01.
- Recovery video: seed 14002, ACT 222k, execute 50, no ensembling or expert takeover; verified playback job 707658.
- Main results: job 707503, fresh seeds 14000 onward. Full task 20 trials; controlled starts 10 per condition.
- Earlier diagnostic: job 706499, checkpoint 150k, seeds 1000–1009.
- Spatial curriculum is described as a next stage; no results for it are claimed.

Serve the main branch root with GitHub Pages.
