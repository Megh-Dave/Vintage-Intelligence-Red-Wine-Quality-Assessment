# Vintage Intelligence: Assessing the Quality of Red Wine

## Overview
This project explores the relationship between the physicochemical properties of red wines and their sensory quality ratings. By analyzing various chemical properties, such as acidity, sugar content, and alcohol levels, the project aims to understand the factors that influence wine quality and provide insights for winemakers and enthusiasts. The project leverages machine learning techniques to predict wine quality based on its measurable attributes.

## Features
- Analysis of physicochemical properties affecting wine quality
- Implementation of various machine learning models to classify wine quality
- Data visualization to interpret the relationship between chemical properties and quality ratings

## Objectives
- Analyze the correlation between chemical properties and wine quality ratings
- Develop predictive models to assess wine quality based on physicochemical attributes
- Identify the most influential factors in determining wine quality
- Provide insights that can be used to optimize wine production processes

## Dataset
The dataset used in this project is the Wine Quality Dataset from the UCI Machine Learning Repository. It includes the following features:
1. Fixed acidity
2. Volatile acidity
3. Citric acid
4. Residual sugar
5. Chlorides
6. Free sulfur dioxide
7. Total sulfur dioxide
8. Density
9. pH
10. Sulphates
11. Alcohol
12. Quality (target variable)

## Technologies Used
- Python
- Pandas (for data manipulation)
- Scikit-learn (for machine learning models)
- Matplotlib/Seaborn (for data visualization)
- Jupyter Notebooks (for interactive development and presentation)

## Usage
- Load the wine dataset.
- Run the classification models to assess the quality based on chemical properties.
- Visualize the results to understand key factors influencing wine quality.

## Key Findings
- Citric Acid shows the strongest positive correlation with wine quality:
Citric acid, commonly associated with freshness and balance in wine, showed the highest positive correlation with quality ratings. Higher levels are often found in wines rated "good" to "excellent."

- The Random Forest model achieved the highest prediction accuracy of 87%:
Among the machine learning models tested, the Random Forest classifier outperformed others, achieving an accuracy of 87% in predicting wine quality based on physicochemical properties.

- Alcohol content and volatile acidity are among the top predictors of wine quality:
Alcohol content positively correlates with wine quality, while higher volatile acidity typically indicates lower quality. Both are critical factors in determining the sensory appeal of wine. Higher alcohol content generally indicates better quality.

- Residual sugar has a minimal impact on quality ratings:
Residual sugar levels showed little to no correlation with the overall quality ratings, suggesting that other factors like acidity and alcohol play a more significant role in determining wine quality. Sugar content does not have a significant impact on the quality rating.

- Sulphates contribute moderately to quality but are less influential than alcohol or acidity:
Sulphates, which help stabilize wine and contribute to aroma, have a moderate positive correlation with quality, though their impact is less significant compared to alcohol content and acidity.

## Methodology
1. Data Preprocessing: Handling missing values, outlier detection, and normalization
2. Exploratory Data Analysis: Correlation analysis, distribution of features, and quality ratings
3. Feature Engineering: Creating new features and selecting the most relevant ones
4. Model Development: Training and comparing multiple machine learning models
5. Model Evaluation: Using cross-validation and various performance metrics
6. Interpretation: Analyzing feature importance and model predictions

## Challenges Overcome
- Dealing with class imbalance in the quality ratings
- Handling multicollinearity among features
- Interpreting complex model outputs for practical insights

## Future Improvements
- Incorporate data from white wines for a comprehensive analysis
- Implement more advanced feature selection techniques
- Develop a web application for real-time wine quality prediction
- Explore the impact of vintage and wine region on quality ratings

## Contributing
We welcome contributions to enhance the Vintage Intelligence project. Please open an issue or submit a pull request.
