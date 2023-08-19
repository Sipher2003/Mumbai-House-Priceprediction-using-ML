# Mumbai House Price Prediction

My first Data Science and Machine Learning project! In this project, I've developed a model to predict house prices in Mumbai using various features. The dataset used for this project was obtained from Kaggle. You can find the dataset [here](https://www.kaggle.com/datasets/karanchinchpure/house-price-predict-in-mumbai-city).

## Project Overview

This project is about predicting house prices in Mumbai, a city with a dynamic real estate market. The goal was to create a machine learning model that could predict house prices based on different attributes like square footage, number of bedrooms, location, etc.

### Data Exploration and Cleaning

- I started by exploring the dataset obtained from Kaggle.
- The dataset had a mix of good and not-so-good quality data.
- I performed data cleaning, which involved handling missing values and converting the price column into proper numerical values.
- I used data visualization techniques such as charts and graphs to gain insights into the data distribution and relationships.

### Feature Engineering and Preprocessing

- I dropped unnecessary columns that wouldn't contribute to the prediction.
- Outliers were detected and handled to improve the model's robustness.
- I used one-hot encoding to convert categorical variables, especially the 'location' feature, into numerical values for model training.

### Model Selection and Training

- I evaluated three different regression models: Linear Regression, Random Forest Regressor, and Decision Tree Regressor.
- To find the best model, I utilized GridSearchCV for hyperparameter tuning.
- Based on the results, the Random Forest Regressor showed the best performance, so I selected it as the final model.

### Model Deployment

- After selecting the Random Forest Regressor as the best model, I trained it on the cleaned dataset.
- I saved the trained model as a pickle file, which can be used for making predictions without retraining the model every time.


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


Happy coding!

 
