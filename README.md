# Dynamic Vulnerability Assessment of Urban Emergency Services
### Master of Science in Data Science | Amity University, Noida

## 📌 Project Overview
This research project focuses on the **Dynamic Vulnerability Assessment of Urban Emergency Services** in the Delhi National Capital Region (NCR). By integrating **OpenStreetMap (OSM)** spatial data with **Real-time Transit Data (GTFS)**, this study evaluates the accessibility and resilience of emergency services (Hospitals, Fire Stations, etc.) against urban disruptions.

The project utilizes **DBSCAN Clustering** to identify high-vulnerability zones and spatial gaps in service delivery.

## 🚀 Key Features
- **Spatial Data Extraction:** Automated retrieval of urban infrastructure data via OSM.
- **Transit Network Analysis:** Integration of Delhi Bus/Metro data to simulate real-world accessibility.
- **Machine Learning Integration:** Implementation of **DBSCAN** (Density-Based Spatial Clustering of Applications with Noise) to identify underserved urban clusters.
- **Vulnerability Mapping:** Visualizing service bottlenecks using GeoPandas and Folium.

## 🛠️ Tech Stack
- **Language:** Python 3.x
- **Libraries:** - `GeoPandas` & `Shapely` (Spatial Data Processing)
  - `Scikit-Learn` (DBSCAN & Clustering)
  - `OSMnx` (Network Analysis)
  - `Pandas` & `NumPy` (Data Manipulation)
- **Visualization:** Matplotlib, Folium, Seaborn

## 📂 Project Structure
```text
├── src/
│   ├── data_preprocessing.py   # Cleaning Delhi bus and transit data
│   ├── clustering_logic.py     # DBSCAN implementation
│   └── network_analysis.py     # Accessibility metrics calculation
├── notebooks/
│   └── analysis_demo.ipynb     # Exploratory Data Analysis
├── .gitignore                  # Rules to ignore GTFS, CSVs, and WPRs
└── README.md                   # Project Documentation
