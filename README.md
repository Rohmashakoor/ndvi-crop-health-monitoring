# NDVI Crop Health Monitoring Using Sentinel-2 and Google Earth Engine

## Project Overview

This project demonstrates a satellite-based crop health monitoring workflow using Sentinel-2 imagery and Google Earth Engine (GEE). Monthly NDVI maps are generated to assess vegetation condition and monitor changes in crop health over time.

The workflow is designed for agricultural monitoring applications and can support farmers, agricultural consultants, researchers, and environmental organizations.

## Objectives

* Calculate monthly NDVI from Sentinel-2 imagery
* Monitor vegetation health trends throughout the growing season
* Generate time-series statistics for crop monitoring
* Produce professional maps and reports for decision-making

## Study Area

The analysis was conducted over an agricultural region using a user-defined Area of Interest (AOI).

## Data Source

* Sentinel-2 Surface Reflectance
* Spatial Resolution: 10 meters
* Source: Copernicus Programme
* Platform: Google Earth Engine

## Methodology

1. Define Area of Interest (AOI)
2. Filter Sentinel-2 imagery by date and cloud cover
3. Apply cloud masking
4. Calculate NDVI
5. Create monthly NDVI composites
6. Extract monthly mean NDVI values
7. Generate maps and time-series charts
8. Export results for reporting

## NDVI Formula

NDVI = (NIR - Red) / (NIR + Red)

Where:

* NIR = Sentinel-2 Band 8
* Red = Sentinel-2 Band 4

## Results

The generated NDVI maps reveal spatial and temporal variations in vegetation health. Higher NDVI values indicate healthy and dense vegetation, while lower values may indicate sparse vegetation, bare soil, or crop stress.

## Repository Structure

scripts/

* Google Earth Engine JavaScript workflow

outputs/

* Monthly NDVI maps
* Time-series plots

report/

* Final PDF report

## Applications

* Crop health monitoring
* Agricultural management
* Drought assessment
* Environmental monitoring
* Precision agriculture

## Tools Used

* Google Earth Engine
* Sentinel-2 Imagery
* QGIS
* Python
* GitHub

## Author

Rohma Shakoor

BS Space Science | GIS & Remote Sensing | WebGIS Developer
