# Colorado Crash Data Modeling and Analysis 🚗📊

This project explores traffic accident patterns across Colorado from 2007 to 2022 using machine learning models. Leveraging a dataset of over 1.6 million incidents provided by the Colorado Department of Transportation (CDOT), we analyze correlations between factors like weather, lighting, road conditions, and time of day—and apply predictive modeling techniques to understand accident severity and trends.

## 📌 Project Overview

- **Goal:** Identify patterns in traffic accident data and evaluate the predictive power of four machine learning models: ID3, Random Forest, Naïve Bayes, and Logistic Regression.
- **Motivation:** Despite a decrease in total accidents, traffic fatalities in the U.S. have risen. This study aims to provide actionable insights for prevention strategies.
- **Scope:** Focused on the state of Colorado, a diverse region with urban, rural, and mountainous terrain contributing to varied crash conditions.

## 📊 Dataset Summary

- **Source:** Colorado Department of Transportation (CDOT)
- **Years Covered:** 2007–2022
- **Total Records:** 1,627,682 incidents
- **Features:** Up to 84 attributes per incident (e.g., weather, lighting, location, severity, driver demographics)

## 🧠 Modeling Techniques

We implemented and compared the performance of:
- **ID3 (Decision Tree)**
- **Random Forest**
- **Naïve Bayes**
- **Logistic Regression**

Each model was evaluated using accuracy metrics and classification reports. ID3 and Random Forest showed the highest performance, with ID3 achieving up to **99.95% accuracy** on structured subsets of data.

## 🔧 Tools and Libraries

- Python 3.x
- Pandas, NumPy – Data handling
- Scikit-learn – Modeling
- Matplotlib, Seaborn – Visualization
- Jupyter Notebooks – Development and analysis

## 📈 Key Findings

- **Weather:** Surprisingly, most accidents occurred during clear weather, indicating human error as a primary cause.
- **Time of Day:** Daylight hours saw the highest accident frequency.
- **Age Demographics:** Drivers aged 25–35 were more prone to incidents than younger groups.
- **Model Accuracy:** Random Forest and ID3 outperformed other models in capturing accident severity patterns.

## 🗺️ Visualizations

We created intuitive visualizations including:
- Correlation heatmaps
- Accident severity by region, time, and weather
- Temporal trends across months/days
- Pairplots and histograms for demographic breakdowns

## 💡 Future Work

- Incorporating real-time traffic and weather data
- Geographic clustering of accident hotspots
- Expanding to additional states or national scale
- Hyperparameter tuning and ensemble model stacking

## 👨‍💻 Team Members

- **Saurav Avinash Changde** – Literature review, modeling evaluation  
- **Sai Srikar Emani** – Model development and codebase  
- **Kurt Cushman** – Data preprocessing and statistical analysis  
- **Harshitha Sai Addepalli** – Visualization and experiment design  

## 📁 Structure

```bash
├── data/                    # Raw and cleaned datasets
├── notebooks/               # Jupyter notebooks for EDA and modeling
├── src/                     # Python scripts for model training and preprocessing
├── visuals/                 # Generated plots and charts
├── README.md
└── requirements.txt         # Python dependencies
