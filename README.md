# Campground-Suitability - Knuckles
## Spatial Suitability Analysis for Sustainable Camping Sites in Knuckles, Sri Lanka

## Overview
This study integrates Geographic Information Systems (GIS) with Multi-Criteria Decision Analysis (MCDA) to determine optimal locations for sustainable campsite development in the Knuckles Conservation Forest, Sri Lanka. 

<img width="3507" height="4960" alt="Final Camping sites Suitability Map" src="https://github.com/user-attachments/assets/6eab7205-75a6-4125-b826-f24f190200d4" />

Using an **Analytic Hierarchy Process (AHP)**, eight spatial variables were evaluated across Natural Environment, Landscape, Infrastructure, and Safety criteria.

## Key Findings
- **Suitable Zones (Class 1):** 225.54 km² (44.37%)
- **Moderately Suitable (Class 2):** 250.16 km² (49.22%)
- **Unsuitable (Class 3):** 32.58 km² (6.41%)
- **Safety Dominance:** Safety factors (Landslide & Flood Risk) accounted for **49.9%** of the composite model weight.

## Methodology & Variables
- **Techniques Used:** Multi-Ring Buffering, Raster Reclassification, Vector Attribute Scoring, Sequential Vector Union.
- **Tools:** QGIS, QuickOSM, SRTM DEM (30m).
- **Coordinate Reference System:** EPSG:5234 (Kandawala / Sri Lanka Grid).

| Variable | Group | AHP Weight | Priority Rank |
| :--- | :--- | :--- | :--- |
| Geological Disaster Risk | Safety Condition | 30.5% | Rank 1 |
| Flood Risk | Safety Condition | 19.4% | Rank 2 |
| Distance to Scenic Spots | Landscape Condition | 16.5% | Rank 3 |
| Slope | Natural Environment | 11.8% | Rank 4 |
| Distance to Waterways | Natural Environment | 6.3% | Rank 5 |
| Telecommunication | Infrastructure | 5.5% | Rank 6 |
| Canopy Density | Natural Environment | 5.2% | Rank 7 |
| Roads | Infrastructure | 4.8% | Rank 8 |

## Project Report
The complete detailed report is available in the [`docs/`](./docs/) directory.
