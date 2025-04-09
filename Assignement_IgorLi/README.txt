# Cryptocurrency Price Prediction Using Machine Learning

## Project Overview
This project aims to predict the prices of the top 10 cryptocurrencies for the year 2025 using machine learning techniques. The project utilizes historical price data and sentiment analysis from news titles to train a model. The model predicts future prices using a linear regression approach.

## Requirements
- Python 3.x
- Libraries:
    - pandas
    - numpy
    - matplotlib
    - seaborn
    - scikit-learn
    - nltk
    - requests
- API:
    - CryptoCompare API (no registration required)

## Project Structure
- `crypto_price_prediction.py`: Main Python script for data collection, processing, sentiment analysis, model training, and predictions.
- `README.txt`: Documentation for the project.
- `requirements.txt`: List of Python libraries required to run the project.
- `data/`: Directory where data files are stored (if any).
- `models/`: Directory for saving trained machine learning models (optional).

## Steps to Run the Code
1. **Install Required Libraries**:
    - Install dependencies using pip:
    ```bash
    pip install -r requirements.txt
    ```

2. **Run the Python Script**:
    - Execute the script to collect cryptocurrency data, perform sentiment analysis, train the machine learning model, and generate price predictions for 2025:
    ```bash
    python crypto_price_prediction.py
    ```

3. **View the Results**:
    - The script will display the price trends for each cryptocurrency and the predicted prices for 2025.
    - Plots will be shown as output for each cryptocurrency.

## Model Details
- **Data Source**: CryptoCompare API (Historical price data for cryptocurrencies).
- **Model Used**: Linear Regression
- **Features**: Day of the year, Year, Sentiment score (from simulated news titles).

## Evaluation Metrics
- **RMSE (Root Mean Square Error)**: Measures the model's prediction accuracy.
- **R2 Score**: Indicates how well the model explains the variance in the data.

## Results
- The script will output the RMSE and R2 scores for each cryptocurrency, as well as show the predicted price trends for 2025.

## License
This project is open-source. You can freely use, modify, and distribute the code.

## Credits
- Data sourced from CryptoCompare API.
- Machine learning model and sentiment analysis implemented using Python.
