# Front End Engineering Challenge

Design and build a small web application to present USGS earthquake data on a map in the browser.

## Requirements

- Frontend logic must be handled using React.
- Use separate CSS file(s).
- Include a selector to view all earthquakes in the data set or filter by a specific country.
- Clicking on an earthquake data point on the map should surface the magnitude, title, and timestamp of the earthquake in a legend and popup marker on the map.

## Resources

- Turf js and Mapbox GL are pre-installed for your use. Any of the geospatial functionality of the libraries can be utilized. You are not restricted to using mapbox or turf and are allowed to include additional libraries as you see fit.
- The data directory of this repo contains 2 files. `countries.geojson` includes the geographic boundaries of the countries of the world. `earthquakes.geojson` contains location and metadata for all of the earthquakes detected by USGS in the past 7 days (at time of this writing).
- If you choose to work with Mapbox, an api access token will be provided to you but other map provider usage will require you to generate your own api tokens.
- All packages included with create-react-app are preinstalled. Run the start script from the root of this repository to begin.

## Bonuses

- Automatically zoom to the boundary of a country when it is selected.
- Add a datepicker component to filter earthquakes by a specific date range.
