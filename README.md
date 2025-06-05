# Geo Risk Map

This repository contains a simple interactive world map highlighting geo-risk classifications.

Open `index.html` in a web browser. The map colors countries according to:

- **Low risk** – grey
- **Offshore** – yellow
- **FATF grey list** – orange
- **High risk** – red
- **Blocked** – black

Hover over a country to view its flag, classification and reasoning.

The map relies on D3 and TopoJSON libraries via CDN, so an Internet connection is required when viewing the page.
