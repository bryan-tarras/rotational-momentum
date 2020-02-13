# rotational-momentum
 Rotational Momentum Trading Algorithm

This algorithm rotates between the best performing ETF amoung a list of 19 ETFs that represent major Industrial Sectors in the US.

Ranking is based on 4 criteria:
- Momentum across period "A"
- Momentum across period "B"
- Volatility across period "S"
- Predicted Return based on ML Algorithm

The ML algorithms explored can be seen in the "Final_Project_ML_models" file.

4 Trading algorithms have been developed. They are as follows:
- Baseline Model (No ML, Just Trading on Momentum across "A", "B", and Volatility across "S")
- Trading with Ranking including Random Forest Regression Predictions across a 20W-Thu period
- Trading with Ranking including Random Forest Classification Predictions for quartile performance across a 20W-Thu period
- Trading with Ranking including Support Vector Machine Predictions across a 20W-Thu period
