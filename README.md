# Food Delivery Waiting Time Prediction

## Overview
This project aims to predict food delivery waiting time (in minutes) using order-level data.  
The goal is to explore how basic order information can be used to estimate customer waiting time and identify key factors affecting delays.

## Objective
- Build regression models to predict total waiting time
- Compare baseline and machine learning models
- Interpret results from both technical and business perspectives

## Dataset
The dataset contains approximately 1,900 food delivery orders with features such as:
- Day type (weekday / weekend)
- Cuisine category
- Cost of the order
- Target variable: total waiting time (minutes)

> Note: The dataset is used for educational purposes.

## Methodology
1. Exploratory Data Analysis (EDA)
2. Baseline model (mean predictor)
3. Linear Regression
4. Decision Tree
5. Random Forest
6. Cross-validation and error analysis

## Results
- **Best Model:** Linear Regression  
- **Performance:**  
  - Mean Absolute Error (CV) â **5.2 minutes**
- Tree-based models did not outperform the linear baseline due to limited feature richness.

## Key Insights
- Day of week is the strongest predictor of waiting time.
- Cuisine type has a moderate effect on delays.
- Order cost alone is a weak predictor of delivery time.

## Limitations
Missing operational features such as:
- Distance between restaurant and customer
- Traffic conditions
- Rider availability

## Future Work Possible
- Add geospatial and time-of-day features
- Model preparation time and delivery time separately
- Explore classification for late delivery prediction

## Tools & Libraries
- Python
- pandas, numpy
- scikit-learn
- matplotlib, seaborn

---

Author: Chitsanupong Chinsirichokchai, IE, Chulalongkorn University
