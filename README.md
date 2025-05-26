# 🚲 Bike Dock Saturation Prediction

## 🧠 Overview

In this project, I built a predictive model to identify saturation issues in a city-wide bike-sharing system. The goal was to help the company improve operational efficiency and user experience by forecasting when and where docks would become full.

---

## 🟡 Situation

The San Francisco bike-sharing system was experiencing frequent **dock saturation**, particularly during peak hours. This caused user frustration and operational bottlenecks.

## 🔴 Complication

The company lacked predictive tools to **anticipate saturation in advance**, making it difficult to proactively manage bike redistribution and maintain service quality.

## 🟢 Action

* Collected and preprocessed historical usage data enriched with **temporal** and **weather** features.
* Developed and validated a **Gradient Boosting Machine (GBM)** model to forecast dock saturation.
* Focused on minimizing **false negatives** to avoid missed opportunities for operational intervention.
* Analyzed **feature importance**, with **Hour of the day** emerging as the most impactful predictor.

## 🟢 Result

* Delivered a reliable model that supported **real-time operational decision-making**.
* Provided **actionable insights** for bike redistribution during peak usage windows.
* Improved **user satisfaction** by reducing occurrences of full docks and enhancing system reliability.

---

## 🛠 Tools & Techniques

* Python (pandas, scikit-learn, matplotlib)
* Gradient Boosting Machine (GBM)
* Feature Engineering (Temporal & Weather Data)
* Classification Metrics (Recall-focused)
* Model Validation & Feature Importance Analysis

---

## 📌 Key Insight

Predicting dock saturation requires **temporal awareness**, **hour of the day** proved to be the most powerful signal. By focusing on reducing false negatives, the model enabled **proactive redistribution strategies**, directly supporting a smoother user experience and more efficient operations.
