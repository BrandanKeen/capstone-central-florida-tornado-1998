# Florida Reanalysis Visualizations

This directory showcases a set of meteorological plots generated using **ERA5 reanalysis data** for **February 23, 1998**, focusing on Florida and Central Florida. All visualizations were created using Python with `xarray`, `cartopy`, and `matplotlib`.

Plots are organized by region and atmospheric level. This collection demonstrates proficiency in scientific data visualization and meteorological plotting.

---

## Florida (Statewide Domain)

### Surface
- [2m Temperature, 10m Wind, MSLP](FL_surface_Temp_MSLP_Wind_1998_02_23_00.png)
- [2m Dewpoint, 10m Wind, MSLP](FL_surface_Dewpoint_MSLP_Wind_1998_02_23_00.png)

### 850 mb
- [850 mb Temperature, Wind, Heights](FL_850mb_Temp_Heights_Wind1998_02_23_00.png)
- [850 mb Theta-e, Wind](FL_850mb_Theta-e_Heights_Wind_1998_02_23_00.png)
- [850 mb Heights, Wind (04z)](FL_850mb_Heights_Wind_1998_02_23_04.png)

### 700 mb
- [700 mb Temperature, Wind, Heights](FL_700mb_Temp_Heights_Wind1998_02_23_00.png)

### 500 mb
- [500 mb Temperature, Wind, Heights](FL_500mb_Temp_Heights_Wind1998_02_23_00.png)
- [500 mb Relative Vorticity, Heights (05z)](FL_500mb_RelVorticity_Heights_1998_02_23_05.png)
- [500 mb Baroclinic Potential Vorticity, Theta (05z)](FL_500mb_BaroPotVorticity_Theta_1998_02_23_05.png)

### CAPE, Wind Shear, and MSLP Crossovers
- [CAPE + Wind Crossover + MSLP – 00z](FL_CAPE_MSLP_WindCrossover_1998_02_23_00.png)
- [CAPE + Wind Crossover + MSLP – 01z](FL_CAPE_MSLP_WindCrossover_1998_02_23_01.png)
- [CAPE + Wind Crossover + MSLP – 02z](FL_CAPE_MSLP_WindCrossover_1998_02_23_02.png)
- [CAPE + Wind Crossover + MSLP – 03z](FL_CAPE_MSLP_WindCrossover_1998_02_23_03.png)
- [CAPE + Wind Crossover + MSLP – 04z](FL_CAPE_MSLP_WindCrossover_1998_02_23_04.png)
- [CAPE + Wind Crossover + MSLP – 05z](FL_CAPE_MSLP_WindCrossover_1998_02_23_05.png)
- [CAPE + Wind Crossover + MSLP – 06z](FL_CAPE_MSLP_WindCrossover_1998_02_23_06.png)

---

## Central Florida (Zoomed Region)

### 850 mb
- [850 mb Theta-e, Wind (04z)](CFL_850mb_Theta-e_Heights_Wind_1998_02_23_04.png)
- [850 mb Dewpoint Depression, Wind, Heights](CFL_850mb_DewpointDepression_Heights_Wind_1998_02_23_04.png)

### CAPE and Wind Shear
- [CAPE + Wind Crossover + MSLP – Central FL (04z)](CFL_CAPE_MSLP_WindCrossover_1998_02_23_04.png)

---

## Jupyter Notebooks

| File | Description |
|------|-------------|
| `Reanalysis_FL.ipynb` | Full-domain plots for Florida |
| `Reanalysis_CFL.ipynb` | Central Florida zoomed plots |
| `Reanalysis_US.ipynb` | Broader US-wide context (not shown) |
