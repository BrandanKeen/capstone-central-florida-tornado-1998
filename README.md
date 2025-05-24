# Capstone: Central Florida Tornado Outbreak (1998)

This repository contains work completed for the *Data Analysis in Meteorology* capstone project at Florida Institute of Technology. It showcases the use of Python, Jupyter Notebooks, radar software, satellite data, and geospatial tools such as QGIS, GrADS, and Excel for the analysis and visualization of the 1998 Central Florida Tornado Outbreak.

The objective of this repository is to demonstrate the technical skills applied throughout the development of this project.

## Tools & Visualizations

This section provides a directory of the various visual products generated as part of this capstone project. It is organized by the primary program or software used in the analysis. This serves as the main visual archive for the project.

Each visual directory folder contains:

- Sampling of output figures (`.png`) developed during the project  
- The code used to produce the figures (`.ipynb`, `.gs`), depending on the tool used  
- A `README.md` file detailing the variables visualized  

##

### Python / Jupyter Notebooks

- [GOES-8 Satellite](graphics/satellite/README.md)
- [Soundings (sourced from Wyoming Upper Air)](graphics/soundings/README.md)
- [Reanalysis](graphics/reanalysis/README.md)

##

### GrADS
- [Reanalysis](graphics/grads_reanalysis/README.md)

##

### GR2Analyst / Gibson Ridge
- [Four Panel Plots (BR, BV, SW, SRV)](graphics/gr_analyst/4_panel/README.md)
- [Volumetric Scans](graphics/gr_analyst/volumetric/README.md)
- [Base Reflectivity (0.4° and 2.4° tilts)](graphics/gr_analyst/BR/README.md)

##

### QGIS
- [Topographical Relief](graphics/topographical/README.md)

##

### Microsoft Excel
- [ERA5 vs ASOS Temperature – Scatterplot and Regression Analysis](graphics/regression_analysis/README.MD)

---

Below is a comprehensive list of all Python libraries, and file formats used throughout the project.

## Python Libraries Used

## Python Libraries Used

- `numpy` – Array operations and numerical calculations  
- `pandas` – Handling tabular and time series data  
- `matplotlib` – Plot generation and figure customization  
- `cartopy` – Map projections and geospatial plotting  
- `metpy` – Meteorological calculations and Skew-T plotting  
- `sounderpy` – Custom Skew-T visualizations from reanalysis  
- `xarray` – Working with multidimensional NetCDF datasets  
- `siphon` – Accessing reanalysis and upper-air data via THREDDS  
- `scipy` – Data interpolation and scientific routines  
- `datetime` – Managing dates and timestamps  
- `os` – File and directory operations  
- `requests` – Downloading remote data via HTTP  
- `netCDF4` – Reading NetCDF files  

---

## File Formats Used

- `.ipynb` – Jupyter Notebooks (Python code and analysis)  
- `.csv` – Tabular meteorological and station data  
- `.txt` – Raw sounding and formatted text input  
- `.xlsx` – Excel files for regression and validation  
- `.json` – Configuration and metadata  
- `.nc` – NetCDF files for ERA5 reanalysis data  
- `.xml` – THREDDS catalog references  
- `.shp` – Shapefiles for geographic features  
- `.tif` – DEM raster files for elevation and topography  
- `.gs` – GrADS scripts

