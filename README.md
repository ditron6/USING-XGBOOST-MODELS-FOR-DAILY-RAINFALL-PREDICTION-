# USING XGBOOST MODELS FOR DAILY RAINFALL PREDICTION

## Overview
This repository contains a study on daily rainfall prediction using **XGBoost models**. The project explores both **classification** and **regression** approaches to estimate precipitation events based on meteorological data.

Precipitation forecasting is a complex task that involves various methodologies, including **machine learning (ML)** techniques. The **XGBoost algorithm** has been widely applied to environmental studies, demonstrating high efficiency in predicting extreme events, climate patterns, and precipitation values. 

This study aims to compare the performance of XGBoost models in **classification** (predicting whether precipitation will occur) and **regression** (estimating the amount of precipitation in millimeters).

## Motivation
Accurate rainfall prediction is crucial for multiple sectors, including agriculture, water resource management, and disaster prevention. By leveraging **ML models**, we can improve the precision of daily precipitation forecasting, supporting informed decision-making processes.

## Dataset
- **Meteorological data sources**: The dataset consists of daily rainfall records collected from official climatological stations.
- **Features used**: Atmospheric variables such as temperature, humidity, wind speed, and historical precipitation values.
- **Target variables**:
  - **Classification task**: Binary outcome (rain/no rain)
  - **Regression task**: Continuous precipitation values (in mm)

## Methodology
1. **Data Preprocessing**
   - Handling missing values
   - Feature selection and engineering
   - Data normalization
   
2. **Model Selection & Training**
   - Implementing **XGBoost classification** for predicting rainfall occurrence
   - Implementing **XGBoost regression** for estimating precipitation levels
   - Hyperparameter tuning using Grid Search and Random Search
   
3. **Model Evaluation**
   - Metrics for classification: **Accuracy, Precision, Recall, F1-score, ROC-AUC**
   - Metrics for regression: **Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), R² Score**

## Results & Discussion
The results are evaluated based on model performance, highlighting the advantages of using **gradient boosting methods** for rainfall prediction. Comparisons with baseline models (e.g., Linear Regression, Decision Trees) are also discussed.

## Installation & Usage
### Requirements
Ensure you have the following dependencies installed:
```bash
pip install xgboost pandas scikit-learn matplotlib seaborn
```

### Running the Project
Clone this repository and run the main script:
```bash
git clone https://github.com/ditron6/USING-XGBOOST-MODELS-FOR-DAILY-RAINFALL-PREDICTION.git
cd USING-XGBOOST-MODELS-FOR-DAILY-RAINFALL-PREDICTION
python main.py
```

## Future Work
- Incorporating additional meteorological variables
- Exploring deep learning models for rainfall forecasting
- Extending the study to different climatic regions

## References
This study builds upon various research findings, including:
- **Facco et al. (2020)**, **He et al. (2022)**, **Pham et al. (2020)**: Machine learning for climate forecasting.
- **Chen and Guestrin (2016)**: XGBoost implementation and efficiency.
- **Mu et al. (2021)**, **Xu et al. (2022)**: Applications of XGBoost in environmental studies.

For a complete list of references, refer to the research paper associated with this repository.

---
© 2025, Pedro Rios | Civil Engineer & CS Researcher
