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
- [ERA5 vs ASOS Temperature – Scatterplot and Regression Analysis](graphic/regression_analysis/README.md)

---
Below is a comprehensive list of all software/programs, Python libraries, file formats, and data types used throughout the project.

## 💻 Software / Programs Used

- Python (Jupyter Notebooks)  
- Excel (for regression, plotting, and validation)  
- QGIS  
- GR2Analyst / Gibson Ridge  
- GrADS  
- NOAA Weather and Climate Toolkit  
- GitHub  

---

## 📚 Python Libraries Used

- `numpy` – Numerical computations  
- `pandas` – Data manipulation and time series  
- `matplotlib` – Plotting and figure generation  
- `cartopy` – Map projections and spatial plotting  
- `metpy` – Meteorological calculations and Skew-T diagrams  
- `SounderPy` – Sounding plotting library  
- `xarray` – Multidimensional array datasets (e.g., NetCDF)  
- `siphon` – Downloading upper-air and model data from remote servers  
- `scipy` – Scientific computing and interpolation  
- `datetime` – Time handling  
- `os`, `glob` – File operations and pattern matching  

---

## 📁 File Formats Used

- `.ipynb` – Jupyter Notebooks  
- `.py` – Python scripts  
- `.png` – Output figures and images  
- `.csv` – Tabular observational data  
- `.txt` – Sounding and raw text files  
- `.nc` – NetCDF gridded datasets  
- `.grib` – GRIB model data (if applicable)  
- `.tif` – Raster GIS elevation data  
- `.shp` – Vector shapefiles for mapping  
- `.xml` – Metadata or THREDDS catalogs  
- `.qgz` – QGIS project files  
- `.gs` – GrADS script files  
- `.xlsx` – Excel workbook for data validation and plotting  

---

## 📊 Data Types Used

- Reanalysis  
- Radar  
- Satellite imagery  
- Atmospheric soundings  
- Surface observations  
- Topographic elevation  

---

## 👤 Author

**Brandan Keen**  
Capstone Project – MET 3403  
Florida Institute of Technology  
[GitHub Profile](https://github.com/BrandanKeen)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
