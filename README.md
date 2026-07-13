# Travel Planner

Data-driven trip dashboards. Each trip is a `trip.json` injected into a shared HTML template at build time, so the published dashboard is a single self-contained file.

## Lofoten Roadtrip 2026

Tromso to Lofoten camper loop, 1-14 Aug 2026. ~1,400 km, 13 nights, 9 summit hikes.

- `index.html` - the dashboard. Self-contained: the trip data is embedded, nothing is fetched at runtime. Open it locally or view it on GitHub Pages.
- `trip.json` - the source data behind the dashboard.

### Live

Settings > Pages > deploy from `main` / root serves the dashboard at https://gillesrobijns.github.io/travel-planner/
