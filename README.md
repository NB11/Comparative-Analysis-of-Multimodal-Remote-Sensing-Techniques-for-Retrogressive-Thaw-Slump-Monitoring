# Comparative Analysis of Multimodal Remote Sensing Techniques for Retrogressive Thaw Slump Monitoring

This repository contains Jupyter Notebooks used to process and analyze data from optical and Digital Elevation Model (DEM) remote sensing techniques for monitoring retrogressive thaw slumps. The code prepares the data so that the GeoJSON files from different monitoring methods can be compared more easily by calculating shape-specific metrics and appending them to the shapes found in the GeoJSON files.

## Overview

The following workflow chart illustrates the steps involved in the data processing and the specific Jupyter Notebooks used at each step. Each notebook includes a short description of its purpose and functionality.

![Retrogressive Thaw Slump Workflow](Workflow_Chart.png)

## Repository Structure

- `notebooks/`: Contains the Jupyter Notebooks for data preparation and analysis.
- `data/`: Includes the input data files (e.g., optical images, DEMs).
- `output/`: Stores the processed GeoJSON files and other output data.
- `images/`: Contains images used in the documentation (e.g., workflow charts).

## Notebooks

1. **01_data_preparation.ipynb**: Prepares raw optical and DEM data for analysis.
2. **02_shape_metrics_calculation.ipynb**: Calculates shape-specific metrics for the GeoJSON files.
3. **03_comparative_analysis.ipynb**: Compares the monitoring methods based on the calculated metrics.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook

## Required Python Packages

- numpy
- pandas
- geopandas
- shapely
- rasterio
- matplotlib
- seaborn
- basemap
- scipy
- gdal


