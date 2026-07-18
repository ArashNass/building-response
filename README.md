# Building Response Lab

**Live tool:** https://arashnassirpour.com/building-response/

An educational, first-mode building-response simulation showing how height, relative stiffness, mass, damping, and a soft ground storey affect motion under earthquake excitation.

## Features

- Configurable 2–20-storey concrete or steel buildings.
- Selectable 2D structural and MDOF animation views.
- Real digitised accelerograms including El Centro, Kobe, Northridge, Chi-Chi, Kocaeli, Landers, Loma Prieta, and others.
- Synthetic pulse, harmonic, and frequency-sweep motions.
- Live roof displacement, floor displacement, interstorey drift, and peak-response charts.
- Timeline scrubbing, playback controls, presets, and JSON snapshot export.
- A shared deformation profile so the animation and calculated response remain consistent.

The real accelerograms are sourced from public NHERI SimCenter and PEER Strong Motion datasets, with source details shown in the application.

## Model scope

This is a simplified first-mode model. Its period is an empirical estimate, higher-mode response is not included, and the displayed drift thresholds are illustrative rather than code-calibrated. Near-resonant, low-damping cases can produce physically unrealistic displacements because results are not artificially capped.

Use it for learning and exploration—not structural design, code compliance, or professional engineering decisions.

## Run locally

The application is a self-contained `index.html`. Open it directly in a modern browser or serve the directory with any static web server.

## Deployment

GitHub Pages publishes `main` at the live URL above.

## Licence

Copyright (C) 2026 Arash Nassirpour.

Licensed under the GNU Affero General Public License v3.0 only (`AGPL-3.0-only`). See [LICENSE](LICENSE).
