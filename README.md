# FIRE_CLASSIFICATION
AICTE - Fire Classification Weekly Project / Assignnment Submissions.

# MOTIVE
To detect the fire across India and claasify them into different levels and stages where mainly deforestation takes place.

# REFERENCES
.https://www.earthdata.nasa.gov/data/tools/firms
.https://firms.modaps.eosdis.nasa.gov/download/

# Classification of Fire Types in India Using MODIS Satellite Data (2021–2023)
India witnesses various types of fire incidents annually, including forest fires, agricultural burning, volcanic activity, and other thermal anomalies. Accurate identification of fire sources is crucial for timely disaster response, environmental monitoring, and resource management. The MODIS sensors aboard NASA’s Terra and Aqua satellites provide reliable, near real-time thermal anomaly data globally, including for India.
While the MODIS dataset includes rich geospatial and thermal parameters, the challenge lies in correctly classifying the type of fire event — whether it stems from vegetation, volcanoes, static land sources, or offshore sources — using satellite-captured features.

# Objective:
To develop a machine learning classification model that can accurately predict the type of fire using MODIS fire detection data for India from 2021 to 2023

# 🔥 MODIS Dataset Summary (India: 2021–2023) 

# 1📌 About MODIS:
The Moderate Resolution Imaging Spectroradiometer (MODIS) is a key NASA sensor aboard the Terra (launched 1999) and Aqua (launched 2002) satellites. It captures Earth observation data at a spatial resolution of 1 km, suitable for global fire monitoring and environmental studies.
MODIS data used in this project is sourced from NASA’s FIRMS (Fire Information for Resource Management System) and focuses on thermal anomalies and active fire detection.

# 2🛰️ Satellite Characteristics:
Terra satellite (EOS AM) captures morning overpasses.
Aqua satellite (EOS PM) captures afternoon overpasses.
MODIS provides 2–4 observations per day, especially in mid-latitudes like India.

# 3🔍 Fire Detection Mechanism:
MODIS uses contextual algorithms to detect thermal anomalies.
It evaluates each pixel using mid-infrared channels (Bands 21/22 for fire detection and 31 for surface temperature).
The pixel is marked as one of: missing, cloud, water, non-fire, fire, or unknown.

# 4⚠️ Note on Accuracy:
MODIS NRT (Near Real-Time) data may have slightly lower geolocation accuracy, particularly from Aqua satellite due to orbit estimation delays. Errors can occasionally reach several kilometers.

# 5✅ Use Cases for MODIS Fire Data:
Real-time wildfire alerts
Agricultural burn detection
Forest fire management
Hotspot pattern analysis in ecological studies

# Import Libraries
pip install numpy pandas matplotlib seaborn scikit-learn folium

# Data
"C:\Users\G RUBIKA\OneDrive\Documents\AICTE FIRE INTERNSHIP\modis_2021_India.csv"
"C:\Users\G RUBIKA\OneDrive\Documents\AICTE FIRE INTERNSHIP\modis_2022_India.csv"
"C:\Users\G RUBIKA\OneDrive\Documents\AICTE FIRE INTERNSHIP\modis_2023_India.csv"

# AUTHORS
@karankrishnang
email:- karankrishnang17@gmail.com
