# O Stree, Kal Aana! · Chanderi Samachar

A scroll-driven town-alert portal for the fictional town of Chanderi, built for the **Stree's Curse** challenge with **The Evidence Wall** hex.

**Live site:** https://compiledbyutkarsh.github.io/stree-kal-aana/

## The idea

Chanderi's residents are struggling to keep track of mysterious disappearances and supernatural sightings. This site works as their town newspaper and alert portal: incident reports, location pins, warnings and a timeline of events, all wrapped around one main feature, the Evidence Wall.

## Features

- **Opening door:** a wooden door swings open as you scroll and reveals a veiled figure in red.
- **Evidence Wall (main feature):** torn-paper clues pinned to a painted wall with red string. Drag any clue and the strings follow. "Decode the wall" reveals the twist.
- **Incident map:** a hand-drawn map of Chanderi with pulsing pins, filterable by disappearance, sighting or warning.
- **Dusk-to-midnight scene:** a pinned scroll scene where the sun sets, the moon and stars rise, windows light up and a clock runs from 18:30 to 23:47.
- **Seven clippings:** a horizontal scroll gallery of newspaper reports that leans with your scroll speed.
- **Missing posters:** four missing-person posters with tear-off strips and a stamp animation.
- **Six rules of the night:** cards that stack as you scroll.
- **Mark your door:** type your house name and watch the protective phrase paint itself onto a door plate.
- **Night walk:** a torch that reveals hidden writing on dark walls.
- **Timeline, witness statements, scroll-filled manifesto, counters and a stitched progress bar.**

## Tech

Pure HTML, CSS and vanilla JavaScript in a single `index.html` file. There are no frameworks, no build step and no image files. All artwork is inline SVG and CSS. Fonts (Alfa Slab One, Hind, Kalam, Special Elite) load from Google Fonts.

## Run locally

Open `index.html` in any modern browser, or serve the folder:

    python3 -m http.server 8000

Then visit http://localhost:8000.

## Accessibility

Keyboard focus is visible on all interactive elements, map pins can be opened with the Enter key, and `prefers-reduced-motion` turns off animations.

## Credits

Designed and developed by **Kannupriya Malik**.
