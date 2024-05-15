# Game Rating Data Analysis

This repository contains Python code for analyzing game rating data using various regression models. The code includes data preprocessing, model training, and evaluation.

## Getting Started

To run the code, follow these steps:

1. Clone this repository to your local machine.
2. Install the required dependencies using pip:
   ```bash
   pip install pandas numpy seaborn matplotlib fancyimpute scikit-learn xgboost lightgbm catboost
   ```
3. Download the dataset `game-rating-data-set-train.csv` and `game-rating-data-set_test.csv`.
4. Execute the Python script `game_rating_analysis.py`.

## Dependencies

The following Python libraries are used in this project:
- pandas
- numpy
- seaborn
- matplotlib
- fancyimpute
- scikit-learn
- xgboost
- lightgbm
- catboost

## File Descriptions

- `game_rating_analysis.py`: Python script containing the main code for data analysis.
- `game-rating-data-set-train.csv`: Training dataset containing game rating data.
- `game-rating-data-set_test.csv`: Test dataset for evaluating the trained models.

## Usage

The `game_rating_analysis.py` script performs the following tasks:

1. Data preprocessing:
   - Loading the dataset using pandas.
   - Dropping irrelevant columns.
   - Converting data types and performing feature engineering.

2. Model training:
   - Splitting the dataset into training and test sets.
   - Training various regression models including Linear Regression, Gradient Boosting, XGBoost, Random Forest Regression, Ridge Regression, Lasso Regression, ElasticNet, Huber Regression, and CatBoost.

3. Model evaluation:
   - Calculating Mean Squared Error (MSE) for each model.
   - Visualizing the performance of different models using a bar chart.

4. Best model selection:
   - Identifying the top three models based on MSE.

## Results

The trained models are evaluated based on their MSE scores, and the top-performing models are selected for further analysis.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
