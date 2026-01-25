# Visualizing FEMA National Risk Index Data
### Lucian Scher - 1/25/26

### Final Output Visualization
<img width="1344" height="960" alt="image" src="https://github.com/user-attachments/assets/d597f46b-15ff-4d0b-86d9-f797e9c06f8a" />

## Purpose

This repository produces an analysis focusing on data visualization technique practice using FEMA National Risk Index (NRI) data. The primary objective is to explore how FEMA NRI scores for counties in California compare to those in other states through effective, accessible, and aesthetically-pleasing visualizations built in R using the ggplot2 package.

## Repository Contents

This repository is organized as follows:

```
eds240-nri-acs-viz/
├── README.md 
├── HW2.qmd # Homework 2: FEMA NRI visualization
├── HW3.qmd # Homework 3: FEMA NRI + ACS data
├── data/ # Data files (gitignored)
│ └── nri_counties.csv
└── .gitignore
```

**Key Files:**
- `HW2.qmd`: Quarto document containing the FEMA NRI data visualization, data wrangling code, and responses to assignment questions
- `data/`: Folder containing the FEMA National Risk Index Counties dataset (not tracked in git)

## Data Access

The FEMA National Risk Index data used in this project can be accessed through the [FEMA Resilience Analysis and Planning Tool (RAPT)](https://hazards.fema.gov/nri/map)
   - Navigate to RAPT → Click "NRI" in top menu → Find "National Risk Index Counties" layer → Click three dots (⋯) → Export to CSV

**Citation**:

Federal Emergency Management Agency (FEMA), National Risk Index Dataset: National Risk Index County_National Risk Index_Rating_Composite - v1.20. Retrieved from [FEMA GIS](https://fema.maps.arcgis.com/home/item.html?id=5771b821a2124413b2ee590a73ca338d) on January 25th, 2026, 10:30 am PST. This product uses the FEMA National Risk Index dataset API or downloadable datasets but is not endorsed by FEMA. The Federal Government or FEMA cannot vouch for the data or analyses derived from these data after the data have been retrieved from the Agency's website(s).

**To reproduce the project:**
1. Clone this repository
2. Download the FEMA NRI Counties CSV file using one of the methods above
3. Place the CSV file in the `data/` folder
4. Open `HW2.qmd` in RStudio or your preferred Quarto editor
5. Render the document

## References & Acknowledgements

This repository and its contained projects are homework #2 and #3 for the Masters of Environmental Data Science program **EDS 240 Course**, developed and taught by S. Shanny-Csik and licensed under a Creative Commons Attribution 4.0 International License.
