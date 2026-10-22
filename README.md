# Parker & Pine

A standalone HTML, CSS, and JavaScript bookshelf with the ten-page interactive story **Johnny Builds to Mars**. All story art is inline SVG; no libraries, frameworks, or build step are needed.

The site files are at the repository root so GitHub Pages can serve `index.html` directly. GitHub Actions deploys the site whenever a commit reaches `main`.

To preview locally, run:

```sh
python3 -m http.server 4173
```

Then open http://localhost:4173.

## Story activities

1. Draw Johnny’s rocket idea in the night sky.
2. Drag household supplies into Johnny’s basket.
3. Fit rocket parts together while Pickles judges.
4. Pull the launch handle.
5. Guide the rocket toward the Moon.
6. Tap the planets and comet to find Johnny’s space neighbors.
7. Tap three meteors to send them fizzing out of the way.
8. Steer around the Moon.
9. Tap the bright landing spot to guide Johnny safely to Mars.
10. Swipe the lunchbox open and discover the missing snacks.

Each page reveals the story one word at a time. Children read each short part and complete its activity before moving ahead. Activities include drawing, dragging, tapping, pulling, steering, and swiping. Reduced-motion preferences are respected.
