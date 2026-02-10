# Visualizing FEMA National Risk Index Data
### Lucian Scher - 2/10/26

### Final Output Visualizations

**HW #2:**
<img width="1344" height="960" alt="image" src="https://github.com/user-attachments/assets/d597f46b-15ff-4d0b-86d9-f797e9c06f8a" />

**HW #3:**
<img width="1056" height="739" alt="image" src="https://github.com/user-attachments/assets/c828cdec-ad49-44db-a1da-6671f99cbdcc" />


## Purpose

This repository produces analyses focusing on data visualization technique practice using FEMA National Risk Index (NRI) data and US Census Bureau American Community Survey (ACS) data. 

**HW #2** explores how FEMA NRI scores for counties in California compare to those in other states through effective, accessible, and aesthetically-pleasing visualizations built in R using the ggplot2 package.

**HW #3** examines how climate hazard risk exposure varies across racial and ethnic groups in California by joining FEMA NRI data with ACS demographic data, using a diverging bar chart to show deviations from the state average risk.

## Repository Contents

This repository is organized as follows:
```
eds240-nri-acs-viz/
├── .gitignore
├── README.md
├── HW2.qmd
├── HW2.html
├── HW2_files/
├── HW3.qmd
├── HW3.pdf
└── eds240-nri-acs-viz.Rproj
```
**Key Files:**
- `HW2.qmd`: Quarto document containing the FEMA NRI state comparison visualization, data wrangling code, and responses to assignment questions
- `HW3.qmd`: Quarto document containing the FEMA NRI x ACS racial/ethnic group analysis, data wrangling code, and responses to assignment questions

## Data Access

### FEMA National Risk Index Data

The FEMA National Risk Index data used in both projects can be accessed through the [FEMA Resilience Analysis and Planning Tool (RAPT)](https://hazards.fema.gov/nri/map)
   - Navigate to RAPT → Click "NRI" in top menu → Find "National Risk Index Counties" layer → Click three dots (⋯) → Export to CSV

**Citation**:

Federal Emergency Management Agency (FEMA), National Risk Index Dataset: National Risk Index County_National Risk Index_Rating_Composite - v1.20. Retrieved from [FEMA GIS](https://fema.maps.arcgis.com/home/item.html?id=5771b821a2124413b2ee590a73ca338d) on January 25th, 2026, 10:30 am PST. This product uses the FEMA National Risk Index dataset API or downloadable datasets but is not endorsed by FEMA. The Federal Government or FEMA cannot vouch for the data or analyses derived from these data after the data have been retrieved from the Agency's website(s).

### US Census Bureau American Community Survey Data (HW #3)

The ACS data used in HW #3 is accessed via the `tidycensus` R package using the US Census Bureau API.

**To access ACS data:**
1. Obtain a free Census API key from: https://api.census.gov/data/key_signup.html
2. Set your API key using: `census_api_key("YOUR_KEY", install = TRUE)`
3. The `HW3.qmd` file contains code to download race/ethnicity data for California counties

**Citation**:

US Census Bureau. (2023). American Community Survey 1-Year Estimates. Retrieved via tidycensus R package. This product uses the Census Bureau Data API but is not endorsed by the US Census Bureau.

**To reproduce the projects:**
1. Clone this repository
2. **For HW #2:**
   - Download the FEMA NRI Counties CSV file using the method above
   - Place the CSV file in the `data/` folder
   - Open `HW2.qmd` in RStudio or your preferred Quarto editor
   - Render the document
3. **For HW #3:**
   - Download the FEMA NRI Counties CSV file (same as HW #2)
   - Obtain a Census API key and set it up (see above)
   - Open `HW3.qmd` in RStudio or your preferred Quarto editor
   - Run the code to download ACS data (will be saved to `data/` folder)
   - Render the document

## References & Acknowledgements

This repository and its contained projects are homework assignments #2 and #3 for the Masters of Environmental Data Science program **EDS 240 Course**, developed and taught by S. Shanny-Csik and licensed under a Creative Commons Attribution 4.0 International License.
