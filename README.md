# 🌍 Global Pollution and Energy Recovery Analysis using Apriori Algorithm

## 📌 Objective
The goal of this project is to analyze global pollution data to uncover hidden associations between pollution levels (air, water, soil) and energy recovery across different countries. Using the **Apriori Algorithm**, we aim to identify frequent patterns and meaningful relationships that can guide pollution control and energy optimization strategies.

---

## 📁 Dataset
**Filename:** `Global_Pollution_Analysis.csv`  
The dataset includes:
- Pollution indices (Air, Water, Soil)
- Energy consumption and recovery metrics
- Country and Year data

---

## 🧪 Project Phases

### ⚙️ Phase 1: Data Preprocessing and Feature Engineering

#### ✅ Data Import and Cleaning
- Load the dataset.
- Handle missing data using imputation techniques or row/column removal.
- Normalize pollution indices (Air, Water, Soil) using standard scaling.
- Encode categorical columns (Country, Year) using label encoding.

#### 🛠 Feature Engineering
- **Energy Consumption per Capita:** Derived to analyze energy efficiency.
- **Pollution Trends:** Identified trends across years and countries.
- **Pollution Severity Categories:** Created `Low`, `Medium`, and `High` severity classes based on threshold values.

---

### 🛒 Phase 2: Association Rule Mining with Apriori

#### 🔍 Introduction
The Apriori Algorithm is used to mine frequent itemsets and generate association rules that reflect pollution-energy patterns.

#### 💡 Implementation
- Apply Apriori on transformed and categorical data.
- Identify frequent itemsets such as countries with high air pollution and low energy recovery.
- Mine association rules based on minimum **support**, **confidence**, and **lift** thresholds.

#### 📊 Visualization and Interpretation
- Frequent itemsets plotted using bar graphs.
- Association rules visualized with network diagrams.
- Strategic insights derived from the strongest rules.

---

### 📈 Phase 3: Model Evaluation and Validation

#### 🎯 Validation Strategy
- Split dataset into training and test sets (where applicable).
- Use k-fold cross-validation to ensure model robustness.
- Validate mined rules for consistency.

#### 📐 Evaluation Metrics
- **Support**: How often the itemset appears.
- **Confidence**: Likelihood of rule accuracy.
- **Lift**: Rule strength compared to random chance.

---

## 📎 Key Insights
- Strong association found between high air pollution and low energy recovery in industrialized countries.
- Countries with high energy consumption per capita also show high soil pollution levels.
- Medium air pollution levels often correlated with moderate energy recovery rates.

---

## 🚀 Technologies Used
- Python (pandas, mlxtend, matplotlib, seaborn)
- Jupyter Notebook
- Apriori Algorithm (from `mlxtend.frequent_patterns`)
- Scikit-learn (for encoding and scaling)

---
## 📧 Contact
**Author**: Tushar Walia  
📫 [wtushar@gmail.com]  


---



