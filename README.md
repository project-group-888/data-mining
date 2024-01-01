## Project Title:
**Beyond Charts: Stock Price Prediction with Combined Machine Learning Algorithms**

## Description:
This project explores the prediction of stock prices using a combination of machine learning algorithms, such as random forest regression, decision trees, xgb and adaboost. This project combines different algorithms into a voting regression model and make predictions for future stock prices.

## Installation:
To run this project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/stock-price-prediction.git
   cd stock-price-prediction
   ```

2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Dependencies:
This project requires the following Python libraries:

- pandas==1.3.3
- numpy==1.21.2
- matplotlib==3.4.3
- scikit-learn==0.24.2
- plotly==5.3.1
- ta==0.7.0

You can install these dependencies using pip. Create a `requirements.txt` file in your project directory and copy the above libraries and their versions into it. Then run the following command:

```bash
pip install -r requirements.txt
```

## Data:
The project uses historical stock price data for the chosen stock "STOCK_NAME" variable(default is AMZN-AMAZON), which is contained in the `AMZN.csv` file. Please ensure that you have a csv file that consists historical stock data for the stock you want to work on.

## Usage:
After installing the dependencies and ensuring the data file is in place, you can run the project using Python:

```bash
python main.py






