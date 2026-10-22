# Parker & Pine

A standalone HTML, CSS, and JavaScript bookshelf with the ten-page interactive story **Johnny Builds to Mars**. No libraries, frameworks, packages, or build step are required. All artwork is inline SVG. Read-aloud uses the device's built-in speech synthesis when available.

Serve `dist/` using any static HTTP server, for example:

```sh
python3 -m http.server 4173 --directory dist
```

Open http://localhost:4173.

## Story activities

1. Draw Johnny’s rocket idea in the night sky.
2. Drag household supplies into Johnny’s basket.
3. Fit rocket parts together while Pickles judges.
4. Pull the launch handle.
5. Guide the rocket toward the Moon.
6. Fly through a sky full of planets, stars, and a comet.
7. Clear three meteors from the flight path.
8. Steer around the Moon.
9. Guide Johnny to a safe Mars landing spot.
10. Open the lunchbox on Mars and discover the missing snacks.

Each page reveals its story a word at a time. Children tap to move between short lines, and can advance only after reading the page and finishing its hands-on activity. Page dots and navigation unlock one page at a time. The activities use drawing, touch dragging, pulling, and swiping. Each page has a distinct space scene, and the Mars landing has a starry sky, comet, distant planets, and red hills. Replay restarts the story. Reduced-motion preferences are respected.
