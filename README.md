# EV Charging Feasibility Assessment — Rubochi, Nigeria

## Overview

This project uses GIS and Python to assess potential electric-motorcycle charging locations in Rubochi, Federal Capital Territory (FCT), Nigeria, considering existing utility-grid and solar mini-grid infrastructure.

The analysis integrates road accessibility, settlement distribution, population estimates, demand hubs, and electricity-infrastructure proximity to support preliminary charging-location planning.

## Data Used

| Dataset | Source | Purpose |
|---|---|---|
| Road network | OpenStreetMap (OSM) | Road connectivity and network-distance analysis |
| Settlement extents | GRID3 Nigeria | Settlement distribution and spatial screening |
| Buildings and population proxies | OpenStreetMap / GRID3 | Estimating population distribution and coverage |
| Community destinations | OpenStreetMap | Identifying markets, facilities, and potential demand hubs |
| Mini-grid information | REA / Nigeria SE4All | Infrastructure proximity and site assessment |
| EV energy assumptions | Scenario-based estimates | Estimating preliminary fleet charging demand |

## Key Analyses

- GIS suitability screening of 71 candidate charging locations.
- Spatial Suitability Index based on roads, destinations, and mini-grid accessibility.
- Population coverage assessment using a 1.5 km road-network catchment.
- Preliminary charging-station selection using a greedy algorithm.
- Illustrative electricity-demand scenarios for electric motorcycles.

## Tools

Python · Jupyter Notebook · GeoPandas · OSMnx · NetworkX · Pandas · Matplotlib

## Project Status

**Ongoing preliminary feasibility assessment.** Charging locations, electricity availability, and fleet requirements require further field and technical verification.

## Author

**Toussaint Dukundimana**  
Carnegie Mellon University Africa
