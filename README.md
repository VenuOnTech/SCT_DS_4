# 🚗 US Accidents Dataset — Scalable EDA & Geospatial Insights

This project was completed as part of my final task during the **SkillCraft Technologies Internship**. The dataset used contains over **3 million+ accident records in the US** (3+ GB in size) sourced from Kaggle.

---

## 📦 Dataset
- **Source:** [US Accidents (Kaggle)](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents)
- **Size:** 3.5+ GB
- **Records:** 3.2 million+
- **Features:** Over 47 columns including location, time, weather, severity, and road conditions.

---

## 🧠 Objectives
- Efficiently handle large datasets in **Google Colab** using chunking.
- Perform detailed **Exploratory Data Analysis (EDA)**.
- Create **interactive heatmaps** of accident hotspots for the top 10 cities.
- Analyze key factors contributing to accident severity (weather, time, location).

---

## 📌 Key Features
- ✅ **Memory-Efficient Data Loading** using `pandas.read_csv()` with `chunksize`
- 🔍 Feature engineering: Hour, Month, Year, Day/Night, Weekend indicators
- 📊 EDA using **Seaborn** and **Matplotlib**
- 🌎 **Folium Heatmaps** for top 10 most accident-prone US cities
- 🧼 Cleaned and saved dataset for downstream tasks

---

## 📊 Visual Insights

- Top accident cities  
- Accidents by hour, day, and severity  
- Severity vs temperature and visibility  
- Impact of road features like crossings, junctions, signals  
- Weather condition breakdown by severity  
- Correlation heatmaps  
- Folium-based interactive heatmaps

---

## 📂 Project Structure
  
├── heatmaps/  
│ ├── Los_Angeles_heatmap.html  
│ ├── Houston_heatmap.html  
│ ├── Miami_heatmap.html  
│ ├── Orlando_heatmap.html  
│ ├── Dallas_heatmap.html  
│ ├── Charlotte_heatmap.html  
│ ├── Raleigh_heatmap.html  
│ ├── Nashville_heatmap.html  
│ ├── Baton_Rouge_heatmap.html  
│ └── Sacramento_heatmap.html  
├── US_Accidents_Analysis.ipynb  
└── README.md  


---

## 💡 How to Use
1. Clone the repository  
2. Run the notebook in **Google Colab**  
3. Upload your Kaggle `kaggle.json` API key  
4. Run the full pipeline for analysis and visualization  

---

## ✅ Tech Stack

- Python 🐍
- Pandas, NumPy
- Matplotlib, Seaborn
- Folium + Leaflet.js
- Google Colab
- Kaggle Datasets

---

## 📌 Final Note

This project gave me hands-on experience with **big data handling**, **visual storytelling**, and **geospatial mapping** using Python. A great finale to my internship at **SkillCraft Technologies**!

---

## 🔗 Connect
- 💼 [LinkedIn](https://www.linkedin.com/)

