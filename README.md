# Crop-Monitoring-using-Satellite-Imagery
This project harnesses satellite imagery and machine learning to monitor crop health, growth stages, and vegetation density, providing crucial insights for precision agriculture. 
Project Overview
This project harnesses satellite imagery and machine learning to monitor crop health, growth stages, and vegetation density, providing crucial insights for precision agriculture. By analyzing multispectral data from Landsat and Sentinel-2 satellites, specifically using bands like Red, NIR (Near-Infrared), Green, and SWIR (Short-Wave Infrared), the project aims to assess crop health and growth conditions over time. These insights allow farmers to optimize their resource usage, respond proactively to crop stress, and support accurate yield forecasts.

Objectives
Assess Crop Health: Calculate vegetation indices such as NDVI (Normalized Difference Vegetation Index), GNDVI (Green NDVI), NDMI (Normalized Difference Moisture Index), and SAVI (Soil-Adjusted Vegetation Index) to quantify crop vigor, detect health issues, and monitor vegetation density.
Monitor Growth Stages: Track phenological stages (growth stages) to understand crop progress and identify critical periods for optimal intervention.
Time Series Analysis: Analyze changes in vegetation indices over time to identify seasonal trends, patterns, and anomalies that impact crop health.
Methodology
Data Collection: Retrieve multispectral images from Landsat and Sentinel-2 for the designated agricultural regions.
Preprocessing: Align and clean images, handle any missing values, and resample bands as needed for pixel-level accuracy across time-series data.
Index Calculation: Compute NDVI, GNDVI, NDMI, and SAVI values using bands relevant to vegetation health, moisture levels, and soil-vegetation interaction.
Classification & Analysis: Train a Random Forest classifier to categorize crop health levels into different density classes based on NDVI and other indices, allowing for robust crop health monitoring and growth analysis. Perform time series analysis to observe changes over time and track crop phenology.
Visualization: Create a dynamic dashboard to visualize crop health trends, growth stages, and index variations over the season.


OUTPUTS 

![image](https://github.com/user-attachments/assets/38fb6ccb-21f1-4096-8bf0-34f484bc5635)
![image](https://github.com/user-attachments/assets/328e3b2c-08ea-4696-a758-192aa4b45576)
![image](https://github.com/user-attachments/assets/194e6f5a-459d-4101-bec1-dd85a010c377)
![image](https://github.com/user-attachments/assets/00f98ea5-cff4-418e-a422-de21d5cdd124)
