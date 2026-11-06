# Floor plan walkthrough

An interactive Three.js reconstruction of a floor plan, with a five-foot bathroom extension and an interior kitchen-to-side-room doorway. The bathroom has a centered 1.8 m wide by 1.05 m deep, dark-tiled walk-in shower with glass sliding doors, a wall-mounted shower head, and a ceiling-mounted rain head. Sliding doors are shown parked open for walkthrough access; the roof is omitted but the ceiling-head mount remains visible.

**[Open the public walkthrough](https://reztierk.github.io/floor-plan-walkthrough/)**

## Controls

- **Desktop:** WASD or arrow keys to move, Shift to move faster, click the scene for mouse look or drag to look, and Escape to release the mouse.
- **Mobile:** hold the movement buttons and drag the scene to look around.
- **Overview:** drag to orbit; scroll or pinch to zoom.
- **Top down:** scroll or pinch to zoom.
- Use **Reset** to restore the current view and **Furniture** to toggle furnishings.

## Running locally

Open [index.html](./index.html) in a modern browser with WebGL 2 enabled. An internet connection is required to load the pinned Three.js library from jsDelivr. No build step is needed.

Dimensions and furnishings are approximate. The laundry entrance is inferred, and doors are shown open to permit navigation. This is a visualization, not a construction drawing.

## Publishing

GitHub Pages serves `index.html` from the root of the `main` branch. Updates pushed to that branch are published automatically.
