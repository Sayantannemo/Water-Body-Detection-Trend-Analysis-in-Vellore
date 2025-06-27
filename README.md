# Satellite-Based Water Body Detection and Trend Analysis in Vellore Using Deep Learning

This project uses deep learning and satellite imagery to detect water bodies in Vellore and analyze long-term seasonal and yearly water spread trends. The project is divided into two parts:

## 🔹 Part 1: Water Body Detection
- Built a U-Net deep learning model to detect water bodies from Sentinel-2 satellite images.
- Trained using 2841 satellite images and their NDWI-derived masks.
- Achieved an Intersection over Union (IoU) of **64%** and an accuracy of **74.10%** with a validation loss of **0.2522**.

## 🔹 Part 2: Water Body Trend Analysis
- Utilized month-wise water spread area data of Vellore from **Bhuvan (ISRO)**.
- Performed trend analysis to observe seasonal changes, water depletion during summers, and replenishment during monsoons.
- Tools like Pandas, Seaborn, and Matplotlib were used for visualization and decomposition.

## 📁 Contents
- `WaterBodyDetection/`: U-Net model training code, masks, and sample images.
- `TrendAnalysis/`: CSV data, Jupyter Notebooks, visualizations, and seasonal decomposition.
- `results/`: Final graphs and visual insights.

## 🛠️ Tech Stack
- Python, Keras, OpenCV, NumPy, Matplotlib, Scikit-learn
- Dataset: Sentinel-2 Images (Google Earth Engine), Bhuvan Water Spread Area

## 📊 Key Outcomes
- Robust detection of water bodies from satellite data.
- Insightful trend reporting for Vellore's water conditions (2012–2024).
- Seasonal patterns and drought-prone periods identified for resource planning.
