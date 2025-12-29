# Waste Collection Route Optimization using CVRP

This project focuses on optimizing municipal waste collection routes in Langkawi, Malaysia, using **Capacitated Vehicle Routing Problem (CVRP)** techniques.

The study applies heuristic and metaheuristic algorithms to reduce travel distance, operational time, and improve route balance.

## Project Background
Waste collection in Langkawi faces challenges due to:
- Increasing waste volume from tourism
- Fixed and inefficient routing plans
- High operational and fuel costs

This project models the waste collection problem as a CVRP and proposes optimized routing solutions.

## Methods Used
- **Path Cheapest Arc (PCA)** heuristic to generate initial routes
- **Path Cheapest Arc with Guided Local Search (PCA-GLS)** for route improvement
- **Google OR-Tools** for VRP modeling and optimization

## Data
- Real-world waste collection locations in Langkawi
- Depot and landfill coordinates
- Vehicle capacity, service time, and operational constraints
- Distance matrix generated from geographic coordinates

## My Contribution
This project was completed as part of my final year research.  
My responsibilities included:
- Formulating the CVRP model
- Implementing PCA and PCA-GLS algorithms using Python
- Generating distance matrices and route solutions
- Visualizing optimized routes using Folium
- Evaluating and comparing heuristic performance

## Key Results
- PCA-GLS reduced total travel distance by **13.25%**
- Operational time reduced by **3.89%**
- Improved workload balance across vehicles

## Tools & Technologies
- Python
- Google OR-Tools
- Folium (route visualization)
- Pandas
- Excel (data preparation)

## Files
- `solution.py` – CVRP solution using OR-Tools
- `distance.py` – Distance matrix generation
- `coordinate_map.py` – Location mapping
- `final_solution_map.html` – Route visualization
- `Dataset Waste Collection Langkawi.xlsx` – Dataset
- `fyp report heuristic.pdf` – Full research report

## Notes
This project is based on real-world data and developed for academic research purposes.
