# Gold-Price-Prediction

### Version 1
This project builds a machine learning model to predict Gold (GLD) prices using historical market indicators such as "SPX", "USO", "SLV", and "EUR/USD".
The model uses a Random Forest Regressor, known for its robustness and ability to capture non-linear patterns.

This repository documents my learning process and demonstrates end-to-end workflow from data exploration to model evaluation.

---

#### Features
  - Data exploration and preprocessing
  - Correlation heatmap
  - Distribution analysis
  - Train–test split
  - Random Forest model training
  - Evaluation using R² score
  - Actual vs predicted plots

---

#### Model Used

RandomForestRegressor (scikit-learn)
  - 100 trees
  - Handles complex relationships
  - Resistant to overfitting
  - Performs well on tabular financial data

---

#### Dataset

The dataset is included in this repository:
  - "gld_price_data.csv"
  - Contains gold price and related market indicators

---

#### Results

- Achieved scores:
    - R squared error :  0.9900411625357386
    - MAE:  1.2409960695414846
    - RMSE:  2.3367562009346283
    - Pearson Correlation:  0.9950120323665074
    - MAPE (%):  1.0062523284551306
- Random Forest shows strong alignment between actual and predicted prices
- Plot visualizations clearly show trends learned by the model

---

#### Future Improvements

- Add lag features and moving averages
- Hyperparameter tuning with GridSearchCV
- Try XGBoost, CatBoost, or LSTM models
- Deploy using Streamlit or Flask

---

#### License

This project is licensed under the MIT License.
See the "LICENSE" file for details.

#### Resorces

- YouTube Tutorial:
    https://youtu.be/9ffkBvh8PTQ?si=fi7GY--3oKFTyo94
- Dataset Source:
[https://www.kaggle.com/<link-here>
](https://www.kaggle.com/datasets/altruistdelhite04/gold-price-data)
