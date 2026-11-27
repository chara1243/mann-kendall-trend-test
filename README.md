# Mann-Kendall Trend Test Using ERA5 Temperature Data

## Project Overview

This project performs spatial Mann-Kendall trend analysis of monthly 2-metre air temperature using ERA5 monthly climate data and Google Earth Engine.

The analysis uses Python, Google Earth Engine, Geemap, Xarray, XEE, and PyMannKendall.

## Objectives

- Retrieve ERA5 monthly temperature data.
- Define a study area using an interactive map.
- Extract temperature data using Google Earth Engine.
- Apply the original Mann-Kendall trend test.
- Calculate trend direction, Mann-Kendall S statistic, and p-value.
- Visualize spatial temperature trends.

## Data Source

ERA5 Monthly Aggregates, Google Earth Engine.

Dataset ID: `ECMWF/ERA5/MONTHLY`

Variable: `mean_2m_air_temperature`

Study period: 1980 to 2025.

## Technologies Used

- Python
- Google Earth Engine
- Geemap
- Xarray
- XEE
- PyMannKendall
- Matplotlib

## Repository Structure

```text
mann-kendall-trend-test/
│
├── mannkendall_trendtest_practice.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

## Analysis Workflow

1. Authenticate and initialize Google Earth Engine.
2. Create an interactive study area.
3. Retrieve ERA5 monthly temperature data.
4. Process the data using Xarray and XEE.
5. Apply the original Mann-Kendall trend test.
6. Calculate trend direction, S statistic, and p-value.
7. Generate spatial trend maps.

## Output

The notebook generates three spatial maps:

- Temperature trend direction.
- Mann-Kendall S statistic.
- Mann-Kendall p-value.

## Requirements

Install the required Python packages using:

```bash
pip install -r requirements.txt
```

Google Earth Engine authentication and an authorized Earth Engine project are required.

## Author

Charan Bhattarai
