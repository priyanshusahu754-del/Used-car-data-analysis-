# 🚗 Used Cars Market Analysis | Exploratory Data Analysis (EDA)

<p align="center">

### **Unlocking Market Trends & Pricing Insights from Used Car Data**

*Python • Pandas • NumPy • Matplotlib • Seaborn • Data Cleaning • Feature Engineering • Business Insights*

</p>

---

## 📖 Project Overview

The used car market is highly dynamic, with vehicle prices influenced by factors such as age, mileage, fuel type, transmission, and brand reputation. Before any predictive modeling can be performed, the dataset must be cleaned and analyzed to ensure reliable insights.

This project presents a complete **Exploratory Data Analysis (EDA)** pipeline on a Used Cars dataset, focusing on identifying data quality issues, performing feature engineering, cleaning inconsistencies, handling outliers, and extracting actionable business insights through visual analysis.

The project follows a real-world data analytics workflow from raw data to business-ready insights.

---

# 🎯 Project Objectives

This project aims to:

- Understand the structure of the used car dataset
- Clean missing, incorrect, and unrealistic values
- Perform feature engineering for deeper analysis
- Analyze pricing patterns across different vehicle attributes
- Identify factors affecting resale value
- Discover hidden trends using statistical and visual analysis
- Generate business recommendations for the used car market

---

# 📂 Dataset Information

The dataset contains information about second-hand vehicles, including:

- Brand
- Model
- Manufacturing Year
- Price
- Mileage
- Fuel Type
- Transmission
- Ownership Details *(if available)*
- Other vehicle specifications

---

# ⚙️ Feature Engineering

To improve analytical depth, a new feature was created:

### 🚘 Car Age

```python
Car Age = Current Year − Manufacturing Year
```

This engineered feature enables analysis of:

- Vehicle depreciation
- Age vs Price relationship
- Age vs Mileage
- Market trends based on vehicle age

---

# 🧹 Data Cleaning

Extensive preprocessing was performed to improve data quality.

### ✔ Handling Missing Values

- Identified missing entries
- Treated invalid records as missing values
- Imputed missing values using logical grouping techniques

---

### ✔ Mileage Cleaning

- Removed negative mileage values
- Converted zero mileage to missing values
- Filled missing mileage using average mileage based on **Brand + Car Age**

---

### ✔ Fuel Type Correction

Invalid fuel category values (such as **"xyz"**) were identified and corrected using domain knowledge.

---

### ✔ Manufacturing Year Validation

Removed unrealistic records where:

- Manufacturing year exceeded the current year

---

### ✔ Removing Illogical Records

Filtered unrealistic vehicle combinations, including:

- Very old diesel vehicles
- Very old petrol vehicles
- Unrealistically aged hybrid vehicles

---

### ✔ Outlier Treatment

Detected and removed extreme pricing outliers that could distort the analysis, including unrealistic vehicle prices.

---

# 📊 Exploratory Data Analysis

The project includes comprehensive exploratory analysis.

## 📈 Univariate Analysis

Analyzed:

- Vehicle Brands
- Fuel Types
- Transmission Types
- Manufacturing Years
- Car Age
- Mileage Distribution
- Price Distribution

---

## 📊 Bivariate Analysis

Studied relationships between:

- Price vs Car Age
- Price vs Mileage
- Price vs Fuel Type
- Price vs Brand
- Price vs Transmission

---

## 📉 Multivariate Analysis

Explored combined effects of multiple variables on vehicle prices, including:

- Brand
- Car Age
- Mileage
- Fuel Type
- Transmission

---

# 📌 Data Visualizations

The notebook includes professional visualizations such as:

- Bar Charts
- Histograms
- Count Plots
- Box Plots
- Scatter Plots
- Correlation Heatmaps
- Distribution Plots

These visualizations help identify pricing patterns, outliers, and relationships between variables.

---

# 📊 Statistical Analysis

The project applies statistical techniques including:

- Descriptive Statistics
- Correlation Analysis
- Distribution Analysis
- Outlier Detection
- Trend Analysis

---

# 💡 Key Business Insights

Some important insights discovered during the analysis include:

- 🚗 Car price decreases as vehicle age increases.
- 📉 High mileage vehicles generally have lower resale value.
- ⛽ Fuel type influences market pricing.
- 🏷️ Premium brands retain higher resale value than economy brands.
- ⚙️ Transmission type impacts selling price.
- 🧹 Proper data cleaning significantly improves analytical reliability.
- 📊 Feature engineering enhances business understanding.

---

# 🛠️ Technologies Used

| Category | Tools |
|----------|--------|
| Programming Language | Python |
| Data Analysis | Pandas, NumPy |
| Data Visualization | Matplotlib, Seaborn |
| Development Environment | Jupyter Notebook |

---

# 📂 Project Structure

```
Used-Cars-EDA/
│
├── data/
│   └── used_cars.csv
│
├── notebooks/
│   └── Used_Cars_EDA.ipynb
│
├── images/
│   └── charts/
│
├── README.md
│
└── requirements.txt
```

---

# 🚀 Skills Demonstrated

✔ Data Cleaning

✔ Data Wrangling

✔ Feature Engineering

✔ Exploratory Data Analysis

✔ Data Visualization

✔ Business Analysis

✔ Outlier Detection

✔ Statistical Thinking

✔ Python Programming

✔ Problem Solving

---

# 📚 Learning Outcomes

Through this project, I strengthened my understanding of:

- Cleaning real-world datasets
- Handling missing and inconsistent values
- Feature engineering for analytics
- Exploratory Data Analysis (EDA)
- Identifying business trends
- Creating professional visualizations
- Extracting actionable insights for decision-making

---

# 🎯 Business Value

The insights from this project can help:

- 🚘 Used Car Dealerships optimize pricing strategies
- 💰 Buyers evaluate fair market value
- 📊 Sellers understand factors affecting resale prices
- 📈 Businesses make data-driven inventory decisions

---

# 🔮 Future Improvements

Future enhancements may include:

- Used Car Price Prediction using Machine Learning
- Interactive Dashboard using Power BI or Tableau
- SQL Database Integration
- Streamlit Web Application
- Vehicle Recommendation System

---

# 🤝 Connect With Me

If you found this project useful, feel free to explore my other Data Science projects and connect with me.

⭐ **If you like this project, consider giving it a Star!**

---

## 📜 License

This project is created for educational and portfolio purposes.

---

<p align="center">

### 🚀 Turning Raw Data into Business Insights

**Made with ❤️ using Python**

</p>
