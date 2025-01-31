# Leaflet Earthquake Visualization

## Overview
This project uses **Leaflet.js** to visualize earthquake data from the **USGS GeoJSON API**. The goal is to create an interactive map that plots earthquake locations, with markers sized by magnitude and colored by depth.

## Steps
1. **Load and Process Earthquake Data**
   - Fetch real-time earthquake data from the **USGS GeoJSON API**.
   - Extract latitude, longitude, magnitude, and depth.

2. **Create an Interactive Map**
   - Use **Leaflet.js** to generate the base map.
   - Plot earthquake locations with markers.
   - Adjust marker **size based on magnitude** and **color based on depth**.
   - Add **popups** displaying earthquake details (magnitude, location, depth).

3. **Add a Legend**
   - Display a legend explaining the **depth-based color scale**.

## Features
- **Dynamic markers** that scale based on earthquake magnitude.
- **Color-coded depth levels** for easy interpretation.
- **Interactive popups** showing earthquake details.
- **Legend** explaining marker colors.

## Files
- `index.html` - Main HTML file for the Leaflet map.
- `logic.js` - JavaScript code for fetching data and generating the map.
- `style.css` - Optional CSS styling.
- `README.md` - Project documentation.

## Tools Used
- **Leaflet.js** (Map rendering)
- **D3.js** (Fetching and processing GeoJSON data)
- **JavaScript** (Map interaction)
- **HTML & CSS** (Frontend structure)

## Submission
- All files are uploaded to the **leaflet-challenge** GitHub repository.
