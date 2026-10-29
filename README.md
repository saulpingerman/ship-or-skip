# Ship or Skip

A small swipe game: is there a ship at this harbour berth in 10 m Sentinel-2 imagery?

Each card blinks one satellite pass against a pass when AIS reported a ship at the same berth. Swipe right for vessel,
left for no vessel, up for can't tell. After each answer the page shows what is known about that berth: a ship AIS
reported, an empty berth, or a spot where a ship detector fired although AIS showed nothing.

Play it at https://saulpingerman.github.io/ship-or-skip/

The page is one self-contained HTML file. Answers stay in your browser.

Contains modified Copernicus Sentinel data (2021 to 2024). Vessel positions from AIS (Danish Maritime Authority).
Touch gestures by Hammer.js (MIT licence, included in the page).
