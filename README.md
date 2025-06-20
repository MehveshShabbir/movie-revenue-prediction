# TMDB Box Office Revenue Prediction

This project predicts movie box office revenue using the TMDB dataset and machine learning models in Python.

## Features

- Data cleaning and feature engineering on TMDB movie data
- Exploratory Data Analysis (EDA) with visualizations
- Predictive modeling using:
  - Random Forest Regressor
  - XGBoost Regressor
- Model evaluation and feature importance analysis
- Model serialization and prediction on new data

## Project Structure

- `TMDB_notebook.ipynb`: Main Jupyter notebook with all code and analysis
- `tmdb.csv`: Source dataset (not included in repo)
- `TMDB_prediction_model.pickle.dat`: Saved Random Forest model
- `.ipynb_checkpoints/`: Jupyter notebook checkpoints (ignored by git)

## Usage

1. Install requirements:
   ```sh
   pip install numpy pandas matplotlib seaborn scikit-learn xgboost missingno
   ```
2. Place `tmdb.csv` in the project directory.
3. Open and run `TMDB_notebook.ipynb` in Jupyter or VS Code.
4. The notebook will:
   - Clean and preprocess the data
   - Train and evaluate models
   - Save the trained model
   - Predict revenue for sample input

## Output

- The notebook prints model metrics and predicted revenue for a sample movie.
- Feature importance plots are generated for both models.

## Notes

- The dataset file (`tmdb.csv`) is required but not included in this repository.
- The trained model is saved as `TMDB_prediction_model.pickle.dat`.
