 ## Healthcare Insurance Prediction – Data Science Project

##About

Hello! This is my first Data Science project, created as part of my learning journey. The goal of this project was to apply key Data Science concepts using a healthcare dataset. 
I explored, cleaned, and visualized data, then built a machine learning model to predict whether an individual has insurance coverage based on features such as age,  status, and more.

### Skills Practiced:
- Data Cleaning with **pandas**
- Exploratory Data Analysis (EDA)
- Data Visualization
- Machine Learning using **Random Forest Classifier**

---

##  Dataset

- Name: Healthcare Dataset
- Format: Excel / CSV
- Description: Includes patient information such as age, sex, Marital status, Location/region, Monthly Household Income, Number of Children, and insurance status.
- Target Variable: `insurance` (binary: has insurance / no insurance)
- Source: Safra Data School

---

##  Technologies Used

- Python
- Jupyter Notebook
- pandas
- matplotlib / seaborn
- scikit-learn

---

## Project Workflow

1. Data Loading – Read the healthcare dataset using `pandas`
2. Data Cleaning – Handle missing values, data types, and duplicates
3. EDA – Discover insights, outliers, and feature relationships
4. Visualization – Create histograms, heatmaps, and boxplots
5. Feature Selection– Choose meaningful features for modeling
6. Modeling – Apply **Random Forest Classifier** to predict insurance status
7. Evaluation – Use metrics like Accuracy, Precision, Recall, and Confusion Matrix

---

## Model Summary

- Algorithm: Random Forest Classifier (RFC)
- Target: Predict whether a person has insurance coverage
- Key Features:
  - Age
  - Monthly Houseold Income
  -Children
  - Region/Location
  - Gender
- **Performance Metrics**:
  - Accuracy: `70.5%` *(replace with actual value)*
 



## Future Improvements

- Perform hyperparameter tuning (GridSearchCV / RandomizedSearchCV)
- Try other models: Logistic Regression, Gradient Boosting
- Deploy the model using Flask or Streamlit for real-time prediction
- Improve class balance using SMOTE or class weighting (if needed)

---

## Author

- Name: Anthony Macharia
- Learning Focus: Data preprocessing, EDA, ML model building
- Tools Practiced: pandas, matplotlib, seaborn, scikit-learn

---

##  How to Run This Project

1. Clone the repository:
   ```bash
   git clone https:https://github.com/Antoe26/HealthCare-Data-Set-Project.git
   cd HealthCare-Data-Set-Project
2 Launch jupyter notebook
 ```bash
jupyter notebook

