# Stock-Price-Prediction

This project demonstrates various machine learning models for predicting stock prices using historical data from Yahoo Finance.

## Models Used
1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor
4. Support Vector Regressor (SVR)
5. Long Short-Term Memory (LSTM) Network

## Steps
1. **Data Collection**: Collected historical stock price data using the Yahoo Finance API.
2. **Data Preprocessing**: Preprocessed the data to create features and targets for the models.
3. **Model Training**: Trained multiple models on the training data.
4. **Model Evaluation**: Evaluated and compared the models' performance using Mean Squared Error (MSE) and visualizations.

## Results
- Linear Regression MSE: 4.483507164009182
- Decision Tree Regressor MSE: 59.71230484369305
- Random Forest Regressor MSE: 66.37822387462234
- Support Vector Regressor MSE: 461.23044765446707
- LSTM MSE: 4.453972093244338

## How to Run
1. Clone the repository.
2. Install the required libraries: `pip install yfinance pandas scikit-learn matplotlib tensorflow`.
3. Run the script to see the results.

## License
This project is licensed under the MIT License.
