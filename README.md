# han-river-water-quality

Exploratory data analysis on water quality measurements from the Han River (South Korea).

## Overview

- Load and clean raw CSV data  
- Remove unused columns and handle missing values  
- Compute summary statistics (mean, median, variance, std)  
- Visualize relationships between environmental variables  

## Data

Features used:

- Salinity (ppt)  
- pH (standard units)  
- Water depth (m)  
- Water temperature (°C)  
- Air temperature (°F → converted to °C)  

Preprocessing:

- Dropped irrelevant metadata columns  
- Removed rows with missing values  
- Subset to a fixed range for consistent plotting  

## Analysis

- Summary statistics for salinity and pH  
- Time-indexed plots:
  - Water temperature vs water depth  
  - Salinity vs water depth  
- Scatter plots:
  - Salinity vs pH  
  - Water temperature vs air temperature  

## Implementation

- pandas for data cleaning and aggregation  
- matplotlib for visualization  
- Manual unit conversion (F → C) for consistency  

## Stack

- Python  
- pandas  
- matplotlib  

## Notes

- Simple EDA, no modeling  
- Uses synthetic index for x-axis (not actual timestamps)  
- Kept as a lightweight analysis reference  
