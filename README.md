## 🦠 REACH of COVID-19 in India
### 📌 Overview

This project analyzes and visualizes the spread, impact, and vaccination trends of COVID-19 in India using Exploratory Data Analysis (EDA) and Machine Learning.


### 🎯 Objectives
```
Study state/district-wise COVID-19 spread

Evaluate recovery & mortality rates

Analyze vaccination progress

Predict vaccination trends with ML models
```

### 🧩 Datasets
```
covid_19_india (1).csv – State-wise cases

district_level_latest.csv – District-level stats

covid_vaccine_statewise.csv – Vaccination data
```


### 🧹 Preprocessing
```
Removed irrelevant columns & handled nulls

Corrected state names

Added computed metrics: Recovery, Mortality, Active Cases
```

### 📊 Analysis Highlights
```
State & district-wise case distribution

Time-series trends (1st & 2nd wave)

Gender & age-based vaccination insights

Vaccine type comparison (Covaxin vs Covishield)
```

### 🤖 Models Used

```
Model	Purpose
Linear Regression	Baseline trend prediction
Random Forest	High-accuracy ensemble model
Bayesian Ridge	Probabilistic, stable results
```

### 🧠 Key Insights
```
Maharashtra, Kerala, Karnataka → highest cases

Punjab → high mortality rate

A&N Islands → top recovery rate

18–44 age group → most vaccinated
```

### ⚙️ Tech Stack
```
Python, Pandas, NumPy, Matplotlib, Seaborn, Plotly, Scikit-learn
```

### 📁 Structure
```
📦 REACH-of-COVID-19
│── REACH of COVID-19.ipynb
│── covid_19_india (1).csv
│── district_level_latest.csv
│── covid_vaccine_statewise.csv
└── README.md

```

### 📈 Future Work
```
Real-time data via API
Interactive dashboard (Streamlit/Power BI)
```
