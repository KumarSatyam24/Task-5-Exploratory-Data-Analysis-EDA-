# Task-5-Exploratory-Data-Analysis-EDA-
Extracting insights using visual and statistical exploration.(TITANIC DATASET)


# 🧊 Titanic Dataset - EDA Summary Report

## 📋 Summary of Findings

### 1. Survival Overview
- Around **38%** of the passengers survived.  
- The dataset is **imbalanced**, with more non-survivors than survivors.

### 2. Gender and Survival
- **Females had a significantly higher survival rate** than males.  
- The majority of **male passengers did not survive**, highlighting gender-based evacuation priority ("women and children first").

### 3. Passenger Class (Pclass)
- **Survival rates were highest in 1st class**, followed by 2nd class, and lowest in 3rd class.  
- Passengers in higher classes likely had **better access to lifeboats** and crew.

### 4. Age Distribution
- Age ranged from **0.42 to 80 years**.  
- **Younger passengers** had slightly better survival chances.  
- **Infants and children** had particularly high survival rates, consistent with emergency protocols.

### 5. Fare Analysis
- Passengers who paid **higher fares** were more likely to survive.  
- This suggests a relationship between **fare → class → survival**.

### 6. Embarkation Port
- Most passengers boarded at **Southampton ('S')**.  
- Passengers from **Cherbourg ('C')** had **higher survival rates**, likely due to more 1st class passengers boarding there.

### 7. Correlation Insights
- Strongest positive correlation with survival:
  - **Fare** (higher fare, more survival)
  - **Being female**
  - **Lower Pclass value** (1st class)
- **Negative correlation** between Pclass and survival (higher class number, lower survival).

### 8. Missing Data
- **Age** and **Cabin** columns have missing data.
- **Cabin** is missing in ~77% of records, and may need to be **excluded or imputed** cautiously.
- **Embarked** has a few missing values and can be filled with the most common port.