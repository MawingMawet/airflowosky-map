# AirflowOSky - Bangkok airspace heatmap

A static, client-side heatmap of aircraft position density over Bangkok,
built from live OpenSky Network data by the AirflowOSky data-engineering
project. Pick a UTC hour range in the panel to filter the map; the two
markers are Suvarnabhumi (VTBS) and Don Mueang (VTBD).

Live site: https://mawingmawet.github.io/airflowosky-map/

- Data: OpenSky Network (non-commercial use, attributed on the page)
- Cells: 2-decimal lat/lon (about 1.1 km), aggregated per UTC hour
- Hours are UTC; Bangkok local time is UTC+7

These are generated artifacts. The pipeline, decisions, and documentation
live in the AirflowOSky repository.
