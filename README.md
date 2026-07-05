# Data-Preprocessing-Final

# Customer Purchase Propensity Data Cleaning and Feature Engineering Pipeline

## Project Overview

This project demonstrates a complete Data Cleaning and Feature Engineering pipeline for Customer Purchase Propensity Analysis. The objective is to collect data from multiple sources, clean and preprocess the data, perform exploratory data analysis, engineer useful features, and prepare the dataset for future machine learning applications.

The project follows industry-standard data preprocessing practices using Python and Scikit-learn.

---

# Project Objectives

- Import data from multiple data sources.
- Merge datasets into a unified dataset.
- Perform Exploratory Data Analysis (EDA).
- Handle missing values.
- Detect and treat outliers.
- Process date and mixed variables.
- Encode categorical variables.
- Scale numerical features.
- Perform feature engineering.
- Export a machine-learning-ready dataset.

---

# Dataset Sources

The project uses the following datasets:

| Dataset | Description |
|---------|-------------|
| customers.csv | Customer information |
| transactions.json | Customer transaction details |
| products.sql | Product information |
| DummyJSON API | Additional customer information |

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SQLite
- Requests
- Google Colab
- GitHub

---

# Project Structure

```
Customer-Purchase-Propensity/
│
├── customers.csv
├── transactions.json
├── products.sql
├── Data_Preprocessing.ipynb
├── processed_customer_data.csv
├── feature_pipeline.pkl
├── README.md
```

---

# Project Workflow

```
Raw Data
│
├── CSV
├── JSON
├── SQL Database
└── REST API
        │
        ▼
Data Import
        │
        ▼
Data Integration
        │
        ▼
Data Cleaning
        │
        ▼
Missing Value Handling
        │
        ▼
Outlier Detection and Treatment
        │
        ▼
Date and Mixed Variable Processing
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Categorical Encoding
        │
        ▼
Feature Scaling
        │
        ▼
Feature Engineering
        │
        ▼
Processed Dataset
        │
        ▼
Ready for Machine Learning
```

---

# Data Import

Data was imported from multiple sources using appropriate Python libraries.

- CSV using Pandas
- JSON using Pandas
- SQL Database using SQLite
- REST API using Requests

---

# Data Integration

The imported datasets were merged using common identifiers such as:

- customer_id
- product_id

This created a single integrated dataset for analysis.

---

# Exploratory Data Analysis

Several visualization techniques were used to understand the dataset.

- Histogram
- Box Plot
- Count Plot
- Scatter Plot
- Pair Plot
- Correlation Heatmap
- Violin Plot

EDA helped identify:

- Data distribution
- Missing values
- Outliers
- Relationships among variables
- Customer purchasing patterns

---

# Missing Value Handling

Different imputation techniques were applied to handle missing values.

- Mean Imputation
- Median Imputation
- Mode Imputation
- Random Sample Imputation
- KNN Imputation
- MICE Imputation
- Complete Case Analysis

These techniques improved data quality and prevented information loss.

---

# Outlier Detection

The following methods were implemented.

- Z-Score Method
- Interquartile Range (IQR)
- Percentile Method
- Winsorization

Outlier treatment reduced the effect of extreme values.

---

# Date and Mixed Variable Processing

Date columns were converted into datetime format.

New features were created, including:

- Days Since Signup
- Days Since Last Purchase
- Signup Year
- Signup Month

Mixed variables such as customer IDs were converted into machine-readable formats.

---

# Categorical Encoding

Categorical variables were converted into numerical values using:

- Label Encoding
- One-Hot Encoding
- Ordinal Encoding
- Numerical Feature Binning

Encoding makes categorical variables suitable for machine learning algorithms.

---

# Feature Scaling

The following scaling techniques were applied.

- StandardScaler
- MinMaxScaler
- RobustScaler
- MaxAbsScaler
- Normalizer
- ColumnTransformer

Scaling ensures that numerical features are on comparable scales.

---

# Feature Engineering

New features were created to improve predictive performance.

Examples include:

- Purchase Per Day
- Average Purchase Amount
- Income Log Transformation
- Square Root Transformation
- Reciprocal Transformation
- Box-Cox Transformation
- Yeo-Johnson Transformation
- Income Groups
- Frequent Buyer Indicator

These engineered features capture additional business insights.

---

# Project Output

The final processed dataset generated is:

```
processed_customer_data.csv
```

The dataset is:

- Clean
- Integrated
- Feature Engineered
- Ready for Machine Learning

---

# Future Scope

The project can be extended by:

- Building customer purchase prediction models
- Customer segmentation using clustering
- Recommendation systems
- Business dashboards using Power BI or Tableau
- Real-time prediction APIs
- Cloud deployment
- Automated preprocessing pipelines

---

# Learning Outcomes

This project demonstrates practical implementation of:

- Data Collection
- Data Integration
- Data Cleaning
- Missing Value Handling
- Outlier Detection
- Exploratory Data Analysis
- Feature Engineering
- Feature Scaling
- Data Transformation
- Machine Learning Data Preparation

---

# Conclusion

A complete Data Cleaning and Feature Engineering pipeline was successfully developed using Python and Scikit-learn.

The project integrates data from multiple sources, preprocesses the data using industry-standard techniques, performs feature engineering, and prepares a high-quality dataset for machine learning. The final processed dataset provides a strong foundation for predictive analytics and customer purchase propensity modeling.

---

# Author

Swarna Pathak

Data Analytics and Machine Learning Project

Xrademy Data Science Program
