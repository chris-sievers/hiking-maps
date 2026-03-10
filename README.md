# US Hiking List Map

Single-file interactive map of 35 hikes across the US, built with Leaflet.js on dark CARTO tiles.

**Live:** https://chris-sievers.github.io/hiking-maps/

## What it does

- Side panel with ranked hike cards (name, stats, difficulty, description, Google Maps link)
- Selecting a hike (card or map marker) opens travel info and animates routes from 3 origin cities: Tucson AZ, Cincinnati OH, Philadelphia PA
- Travel recommends driving (<8h) or flying with airport/flight details
- Ranking prioritizes hikes drivable by the most origins, then shortest avg travel time
- Responsive: on mobile, panel becomes a bottom drawer with minimize/restore

## Tech

- Single `index.html`, no build step, no server
- Leaflet.js + CARTO dark tiles via CDN
- Fonts: Playfair Display + DM Sans via Google Fonts
- Hosted on GitHub Pages (legacy mode, deploys on push to master)

## Updating

Edit `index.html`, then:
```bash
git add index.html && git commit -m "description" && git push
```
Site updates in ~30 seconds.
