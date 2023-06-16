# Melbourne Housing Price Prediction

This repository contains a project for predicting housing prices in Melbourne, Australia. The project focuses on analyzing a dataset of housing market data and building regression models to predict the price of a home based on its features.

## Dataset

The dataset used in this project is `melb_data.csv`. It contains various features that describe a house when it was sold on the market, including the number of rooms, distance from the CBD, property type, number of bedrooms and bathrooms, land size, and more.

## Analysis and Modeling

The `project_submission.ipynb` notebook provides a step-by-step analysis of the dataset and the modeling process. It explores the relationships between the features and the price of the houses using visualizations and correlation analysis.

Several regression models are implemented and evaluated for their performance in predicting housing prices. The models include:

- Linear Regression
- Polynomial Regression
- Ridge Regression
- Lasso Regression
- RidgeCV (Ridge Regression with cross-validation)
- LassoCV (Lasso Regression with cross-validation)
- ElasticNetCV (Elastic Net Regression with cross-validation)

The performance of each model is measured using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R2 Score.

## Key Findings and Insights

Based on the comparison of the regression models, the ElasticNetCV model shows the best performance in terms of RMSE. However, all the models exhibit relatively high RMSE values, indicating that further improvements could be made.

The Polynomial Regression was not fully explored due to memory constraints, but it can be investigated further for potential improvement.

## Usage

To run the project and reproduce the results, follow these steps:

1. Clone the repository:

```
git clone https://github.com/your-username/melbourne-housing-prediction.git
```

2. Install the required dependencies. It is recommended to set up a virtual environment before installing the dependencies:

```
cd melbourne-housing-prediction
pip install -r requirements.txt
```

3. Open and run the `project_submission.ipynb` notebook in Jupyter or any compatible environment. Make sure to adjust the file paths if necessary.

## Contributing

Contributions to this project are welcome. If you have any suggestions, improvements, or additional features to add, feel free to submit a pull request or open an issue.

## Acknowledgments

- Credit to [Kaggle user nishathakkar](https://www.kaggle.com/code/nishathakkar/melbourne-housing-price-eda-and-rf-model#Feature-Engineering) for providing a framework for the analysis and modeling of the Melbourne housing dataset.

Feel free to customize this readme file according to your specific project details and requirements.
