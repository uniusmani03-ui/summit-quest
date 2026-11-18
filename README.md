# Summit Quest: Gamified Trekking Web App

> **Personal project**: built in my own time
> **Dates:** June 2026
> **Author:** Unais Usmani

This is a single-page web app that turns hiking into a game. It has a live GPS map, real trails and an XP/badge system.

- **Live GPS tracking** on a topographic map (Leaflet + OpenTopoMap). It measures distance with the haversine formula and filters out GPS noise.
- **World Atlas.** 18 curated famous trails across six continents, colour-coded by difficulty.
- **Near Me.** Searches any place (Nominatim geocoding) and pulls real local walking routes from OpenStreetMap through the Overpass API, within 8, 15 or 30 km. It parses multi-segment route geometry and works out distance and difficulty automatically.
- **Gamification.** 10 XP levels, 18 badges (continents, distance milestones, streaks), daily streaks and a trophy cabinet. Progress is saved in browser storage.
- **Directions to the trailhead** through Google Maps.

**Stack:** HTML/CSS/JavaScript, Leaflet, the OpenStreetMap Overpass and Nominatim APIs, and the Geolocation API.

## Run

Open `index.html` in a browser. To use live GPS, serve it over HTTPS or from localhost, for example `python -m http.server`.
