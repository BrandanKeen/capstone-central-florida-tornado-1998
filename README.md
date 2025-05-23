# 🌪️ Capstone: Central Florida Tornado Outbreak (1998)

This repository contains work completed for the *Data Analysis in Meteorology* capstone course at Florida Institute of Technology. It showcases the use of Python, Jupyter Notebooks, radar software, satellite data, and geospatial tools such as QGIS, GrADS, and Excel for the analysis and visualization of the 1998 Central Florida Tornado Outbreak.

The objective of this repository is to demonstrate the technical skills, scientific tools, and meteorological reasoning applied throughout the development of this project.

Each project folder includes:
- Output figures (`.png`)
- The exact code used to generate each figure (`.ipynb`, `.py`, `.qgz`, `.gs`)
- A `README.md` describing the image's purpose, method, and scientific interpretation

---

## Tools & Visualizations

### Python / Jupyter Notebooks
- [GOES-8 Satellite](graphics/satellite/README.md)
- [Soundings (Sourced from Wyoming Upper Air)](graphics/soundings/README.md)
- [Reanalysis](graphics/reanalysis/README.md)



### Microsoft Excel
- [ERA5 vs ASOS Temperature Validation – Scatterplot and Regression](graphics/reanalysis/README.md)

---

### QGIS
- [Topographical Relief](graphics/topographical/README.md)

---

### GR2Analyst / Gibson Ridge
- [Four Panel Plots (BR, BV, SW, SRV)](graphics/radar/README.md)
- [Volumetric Scans and Base Reflectivity (0.4° and 2.4° tilts)](graphics/radar/README.md)

---

### GrADS
- [Reanalysis](graphics/reanalysis/README.md)

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
