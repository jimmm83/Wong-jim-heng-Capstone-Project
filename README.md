# Capstone-Project
EuroControl - En-Route ATFM Delay Analysis (2016–2024)

![img_text](https://github.com/jimmm83/Wong-jim-heng-Capstone-Project/blob/main/eurocontrol_members.jpg)

*Eurocontrol Members State*

## Overview

This project analyzes **En-Route Air Traffic Flow Management (ATFM) delays** across Eurocontrol’s network from **2016 to 2024**. Using Python-based data analysis and visualization, it identifies **trends, seasonal patterns, delay causes, and country-level impacts**.

The goal is to better understand **when, where, and why en-route delays occur** and provide insights for operational improvements by Eurocontrol and airlines.

---

## What is ATFM?

**Air Traffic Flow Management (ATFM)** is the process of balancing air traffic demand with available capacity to ensure safe and efficient flight operations.
In this context, **en-route ATFM delays** are delays that occur during the airborne phase of a flight due to constraints like ATC capacity, weather, or airspace restrictions.

---

## Features

* **Trend & Seasonality Analysis** – Yearly/monthly delay patterns
* **Cause Attribution** – Ranking top delay causes per country and year
* **Visualizations** – Academic-style charts using Matplotlib & Seaborn
* **Predictive Modeling** – Decision Tree, Random Forest models on delay factors
* **Recommendations** – Strategies for delay reduction in Eurocontrol’s airspace

---

## Technologies Used

* **Python** (pandas, matplotlib, seaborn, scikit-learn)
* **Jupyter Notebook**
* **Excel Dataset** from Eurocontrol (processed under DATA sheet)

---

## Repository Structure

```
├── data/
│   └── En-Route_ATFM_Delay_FIR_projectdataset.xlsx
├── notebooks/
│   └── Capstone.ipynb
├── images/
│   └── charts & visualizations
├── README.md
```

---

## Key Insights

* Clear **seasonal peaks** in delays during summer months
* **ATC Capacity** and **Weather** remain top delay causes
* Some countries show **shifting delay patterns** post-COVID
* Predictive models indicate **operational & environmental factors** are significant

---

## Future Work

* Expand modeling with **time-series forecasting**
* Integrate **real-time weather data** for improved predictions
* Explore **cost impact** of delays for airlines

---

