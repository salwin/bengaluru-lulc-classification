# 🏙️ Bengaluru Land Cover Classification 2024
### Machine Learning + Google Earth Engine + Sentinel-2

![Python](https://img.shields.io/badge/Python-3.x-blue)
![GEE](https://img.shields.io/badge/Google%20Earth%20Engine-4285F4)
![ML](https://img.shields.io/badge/Random%20Forest-ML-green)
![Sentinel-2](https://img.shields.io/badge/Sentinel--2-ESA-orange)
![Folium](https://img.shields.io/badge/Folium-WebMap-brightgreen)

---

## 📌 Project Overview
Land Use Land Cover (LULC) classification of Bengaluru Urban District 
using Random Forest machine learning on Sentinel-2 satellite imagery 
processed via Google Earth Engine.

## 🗺️ Map
![Bengaluru LULC 2024](Bengaluru_lulc_Map.png)


## 🎯 Land Cover Classes
| Class | Description |
|---|---|
| 🔴 Urban / Built-up | Roads, buildings, concrete surfaces |
| 🟢 Vegetation | Parks, forests, mixed cropland |
| 🔵 Water Bodies | Lakes, reservoirs, wetlands |
| 🟫 Fallow / Agriculture | Uncultivated farmland, open soil |

## 🛠️ Tech Stack
- **Google Earth Engine** — cloud satellite data processing
- **Sentinel-2 L2A** — 10m resolution imagery (Jan–Mar 2024)
- **Random Forest** — scikit-learn classifier
- **Python** — GeoPandas, Pandas, Matplotlib

## 📊 Model Performance
- Training samples: 800 pixels (200 per class)
- Spectral features: B2, B3, B4, B8, B11, B12, NDVI, NDBI, MNDWI

## ⚠️ Limitations
- Accuracy may be optimistic due to spatial autocorrelation in training samples
- Agriculture and Vegetation merged due to spectral similarity in dry season
- Fallow land dominant in peri-urban areas due to seasonal cultivation patterns
  
## Author
Salwin M S | GIS Analyst | TUM graduate | Kerala, India
