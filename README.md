This is a **machine learning model** using _Python_ to predict any closing stock price based on a limited set of features, including the stock’s opening price and date-related variables (day, weekday, and day of the year). Using historical stock data pulled from the _yfinance API_ and the _pandas_ and _scikit-learn libraries_, I trained and tested a _linear regression model_ to evaluate how well simple time-based features could model price behavior.

**Tools & Technologies:**
- Python (Jupyter Notebook)
- Libraries: yfinance, pandas, matplotlib, scikit-learn
- Linear Regression Model
  
**Evaluation Metrics**:
- R² Score
- RMSE
  
**Key Features:**
- Automatic download of real-time stock data using the yfinance API
- Feature engineering using calendar-based patterns (day, weekday, day of year, etc.)
- Train-test split of data points for model evaluation
- RMSE and R² score reporting for performance analysis
- Visualization of predicted vs. actual closing prices


**My Own Insight**:

This project taught me how data, when thoughtfully selected, can offer valuable predictions. I was surprised to see that the model could capture some underlying trends. However, this also showed me the _limits of linear models_ when dealing with something as dynamic and noisy as stock prices.
A big takeaway for me was understanding how important _feature selection_ and _data quantity_ are in real-world machine learning problems. I also learned how to visualize and interpret results beyond just metric, looking at prediction curves helped me spot inconsistencies and think critically about _model accuracy_ and _overfitting_.
This project sparked my curiosity about applying more advanced models (like Random Forests or LSTM networks) and incorporating features like technical indicators or sentiment data to improve predictions in the future.

