# Chicago-Permit-Analysis
An interactive Tableau dashboard analyzing Chicago permit types, review timelines, and emerging neighborhoods. The project highlights where development activity is accelerating and identifies factors that contribute to shorter permitting paths, giving developers clearer insight into how to streamline approvals and target high‑opportunity areas.

## 🚀 Key Features
* **Interactive Dashboard**: Explore Chicago building permit trends visually.
* **Timeline Analysis**: Identify bottlenecks and factors reducing approval times.
* **Geospatial Mapping**: Discover emerging neighborhoods with accelerating development.
* **Predictive Insights**: Target high-opportunity areas based on historical data.

## 📂 Repository Structure
```text
chicago-permit-analysis/
├── data/
│   └── README.md              # Instructions for downloading source data
├── notebooks/
│   └── data_cleaning.ipynb    # Python notebook for initial data prep
├── scripts/
│   └── fetch_data.py          # Script to pull data from Chicago Data Portal API
├── tableau/
│   └── chicago_permits.twbx   # Tableau Packaged Workbook file
├── .gitignore                 # Excludes local data files and credentials
└── README.md                  # Project documentation
```

## 📊 Data Source
This analysis uses public data from the [City of Chicago Data Portal](https://cityofchicago.org).
* Dataset includes building permits issued from historical records to the present.
* Attributes analyzed include permit types, application dates, issue dates, and geographic coordinates.

## 🛠️ Tech Stack
* **Visualization**: Tableau Desktop / Tableau Public
* **Data Processing**: Excel Power Query
* **Data Source**: Chicago Data Portal API / CSV
* 

## 📈 Dashboard Insights
* **Speed Factors**: Projects using certified plans experience significantly shorter review times.
* **Hotspots**: Specific West and South Side neighborhoods show a surge in commercial permits.
* **Seasonality**: Permit applications peak in spring, causing longer seasonal processing backlogs.

## 💻 Getting Started
1. Clone this repository to your local machine.
2. Download the source data from the Chicago Data Portal.
3. Open the `.twbx` file in Tableau Desktop or Tableau Public.
4. Link the data source if prompted.
