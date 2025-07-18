# School Accessibility Analysis in Bay of Plenty (BOP) Region

This project analyzes school accessibility in the Bay of Plenty region using GIS (Geographic Information Systems). The goal is to assess how well school-age children (ages 5–19) can access intermediate, secondary, and composite schools either by walking or public transportation.

## Project Objectives

- Evaluate walking access to schools using 800-meter buffers.
- Assess bus-only access by excluding school walking zones.
- Identify populations with no reasonable access to schools.
- Recommend optimal locations for new bus stops based on underserved areas.

##  Data Sources

- **NZ Schools Directory**: [Eagle GIS](https://hub.arcgis.com/datasets/eaglegis::nz-schools-directory/explore)
- **Bus Stops**: [Bay of Plenty Regional Council Open Data](https://maps-boprc.opendata.arcgis.com/datasets/bus-stops-bay-of-plenty/explore)
- **Population Data**: [Stats NZ](https://datafinder.stats.govt.nz/layer/8447-age-by-meshblock-2013-census/)
- **Road, River, and Lake Data**: [LINZ](https://data.linz.govt.nz/)
- **Regional Boundaries**: [Stats NZ Regional Council 2025](https://datafinder.stats.govt.nz/layer/120946-regional-council-2025/)

##  Methodology

- Buffer analysis (800m) around schools and bus stops
- Proportional meshblock analysis to estimate accessibility
- Erase analysis to prevent overlap between access types
- Final classification into: Walk Access, Bus-only Access, No Access

##  Key Findings

- About **11,714 children** lack adequate access to schools.
- Four meshblocks identified with **30+ underserved children**.
- Proposed **new bus stop locations** could significantly improve coverage.
- Urban areas are better served; rural zones face major access gaps.

##  File Structure

- `School_Access_BOP.gdb/` – ArcGIS project files and data
- `*.xlsx` – Exported summary tables
- `School_Access_BOP.aprx` – Main ArcGIS project file
- `README.md` – Project documentation

##  Author

- Sumeet


