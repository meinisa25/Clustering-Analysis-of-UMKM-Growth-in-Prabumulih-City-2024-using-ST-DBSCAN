# Clustering Analysis of UMKM Growth in Prabumulih City (2024) using ST-DBSCAN

## 👨‍💻 Team Members
- Abdurrahman Al-atsary
- Ahmad Zidan Wirawan
- Meinisa
- Rizki Adrian Bennovry
- Sarah Natalia Geraldine
- 
---

## 📱 **About the Project**

This project applies **ST-DBSCAN (Spatial-Temporal Density-Based Spatial Clustering of Applications with Noise)** to analyze the **growth patterns of Micro, Small, and Medium Enterprises (UMKM)** in **Prabumulih City, Indonesia (2024)**.  
The study explores how spatial-temporal clustering can provide insights into urban economic development and trade distribution.  

- **Key Finding**: Significant UMKM growth in **Prabumulih Utara** and **Prabumulih Timur** districts.  
- Peripheral regions such as **Camboi, Lembak, and Prabumulih Selatan**, initially classified as *noise*, show emerging business potential.  
- Results support **policy-making and resource allocation** for balanced city development.  

---

## 📋 Dataset

The dataset used in this study represents **UMKM point data in Prabumulih City** collected during **April–May 2024**.  
- Data was obtained using **Google Maps**, by retrieving the **latitude and longitude** of UMKM locations.  
- The dataset was then processed and analyzed with the **ST-DBSCAN algorithm** supported by **GIS tools**.  
- The process included:  
  - Selecting appropriate parameters for the algorithm.  
  - Applying the clustering model to the dataset.  
  - Interpreting the results to identify clustering patterns and dynamics of UMKM growth (whether increasing or decreasing) over time.  

---

## 🔎 Methodology

The clustering process followed 4 main stages:

1. **Data Preparation**  
   - Collected and cleaned UMKM records (location & temporal data).  

2. **Parameter Selection**  
   - Determined **ε (epsilon), MinPts, and temporal threshold** for ST-DBSCAN.  

3. **Clustering with ST-DBSCAN**  
   - Identified high-density regions and separated noise points.  

4. **Cluster Evaluation**  
   - Visualized clusters using maps & density plots.  
   - Interpreted results for regional economic development insights.  

---

## 🖥 Tools & Libraries

![RStudio](https://img.shields.io/badge/-RStudio-75AADB?style=flat&logo=rstudio&logoColor=white)   
![ST-DBSCAN](https://img.shields.io/badge/-STDBSCAN-FF6F00?style=flat&logo=python&logoColor=white)  
![Data Visualization](https://img.shields.io/badge/-Visualization-FF5733?style=flat&logo=r&logoColor=white)  
![QGIS](https://img.shields.io/badge/-QGIS-2E7D32?style=flat&logo=qgis&logoColor=white)  

---

## 📊 Results

- **Cluster Insights**:  
  - Prabumulih Utara & Timur: high-density UMKM clusters.  
  - Camboi, Lembak, Selatan: emerging clusters from noise points.  

- **Impact**:  
  - Provides **spatial-economic evidence** for UMKM development strategies.  
  - Supports **local government planning** for infrastructure & trade growth.  

✅ ST-DBSCAN proved effective in revealing both **established and emerging business hubs**.  

---

## 📈 Visual Insights

- **Heatmaps**: Showed dense concentration of UMKM in northern and eastern Prabumulih.  
- **Cluster Maps**: Visualized distinct clusters vs. noise points.  
- **Temporal Trends**: Identified new UMKM hotspots formed in 2024.  
