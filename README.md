# Boston_house_predict
# 🏠 Boston Housing Price Prediction

This project implements Linear Regression, Random Forest, and XGBoost **from scratch** to predict house prices using the [Boston Housing Dataset](https://www.kaggle.com/datasets/fedesoriano/the-boston-houseprice-data). The goal is to compare model performance and visualize feature importance.

##   Dataset
- Source: Kaggle - [Boston HousePrice Data](https://www.kaggle.com/datasets/fedesoriano/the-boston-houseprice-data)
- Target: `medv` - Median house value in $1000s
- Features: 13 numerical attributes like crime rate, number of rooms, etc.

##  Features
- Data normalization and preprocessing
- Linear Regression from scratch
- Random Forest from scratch
- XGBoost (basic custom implementation)
- Evaluation using **RMSE** and **R²**
- Visualization of **model comparison** and **feature importance**

##  Sample Output
- Console prints RMSE & R² scores
- Comparison and feature importance plotted using Matplotlib

##  How to Run
1. Clone the repo
    ```git clone https://github.com/yourusername/boston-house-price-prediction.git ```

   Install requirements:


```pip install -r requirements.txt ```

Run the model:

```python boston_price_prediction.py ```
