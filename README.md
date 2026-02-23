# Elkana Kipruto

**Geospatial Data Engineer & Data Scientist | Spatial Solutions Architect**   *Bridging the gap between raw satellite telemetry and actionable spatial insights.*

I build data-driven solutions with a geographical lens. Whether a problem is inherently spatial or a traditional business challenge, I specialize in adding the "where" component to uncover patterns that tabular data alone cannot reveal. I bridge the gap between high-scale data engineering and rigorous spatial analysis.

---

### Core Competencies

* **Geospatial Engineering:** Architecting pipelines for Raster (Sentinel, Landsat) and Vector (OSM, Census) data. Expert in CRS management, spatial indexing (H3, S2), and optimizing SpatioTemporal Asset Catalogs (STAC).
* **Data Engineering & Orchestration:** Designing cloud-native ETL/ELT workflows for high-velocity environmental data. Focus on idempotent pipelines ensuring data lineage from raw telemetry to feature stores.
* **Spatial Data Science:** Applying ML to geographic problems: LULC classification, change detection, and spatial interpolation for climate variables.
* **Interactive Visualization:** Transforming complex spatial datasets into intuitive dashboards. I believe map-based storytelling is the most effective way to communicate multi-dimensional insights.

---

### Technical Stack

| Category | Tools & Technologies |
| :--- | :--- |
| **Languages & SQL** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-CC2927?style=flat-square&logo=postgresql&logoColor=white) ![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white) |
| **Spatial Analysis** | ![GeoPandas](https://img.shields.io/badge/GeoPandas-150458?style=flat-square&logo=pandas&logoColor=white) ![Rasterio](https://img.shields.io/badge/Rasterio-lightgrey?style=flat-square) ![Xarray](https://img.shields.io/badge/Xarray-blue?style=flat-square) |
| **Engineering** | ![PostGIS](https://img.shields.io/badge/PostGIS-336791?style=flat-square&logo=postgresql&logoColor=white) ![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white) |
| **Orchestration** | ![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apache-airflow&logoColor=white) ![Prefect](https://img.shields.io/badge/Prefect-ffffff?style=flat-square&logo=prefect&logoColor=209293) |
| **Viz & GIS** | ![QGIS](https://img.shields.io/badge/QGIS-589632?style=flat-square&logo=qgis&logoColor=white) ![Mapbox](https://img.shields.io/badge/Mapbox-000000?style=flat-square&logo=mapbox&logoColor=white) ![GEE](https://img.shields.io/badge/Google_Earth_Engine-4285F4?style=flat-square&logo=google&logoColor=white) |

---

### Featured Projects

#### **Admin Lookup & Extraction API**
A high-performance spatial discovery service bridging raw coordinates and administrative context.
* **The Solution:** Users provide `lat/lon`; the backend performs a point-in-polygon lookup against multi-level administrative hierarchies (Country, County, Ward).
* **Engineering Highlight:** Built a **FastAPI** backend optimized with **PostGIS GIST indexing** for sub-second responses.
* **Data Portability:** Dynamically clips and allows downloads of specific administrative Shapefiles or GeoJSONs for queried areas.

#### **Lake Baringo Expansion Analysis Pipeline**
An automated Earth Observation pipeline quantifying environmental shifts in the Kenyan Rift Valley.
* **The Solution:** Automates Sentinel-2 imagery ingestion to track fluctuating shorelines.
* **Engineering Highlight:** Uses **NDWI** thresholds for water masking. Engineered a temporal analysis script calculating surface area changes in $km^2$ over a 5-year window.
* **Insight:** Correlates pixel-level changes with seasonal rainfall to visualize land displacement.

#### **Geospatial Feature Store**
Architecting a centralized repository for pre-computed spatial features (elevation, slope, population density).
* **Goal:** Provide "Spatial-Features-as-a-Service" for ML models, allowing any point-based prediction to instantly ingest its surrounding environmental context.

---

### 📫 Connect & Collaborate

* **Location:** Nairobi, Kenya 🇰🇪 | Open to Remote & Hybrid Opportunities
* **Email:** [kipruto.kosonei.geo@gmail.com](mailto:kipruto.kosonei.geo@gmail.com)
* **LinkedIn:** [Elkana Kipruto](https://www.linkedin.com/in/elkana-kipruto-83769b303/)
* **Portfolio:** [kosoneigeo.vercel.app](https://kosoneigeo.vercel.app/)

I am looking to collaborate on **Climate-Tech**, **Precision Agriculture**, or **Urban Intelligence**. I thrive on turning messy, unstructured spatial data into clean, reliable infrastructure.

---
*Last Updated: February 2026*
