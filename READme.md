# Asthma Data Analysis Project

This is a data analysis project focused on understanding the key factors contributing to asthma using a synthetic dataset from Kaggle.

## Dataset Information

- Name: synthetic_asthma_dataset.csv
- Source: https://www.kaggle.com/datasets/miadul/asthma-synthetic-medical-dataset
- Rows: 1499
- Columns: 17
- Main Target Column: `Has_Asthma`

## Tools & Libraries Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
-

1. **Importing the dataset** from Kaggle
2. **Data cleaning:**
   - Dropped irrelevant columns like `Patient_ID`
   - Handled missing values in `Allergies`, `Comorbidities`, and `Asthma_Control_Level`
3. **Exploratory Data Analysis (EDA):**
   - Checked data distributions
   - Visualized correlations using heatmaps and bar charts
4. **Feature Selection:**
   - Identified that `Family_History`, `Allergies`, and `Physical_Activity_Level` are strongly correlated with `Has_Asthma`
5. **Key Insights:**
   - People with family history of asthma are at higher risk
   - Regular physical activity lowers asthma risk
   - Consanguineous (within-family) marriages can contribute to genetic asthma
6. **Recommendations:**
   - Promote exercise and discourage within-family marriages to reduce asthma risk
7. **END**

## Visualizations

- Correlation heatmap
- Bar charts of asthma by gender, family history, and activity level
- Distribution plots for age and BMI
- ## How to Run

1. Clone the repo git clone https://github.com/Moazam16/asthma_data_analysis.git
2. Install dependencies
3. Run the notebook
   Open Asthma_Analysis.ipynb in Jupyter Notebook or any IDE.
