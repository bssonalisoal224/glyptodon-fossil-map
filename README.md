# Glyptodon Fossil Map

An interactive web-based map visualizing the geographic distribution of Glyptodon fossil sites across the Americas, with a focus on sites where fossil evidence co-occurs with potential evidence of human activity (tools, butchery marks, etc.).

## Purpose

This project serves as a shareable visual tool for geologists, paleontologists, and students to better understand the spatial patterns of Glyptodon fossils during the Pleistocene epoch. By highlighting sites with possible human interaction, it aims to foster discussion about early human-megafauna relationships in the Americas.

## Data

The primary dataset (`glyptodon_sites.csv`) includes:
- **SiteID**: Unique identifier for each fossil location
- **Latitude** & **Longitude**: Geographic coordinates
- **Species**: Identified Glyptodon species (e.g., *Glyptodon clavipes*)
- **Age_MYA**: Estimated age in millions of years ago
- **HumanEvidence**: Boolean (`true`/`false`) indicating whether human artifacts or evidence of interaction have been found at the site

## Features

1. **Interactive Map**: Loads the CSV data and places a marker for each fossil site.
2. **Marker Differentiation**: Sites with `HumanEvidence = true` are displayed with distinct color/shape markers.
3. **Pop-up Details**: Clicking a marker shows a pop-up with the SiteID, Species, and Age_MYA.

## Technology

Built with HTML, CSS, and JavaScript using the [Leaflet.js](https://leafletjs.com/) library for mapping.

## How to Use

1. Clone the repository.
2. Open `index.html` in a modern web browser.
3. The map will automatically load the fossil site data from `glyptodon_sites.csv` and display interactive markers.

## License

This project is released under the MIT License.