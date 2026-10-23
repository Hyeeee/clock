# Drum World Clock

A minimal 3D world clock built with p5.js.

Hours, minutes and seconds sit on stacked rings that turn so the current time always lines up at the front. Switch between cities, see each city's time difference from New York (Eastern Time), and flip between a rotating **DRUM** view and a flat **DIAL** view, in dark or light mode. On first load it can use your location to show your own city.

**Live:** https://hyeeee.github.io/clock/

## Controls
- Drag to rotate · scroll to zoom
- Double-click (or the DRUM / DIAL buttons) to switch view
- Click a city at the bottom, or press 1–9
- Keys: `V` view · `L` light / dark

## Files
- `index.html` — loads p5.js and the sketch
- `sketch.js` — the clock (the `Ring` class draws each ring; nested loops draw the rings, the dot grid and the city grid)
