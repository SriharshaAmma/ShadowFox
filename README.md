<h1 align="center">📊 Data Visualization & Analysis with Python</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Level-Beginner_to_Advanced-success?style=flat-square" />
  <img src="https://img.shields.io/badge/Python-3.10+-blue.svg" />
  <img src="https://img.shields.io/badge/Libraries-Pandas%2C%20Matplotlib%2C%20Seaborn%2C%20Sklearn-informational" />
</p>

---

## 🧭 Table of Contents
- [🌟 Overview](#-overview)
- [📁 Project Structure](#-project-structure)
- [🟢 Beginner: ShadowFox Visualization Guide](libraryDocumentation.ipynb)
- [🟡 Intermediate: Delhi AQI Analysis](Air_Quality_Analysis.ipynbs)
- [🔴 Advanced: Cricket Fielding Performance](T20_Cricket_Perforance_Analysis.ipynb)
- [🛠️ Setup & Installation](#️-setup--installation)
- [📌 Future Enhancements](#-future-enhancements)
- [🙌 Credits](#-credits)

---

## 🌟 Overview

This repository is a **complete showcase of data storytelling using Python**. From mastering plots, to real-world air pollution data analysis, to match-by-match cricket fielding breakdowns — it's all here.

🎓 Ideal for:
- Students building projects  
- Analysts enhancing reports  
- Developers learning data visualization  
- Sports or environment enthusiasts

---

## 📁 Project Structure

📂 Python-Visualization-Projects/
├── Beginner-ShadowFox/
│ └── shadowfox_visuals.ipynb
├── Intermediate-DelhiAQI/
│ ├── delhi_aqi.csv
│ └── delhi_air_quality_analysis.ipynb
├── Advanced-CricketFielding/
│ ├── fielding_data.csv
│ └── cricket_fielding_analysis.ipynb
└── README.md

yaml
Copy
Edit

---

## 🟢 Beginner: ShadowFox Visualization Guide

📘 **Project Goal:** Master data visualization using **Matplotlib** and **Seaborn**

### 💡 Features:
- Side-by-side usage of `matplotlib` vs `seaborn`
- Charts included: Line, Bar, Pie, Scatter, Histogram, Boxplot, Heatmap, KDE
- Clean layout, reusable templates, and plotting tips

### 🎯 Ideal For:
- Newcomers to Python visualization
- Those making dashboards, reports, or Jupyter visuals

### 🖼️ Gallery Snippet:
✅ Line Plot | ✅ Pie Chart | ✅ KDE + Histogram
✅ Heatmap | ✅ Multi-line Comparison | ✅ Box Plot

yaml
Copy
Edit

---

## 🟡 Intermediate: Delhi AQI Analysis

🌆 **Project Goal:** Explore, visualize, and model Delhi's air quality using pollutant data

### 🔬 Analysis Flow:
1. Data cleaning: dates, nulls, seasons
2. EDA: seasonal pollutant boxplots, correlation heatmap
3. ML Modeling:
   - 🔹 Linear Regression
   - 🔹 Random Forest Regression
4. 🎯 Target: Predict PM2.5 with feature importance

### 📊 Visual Output:
- PM2.5 & NO₂ seasonal boxplots  
- Pollutant correlation matrix  
- Random Forest feature importance

### 📂 Output Files:
- `seasonal_averages.csv`  
- `regression_results.txt`  
- Graphs in `/output/graphs/`

---

## 🔴 Advanced: Cricket Fielding Performance

🏏 **Project Goal:** Analyze player-level fielding performance from a real T20 innings

### 📋 Dataset:
- `Player`, `Position`, `Pick`, `Throw`, `Runs` (saved/conceded)

### 📈 Metrics Calculated:
- ✅ Fielding Score per player
- ✅ Pick & Throw accuracy rates
- ✅ Runs saved vs conceded
- ✅ Player Efficiency Score
- ✅ Fielding Hotspot Map

### 🔥 Visuals Generated:
- Bar charts (fielding score)
- Heatmap (Pick vs Throw)
- Position activity map
- Radar chart (multi-metric for 3 players)

### 🧠 Objective:
Help coaches **identify top fielders** and optimize **on-field placements** using data.

---

## 🛠️ Setup & Installation

Make sure you have Python 3.10+ and the following libraries:

```bash
pip install pandas matplotlib seaborn scikit-learn tabulate numpy
To run:

Launch Jupyter Notebook or Google Colab

Open any .ipynb file and follow the markdown cells

📌 Future Enhancements
 Streamlit Dashboard for all projects

 Geo-visualization using folium for AQI

 Cricket radial field heatmap

 Live data pipeline for AQI using APIs

 Clustering-based pollution hotspot detection

🙌 Credits
Developer: Sriharsha Amma
Tech Used: Python, Pandas, Matplotlib, Seaborn, Scikit-learn
Data Sources:

AQI Data: CPCB, Kaggle

Fielding Data: Custom-recorded (ball-by-ball)

Visual Template: Custom-created for ShadowFox

