# ERA5 vs. ASOS Temperature Comparison

This directory presents a regression analysis comparing **ERA5 2-meter temperature** data with **KTPA ASOS (METAR)** observations.

The analysis includes hourly comparisons, a 6-hour event window on the day of the 1998 Central Florida Tornado Outbreak, and monthly average climatology.

---

## Data File

- [Reanalysis vs. METAR Temperature Dataset (Excel)](Reanalysis_2mT_KTPA_1998.xlsx)

---

## Plots

### 1. Full Hourly Comparison
- Regression of all available hourly 2-meter temperatures from ERA5 vs. METAR.
- $R^2$ = **0.9373**, slope ~0.998 — very strong agreement.
- ![Hourly Comparison](Hourly_Regression_Full.png)

### 2. 6-Hour Event Window – 1998-02-23 02:00–08:00 UTC
- Short-term focus during the tornadic event.
- $R^2$ = **0.9162**, slope suggests overestimation trend.
- ![6-Hour Event](Hourly_Regression_EventWindow.png)

### 3. Monthly Average Comparison
- Long-term mean comparisons of ERA5 and METAR monthly averages.
- $R^2$ = **0.998**, demonstrating excellent climatological agreement.
- ![Monthly Average](Monthly_Regression.png)

---

**Reanalysis**: ECMWF ERA5 hourly 2m temperature  
**Observations**: KTPA ASOS (Sourced from Iowa Environmental Mesonet)
