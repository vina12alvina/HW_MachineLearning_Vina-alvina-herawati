# Sales and Advertising Cost Prediction

This repository contains a project to predict advertising costs based on sales using simple linear regression.

## Project Description

A company wants to predict the advertising cost required to achieve certain sales targets. This project uses historical data to build a simple linear regression model that predicts advertising costs based on sales figures.

## Data

The dataset used in this project can be found [here](https://www.econometrics.com/intro/SALES.txt). It contains two columns:
- `Sales`: Sales in million dollars
- `Advertising`: Advertising cost in million dollars

## Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib

## Running the Code

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/sales-advertising-prediction.git
    cd sales-advertising-prediction
    ```

2. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

3. Run the script:
    ```sh
    python sales_advertising_prediction.py
    ```

## Results

The model's performance is evaluated using RMSE and R² score. The advertising costs predicted for sales values of 50, 100, and 150 are as follows:
- Predicted advertising cost for 50 sales: $X million
- Predicted advertising cost for 100 sales: $Y million
- Predicted advertising cost for 150 sales: $Z million

## Interpretation

The regression model provides an estimate of the advertising costs based on sales figures. The R² score indicates the proportion of variance in the dependent variable that is predictable from the independent variable.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
