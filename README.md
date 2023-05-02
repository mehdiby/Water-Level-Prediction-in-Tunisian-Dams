# Water Level Prediction in Tunisian Dams

![water_level_image](https://assafirarabi.com/wp-content/uploads/2021/06/%D8%A7%D9%84%D8%B1%D9%8A-%D8%A8%D8%A7%D9%84%D8%B3%D9%8A%D9%81%D9%88%D9%86%D8%A7%D8%AA-%D8%AA%D9%88%D9%86%D8%B3.jpg)

Water scarcity is a real threat facing not only Tunisia but the entire world. With water being a finite resource, it's essential to measure and manage it accurately to avoid shortages and ensure access to clean water for all. This project aims to predict the water level in various dams across Tunisia using machine learning algorithms, which could be used to improve water management and mitigate the risk of water shortages.

## Data

The data for this project consists of two CSV files:

- `dam_data.csv`: Contains the water level measurements for 28 Tunisian dams from 1/8/2014  to 2/5/2019.
- `weather_data.csv`: Contains daily weather data (temperature, precipitation, wind speed, etc.) for weather stations located near the dams.

## Methodology

We used Jupyter Notebook and Python to preprocess the data and train machine learning models. After cleaning the data and exploring its features, we trained several models, including Random Forest, XGBoost, and Gradient Boosting, to predict the water level in each dam. We evaluated the models using root mean squared error (RMSE) and found that the combination of Random Forest, XGBoost, and Gradient Boosting algorithms provided the best results, achieving an RMSE of 15.4.

## Visualization

We used Matplotlib and Seaborn to visualize the water level predictions for each dam and the correlation between the water level and weather features. The visualizations provided insights into the relationships between the variables and helped us to better understand the data.

We also generated a report of the data using pandas profiling, which provided a quick and easy way to get insights into the data. You can view the report by clicking [here](./reports/report.html).

## Notebook

To reproduce the results of this project, please refer to the Jupyter notebook `water_level_prediction.ipynb`. 

## Conclusion

This project demonstrates the effectiveness of machine learning algorithms in predicting water levels in dams when weather data is incorporated into the model. By accurately predicting water levels, we can improve water management and mitigate the risk of water shortages in Tunisia and beyond. The combination of Random Forest, XGBoost, and Gradient Boosting algorithms proved to be the most effective in predicting water levels in Tunisian dams, achieving an RMSE of 15.4.
