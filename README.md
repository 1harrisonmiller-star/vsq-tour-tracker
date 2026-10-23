# VSQ Tour Tracker

Live tour tracker for Vitamin String Quartet with Girl Named Tom: The Crazy Ordinary World Tour, Fall 2026.

Open `index.html` in any browser, or turn on GitHub Pages (Settings > Pages > Deploy from a branch > `main` > `/ (root)`) and share the link GitHub gives you.

## What's in it

- Route map with real state lines, zoom and pan, a hover popup for every stop, and a bus that moves with the calendar (it sits in Los Angeles until the tour starts)
- Full itinerary showing Girl Named Tom dates, VSQ solo dates, VIP soundcheck dates and venue photos
- Quartet player: four synthesized parts on one loop, with mute and solo for each
- The four instruments, the four touring players, a tour gallery, merch, and a fan chat

## Updating it

Everything lives in `index.html`. Show dates, venues and tags are the `shows` list near the top of the script. Merch is the `MERCH` list. Player headshots, fan photos and real audio stems go in the `ASSETS` block.

## Notes

- Photos are linked from VSQ's store and from each venue's own site, not stored in this repo. If a site changes or blocks the link, that photo falls back to a placeholder.
- Quartet audio is synthesized in the browser with the Web Audio API. It is not a recording.
- The fan chat is not saved. Posts reset when the page reloads.
- Map: US Census state boundaries via us-atlas, drawn with d3.
