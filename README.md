
# Flood-Impact-Muzaffargarh-Multan-Region
Multi-index flood mapping using Sentinel-2 imagery, ERDAS Imagine, and ArcGIS for post-flood assessment in the Muzaffargarh–Multan Region ,Pakistan.
**The primary goals of this analysis were:**

To acquire and pre-process pre-flood (2025-08-20) and post-flood (2025-09-01) Sentinel-2 satellite imagery.


To apply spectral water indices (NDWI and MNDWI) to delineate flood-inundated areas.

To quantify the total inundated area in hectares.

To assess the flood's impact on vegetation (using NDVI) and built-up areas (using NDBI).
**Study Area**
The study area is the Muzaffargarh-Multan region along the River Chenab in Punjab, Pakistan. This area is a flat alluvial floodplain, highly prone to seasonal inundation, and was severely affected by the 30 August 2025 flood event.
**Data & Software
Data**
Satellite: Sentinel-2 L2A (Level-2A) Surface Reflectance 
Acquisition Portal: Google Earth Engine (GEE) 

**Imagery Dates:**
Pre-Flood: 2025-08-20 
Post-Flood: 2025-09-01 
Resolution: 10m 

**Software**
Google Earth Engine (GEE): Used for data acquisition, filtering, cloud masking, and clipping to the Area of Interest (AOI).
ERDAS IMAGINE: Used for calculating spectral indices via Model Maker and performing the final flood extent calculation.
ArcMap: Used for final map layout, classification, and symbology.

**Methodology**
The analysis was conducted using a spectral index approach to compare the pre-flood and post-flood landscapes. The core of the methodology involved calculating four key indices from the Sentinel-2 bands.

**Spectral Indices** 
Normalized Difference Vegetation Index (NDVI)
Purpose: To assess vegetation health and density17.

Normalized Difference Water Index (NDWI):
Purpose: To enhance and detect open water features.

Modified Normalized Difference Water Index (MNDWI):
Purpose: To improve water detection and minimize confusion with built-up land or soil, which is a common issue with NDWI.

Normalized Difference Built-up Index (NDBI):
Purpose: To identify built-up and urban areas.


**Key Results**
The analysis successfully quantified the extent of the flood and its impact on the surrounding land cover.
Total Flooded Area: The total newly inundated area within the AOI was calculated to be 4938.47 Hectares (or 12,202.95 Acres).

Vegetation Impact (NDVI): The NDVI Change Map (Pre vs. Post) showed significant vegetation loss and stress concentrated within the Chenab River's floodplain, confirming major damage to agricultural lands.

Water Delineation (MNDWI): The MNDWI provided a more accurate and clearer delineation of floodwater compared to the standard NDWI, especially in mixed agricultural and semi-urban zones.

Built-up Area (NDBI): The NDBI analysis, when overlaid with the flood extent, identified several settlements and infrastructure components vulnerable to or impacted by the floodwaters.

