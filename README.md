# Wine_quality_prediction


This project aims to predict the quality of red wine using a machine learning model based on the given dataset. The dataset contains various chemical properties of red wine along with their corresponding quality ratings.

## Dataset

The dataset is provided in a CSV file named `winequality-red.csv`. It contains the following columns:

- fixed acidity
- volatile acidity
- citric acid
- residual sugar
- chlorides
- free sulfur dioxide
- total sulfur dioxide
- density
- pH
- sulphates
- alcohol
- quality

## Requirements

To run the project, you'll need the following Python libraries:

- pandas
- scikit-learn

You can install them using pip:
```bash
pip install pandas scikit-learn
```

## Usage

1. Download the project code and the dataset `winequality-red.csv`.

2. Make sure you have the required libraries installed.

3. Run the Python script `wine_quality_prediction.py`.

4. The script will load the dataset, split it into features and target, create a Linear Regression model, and then fit the model to the training data.

5. It will predict the wine quality using the test set and calculate the Mean Squared Error (MSE) and R-squared (Coefficient of Determination) to evaluate the model's performance.

6. The performance metrics will be printed on the console.

7. To predict the quality for new data, modify the `new_data` dictionary in the script with the new input data and run the script again.

## Note

- The provided example uses a simple Linear Regression model for wine quality prediction. Depending on the dataset and problem complexity, you might explore other machine learning models for better predictions.

