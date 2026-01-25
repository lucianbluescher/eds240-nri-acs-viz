# Visualizing FEMA National Risk Index Data
### Lucian Scher

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

**To reproduce the project:**
1. Clone this repository
2. Download the FEMA NRI Counties CSV file using one of the methods above
3. Place the CSV file in the `data/` folder
4. Open `HW2.qmd` in RStudio or your preferred Quarto editor
5. Render the document

## References & Acknowledgements

This repository and its contained projects are homework #2 and #3 for the Masters of Environmental Data Science program **EDS 240 Course**, developed and taught by S. Shanny-Csik and licensed under a Creative Commons Attribution 4.0 International License.
