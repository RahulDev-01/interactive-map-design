# Interactive Map 

## Overview

This project is a responsive web application displaying an interactive map with multiple city markers. It allows users to toggle between the standard OpenStreetMap view and a satellite imagery layer using a custom button. The satellite icon is fetched dynamically from an external API. The design works across desktops and mobile devices.

## Features

- **Interactive Map** rendered with Leaflet.js
- **Markers** for Delhi, Mumbai, Kolkata, Bengaluru, and New York, each with info popups
- **Zoom Controls** on the top left
- **Satellite View Toggle Button** positioned directly below the zoom controls
  - Button icon is fetched dynamically from an API
  - Switches map between OpenStreetMap and ESRI World Imagery
- **Responsive Design** for smooth usability on all screen sizes
- **Custom Marker Styles** for visual appeal

## Installation

1. **Clone or Download the Repository**


2. **Add Project Files**

- Place the HTML file from this project into your directory.
- (Optional) Add a `favicon.png` or `favicon.ico` to your directory.

3. **No Build Tools Needed**

- Everything runs client-side, no server or build step is required.

## Usage

Open `index.html` in your browser. The map will:

- Center on Delhi by default (India).
- Display custom markers for Delhi, Mumbai, Kolkata, Bengaluru, and New York.
- Let you zoom and pan the map.
- Let you toggle between street map and satellite imagery via a button just under the zoom controls.

## Project Structure

| File            | Purpose                                              |
|-----------------|------------------------------------------------------|
| `index.html`    | Main web page with map and all JavaScript/CSS        |
| `favicon.png`   | Favicon for browser tab (optional, recommended)      |

## Code Structure

- **HTML**: Sets up the map container, headings, and meta tags.
- **CSS**: Handles responsive sizing, marker appearance, control button styling, and layout.
- **JavaScript**:
- Initializes the Leaflet map.
- Adds OpenStreetMap and ESRI satellite tile layers.
- Places markers with informative popups.
- Creates a custom Leaflet control for toggling satellite imagery, with the button fetching its icon from a remote API.
- Manages toggling logic between layers and syncs the button’s function.

## Customization

- **Markers**: Add or modify markers as needed by editing the relevant script section.
- **Default Center/Zoom**: Change the coordinates in the initialization to shift the map focus.
- **Satellite Icon**: Update the API URL for the satellite icon to use different imagery or style.
- **Map Layers**: Swap in different tile servers or attribution if you want alternate map styles.

## Credits

- **Leaflet.js** – Mapping framework
- **OpenStreetMap** – Default map tiles
- **ESRI World Imagery** – Satellite tiles
- **Icon source (Flaticon or similar)** – For the dynamically fetched satellite toggle icon

## Notes

- Respect all third-party tile and icon provider usage policies.
- Attribution for map tiles is handled in the map interface per license requirements.
- For production, consider hosting the icon asset locally to reduce reliance on external fetches.

## Screenshots

Include screenshots of your map for quick reference (not included in this README text, but recommended in your repository).

## License

Specify your project’s license here (MIT, Apache, etc.) if sharing publicly.

## Contact

For issues or feature suggestions, please submit them through your repository’s issue tracker or contact the project maintainer.

Enjoy your interactive map with dynamic satellite toggle!
