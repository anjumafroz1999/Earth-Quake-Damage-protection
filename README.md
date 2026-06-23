# Earth-Quake-Damage-protection
# Earthquake Damage Protection Model

## 📌 Project Overview
This repository focuses on building a **predictive model for earthquake damage protection**.  
The goal is to assess building vulnerability, predict potential damage levels, and provide actionable insights for disaster preparedness and risk mitigation.

---

## 📂 Dataset
The dataset includes features such as:
- **Structural attributes**: Building age, height, material type (brick, concrete, wood)  
- **Geographical features**: Region, soil type, seismic zone classification  
- **Socio-economic factors**: Occupancy type, household income, insurance coverage  
- **Damage labels**: No damage, minor damage, major damage, complete destruction  

---

## ⚙️ Methodology
1. **Exploratory Data Analysis (EDA)**  
   - Distribution of building types and damage levels  
   - Correlation between structural features and damage severity  
   - Regional vulnerability mapping  
2. **Data Preprocessing**  
   - Handling missing values  
   - Encoding categorical features (manual & one-hot encoding)  
   - Outlier detection and removal  
   - Balancing classes using **SMOTE**  
3. **Model Building**  
   - Logistic Regression, Random Forest, Gradient Boosting, XGBoost  
   - Neural networks for multi-class classification  
4. **Model Evaluation**  
   - Accuracy, Precision, Recall, F1-score  
   - Confusion Matrix for damage level prediction  
   - ROC-AUC for model comparison  
5. **Risk Insights**  
   - Identifying high-risk zones  
   - Recommending reinforcement strategies for vulnerable structures  

---

## 📈 Key Insights
- **Older buildings** with unreinforced masonry are most vulnerable to severe damage.  
- **Soil type and seismic zone classification** strongly influence damage probability.  
- **Socio-economic factors** (income, insurance coverage) affect recovery and resilience.  
- **Random Forest and Gradient Boosting** models achieved the highest predictive accuracy.  


git clone https://github.com/yourusername/earthquake-damage-protection.git
cd earthquake-damage-protection
