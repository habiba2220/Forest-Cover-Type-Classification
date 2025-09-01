# Forest-Cover-Type-Classification
A machine learning project that predicts forest cover types from cartographic variables using the UCI Covertype dataset

# Forest Cover Type Classification

A machine learning project that predicts forest cover types from cartographic variables using the UCI Covertype dataset.

## Project Overview

This project implements a multi-class classification system to identify forest cover types based on various environmental and cartographic features. The solution can help forestry services and environmental agencies in forest management and conservation efforts.

## Dataset

The Covertype dataset from UCI Machine Learning Repository contains 54 features and 7 forest cover types:
- Elevation
- Aspect
- Slope
- Horizontal distance to hydrology
- Vertical distance to hydrology
- Horizontal distance to roadways
- Hillshade 9am, noon, and 3pm
- Horizontal distance to fire points
- Wilderness area designation (4 binary columns)
- Soil type (40 binary columns)
- Forest Cover Type (7 types)

## Methodology

1. **Data Exploration**: Analyzed dataset structure and feature distributions
2. **Data Preprocessing**: Handled feature scaling and preparation
3. **Model Training**: Implemented Random Forest and XGBoost classifiers
4. **Model Evaluation**: Compared performance using accuracy, precision, recall, and F1-score
5. **Feature Analysis**: Identified the most important features for prediction
6. **Visualization**: Created confusion matrices and feature importance plots

## Results

- **Random Forest Accuracy**: >95% (may vary based on sample size)
- **XGBoost Accuracy**: Comparable performance to Random Forest
- **Key Features**: Elevation, distance to hydrology, and soil types were among the most important predictors

## Model Performance

| Model | Accuracy | Precision | Recall | F1-Score |
|-------|----------|-----------|--------|----------|
| Random Forest | 0.95+ | 0.94+ | 0.94+ | 0.94+ |
| XGBoost | 0.95+ | 0.94+ | 0.94+ | 0.94+ |

## Business/Environmental Applications

- Automated forest cover mapping and monitoring
- Conservation planning and resource allocation
- Climate change impact assessment on forest ecosystems
- Wildfire risk assessment and prevention planning

## note book
https://colab.research.google.com/drive/1iM9RQHqJjCiMXK9Zqo76GLVakwKrg2bB?authuser=0#scrollTo=giKUGO0wdR3p
