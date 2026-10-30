# Ship or Skip

A small swipe game: is there a ship inside the ring in 10 m Sentinel-2 imagery of the open sea?

Tap a card to flip between the pass and the usual view of the same spot (other passes with no ship nearby), or press
Blink. Swipe right for vessel, left for no vessel, up for can't tell. After each answer the page shows what is known
about that spot: a ship AIS reported under way, empty water, or a spot where a ship detector fired although AIS showed
nothing within 300 m.

Play it at https://saulpingerman.github.io/ship-or-skip/

The page is one self-contained HTML file. Answers stay in your browser.

Contains modified Copernicus Sentinel data (2021 to 2024). Vessel positions from AIS (Danish Maritime Authority).
Touch gestures by Hammer.js (MIT licence, included in the page).
