# Australian Weather Prediction Project 🌦️

## Overview
This project implements machine learning models to predict rainfall in Australia using historical weather data. The analysis uses a comprehensive dataset from the Australian Government's Bureau of Meteorology, containing daily weather observations from 2008 to 2017.

## Project Highlights
- Implemented both Random Forest and Logistic Regression classifiers
- Achieved 84% accuracy with Random Forest Classifier
- Performed detailed feature importance analysis
- Handled missing data and categorical variables
- Created visualization for model evaluation

## Dataset Features
The dataset includes various weather measurements such as:
- Temperature (minimum, maximum, 9am, 3pm)
- Rainfall
- Wind (speed, direction, gust)
- Humidity
- Pressure
- Cloud cover
- Sunshine hours

## Key Findings
- Humidity3pm is the most influential feature in predicting rainfall
- Atmospheric pressure (both 9am and 3pm) shows strong predictive power
- Seasonal variables have relatively lower importance
- Model achieves 53.4% true positive rate for rain prediction

## Technical Implementation
- **Language:** Python
- **Key Libraries:** 
  - scikit-learn
  - pandas
  - numpy
  - matplotlib
  - seaborn

## Model Performance
### Random Forest Classifier
- Overall Accuracy: 84%
- True Positive Rate: 53.4%
- Better balanced performance across classes

### Logistic Regression
- Overall Accuracy: 82%
- Slightly lower performance compared to Random Forest
- Less balanced between classes

## Visualizations
- Confusion Matrix
- Feature Importance Plot
- Correlation Heatmaps
- Distribution Plots

## Future Improvements
- Implement more advanced models (XGBoost, Neural Networks)
- Include more historical data
- Add feature engineering for temporal patterns
- Optimize hyperparameters further

## Usage
1. Clone the repository
2. Install required packages
3. Run the Jupyter notebook
4. Explore the analysis and results

## Data Source
Dataset sourced from the Australian Government's Bureau of Meteorology via Kaggle.

## License
This project is open source and available under the MIT License.

---
Created by Amritha S | May 2025

