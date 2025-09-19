# Wave Simulation – README

## Overview

Interactive 2-D wave simulator built in HTML, CSS, and JavaScript.
Users can create, edit, and animate wave sources, adjust medium properties, and observe interference patterns in real time.

## Features

* **Realistic Physics toggle**

  * Switch between exponential decay with user-controlled damping and geometric decay for physically accurate 2-D spreading.
* **Medium Properties panel**

  * Animation speed, damping (hidden in realistic mode), resolution, and color mode controls.
* **Pattern Generator panel**

  * Tools to create preset or custom source patterns.
* **Edit Points panel**

  * Add, move, or delete individual wave sources.
* **Floating toggle buttons**

  * Grid and Points visibility controls with active/inactive color states, always visible above the Clear and Sync buttons.
* **Responsive UI**

  * Panels and floating controls adapt to desktop and mobile layouts.

## Usage

1. Open `index.html` in a modern browser.
2. Use floating buttons to show or hide the grid or source points.
3. Navigate through the three panels to:

   * Adjust medium parameters and enable Realistic Physics.
   * Generate wave patterns.
   * Edit source points manually.
4. Clear or sync the simulation at any time using the floating utility buttons.

## Technical Notes

* Wave computation is handled in `WaveEngine`, which calculates pixel values using either exponential or geometric decay.
* UI state is managed by `UIController`, which updates engine parameters and handles floating button states.
* No external dependencies; runs entirely client-side.

## Browser Support

Tested on recent versions of Chrome, Firefox, Edge, and Safari.

## License

MIT License – see [LICENSE](LICENSE) for details.

## Contributing

Fork the repository and submit pull requests with clear descriptions of changes.
