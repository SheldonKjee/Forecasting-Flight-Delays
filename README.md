# ✈️ Flight Delay Analysis and Prediction

**Author:** Sheldon Khongjee  
**GitHub:** [SheldonKjee/Forecasting-Flight-Delays](https://github.com/SheldonKjee/Forecasting-Flight-Delays)  
**Email:** sheldonkjee216@gmail.com

---

## 📌 Overview

This project analyzes and predicts flight delays in the United States using machine learning. It processes airline, airport, and flight datasets to identify delay patterns and build a predictive model.

**What it does:**
- Analyzes 5.8M flight records to understand delay patterns
- Compares performance across 14 major US airlines
- Visualizes geographic distribution of airports
- Builds ML model with 77.15% accuracy to predict delays

---

## 📊 Key Findings

### � Dataset Summary
- **Total Flights:** 5.8 Million records
- **Airlines:** 14 major US carriers
- **Airports:** 322 airports
- **Data Size:** 8.3 GB
- **Features:** 31 flight attributes

### ✈️ Airline Performance Ranking

| Rank | Airline | Code | Mean Delay |
|------|---------|------|-----------|
| 🥇 1 | Alaska Airlines | AS | -0.98 min (Early) |
| 🥈 2 | Delta Air Lines | DL | +0.19 min |
| 🥉 3 | Hawaiian Airlines | HA | +2.02 min |
| 4 | American Airlines | AA | +3.45 min |
| 5 | Southwest Airlines | WN | +4.37 min |
| ⚠️ Last | Spirit Air Lines | NK | +14.47 min |

**Key Insights:**
- Alaska Airlines is **the most reliable** with -0.98 min average (arrives EARLY)
- Spirit Airlines is **14x more delayed** than Alaska
- Performance gap: **15.45 minutes** between best and worst

### 🎯 Model Performance
- **Algorithm:** Logistic Regression
- **Accuracy:** **77.15%**
- **Classification:** Delayed (>15 min) vs On-Time
- **Train/Test Split:** 80/20

---

## 📈 Visualizations Generated

The analysis produces comprehensive visualizations from the inferred patterns:

### 1. **Distribution Analysis**
- Column-wise distribution plots across all 31 features
- Identifies skewed vs normal distributions
- Reveals data quality issues

### 2. **Correlation Heatmap**
- Shows relationships between delay factors:
  - Air System Delay vs Total Delay
  - Weather Impact on delays
  - Airline-specific delay patterns
  - Time-of-day effects

### 3. **Scatter Matrix**
- Multi-dimensional visualization of key variables
- Highlights outliers and patterns
- Shows feature interactions

### 4. **Airline Delay Comparison**
- Bar charts of mean arrival delays per airline
- Shows best vs worst performing carriers
- Visual comparison of delay magnitudes

### 5. **Delay Type Breakdown**
- Visualizes delay causes:
  - 🌦️ Weather delays
  - ⚙️ Airline delays
  - 🛩️ Late aircraft delays
  - 🔒 Security delays
  - ✈️ Air system delays

### 6. **Geospatial Mapping**
- Airport locations plotted on US map
- Uses Cartopy with Robinson/Lambert projections
- Shows geographic distribution of delays

### 7. **Temporal Patterns**
- Delays by day of week
- Delays by month
- Peak delay hours identified

---

## 🚀 Quick Demo

### Run the Analysis
```bash
# Navigate to project directory
cd Forecasting-Flight-Delays

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter notebook
jupyter notebook DM.ipynb
```

### Expected Output
The notebook will generate:
✅ Statistical summaries of all 5.8M flights  
✅ 7+ high-quality visualizations  
✅ Correlation analysis between delay factors  
✅ Geospatial maps of US airports  
✅ Trained ML model with 77.15% accuracy  
✅ Delay predictions on test dataset

### Step-by-Step Workflow
1. **Load Data** → Airlines, Airports, Flights (5.8M records)
2. **Data Cleaning** → Handle missing values, convert types
3. **EDA** → Distributions, correlations, outliers
4. **Visualizations** → Generate 7+ plots
5. **Feature Engineering** → Prepare data for ML
6. **Model Training** → Logistic Regression
7. **Evaluation** → Test accuracy 77.15%

---

## 🛠️ Technology Stack

### 📚 Core Data Processing
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing and arrays
- **Scikit-learn** - Machine learning library

### 📊 Visualization Libraries
- **Matplotlib** - Base plotting library
- **Seaborn** - Statistical data visualization
- **Cartopy** - Geospatial/mapping tools
- **Mpl_toolkits** - 3D plotting extensions

### 🤖 Machine Learning Components
- **train_test_split** - Data splitting
- **StandardScaler** - Feature scaling
- **LabelEncoder** - Categorical encoding
- **SimpleImputer** - Missing value handling
- **LogisticRegression** - Classification model
- **accuracy_score** - Model evaluation

### 🐍 Language & Environment
- **Python 3.x** - Programming language
- **Jupyter Notebook** - Interactive environment
- **Pip** - Package management

---

## 📁 Project Structure

```
Forecasting-Flight-Delays/
├── DM.ipynb              # Main analysis notebook (All code + visualizations)
├── README.md             # This file
├── LICENSE               # Project license
└── Datasets/
    ├── flights.csv       # 5.8M flight records (31 columns)
    ├── airlines.csv      # 14 airline reference data
    └── airports.csv      # 322 airport reference data
```

### Dataset Features

| Category | Features |
|----------|----------|
| **Temporal** | Year, Month, Day, Day of Week |
| **Flight Info** | Flight Number, Tail Number, Airline |
| **Routing** | Origin, Destination, Distance |
| **Time Data** | Scheduled/Actual times, Durations |
| **Delays** | Air System, Security, Airline, Weather, Late Aircraft |

---

## 📈 Results Summary

### Analysis Results
✅ **5.8M flights analyzed** with complete EDA  
✅ **14 airlines ranked** by on-time performance  
✅ **7+ visualizations** from inference patterns  
✅ **Geospatial mapping** of 322 US airports  
✅ **Delay factors identified:** Airline, Weather, Time-of-day  

### Model Results
✅ **Logistic Regression** trained and evaluated  
✅ **77.15% accuracy** on test dataset  
✅ **Binary classification:** Delayed vs On-Time  
✅ **Feature importance** calculated  
✅ **Predictions** on new flights possible  

### Key Inferences
1. **Airline choice matters:** 15.45 min difference between best/worst
2. **Weather is significant:** Clear seasonal delay patterns
3. **Time patterns exist:** Peak delay hours identified
4. **Geographic factors:** Airport location affects delays
5. **ML effectiveness:** 77% accuracy shows predictability

---

## 📞 Contact

📧 **Email:** sheldonkjee216@gmail.com  
🔗 **GitHub:** https://github.com/SheldonKjee  
📱 **Repository:** https://github.com/SheldonKjee/Forecasting-Flight-Delays
