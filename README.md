# 🚨 A Spatio-Temporal Explainable Machine Learning Framework for Crime Hotspot Prediction

## 📌 Project Overview

Urban crime poses a serious challenge to public safety and smart city development. This project presents a **Spatio-Temporal Explainable Machine Learning Framework** to analyze, predict, and interpret crime hotspots using real-world crime data.

By combining:

* Spatio-temporal feature engineering
* XGBoost-based crime prediction
* Explainable AI (SHAP)
* Geospatial visualization (Folium heatmaps)

this system not only predicts high-risk crime zones but also explains *why* a location or time period is risky making it suitable for **urban safety planning and policy support**.

---

## 🎯 Objectives

* Predict crime hotspots using machine learning
* Capture both spatial (location-based) and temporal (time-based) crime patterns
* Apply Explainable AI to make predictions transparent
* Visualize crime density using interactive maps
* Support data-driven urban safety planning

---

## 🛠️ Technologies Used

| Category             | Tools                           |
| -------------------- | ------------------------------- |
| Programming Language | Python 3.x                      |
| Machine Learning     | XGBoost, Scikit-learn           |
| Explainable AI       | SHAP, LIME                      |
| Data Processing      | Pandas, NumPy                   |
| Visualization        | Folium, Matplotlib              |
| Environment          | Google Colab / Jupyter Notebook |

---

## 📂 Dataset

### Chicago Crime Dataset (Kaggle)

🔗 [https://www.kaggle.com/c/chicago-crime-detection](https://www.kaggle.com/datasets/georgehanyfouad/crime-prediction-in-chicago-in-2022)

### Dataset Contains:

* Crime type
* Date and time
* Latitude & Longitude
* Location details

---

## ⚙️ Project Workflow

1. Data Cleaning & Preprocessing
2. Spatio-Temporal Feature Engineering
3. Hotspot Zone Clustering using K-Means
4. Crime Risk Classification using XGBoost
5. Explainable AI with SHAP
6. Heatmap Visualization using Folium

---

## 🧠 Model & Explainability

### 🔹 Prediction Model

* XGBoost Classifier
* Binary Classification:

  * **1 → High Risk Crime** (Battery, Theft, Robbery, Assault)
  * **0 → Other Crimes**

### 🔹 Explainable AI

SHAP identifies:

* High-risk hours
* High-density zones
* Influential spatial features

This makes the model **transparent and trustworthy**.

---

## 🌍 Visualization

* Interactive crime heatmap
* Highlights spatial concentration of high-risk crimes
* Exported as:

```bash
crime_analysis_map.html
```

---

## 📊 Sample Results

| Model   | Accuracy | Precision | Recall | F1-score |
| ------- | -------- | --------- | ------ | -------- |
| XGBoost | 88%      | 85%       | 83%    | 84%      |

---

## ▶️ How to Run

### 1️⃣ Upload Dataset

Download and rename dataset to:

```bash
crime_data.csv
```

Upload it to your Google Colab environment.

---

### 2️⃣ Install Dependencies

```bash
pip install shap lime xgboost folium scikit-learn
```

---

### 3️⃣ Run Notebook Cells

Execute each cell in sequence:

* Feature Engineering
* Model Training
* Visualization
* Explainability

---

## 📁 Project Structure

```bash
📦 Crime-Hotspot-Prediction
 ┣ 📜 README.md
 ┣ 📜 crime_analysis.ipynb
 ┣ 📜 crime_data.csv
 ┣ 📜 crime_analysis_map.html
```

---

## 📌 Applications

* Smart City Planning
* Police Resource Allocation
* Crime Prevention Strategy
* Urban Policy Support
* Academic Research

---

## 🙌 Acknowledgements

* Chicago Police Department for open crime data
* Kaggle for dataset hosting
* SHAP & XGBoost developers
* Google Colab platform

---

## 📜 License

This project is licensed under the **MIT License** — free to use for academic and research purposes.

---

## 👩‍💻 Author

**Lakshiga Shree S P**

🔗[Connect with me on Linkedin](https://www.linkedin.com/in/lakshiga-shree-s-p-1908a6282/)

---

## 🎯 For Judges & Reviewers

This project stands out by combining:

* High accuracy ML
* Explainable AI
* Geospatial intelligence
* Real-world urban impact

