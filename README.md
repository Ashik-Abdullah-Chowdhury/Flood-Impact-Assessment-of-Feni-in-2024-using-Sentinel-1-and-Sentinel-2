# Flood-Impact-Assessment-of-Feni-in-2024-using-Sentinel-1-and-Sentinel-2
# **Flood Impact Analysis using Sentinel-1 and Sentinel-2**
## **Overview**
This project analyzes flood impact on different Land Use Land Cover (LULC) classes using satellite imagery and GIS techniques. The study focuses on identifying flooded areas and quantifying their impact across vegetation, agriculture, settlements, water bodies, and bare land.
## **Objectives**
*   Detect flood extent using satellite data
*   Analyze LULC-wise flood impact
*   Quantify affected area (km² and %)
*   Support disaster management and planning
## **Data Used**
* Sentinel-1 SAR (Flood detection)
* Sentinel-2 (LULC classification)
* SRTM DEM (Elevation data)

## **Methodology**
* Collected Sentinel-1 (SAR), Sentinel-2, and SRTM DEM data
* Preprocessed imagery (filtering, correction, cloud masking)
* Detected flood extent using SAR-based thresholding and change detection
* Classified LULC from Sentinel-2 imagery
* Overlaid flood map with LULC to calculate affected area
* Generated maps and summarized results
## **Methodological Flowchart**
<img width="734" height="841" alt="flood_mapping_GEE_workflow_1" src="https://github.com/user-attachments/assets/1dbb1f62-4b58-461d-90c6-d0bc5410e50c" /><br>
*Figure 1: Methodological Flowchart*
## **Sample Results**
### **Flood Extent**
* Permanent Water Area: 2.19 km²
* Flooded Area:  204.45 km²
### **Class-wise Flood Extent**

| LULC        |	Area (km²) | Flooded (km²) | % Impact |
|-------------|------------|---------------|----------|
| Vegetation  | 74.51      | 1.24          |1.66      |
| Agriculture | 129.16     | 4.03          |3.12      |
| Settlement  | 9.61       | 0.30          |3.43      |
| Bareland    | 10.36      | 0.52          |5.02      |

## **Tools & Technologies**
* Google Earth Engine
* QGIS

## **Outputs**
<img width="580" height="1007" alt="feni fw copy" src="https://github.com/user-attachments/assets/8de98491-1abd-4192-87b8-b85978569943" /><br>
*Figure 2: Flood Extent Map of Feni*

<img width="580" height="1007" alt="lulc feni" src="https://github.com/user-attachments/assets/6d2b5dee-dd45-44ea-b399-a8a5c35c7e63" /><br>
*Figure 3: LULC of Feni*

## **Author**
Ashik Abdullah<br>
B.Sc (Hons) in Forestry<br>
