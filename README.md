# INOWYA-Vx.1.0
🌍INOWYA Vx.1.0 – Google Location History Visualizer

A beautiful, fast, offline-first web app for exploring your Google Takeout Location History (and other similar JSON exports).

## Features

- Full offline – works with dropped JSON/ZIP files (including full Takeout exports)
- Interactive Leaflet map with heatmaps, paths, raw pings, and stop detection
- Smart date range picker (only shows days that actually have data)
- Animation playback with variable speed (frame-by-frame to 200×)
- Speed chart (km/h over time)
- Activity breakdown pie chart
- Yearly activity heatmap calendar
- Top locations ranking with reverse-geocoded addresses (cached)
- Stop enrichment using OpenStreetMap Nominatim
- Export visible track as GPX
- Save/Load project (`.inowya` backup)
- Dark mode, fully responsive floating panel with tabs


## How to Use (30 seconds)

1. **Get your Google Location History**
   - Go to → https://takeout.google.com
   - Deselect all → only turn on **Location History (JSON)**
   - Click “Next step” → “Create export”
   - Wait a few minutes → download the ZIP

2. **Open INOWYA**
   - Instant (no install)
   - Or download this repo and open `index.html` locally

3. **Drop your file**
   - Drag & drop **any** of these onto the page:
     - The whole Takeout ZIP
     - Just the `Records.json` inside
     - A previous `.inowya` backup file

Done! The map loads instantly, everything stays 100% private in your browser.

### Quick Tips
- Use the calendar heatmap to jump to any day
- Click the play button at the bottom to animate your movements
- “Enrich Visible Stops” → turns coordinates into real addresses (cached forever)
- Export button → GPX (for Strava, Garmin, etc.)
- Save button → creates a tiny `.inowya` backup you can reload later

That’s it — no upload, no account, no tracking.
