# DYNAMIC VULNERABILITY ASSESSMENT OF URBAN EMERGENCY SERVICES

Master of Science in Data Science | Amity University, Noida

**PROJECT** **OVERVIEW** This research project evaluates the resilience and accessibility of emergency infrastructure, such as hospitals and fire stations, in the Delhi **NCR** region. It integrates OpenStreetMap spatial data with real-time transit data for Delhi to identify service gaps through density-based spatial analysis.

**KEY** **FEATURES**

Geospatial Data Extraction: Automated retrieval of urban infrastructure and road networks using OSMnx.

Transit Network Analysis: Integration of Delhi’s public transit network to assess accessibility.

Machine Learning Integration: Implementation of **DBSCAN** to identify underserved urban clusters and vulnerability hotspots.

Document **OCR**: Integration of Tesseract **OCR** to process historical scanned transit reports and logs.

**METHODOLOGY** We utilize **DBSCAN** because urban emergency service locations do not follow spherical distributions. Real-world road network distances are used instead of Euclidean distance to measure accessibility. This allows for the identification of high-vulnerability zones where service density is insufficient relative to transit availability.

**TECH** **STACK**

Language: Python 3.14.2

**OCR** and Imaging: pytesseract (version 0.3.13) and pillow (version 12.2.0)

Spatial and Machine Learning: GeoPandas, OSMnx, Shapely, and Scikit-learn

Core Utilities: packaging (version 26.0)

**PROJECT** **STRUCTURE** .

src/ -- clustering_logic.py (**DBSCAN** implementation for vulnerability mapping) -- ocr_parser.py (Document processing with pytesseract)

requirements.txt (Project dependencies)

.gitignore (Filters for **GTFS**, CSVs, and **WPR** data)

**README**.md (Final Dissertation Documentation)

# DATA PRIVACY AND REPOSITORY SIZE

Raw Delhi Bus Data, **GTFS** feeds, and Weekly Progress Reports (WPRs) are excluded via the gitignore file to maintain data privacy as per university guidelines. These files are stored locally for analysis but are not pushed to the public cloud.

**AUTHOR** Akshat Kotnala, M.Sc. Data Science Candidate (**2024**–**2026**) at Amity University, Noida. Trainee Data Scientist at Glorious Insights.
