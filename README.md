# Waste Collection CVRP Optimization

This project focuses on optimizing municipal waste collection routes in Langkawi, Malaysia,
using the Capacitated Vehicle Routing Problem (CVRP).

Heuristic and metaheuristic approaches are applied to improve routing efficiency and reduce
total travel distance and operational time.

## Project Overview

Waste collection in Langkawi faces challenges due to increasing waste volume from tourism
and inefficient fixed routing schedules.

This project models the waste collection process as a CVRP and applies optimization techniques
to generate more efficient vehicle routes while considering real-world constraints such as
vehicle capacity and service locations.

## Methods Used

- Capacitated Vehicle Routing Problem (CVRP)
- Heuristic and metaheuristic routing approaches
- Google OR-Tools for route optimization
- Geographic distance modeling
- Route visualization using Folium

## Files Description

- `cvrp_solution.py`  
  Main Python script that formulates and solves the CVRP using optimization techniques.

- `distance_matrix.py`  
  Generates the distance matrix between all waste collection locations based on geographic coordinates.

- `location_coordinates.py`  
  Contains the coordinates of the depot, landfill, and waste collection points in Langkawi.

- `dataset_waste_collection_langkawi.xlsx`  
  Dataset containing waste collection locations and related operational data.

- `route_visualization.html`  
  Interactive map visualizing the optimized waste collection routes.

## Results

The optimized routing solution demonstrates reduced total travel distance and improved
route efficiency compared to non-optimized collection routes.

## Notes

This project was developed as part of academic coursework and final year research,
using real-world inspired data for waste collection routing in Langkawi.
