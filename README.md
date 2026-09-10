# Land Use Land Cover (LULC) Classification of Gilgit — 2024

## 📌 Project Overview

This project presents a **Land Use Land Cover (LULC) classification of Gilgit, Gilgit-Baltistan, Pakistan for 2024** using **Google Earth Engine (GEE)** and satellite remote sensing data.

The objective is to identify and map major land-cover classes within the study area and demonstrate the application of **GIS, Remote Sensing, and Google Earth Engine** for spatial analysis and environmental monitoring.

## 🗺️ Study Area

The study area covers **Gilgit, Gilgit-Baltistan, Pakistan**.

The area is characterized by complex mountainous terrain and contains diverse land-cover types including vegetation, built-up areas, barren land, water bodies, and snow/glacier-covered areas.

## 🛰️ Data & Tools

* **Satellite Data:** Sentinel-2
* **Platform:** Google Earth Engine
* **Software/Tools:** Google Earth Engine, GIS
* **Study Year:** 2024
* **Study Area:** Gilgit, Gilgit-Baltistan, Pakistan

## 🌍 LULC Classes

The classification identifies the following major land-cover categories:

1. 🌱 Vegetation
2. 🏘️ Built-up Area
3. 🏜️ Barren Land
4. 💧 Water Bodies
5. ❄️ Snow/Glacier

## ⚙️ Methodology

The workflow followed these major steps:

1. Defined the Gilgit study area using an uploaded GIS asset.
2. Acquired and filtered satellite imagery for 2024.
3. Applied image preprocessing and cloud filtering.
4. Prepared training samples for the selected LULC classes.
5. Performed supervised classification using Google Earth Engine.
6. Generated the final LULC classification map.
7. Clipped the classified image to the study area.
8. Visualized the classified LULC map.
9. Prepared the final results for GIS-based interpretation.

## 🗺️ Final LULC Map

The final classified map represents the spatial distribution of the major land-cover classes across Gilgit.

**Final Result:**

`LULC_Gilgit_2024.png`

## 📊 Results

The resulting LULC map provides a spatial representation of land-cover distribution in Gilgit during 2024.

This dataset can support further analysis related to:

* Urban expansion
* Agricultural and vegetation monitoring
* Environmental change
* Water-resource assessment
* Mountain ecosystem monitoring
* Land-use planning
* Climate and environmental studies

## 💻 Google Earth Engine Code

The complete Google Earth Engine JavaScript code used for this project is included in this repository.

**File:** `LULC_Gilgit_2024.js`

## 🎯 Applications

LULC mapping using satellite remote sensing can help researchers, planners, and environmental organizations understand how land is distributed across mountainous regions and provide a baseline for future land-cover change analysis.

## 🔮 Future Work

Future improvements may include:

* Multi-year LULC change detection
* Classification accuracy assessment
* LULC area statistics
* Comparison with higher-resolution imagery
* Machine-learning-based classification
* Prediction of future land-cover changes
* Integration with Google Earth Engine time-series analysis

## 👩‍💻 Author

**Zohra**

GIS & Remote Sensing
Geospatial Analysis | Remote Sensing | Google Earth Engine | GIS Mapping

---

⭐ This project is part of my growing **GIS & Remote Sensing portfolio** and demonstrates practical experience in satellite image processing, land-cover classification, spatial analysis, and Google Earth Engine.
