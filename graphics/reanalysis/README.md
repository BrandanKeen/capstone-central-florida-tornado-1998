# Reanalysis Visualizations

This directory showcases meteorological plots generated using two reanalysis datasets: **ECMWF–ERA5** and **NCEP–NARR**.  
The goal of this section is to demonstrate technical skill in generating high-quality meteorological visualizations using Python.

Plots are grouped first by reanalysis dataset, then by domain and pressure level or variable.

---

## ERA5 Reanalysis

### Central Florida

#### 850 mb
- [850 mb Theta-e, Wind (04z)](CFL_850mb_Theta-e_Heights_Wind_1998_02_23_04.png)
- [850 mb Dewpoint Depression, Wind, Heights](CFL_850mb_DewpointDepression_Heights_Wind_1998_02_23_04.png)

#### CAPE + Wind Crossover + MSLP
- [CAPE + Wind Crossover + MSLP – Central FL (04z)](CFL_CAPE_MSLP_WindCrossover_1998_02_23_04.png)

---

### Florida

#### Surface
- [2m Temperature, 10m Wind, MSLP](FL_surface_Temp_MSLP_Wind_1998_02_23_00.png)
- [2m Dewpoint, 10m Wind, MSLP](FL_surface_Dewpoint_MSLP_Wind_1998_02_23_00.png)

#### 850 mb
- [850 mb Temperature, Wind, Heights](FL_850mb_Temp_Heights_Wind1998_02_23_00.png)
- [850 mb Theta-e, Wind](FL_850mb_Theta-e_Heights_Wind_1998_02_23_00.png)
- [850 mb Heights, Wind (04z)](FL_850mb_Heights_Wind_1998_02_23_04.png)

#### 500 mb
- [500 mb Temperature, Wind, Heights](FL_500mb_Temp_Heights_Wind1998_02_23_00.png)
- [500 mb Relative Vorticity, Heights (05z)](FL_500mb_RelVorticity_Heights_1998_02_23_05.png)

#### CAPE + Wind Crossover + MSLP
- [CAPE + Wind Crossover + MSLP – 04z](FL_CAPE_MSLP_WindCrossover_1998_02_23_04.png)

---

### United States

#### Surface
- [2m Temperature, 10m Wind, MSLP](US_surface_Temp_MSLP_Wind_1998_02_23_00.png)
- [2m Dewpoint, 10m Wind, MSLP](US_surface_Dewpoint_MSLP_Wind_1998_02_23_00.png)

#### 850 mb
- [850 mb Heights, Wind (05z)](US_850mb_Heights_Wind_1998_02_23_05.png)

#### 500 mb
- [500 mb Temperature, Heights](US_500mb_Temp_Heights_1998_02_23_00.png)

#### 250 mb
- [250 mb Heights, Wind (05z)](US_250mb_Heights_Wind_1998_02_23_05.png)

---

## NARR Reanalysis

### MSLP and 1000–500 mb Thickness

These plots were generated using the **North American Regional Reanalysis (NARR)** dataset and the Siphon data access library.  
The visualization code is provided in:

- [00Z – MSLP and 1000–500 mb Thickness](EAST_US_MSLP_Thickness_Map_1998_02_23_00.png)
- [03Z – MSLP and 1000–500 mb Thickness](EAST_US_MSLP_Thickness_Map_1998_02_23_03.png)
- [06Z – MSLP and 1000–500 mb Thickness](EAST_US_MSLP_Thickness_Map_1998_02_23_06.png)
