# 🌪️ Capstone: Central Florida Tornado Outbreak (1998)

This repository contains work completed for the *Data Analysis in Meteorology* capstone course at Florida Institute of Technology. It showcases the use of Python, Jupyter Notebooks, radar software, satellite data, and geospatial tools such as QGIS, GrADS, and Excel for the analysis and visualization of the 1998 Central Florida Tornado Outbreak.

The objective of this repository is to demonstrate the technical skills, scientific tools, and meteorological reasoning applied throughout the development of this project.

Each project folder includes:
- Output figures (`.png`)
- The exact code used to generate each figure (`.ipynb`, `.py`, `.qgz`, `.gs`)
- A `README.md` describing the image's purpose, method, and scientific interpretation

---

## 🛠️ Tools & Visualizations

### 🐍 Python / Jupyter Notebooks
- [Atmospheric Sounding – Skew-T Plot](graphics/soundings/README.md) - [CAPE/Wind Crossover Composite](graphics/reanalysis/README.md)
- [Wind Rose – KGIF Station](graphics/wind_roses/README.md)

### 📊 Excel / Tabular Tools
- [ERA5 vs ASOS Temperature Validation – Scatter Plot & Regression](graphics/reanalysis/README.md)

### 🌍 QGIS
- [Lake Wales Ridge Relief Map](graphics/topographical/README.md)
- [Central Florida DEM Overlay](graphics/topographical/README.md)

### 📡 GR2Analyst / Radar Tools
- [Base Reflectivity – Kissimmee Tornado Cell](graphics/radar/README.md)
- [Velocity Couplets – KTBW](graphics/radar/README.md)
- [Spectrum Width – Tornadic Cell](graphics/radar/README.md)

### 📈 GrADS
- [300 mb Jet Streak Analysis](graphics/reanalysis/README.md)
- [1000–850 mb Thickness & Surface Pressure](graphics/reanalysis/README.md)

---

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
