# DS108 - Data Preprocessing Course Labs

## 📋 Overview
This repository contains practical assignments for the **Data Preprocessing (DS108)** course, including 5 lab sessions covering various techniques and technologies in the field of data science.

## 🗂️ Directory Structure

### 📊 **Lab 1 (TH1) - Kernel Functions & Data Analysis**
**Description**: Practice with kernel functions and COVID-19 data analysis
- **Technologies Used**: 
  - `Python`, `Pandas`, `NumPy`, `Matplotlib`
- **Main Content**:
  - Implementation and visualization of kernel functions (Rectangular, Triangular, Parabolic, Biweight, Gaussian, Silverman)
  - COVID-19 data analysis: filtering by country, infection statistics over time
  - Creating comparison charts of COVID-19 trends between countries (Vietnam, Indonesia, Philippines)
- **Files**: 
  - `Kernel functions.ipynb` - Kernel functions implementation
  - `TH1.ipynb` - COVID-19 data analysis

### 🌐 **Lab 2 (TH2) - Web Scraping & API**
**Description**: Data collection from web and APIs
- **Technologies Used**:
  - `Python`, `Selenium`, `Requests`, `Pandas`, `Matplotlib`, `GSpread`
  - `Google Sheets API`, `OpenWeatherMap API`
- **Main Content**:
  - **Exercise 1**: Web scraping COVID-19 data from Worldometer using Selenium
  - **Exercise 2**: Collecting Ho Chi Minh City weather data via OpenWeatherMap API
  - **Exercise 3**: Working with Google Sheets API to analyze Japan COVID-19 data
- **Files**:
  - `Bai1/baitap1.ipynb` - Web scraping COVID data
  - `Bai2/baitap2.ipynb` - Weather API integration
  - `Bai3/baitap3.ipynb` - Google Sheets data analysis

### 🔄 **Lab 3 (TH3) - ETL Pipeline & Data Processing**
**Description**: Building ETL pipeline with Bronze-Silver-Gold architecture
- **Technologies Used**:
  - `Python`, `Pandas`, `Scikit-learn`, `Seaborn`, `Matplotlib`
  - `SQLAlchemy`, `MySQL Connector`
- **Main Content**:
  - **Bronze Layer**: Merging UCI HAR Dataset (train + test)
  - **Silver Layer**: Data cleaning, feature engineering, outlier removal, correlation analysis
  - **Gold Layer**: Feature aggregation, data standardization
  - Analysis of Human Activity Recognition dataset with 30 volunteers
- **Dataset**: UCI HAR Dataset (accelerometer & gyroscope data)
- **Files**: `TH3.ipynb`, `tidy_data.csv`

### 🤖 **Lab 4 (TH4) - Machine Learning Models**
**Description**: Building and optimizing machine learning models
- **Technologies Used**:
  - `Python`, `Scikit-learn`, `XGBoost`, `CatBoost`, `LightGBM`
  - `Optuna` (hyperparameter optimization)
  - `Pandas`, `NumPy`, `Matplotlib`
- **Main Content**:
  - Data preprocessing with variable types: nominal, ordinal, discrete
  - Building multiple ML models: CatBoost, LightGBM, XGBoost
  - Hyperparameter tuning with Optuna
  - Model evaluation and feature engineering
- **Files**: 
  - `Model.ipynb` - Main machine learning models
  - `PreprocessPILOT.ipynb` - Data preprocessing
  - `ReprocessData.ipynb` - Data reprocessing
  - `full.ipynb` - Complete pipeline

### 📏 **Lab 5 (TH5) - Statistical Evaluation**
**Description**: Statistical evaluation with Cohen's Kappa
- **Technologies Used**:
  - `Python`, `Scikit-learn`, `JSON`
- **Main Content**:
  - Computing Cohen's Kappa score to measure inter-rater reliability
  - Processing qualitative data from JSONL files
- **Files**: 
  - `Kappa.ipynb` - Cohen's Kappa calculation
  - `23520262_NguyenTienDat_lab5.pdf` - Lab report

## 🛠️ Technologies & Libraries

### Core Technologies
- **Python 3.x** - Main programming language
- **Jupyter Notebook** - Development environment

### Data Processing & Analysis
- **Pandas** - Data manipulation and analysis
- **NumPy** - Scientific computing
- **Scikit-learn** - Machine learning

### Visualization
- **Matplotlib** - Basic plotting
- **Seaborn** - Statistical visualization

### Web Scraping & APIs
- **Selenium** - Automated web scraping
- **Requests** - HTTP requests
- **GSpread** - Google Sheets API
- **Google OAuth2** - Authentication

### Machine Learning
- **XGBoost** - Gradient boosting
- **CatBoost** - Categorical boosting
- **LightGBM** - Light gradient boosting
- **Optuna** - Hyperparameter optimization

### Database & Storage
- **SQLAlchemy** - SQL toolkit
- **MySQL Connector** - Database connectivity

## 📊 Datasets

1. **COVID-19 Data**
   - Source: Worldometer, Google Sheets
   - Countries: Vietnam, Indonesia, Philippines, China, Japan

2. **UCI HAR Dataset**
   - 30 volunteers, age 19-48
   - 6 activities: WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING
   - Accelerometer & Gyroscope data at 50Hz

3. **Weather Data**
   - Source: OpenWeatherMap API
   - Location: Ho Chi Minh City (ZIP: 70000)

4. **Supply Chain Data**
   - Business logistics and delivery prediction
   - Multiple categorical and numerical features

## 🚀 Skills Learned

- **Data Collection**: Web scraping, API integration, database connection
- **Data Preprocessing**: Cleaning, transformation, feature engineering
- **ETL Pipeline**: Bronze-Silver-Gold architecture
- **Statistical Analysis**: Correlation analysis, outlier detection
- **Machine Learning**: Model building, hyperparameter tuning, evaluation
- **Visualization**: Chart creation, data storytelling
- **Evaluation Metrics**: Cohen's Kappa, classification metrics

## 📝 How to Use

1. Clone repository
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   pip install selenium requests gspread google-auth
   pip install xgboost catboost lightgbm optuna
   ```
3. Run notebooks sequentially from Lab 1 → Lab 5

## 👤 Author
**Nguyen Tien Dat - 23520262**  
Course: DS108 - Data Preprocessing  
University: [University Name]

---
*This repository demonstrates the learning journey from basic to advanced concepts in Data Science and Machine Learning.*
