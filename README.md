# Flight Delay Analysis and Prediction

**Author:** Sheldon Khongjee  
**GitHub:** [SheldonKjee/Forecasting-Flight-Delays](https://github.com/SheldonKjee/Forecasting-Flight-Delays)  
**Email:** sheldonkjee216@gmail.com

---

## Overview

This project analyzes and predicts flight delays in the United States using machine learning. It processes airline, airport, and flight datasets to identify delay patterns and build a predictive model.

---

## Key Findings

### 📊 Dataset Summary
- **Total Flights:** 5.8 Million records
- **Airlines:** 14 major US carriers
- **Airports:** 322 airports
- **Data Size:** 8.3 GB

### ✈️ Mean Arrival Delays by Airline (Minutes)

| Rank | Airline | Code | Mean Delay |
|------|---------|------|-----------|
| 1 | Alaska Airlines | AS | -0.98 (Early) |
| 2 | Delta Air Lines | DL | +0.19 |
| 3 | Hawaiian Airlines | HA | +2.02 |
| 4 | American Airlines | AA | +3.45 |
| 5 | Spirit Air Lines | NK | +14.47 (Most Delayed) |

**Key Insight:** Spirit Airlines has the worst on-time performance (+14.47 min), while Alaska Airlines consistently arrives early (-0.98 min).

### 🎯 Model Performance
- **Algorithm:** Logistic Regression
- **Accuracy:** **77.15%**
- **Prediction:** Binary classification (Delayed vs On-Time)

---

## What the Model Does

The system predicts whether a flight will be delayed (>15 minutes) based on:
- Scheduled departure time
- Distance traveled
- Airline carrier
- Origin and destination airports
- Day of week

---

## Dataset Features

| Category | Features |
|----------|----------|
| **Temporal** | Year, Month, Day, Day of Week |
| **Flight Info** | Flight Number, Tail Number, Aircraft Type |
| **Routing** | Origin Airport, Destination Airport, Distance |
| **Delays** | Air System, Security, Airline, Weather, Late Aircraft |

---

## Technology Stack

- **Python** - Core language
- **Pandas & NumPy** - Data processing
- **Scikit-learn** - Machine learning
- **Matplotlib & Seaborn** - Visualizations
- **Cartopy** - Geographic mapping

---

## Quick Start

### Install Requirements
```bash
pip install pandas numpy matplotlib seaborn scikit-learn cartopy
```

### Run Analysis
```bash
jupyter notebook DM.ipynb
```

### Files
- `DM.ipynb` - Complete analysis and modeling notebook
- `Datasets/` - Flight, airline, and airport data files

---

## Analysis Components

1. **Data Exploration** - Dataset structure, missing values, distributions
2. **Visualizations** - Delay patterns, airline comparisons, geographic plots
3. **Correlation Analysis** - Feature relationships and delay factors
4. **Geospatial Mapping** - Airport locations on US map
5. **Predictive Modeling** - Logistic Regression for delay prediction

---

## Results Summary

✅ **Successfully analyzed 5.8M flight records**  
✅ **Identified top delay factors and airlines**  
✅ **Built model with 77.15% accuracy**  
✅ **Created visualizations of delay patterns**  
✅ **Mapped geographic distribution of airports**

---

## Contact

📧 Email: sheldonkjee216@gmail.com  
🔗 GitHub: https://github.com/SheldonKjee
