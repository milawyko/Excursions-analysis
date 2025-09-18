### Analysis of Italian Excursion Data (2014-2022)
_Project Overview_
This project analyzes a dataset of excursions in Italy recorded between 2014 and 2022. The data was obtained from an unverified source and required substantial cleaning and preprocessing due to questionable statistical reliability. The analysis focuses on exploratory data analysis, visualization, and building predictive models to identify patterns in excursion behavior.

_Dataset Characteristics_
The dataset contains 37,829 records with 25 features covering:

_Demographic Information_: Gender, age groups, education levels, and employment status
Geographical Data: Region codes and Italian zone classifications
Excursion Details: Purpose of travel, transportation methods, group size, and destinations
Temporal Features: Month, year, and quarter of each excursion

### Methodology
_Data Preprocessing_
Renamed columns for improved readability and consistency

Normalized date formats and created derived temporal features (e.g., seasons from months)

Processed encoded categorical variables for machine learning applications

_Exploratory Analysis_
Visualized yearly trends with emphasis on COVID-19 impact (2020-2021)

Analyzed seasonal distribution patterns across months

Examined regional variations and transportation preferences

_Machine Learning Applications_
Implemented Random Forest classification to predict seasons using demographic features

Evaluated model performance through accuracy metrics and confusion matrices

Tested additional models for various classification and regression tasks

_Key Findings_
Season Prediction: Achieved approximately 35% accuracy in seasonal classification, outperforming random guessing (25% baseline for 4 classes)

Model Performance: Results varied significantly across different prediction tasks, indicating limitations in feature predictive power

### Technical Stack
Python 3.7+

Data Processing: Pandas, NumPy

Visualization: Matplotlib, Seaborn

Machine Learning: Scikit-learn

Environment: Jupyter Notebook

Limitations and Considerations
Data Quality: The dataset originates from an unverified source with uncleaned entries and potential inconsistencies

Predictive Limitations: Available features showed limited effectiveness for robust predictive modeling

Interpretation Caution: Findings should be viewed as exploratory rather than definitive due to data reliability concerns

Purpose
This project serves as an educational exercise in analyzing imperfect real-world data, demonstrating practical applications of data cleaning, visualization, and machine learning techniques under less-than-ideal data conditions.