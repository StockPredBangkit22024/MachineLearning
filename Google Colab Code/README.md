# Notebook of StockPred

This repository includes several notebooks designed for training stock prediction models. The primary notebook for model training is [Combined Model for 20 Stocks.ipynb](Combined%20Model%20for%2020%20Stocks.ipynb).

## Files Included
- [**Combined Dataset.ipynb**](Combined%20Dataset.ipynb): This notebook focuses on preparing and merging datasets for various stocks.
    - **Data Used**: 20 stock dataset, BI-rate, data USDIDR per bulan, and infation rate.
- [**Combined Model for 20 Stocks.ipynb**](Combined%20Model%20for%2020%20Stocks.ipynb): This is the main notebook utilized for training a predictive model based on data from 20 different stocks.
    - **Data Used**: The combined dataset from the previous notebook.
- [**Conversion of SavedModel to TensorFlow.js.ipynb**](Conversion%20of%20SavedModel%20to%20TensorFlow.js.ipynb):This notebook is dedicated to converting a TensorFlow SavedModel into a format suitable for TensorFlow.js deployment.
    - **Data Used**: The SavedModel.
- [**Model Testing.ipynb**](Model%20Testing.ipynb): A notebook dedicated to testing the performance and accuracy of the trained models.
    - **Data Used**: model.zip, skala_X.pkl, and skala_Y.pkl.
- [**Single Stock Model for Stock Selection.ipynb**](Single%20Stock%20Model%20for%20Stock%20Selection.ipynb): This notebook is centered on training models for analyzing and selecting individual stocks.
    - **Data Used**: Data for one stock, BI-rate, monthly USD to IDR exchange rates, and inflation rates.
    - **Note**: Remember to change the stock code when executing this notebook.
- [**Stock Dataset.ipynb**](Stock%20Dataset.ipynb): A notebook for preparing datasets specifically related to stocks.
- [**USD_IDR Exchange Rate Dataset.ipynb**](USD_IDR%20Exchange%20Rate%20Dataset.ipynb): A notebook that manages datasets concerning the USD to IDR exchange rate, which may be used as a feature in stock predictions.

## How to Use
To use Google Colab effectively, follow these steps:
1. **Upload Files**: Start by uploading your files to the Google Colab platform.
2. **Data Upload**: Ensure you upload the specific data required for your notebook.
3. **Check File Paths**: It's crucial to verify the path of your data files to ensure they can be accessed correctly.
