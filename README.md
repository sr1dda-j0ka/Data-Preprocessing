# Air Quality Data Preprocessing

##  Project Overview
This project focuses on **cleaning and preparing an Air Quality dataset** for further analysis or predictive modeling. The dataset contains hourly sensor readings of various pollutants recorded over a year. The preprocessing steps include:

- Handling missing values
- Feature scaling & encoding
- Time-based feature engineering
- Outlier detection & handling
- Exploratory Data Analysis (EDA)

## Technologies Used
- **Python**
- **Pandas** 
- **NumPy** 
- **Matplotlib** 
- **Seaborn** 
- **Scikit-learn** 

---

##  Dataset Description
The dataset contains air quality sensor readings with missing values and potential sensor drift. The key features include:

- `CO(GT)`: Carbon Monoxide concentration
- `NOx(GT)`: Nitrogen Oxides concentration
- `NO2(GT)`: Nitrogen Dioxide concentration
- `C6H6(GT)`: Benzene concentration
- `Temperature`, `Humidity`, `Absolute Humidity`
- `Timestamp` features (`Date`, `Time`, etc.)

---

## 🔧 Data Preprocessing Steps

### 1️. Handling Missing Values
- Missing values (`-200`) are replaced with `NaN`.
- Integer columns are filled with the **rounded mean**, keeping their data type.
- Float columns are filled with the **mean**.

### 2️. Feature Scaling & Encoding
- **Min-Max Scaling** or **Standardization** (based on model requirements).
- Categorical features (if any) are encoded properly.

### 3️. Time-Based Feature Engineering
- Extracting `Hour`, `Day`, `Month` from the timestamp.

### 4️. Outlier Detection & Handling
- Using **Boxplots and IQR method** to detect outliers.
- Handling outliers using **capping/trimming**.

### 5️. Exploratory Data Analysis (EDA)
- **Histograms** to check data distribution.
- **Boxplots** to detect outliers.
- **Scatter plots** to analyze relationships.
- **Heatmaps** for feature correlation.

---



📌 **Contributions & Feedback Welcome!** 🔥

