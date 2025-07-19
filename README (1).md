# Ethereum Price Prediction (Next 2 Days) Using ML Models

This project predicts the **next 2 days' Ethereum prices** using historical data and multiple machine learning models (Linear Regression, Decision Tree, Random Forest, Support Vector Machine, and K-Nearest Neighbors).

## Features
- **Data Source:** Uses Yahoo Finance (`yfinance`) to fetch the last 1-year historical data for Ethereum (ETH-USD).
- **Machine Learning Models:**
  - Linear Regression
  - Decision Tree Regressor
  - Random Forest Regressor
  - Support Vector Machine (SVR)
  - K-Nearest Neighbors (KNN)
- **Lag Features:** Uses previous 3 days' prices as features for prediction.
- **Evaluation:** Calculates the Mean Squared Error (MSE) of each model to find the best performer.
- **Forecasting:** Predicts Ethereum prices for the **next 2 days** based on the trained Random Forest model.
- **Visualization:** Plots actual vs. predicted prices and highlights the forecasted prices.

## Technologies Used
- Python 3.8+
- Libraries: pandas, numpy, yfinance, matplotlib, scikit-learn

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ethereum-price-prediction.git
   cd ethereum-price-prediction
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the script:
   ```bash
   python ethereum_price_prediction.py
   ```

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
