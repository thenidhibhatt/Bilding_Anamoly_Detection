# Building_Anamoly_Detection
AI-powered energy intelligence system for smart buildings. Uses multi-model anomaly detection with ensemble learning, explainable AI reasoning, and risk prioritization to detect abnormal energy usage and translate insights into actionable business decisions and ROI impact
# AI Energy Intelligence Platform  
### Explainable Anomaly Detection & Decision Intelligence for Smart Buildings

An end-to-end **AI-powered energy intelligence system** that detects abnormal energy consumption patterns in smart buildings and converts machine learning outputs into **explainable, actionable business decisions**.

Unlike traditional anomaly detection projects, this system goes beyond detection to provide **AI reasoning, risk escalation analysis, priority scoring, and ROI-driven insights** through an interactive dashboard.

---

##  Problem Statement

Smart buildings generate massive time-series energy data.  
Abnormal energy usage often indicates:
- Equipment faults
- Energy wastage
- Operational inefficiencies

Traditional monitoring systems either:
- Miss subtle anomalies, or  
- Detect anomalies without explaining *why* they occurred or *what to do next*.

This project addresses that gap by building an **Explainable AI (XAI) decision intelligence system**.

---

##  Solution Overview

The platform follows a complete AI pipeline:


---

##  Key Features

###  Multi-Model Anomaly Detection
- Isolation Forest  
- Local Outlier Factor (LOF)  
- Mahalanobis Distance (Robust Covariance)  
- Z-Score based statistical detection  
- Rule-based domain logic  

### Ensemble Intelligence
- Model voting to reduce false positives  
- Confidence score based on agreement strength  

###  Feature Engineering
- Rolling mean & standard deviation  
- Energy deviation from baseline  
- Lag features for temporal dependency  
- Energy shock detection  
- Stability index for volatility measurement  

###  Explainable AI (XAI)
- Clear explanation of *why* an anomaly was detected  
- Causal breakdown using deviation, persistence, and model agreement  

###  Risk & Severity Analysis
- Severity classification  
- Persistence-based risk escalation  
- AI-driven priority scoring  

###  Business Impact & ROI
- Energy loss estimation  
- High-risk building ranking  
- ROI simulation for anomaly resolution  

### Interactive Dashboard
- Built with **Streamlit**
- Clean, modern, presentation-ready UI
- Designed for both technical and non-technical stakeholders

---

##  Dashboard Preview

The dashboard provides:
- Executive KPIs
- Energy vs AI-expected baseline comparison
- Model-wise anomaly detection insights
- Explainable AI reasoning for anomalies
- Business impact and ROI visualization

---

##  Dataset

- Smart building energy time-series data  
- Multiple buildings with hourly energy measurements  
- Weather and contextual features (preprocessed)

> The processed dataset used by the dashboard is stored as `df_long.csv`.

---

##  Tech Stack

- **Python**
- **Pandas, NumPy**
- **Scikit-learn**
- **Matplotlib**
- **Streamlit**

---
