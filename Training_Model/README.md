## 모델 학습
<br>

### feature engineering을 진행한 데이터를 가지고 모델 학습을 진행

1차 : 1차 feature engineering을 진행한 데이터를 가지고 Modeling
- LinearRegression MAE : 0.097418
- Lasso MAE : 0.126241
- Ridge MAE : 0.097417
- LGBMRegressor MAE : 0.064046
- XGBRegressor MAE : 0.071953
<br><br>

2차 : 2차 feature engineering을 진행한 데이터를 가지고 Modeling
- LinearRegression MAE : 0.1049
- Lasso MAE : 0.1261
- Ridge MAE : 0.1049
- LGBMRegressor MAE : 0.0681
- XGBRegressor MAE : 0.0741
<br><br>

3차 : 3차 feature engineering을 진행한 데이터를 가지고 Modeling
- LinearRegression MAE : 0.1060
- Lasso MAE : 0.1656
- Ridge MAE : 0.1060
- LGBMRegressor MAE : 0.0808
- XGBRegressor MAE : 0.0839
<br><br>

4차 : 4차 feature engineering을 진행한 데이터를 가지고 Modeling + LGBMRegressor feature importances
- LinearRegression MAE : 0.0581
- Lasso MAE : 0.1148
- Ridge MAE : 0.0581
- LGBMRegressor MAE : 0.0467
- XGBRegressor MAE : 0.0417
<br><br>
