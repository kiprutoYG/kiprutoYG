# Elkana Kipruto

**Geospatial Data Engineer & Data Scientist | Spatial Solutions Architect**
*Bridging the gap between raw satellite telemetry and actionable spatial insights.*
I build data-driven solutions with a geographical lens. Whether a problem is inherently spatial or a traditional business challenge, I specialize in adding the "where" component to uncover patterns that tabular data alone cannot reveal. I bridge the gap between high-scale data engineering and rigorous spatial analysis.

---

### Core Competencies

**Geospatial Engineering** Architecting pipelines for Raster (Sentinel, Landsat) and Vector (OSM, Census) data. Expert in Coordinate Reference Systems (CRS) management, spatial indexing (H3, S2), and optimizing SpatioTemporal Asset Catalogs (STAC).

**Data Engineering & Orchestration** Designing cloud-native ETL/ELT workflows that handle high-velocity environmental data. I focus on building idempotent pipelines that ensure data lineage from raw telemetry to feature stores.

**Spatial Data Science** Applying machine learning to geographic problems, including Land Use/Land Cover (LULC) classification, change detection, and spatial interpolation for climate variables.

**Interactive Visualization** Transforming complex spatial datasets into intuitive dashboards. I believe map-based storytelling is the most effective way to communicate multi-dimensional data insights.

---

### Technical Stack

* **Spatial Analysis & Modeling:** GeoPandas, Shapely, PyProj, Rasterio (I/O & Processing), WhiteboxTools, Xarray.
* **Data Engineering & SQL:** PostGIS, DuckDB (Spatial), Apache Sedona (GeoSpark), dbt, BigQuery GIS.
* **Orchestration & Infrastructure:** Apache Airflow, Prefect, Docker, Terraform, GitHub Actions.
* **Visualization & GIS:** QGIS, Mapbox GL JS, Deck.gl, Leaflet, Streamlit, Google Earth Engine.
* **Machine Learning:** Scikit-learn, XGBoost, PyTorch (Geo-AI).

---

### Featured Projects

#### **Admin Lookup & Extraction API (Full-Stack)** A high-performance spatial discovery service that bridges the gap between raw coordinates and administrative context.
* **The Solution:** Users provide `lat/lon` coordinates; the backend performs a point-in-polygon lookup against a multi-level administrative hierarchy (Country, County, Ward).
* **Engineering Highlight:** Built a FastAPI backend optimized with PostGIS GIST indexing for sub-second responses.
* **Data Portability:** Integrated a feature allowing users to dynamically clip and download the specific administrative Shapefile or GeoJSON for their query area.

#### **Lake Baringo Expansion Analysis Pipeline** An automated Earth Observation pipeline designed to quantify environmental shifts in the Kenyan Rift Valley.
* **The Solution:** Automates the ingestion of Sentinel-2 imagery to track the fluctuating shoreline of Lake Baringo.
* **Engineering Highlight:** Uses NDWI (Normalized Difference Water Index) thresholds to mask water bodies. I engineered a temporal analysis script that calculates surface area changes (in $km^2$) over a 5-year window.
* **Insight:** Transformed raw pixel data into a time-series dashboard showing the direct correlation between seasonal rainfall and land displacement.

#### **Geospatial Feature Store for Predictive Modeling** Currently architecting a centralized repository for pre-computed spatial features (e.g., elevation, slope, and population density).
* **Goal:** To provide "Spatial-Features-as-a-Service" for ML models, ensuring that any point-based prediction can instantly ingest its surrounding environmental context.

---

### Connect & Collaborate

**Location:** Nairobi, Kenya | Open to Remote & Hybrid Opportunities  
**Email:** kipruto.kosonei.geo@gmail.com
**LinkedIn:** https://www.linkedin.com/in/elkana-kipruto-83769b303/
**Portfolio:** [https://kosoneigeo.vercel.app/]  

I am looking to collaborate on projects involving **Climate-Tech**, **Precision Agriculture**, or **Urban Intelligence**. I thrive on turning messy, unstructured spatial data into clean, reliable infrastructure.

**Last Updated:** February 2026

## 📬 Connect with Me
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/elkana-kipruto-83769b303/)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=google-chrome&logoColor=white)](https://kosoneigeo.vercel.app/)
