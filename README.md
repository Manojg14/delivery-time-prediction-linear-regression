# 🚚 Delivery Time Prediction using Linear Regression

## 📌 Project Overview

Efficient delivery time estimation is essential for logistics companies, food delivery platforms, and e-commerce businesses to improve customer satisfaction and optimize operations.

This project builds a **Linear Regression Machine Learning model** to predict delivery time based on factors such as delivery distance, traffic conditions, weather, vehicle type, and time of day. The project demonstrates a complete end-to-end Machine Learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and evaluation.

---

# 📂 Repository Structure

```
Delivery-Time-Prediction/
│
├── Dataset/
│   └── delivery_time.csv
│
├── Notebook/
│   └── delivery-time-prediction-linear-regression.ipynb
│
├── Images&Video/
│   └── Graphs/
│   └── Screenshots/
|   └── delivery-time-prediction-linear-regression demo.mp4
|
├── README.md

```

---

# 🎯 Business Problem

Delivery companies need to accurately estimate delivery times to improve customer experience, optimize delivery routes, and manage operational efficiency.

Manual estimation is often inaccurate because delivery time depends on multiple dynamic factors. This project uses Machine Learning to predict delivery time based on historical delivery data.

---

# 🎯 Project Objectives

- Understand the delivery dataset
- Perform Exploratory Data Analysis (EDA)
- Clean and preprocess the data
- Detect and treat outliers
- Encode categorical variables
- Build a Linear Regression model
- Evaluate model performance
- Predict delivery time accurately

---

# 📊 Dataset Information

The dataset contains information related to delivery operations.

| Feature | Description |
|----------|-------------|
| Delivery Distance | Distance between pickup and destination (km) |
| Vehicle Type | Type of delivery vehicle |
| Traffic Level | Traffic condition (Low, Medium, High) |
| Weather Condition | Weather during delivery |
| Time of Day | Morning, Afternoon, Evening, Night |
| Preparation Time | Order preparation time (minutes) |
| Delivery Time | Actual delivery time (Target Variable) |

> **Target Variable:** `Delivery_Time_min`

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# 📈 Exploratory Data Analysis (EDA)

The following analyses were performed:

- Dataset Shape
- Data Types
- Missing Value Analysis
- Duplicate Record Check
- Statistical Summary
- Correlation Analysis
- Outlier Detection
- Feature Distribution
- Target Variable Distribution

### Visualizations

- Histograms
- Box Plots
- Scatter Plots
- Pair Plot
- Correlation Heatmap

---

# 🧹 Data Cleaning

The following preprocessing steps were performed:

- Removed duplicate records
- Checked for missing values
- Verified data types
- Treated outliers using the IQR method

---

# ⚙ Feature Engineering

Feature engineering techniques included:

- Label Encoding of ordinal categorical features
- Feature Selection
- Conversion of categorical variables into numerical format
- Preparation of model-ready dataset

---

# 🔄 Data Preprocessing

The preprocessing pipeline included:

- Missing Value Handling
- Outlier Treatment
- Label Encoding
- Feature Scaling (if required)
- Train-Test Split (80:20)

---

# 🤖 Machine Learning Model

### Regression Algorithm Used

- Linear Regression

---

# 📏 Model Evaluation Metrics

The model performance was evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

---

# 📈 Project Workflow

```
Data Collection
        ↓
Data Cleaning
        ↓
Exploratory Data Analysis
        ↓
Feature Engineering
        ↓
Data Preprocessing
        ↓
Train-Test Split
        ↓
Linear Regression Model
        ↓
Model Evaluation
        ↓
Delivery Time Prediction
```

---

# 🚀 Installation

### Clone the repository

```bash
git clone https://github.com/Manojg14/delivery-time-prediction-linear-regression.git
```

### Navigate to the project directory

```bash
cd delivery-time-prediction-linear-regression
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

---

# 📦 Requirements

```
numpy
pandas
matplotlib
seaborn
scikit-learn
jupyter
```

---

# 📊 Expected Output

The trained model predicts the estimated **delivery time (in minutes)** based on:

- Delivery Distance
- Traffic Level
- Vehicle Type
- Weather Condition
- Time of Day
- Preparation Time

---

# 📚 Learning Outcomes

This project demonstrates:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Outlier Detection
- Feature Engineering
- Data Preprocessing
- Linear Regression
- Model Evaluation
- Machine Learning Workflow
---

# 👨‍💻 Author

**Manoj G**

Aspiring AI Engineer | Data Scientist | Machine Learning Enthusiast | Data Analyst

---
