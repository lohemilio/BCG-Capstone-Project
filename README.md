# BCG Capstone Project

## Overview
This repository contains the code and analysis for the BCG Capstone Project focused on predicting customer churn and demand forecasting for ClientCo, an international distributor of construction and renovation products. This project was conducted as part of the completion of our Master's in Business Analytics and Big Data, in collaboration with the IE School of Science and Technology and BCG X. We are Group 6 of the BCG Capstone Project.

## Repository Contents

1. **EDA and Feature Engineering.ipynb**
   - **Objective**: Conduct Exploratory Data Analysis (EDA) and prepare the dataset for modeling.
   - **Key Steps**:
     - **EDA**: Reviewed missing values, adjusted data types, and analyzed sales trends, seasonality, and anomalies.
     - **Feature Engineering**: Developed features for customer segmentation and behavior analysis, including RFM metrics and Customer Lifetime Value (CLV).

2. **Churn_Prediction.ipynb**
   - **Objective**: Develop a model to predict customer churn.
   - **Key Steps**:
     - **Feature Engineering**: Created features such as recency, frequency, and monetary value.
     - **Model Training**: Utilized XGBoostClassifier, training iteratively with windowed datasets.
     - **Evaluation**: Assessed model performance using F1-score, AUC-ROC, and accuracy.

3. **Demand_Prediction.ipynb**
   - **Objective**: Forecast future sales and inventory needs.
   - **Key Steps**:
     - **Feature Engineering**: Generated additional features from transaction data including date components and target encoding for categorical variables.
     - **Model Training**: Employed XGBoostRegressor to predict sales quantities.
     - **Evaluation**: Evaluated model performance using Mean Absolute Percentage Error (MAPE) and Mean Absolute Error (MAE).

## Methodology

1. **Define the Problem and Objective**
   - Identified the high churn rate and its financial impact on ClientCo.
   - Aimed to develop predictive models for customer churn and demand forecasting.

2. **Exploratory Data Analysis (EDA)**
   - Analyzed transaction data to uncover trends and anomalies.
   - Identified significant churn rates across sales channels and quantified financial impact.

3. **Feature Engineering**
   - Created features such as recency, frequency, monetary value (RFM), and CLV.
   - Engineered additional features to capture customer behavior and engagement.

4. **Model Development**
   - **Churn Prediction**: Trained and validated a churn prediction model using XGBoostClassifier.
   - **Demand Prediction**: Developed a demand prediction model using XGBoostRegressor.

5. **Model Evaluation**
   - Evaluated model performance using metrics such as F1-score, AUC-ROC, accuracy, MAPE, and MAE.

6. **Insights and Recommendations**
   - Provided actionable insights based on model predictions.
   - Recommended strategies to enhance customer retention, optimize inventory management, and improve operational efficiency.

## Instructions

1. **Clone the Repository**
   ```sh
   git clone https://github.com/lohemilio/BCG-Capstone-Project.git

1. **Install Dependencies**
   ```sh
   pip install pandas numpy matplotlib seaborn xgboost


3. **Run the Notebooks**
Open and run each Jupyter notebook in the following order to replicate the analysis:
- `EDA and Feature Engineering.ipynb`
- `Churn_Prediction.ipynb`
- `Demand_Prediction.ipynb`

## Additional Information
For a comprehensive understanding of the project, including detailed insights and recommendations, please refer to the [project report](https://docs.google.com/document/d/1VzAf4yzGz-s7PsmJ7Whjv9uam2sMxhBEzyyfXV3O1lE/edit?usp=sharing).

## Contributors
- Emilio Lopez
- Eugenio Autrique
- Guillermo Brun
- Kangjie Yu
- Mislav Ilijas

## Contact
For any questions or further information, please contact [Sci-Tech](mailto:sci-tech@ie.edu).

---

This README provides an overview of the project, detailing the contents and purpose of each notebook, along with instructions on how to set up and run the analysis. It encapsulates the core objectives, methodologies, and findings of the capstone project.
