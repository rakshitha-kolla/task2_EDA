# Titanic Dataset: Exploratory Data Analysis (EDA)

This repository contains a complete Exploratory Data Analysis (EDA) performed on the Titanic dataset. The objective of this project is to explore and visualize the data to uncover patterns, detect anomalies, understand feature relationships, and prepare for machine learning tasks.

---

## 📁 Files Included

- `task1.ipynb` – Jupyter Notebook with EDA code and visualizations
- `titanic.csv` – Original dataset used for analysis
- `README.md` – This documentation file

---

## 📊 Dataset Overview

The Titanic dataset contains passenger data such as:
- Demographics (Age, Sex, Class)
- Ticket and Fare information
- Travel details (Embarked port, Cabin)
- Survival status (target variable)

Dataset Source: [Titanic Dataset – Kaggle](https://www.kaggle.com/competitions/titanic/data)

---

## 🔍 EDA Steps Performed

1. **Generated Summary Statistics**
   - Used `.info()` and `.describe()` to analyze data types, nulls, and distributions.

2. **Visualized Distributions**
   - Plotted histograms and boxplots for numeric features (`Age`, `Fare`) to detect outliers and skewness.

3. **Analyzed Feature Relationships**
   - Used correlation matrix and heatmap to explore numeric feature relationships.
   - Created bar plots to analyze survival rates across categorical features.

4. **Detected Patterns and Trends**
   - Identified that females and passengers in higher classes had better survival chances.
   - Noticed `Fare` is right-skewed with high outliers.

5. **Made Feature-Level Inferences**
   - Sex, Pclass, and Embarked show strong influence on survival.
   - Cabin has excessive missing data; considered for removal or engineering.

---

## 📈 Visualizations Used

- **Histograms** – To analyze distribution of `Age`, `Fare`
- **Boxplots** – To identify outliers and compare features by category
- **Correlation Heatmap** – To visualize linear relationships
- **Bar plots** – To study survival distribution by gender, class, and embark location

---

## 🧠 Key Learnings

- `Sex` and `Pclass` are strong indicators of survival.
- `Age` has outliers but shows meaningful trends.
- `Fare` is highly skewed and requires transformation in ML models.
- EDA is critical for identifying data issues before modeling.

---

## 🛠️ Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---
## 🚀 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/rakshitha-kolla/task2_EDA.git
   cd titanic-eda
