# 📊 XAI Exercise 5 – Model-Agnostic Methods: Partial Dependency Plots (PDP)

This repository contains the solution to **Exercise 5** from the Explainable Artificial Intelligence (XAI) course, focused on **model-agnostic methods** using **Partial Dependency Plots (PDP)**.

## 🧠 Objective

Apply PDP techniques to two regression problems:
1. **Bike rental prediction**
2. **House price prediction**

We explore how different features influence model predictions by visualizing marginal effects learned by a Random Forest regressor.

## 🧪 Exercises Overview

### 1️⃣ One-Dimensional PDP – Bike Rentals
- Model: Random Forest
- Target: `cnt` (bike count)
- Features: `days_since_2011`, `temperature`, `humidity`, `wind speed`
- Goal: Analyze each feature's impact on the predicted bike rentals.

### 2️⃣ Two-Dimensional PDP – Bike Rentals
- Model: Random Forest
- Target: `cnt`
- Features: `temperature` vs `humidity`
- Goal: Visualize and interpret the joint impact using a 2D plot (`geom_tile()`).

### 3️⃣ PDP – House Prices
- Dataset: `kc_house_data.csv`
- Model: Random Forest
- Target: `price`
- Features: `bedrooms`, `bathrooms`, `sqft_living`, `sqft_lot`, `floors`, `yr_built`
- Goal: Analyze the partial effect of selected features on predicted house prices.

> ⚠️ **Note:** All exercises include sampling from the database (BBDD) to improve performance during PDP generation.