

## Project Details

This project predicts the stock price of State Bank of India (SBI) using a LSTM model.

## Dependencies

- tensorflow
- joblib
- yfinance
- streamlit
- plotly
- pandas-market-calendars
- scikit-learn

Create conda environment and Install dependencies using:

```bash
conda create -n sbi_sto_env python=3.12
conda activate sbi_sto_env
pip install -r requirements.txt
```

## Run the Streamlit App

To run the Streamlit app locally, use the following command:

```bash
streamlit run app.py
```

## Streamlit Hosted App

You can view the hosted Streamlit app at:

https://sbi-stock-prediction.streamlit.app/

## Notebook

The `univariate/univariate_stock_price_prediction.ipynb` notebook contains the code for training the LSTM model and saving the scaler.
