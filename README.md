# VALL_WSVA

Valles Caldera Water Supply Vulnerability Assessment (WSVA)

## Published report

[**Water for People: Water Supply Vulnerability Assessment for Proposed Water Supplies at Valles Caldera National Preserve**](https://irma.nps.gov/DataStore/Reference/Profile/2321192) (NPS DataStore, January 2026)

> Cognac K, Willi K, Mothes C, Gilkerson T, Lawrence D. 2026. Water for People: Water Supply Vulnerability Assessment for Proposed Water Supplies at Valles Caldera National Preserve. National Park Service. <https://irma.nps.gov/DataStore/Reference/Profile/2321192>

This water supply vulnerability assessment evaluates the resilience of the proposed water supply at Valles Caldera National Preserve to projected shifts in hydroclimatic conditions. A scenario-based approach considers individual projections from climate and hydrology models to capture a range of plausible future conditions Valles Caldera may experience, from "Warm Wet" to "Hot Dry." Vulnerability was assessed by examining the proposed water supply's exposure and sensitivity to hydroclimatic changes, including historical and projected water budgets, water demands, storage capacity, droughts, extreme events, and fire. This assessment aims to inform short- and long-term water resource management decisions at Valles Caldera National Preserve, including the proposed water supply shift from surface water to groundwater.

## Repository contents

- `Reports/VALL_Deep_Dive.Rmd`: prepares the data inputs and figures for the report
- `setup.R`: installs/loads required packages and sources every function in `src/`
- `src/`: the functions the report uses, including the NPS Water Balance Model (`src/NPS_WBM/`)

This code was moved from [nps_water_vulnerability](https://github.com/Water-Vulnerability-Analytics/nps_water_vulnerability) with its commit history preserved.
