# Dynamic Vulnerability Assessment of Urban Emergency Services
### Master of Science in Data Science | Amity University, Noida

## 📌 Project Overview
This research project, titled **"Dynamic Vulnerability Assessment of Urban Emergency Services,"** focuses on evaluating the resilience and accessibility of emergency infrastructure (Hospitals, Fire Stations) in the Delhi NCR region. By integrating **OpenStreetMap (OSM)** spatial data with **Real-time Transit Data (GTFS)**, the study identifies urban service gaps through density-based spatial analysis.

## 🚀 Key Features
* **Geospatial Data Extraction**: Automated retrieval of urban points of interest (POIs) and road networks using the Overpass API and OSMnx.
* **Transit Network Analysis**: Integration of Delhi’s public transit network (Bus and Metro) to assess real-world accessibility.
* **Machine Learning Integration**: Implementation of **DBSCAN** (Density-Based Spatial Clustering of Applications with Noise) to identify underserved urban clusters and vulnerability hotspots.
* **Document OCR**: Integration of Tesseract OCR to process historical scanned transit reports and logs.

## 🧪 Methodology
For this research, we utilize **DBSCAN** because urban emergency service locations do not follow spherical distributions. 
* **Parameters**: The core distance function $d(p, q)$ accounts for real-world road network distances rather than Euclidean distance.
* **Clustering**: We identify high-vulnerability zones where service density is insufficient relative to transit availability.

## 🛠️ Tech Stack
* **Language**: Python 3.14.2
* **OCR & Imaging**: 
  * `pytesseract==0.3.13` (Optical Character Recognition)
  * `pillow==12.2.0` (Image Processing)
* **Spatial & Machine Learning**:
  * `GeoPandas`, `OSMnx`, `Shapely`
  * `Scikit-learn` (DBSCAN Clustering)
* **Core Utilities**: `packaging==26.0`

## 📁 Installation & Setup
1. **Clone the Repository**:
   ```bash
   git clone [https://github.com/Ak-Kotnala07/Document-Intelligence-Simulator.git](https://github.com/Ak-Kotnala07/Document-Intelligence-Simulator.git)
   cd Document-Intelligence-Simulator
.
├── src/
│   ├── clustering_logic.py     # DBSCAN implementation for vulnerability mapping
│   └── ocr_parser.py           # Document processing with pytesseract
├── requirements.txt            # Project dependencies
├── .gitignore                  # Filters for GTFS, CSVs, and WPR data
└── README.md                   # Final Dissertation Documentation
