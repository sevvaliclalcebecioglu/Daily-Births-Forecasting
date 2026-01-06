# Daily Female Births Forecasting

This project forecasts the daily number of female births using **Python** and **Facebook Prophet**.

https://huggingface.co/spaces/sevvaliclal/DailyBirthsForecasting

## 📊 Dataset

- Source: `daily-total-female-births.csv`
- Content: Daily female births throughout 1959
- Columns:
  - `Date` : Date
  - `Births` : Number of births

## 🛠 Libraries Used

- pandas, numpy
- matplotlib, seaborn, plotly
- prophet (Facebook Prophet)
- joblib (for saving and loading the model)

## 📈 Model

- Prophet time series model is used.
- The model predicts daily births and shows trend & seasonality components.

## 💾 Saving the Model

The model is saved as `daily_births_model.pkl`
