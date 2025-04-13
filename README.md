# Leaflet Earthquake Visualization

Built an interactive map using Leaflet.js to visualize all earthquakes worldwide from the past 7 days, using real-time data from the USGS Earthquake GeoJSON Feed. Mapped over 1,000 earthquakes with marker size representing magnitude and color indicating depth.

## Tools & Technologies Used

- JavaScript
- Leaflet.js
- d3.js
- GeoJSON API (USGS)
- HTML/CSS

## File Structure

```text
Leaflet-Part-1/
├── index.html                  # Base HTML for map
├── static/
│   ├── js/logic.js             # Core mapping logic with marker styling
│   └── css/style.css           # Custom map styling

Images/
├── [PNG, GIF] project screenshots and visual references
```

## Skills Demonstrated

- Mapping geospatial data using Leaflet.js and GeoJSON
- Dynamic visual encoding of multiple data attributes
- Consuming and visualizing API data in JavaScript
- Building a live-updating, user-friendly dashboard

## Key Findings

- Visualized over 1,000 earthquakes recorded globally in one week.
- Earthquake magnitudes ranged from 0.5 to 7.6+ and were dynamically sized on the map.
- Depths were categorized and color-coded into 6 bands ranging from less than 10 km to over 90 km deep.
- Implemented a legend to improve interpretability of visual encodings.
