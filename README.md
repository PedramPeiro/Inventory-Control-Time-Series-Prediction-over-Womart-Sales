# Inventory-Control-Time-Series-Prediction-over-Womart-Sales

link of the dataset: 
https://www.kaggle.com/shelvigarg/sales-forecasting-womart-store


## Different Approches used in this notebook:
1. Last Period Demand
2. Simple Moving Average
3. Trending Moving Average
4. Weighted Moving Average
5. Simple Exponential Smoothing
6. Trending Exponential Smoothing
7. Seasonal exponential Smoothing
8. Simple Linear Regression
9. Adjusted Linear Regression

*Note that we applied parameter tuning in the methods having parameters. The plots contain different parameters too (for better illustration).*

## Assessment metrics
All of these models are assessed using different metrics:
1. Mean of Errors (ME)
2. Mean of Absolute Errors (MAE)
3. Mean of Squared Errors (MSE)
4. Probable Error (PE)
5. Mean of Probable Errors (MPE)
6. Mean of Absolute Probable Errors (MAPE)
7. Test Statistic (TS)
8. Moving Range Chart

## Best Model
Among all of these different approches, best model was **Seasonal Exponential Smoothing with \alpha=0.9 and c=0.7**
![image](https://user-images.githubusercontent.com/102898063/162277227-138a3647-36f9-4037-9628-4ad0d14a28f6.png)

You can have a better reveiw and understanding of the whole project in the pdf attached to this folder.
Thanks for your time.
