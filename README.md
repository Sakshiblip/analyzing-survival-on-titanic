

# Analysing Survival on the Titanic 🚢

This repository contains a comprehensive Exploratory Data Analysis (EDA) of the Titanic dataset. The project focuses on uncovering the factors that influenced the survival rates of passengers aboard the RMS Titanic using statistical analysis and data visualization.

## 📌 Project Overview
The goal of this analysis is to identify patterns and determine which groups of people were more likely to survive the tragedy. The study investigates variables such as socio-economic status, age, gender, and family size to understand their impact on survival outcomes.



## 🚀 Key Features
* **Data Cleaning & Wrangling:** Handling missing values in the `Age`, `Cabin`, and `Embarked` columns.
* **Feature Engineering:** Creating new features like `Has_Cabin` to determine if cabin ownership affected survival.
* **Socio-Economic Analysis:** Investigating the "Women and Children First" protocol and the impact of Passenger Class (`Pclass`).
* **Statistical Visualizations:** Using distribution plots and categorical plots to highlight survival disparities.
* **Correlation Mapping:** Identifying relationships between different passenger attributes and their survival status.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:**
    * `Pandas`: For data manipulation and structural analysis.
    * `NumPy`: For mathematical operations.
    * `Matplotlib` & `Seaborn`: For generating insightful and aesthetic visualizations.

## 📊 Core Analysis
* **Gender & Survival:** A deep dive into why gender was one of the strongest predictors of survival.
* **Wealth & Class:** Analyzing how first-class passengers had significantly higher survival rates compared to third-class passengers.
* **Age Distribution:** Visualizing the survival rate of different age groups, specifically focusing on the protection of minors.
* **Embarkation Points:** Checking if the port of embarkation (Cherbourg, Queenstown, Southampton) correlated with passenger demographics and survival.

## 📁 Dataset
The project uses the classic **Titanic: Machine Learning from Disaster** dataset.
* **Survival:** 0 = No, 1 = Yes
* **Pclass:** Ticket class (1, 2, or 3)
* **Sex:** Gender
* **Age:** Age in years
* **SibSp:** Number of siblings/spouses aboard
* **Parch:** Number of parents/children aboard
* **Fare:** Passenger fare
* **Cabin:** Cabin number
* **Embarked:** Port of Embarkation (C, Q, S)

## 📖 How to Use
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/titanic-survival-analysis.git](https://github.com/your-username/titanic-survival-analysis.git)
