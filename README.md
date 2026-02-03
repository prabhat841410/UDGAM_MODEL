# AI-Based Flood Prediction & Disaster Preparedness System for Assam

## Overview
This project is an **AI-powered flood prediction and preparedness system** designed specifically for **flood-prone regions of Assam**.  
The system uses **Machine Learning** to analyze historical flood data and predict **early flood risk (12–24 hours in advance)**.  
These predictions can be used to support **early warnings, preparedness planning, and disaster education**, especially for schools and institutions.

---

## Problem Statement
Assam experiences frequent and severe floods every year, causing loss of life, displacement, and disruption of daily activities.  
Most warning systems provide alerts only **1–3 hours before flooding**, which is often too late for effective evacuation and preparedness.  
Additionally, there is a lack of localized, data-driven tools to support early decision-making and preparedness.

---

## Solution
We propose a **Machine Learning–based flood prediction system** that:

- Learns flood patterns from **historical Assam flood data**
- Predicts **flood intensity** (Low / Medium / High / Extreme)
- Provides **early risk assessment** instead of last-minute alerts
- Can be integrated with **digital dashboards, alerts, and preparedness drills**

**Key Idea:**  
> Predict floods early and enable preparedness before the situation becomes critical.

---

## How It Works
1. Historical flood-related data (water level, soil moisture, danger level, etc.) is collected
2. Data is cleaned and feature-engineered (e.g., difference in water level)
3. A Machine Learning model is trained on **past years**
4. The model is tested on **future years** to validate prediction ability
5. New data (real or simulated sensor values) is used for flood risk prediction

---

## Machine Learning Details
- **Model Used:** Random Forest Classifier  
- **Input Features:**  
  - Difference in water level  
  - Soil moisture percentage  
- **Output:** Flood intensity (Low / Medium / High / Extreme)
- **Validation Method:** Time-based split (train on older years, test on recent years)

---

## Technologies Used
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Google Colab / Jupyter Notebook  
- (Optional) IoT sensors for real-time data input

---

## Impact
- Enables **12–24 hour early flood risk prediction**
- Supports disaster preparedness and planning
- Reduces panic by providing early insights
- Can be extended for **schools, communities, and local authorities**
- Scalable to other flood-prone regions

---

## Future Scope
- Real-time sensor integration (river level, rainfall, soil moisture)
- Web or mobile dashboard for alerts
- Disaster preparedness modules for schools
- Expansion to other disasters like landslides and cyclones
- Collaboration with disaster management authorities

---

## Team
Developed as part of a collaborative team project for a national-level hackathon, focusing on **AI for social impact**.

---

## License
This project is intended for educational, research, and prototype purposes.
