# Ethanol-Price-Predictions
Brazilian spot ethanol prediction data using LSTM.

Meaning of columns:

Database CEPEA file:

Price R$ : Ethanol price in reais observed.

Price US$: Ethanol price in dollars observed.




Predictions_63_Horizon, Predictions_126_Horizon, Predictions_252_Horizon files:


Date_Pred: Day for which the forecast is performed.

Price: Ethanol price on forecast day (N days ahead of forecast price)

Predicted_Price: Predicted price N days ahead.

Actual_Price: Actual price verified N days ahead.

Mov_Pred: Predicted price movement (1 high, 0 low)

Mov_true: Verified price movement (1 high, 0 low)
