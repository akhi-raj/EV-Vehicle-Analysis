# EV-Vehicle-Analysis

This project dives into the analysis of electric vehicle (EV) adoption in the United States using the [Electric Vehicle Population dataset](https://www.kaggle.com/datasets/ricardobj/electric-vehicle-population) sourced from Kaggle. It uncovers trends across manufacturers, cities, model years, EV types, and explores policy-related eligibility such as the California Clean Alternative Fuel Vehicle (CAFV) program.

## Dataset Overview

- **Source**: Kaggle – Electric Vehicle Population  
- **License**: CC0: Public Domain  
- **Features include**:
  - Vehicle Make, Model, Model Year
  - Partial VIN (Vehicle Identification Number)
  - EV Type (BEV, PHEV, FCEV)
  - CAFV Eligibility
  - Location Details: Country, State, City, Postal Code

## Objectives

- Understand geographic distribution of EVs in the U.S.
- Analyze market share by EV brand and model
- Track EV adoption trends over time
- Explore relationships between vehicle type, make, and eligibility
- Generate insights for infrastructure needs (charging stations, policy zones)
- Build predictive models to forecast EV adoption growth

## Tools & Technologies

### Data Analysis & Visualization
- `pandas` – data manipulation
- `numpy` – numerical operations
- `matplotlib` / `seaborn` – static visualizations
- `plotly` – interactive charts
- `geopandas` / `folium` – geospatial analysis and maps

### Machine Learning & Forecasting
- `scikit-learn` – clustering (KMeans), regression models
- `statsmodels` or `Prophet` – time series forecasting

### Dashboarding (Planned)
- `Dash` or `Streamlit` – building interactive dashboards
- `Power BI` – for business-style analytics (optional GUI-based)

### Development
- Jupyter Notebooks for analysis
- Git & GitHub for version control
- Python virtual environment setup for reproducibility

## Key Deliverables

- **Exploratory Data Analysis (EDA)**: Cleaned data, feature insights, and patterns
- **Interactive Visualizations**: Brand heatmaps, EV growth trends, policy eligibility breakdowns
- **ML Models**: Linear regression for EV adoption forecasting, clustering for infrastructure planning
- **Dashboard**: An interactive view to explore trends by location, make, model, and eligibility
- **Case Study Summary**: Insightful story-driven report suited for portfolios and LinkedIn

## Project Structure (Expected)


EV-Vehicle-Analysis/
├── data/ # Raw and processed datasets
├── notebooks/ # Jupyter notebooks for EDA, modeling
├── src/ # Python scripts (cleaning, visualization, modeling)
├── visuals/ # Exported charts and plots
├── dashboard/ # Code for Dash/Streamlit app (if used)
├── README.md
└── requirements.txt # Project dependencies


## Outcome

This project aims to serve as a full-stack data analysis portfolio piece—from raw data exploration to final insights, visual storytelling, and potential machine learning implementation. It’s designed to help understand EV trends, policy adoption impact, and future infrastructure demands.

---

**Note**: This dataset is publicly available under the CC0: Public Domain license, making it suitable for educational and portfolio use.