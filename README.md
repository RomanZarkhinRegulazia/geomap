# Geo Risk Map

This repository contains an interactive world map highlighting geo-risk classifications.

Open `index.html` in a web browser. The page loads OpenLayers with OpenStreetMap tiles and colors countries according to:

- **Low risk** – grey
- **Offshore** – yellow
- **FATF grey list** – orange
- **High risk** – red
- **Blocked** – black

Hover over a country to view its flag, classification and reasoning. The map uses client-side OpenLayers, D3 and TopoJSON from CDNs, so an Internet connection is required when viewing the page.
