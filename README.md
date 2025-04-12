# Predicting Manufacturing Defects

## Overview

This project aims to improve the accuracy of defect detection in manufacturing processes using machine learning techniques. We enhance a baseline model's performance from an accuracy of 95% to 96% through targeted feature engineering.

## Dataset

The dataset used for this analysis is named `manufacturing_defect_dataset`. It includes various metrics crucial for predicting defect rates in manufacturing operations. You can access the dataset [here](https://www.kaggle.com/datasets/rabieelkharoua/predicting-manufacturing-defects-dataset).

## Project Structure

- **`main.ipynb`**: The main Jupyter notebook where the data analysis, feature engineering, and model evaluation are conducted.
- **`manufacturing_defect_dataset.csv`**: The dataset used in the analysis (download from the provided Kaggle link).

## Analysis Overview

1. **Data Preprocessing and Exploration**:
   - Handling missing values and assessing data imbalances.
   - Exploratory Data Analysis (EDA) to understand feature distributions and correlations.

2. **Feature Engineering**:
   - Creation of new features such as `CostPerUnit`, `MaintenancePerUnit`, and `QualityDefectRatio` to enhance the model's predictive power.
   - Derived metrics like `MaintenanceEfficiency` and `DefectRatePerEnergyUnit` to capture more nuanced relationships within the data.

3. **Model Training and Evaluation**:
   - Training of the baseline model and evaluation using accuracy, precision, recall, and other metrics.
   - Comparison of the model’s performance before and after feature engineering.

4. **Results and Insights**:
   - Improvement in model accuracy from 95% to 96% through feature engineering.
   - Discussion of the advantages, limitations, and impact of the engineered features on the model's performance.

## Features Engineered

- **`CostPerUnit`**: Production cost per unit.
- **`MaintenancePerUnit`**: Maintenance hours per unit.
- **`QualityDefectRatio`**: Ratio of quality score to defect rate.
- **`TotalProductionCost`**: Total production cost including additive material costs.
- **`MaintenanceEfficiency`**: Efficiency of maintenance in relation to energy consumption and production volume.
- **`ProductivityDefectRatio`**: Ratio of worker productivity to defect rate.
- **`DefectRatePerEnergyUnit`**: Defect rate per unit of energy consumed.
- **`HighQuality`**: Indicator for high-quality score.
- **`HighDefectRate`**: Indicator for high defect rate.

## Getting Started

1. **Clone the Repository**:
   ```bash
   git clone <repository_url>
