# PredictStockPrice

This project aims to predict stock prices using machine learning models. We explore several approaches, including time series forecasting (ARIMA), econometric factor analysis, and deep learning models trained on a large dataset.

## 📁 Folder Structure

### `full/`
- Contains data of five specific companies targeted for prediction.
- Used during the initial phase for data extraction testing and implementing the ARIMA-based approach.

### `data/`
- Includes datasets of companies operating in similar industries as the five main companies.
- Divided into:
  - Five subfolders (one for each industry),
  - A `merge/` folder combining all industry data.
- Used to evaluate the impact of various influencing factors and whether industry-specific characteristics affect prediction accuracy.

### `big_data/`
- Contains data from over 400 Vietnamese companies.
- Used for:
  - Econometric factor analysis,
  - Training advanced machine learning models.
- Includes:

  #### `results/`
  - Output of the model training process.
  - `Submit 1/`: Experimental results using smaller parameters.
  - `Submit 2/`: Final results used for official evaluation.
  - CSV files: Contain prediction outputs.
  
  #### `results/Predict/`
  - Stores the final trained model in `.keras` format.
  - Includes the model's final prediction results.

- Model training was conducted using Kaggle. Corresponding notebooks and output files are also saved here.

---

Feel free to explore the folders to understand different stages of data preparation, modeling, and evaluation in this stock price prediction project.
