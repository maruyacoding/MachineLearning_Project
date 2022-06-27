## 팀원들의 EDA를 토대로 Feature engineering을 진행
<br>

1차 : 원본 데이터 (raw data)에서 object dtype feature를 drop
<br><br>
2차 : 각 팀원들이 1차 EDA를 진행하여 얻은 인사이트를 활용하여 전처리
<br><br>
3차 : 각 팀원들이 2차 EDA를 진행하여 얻은 인사이트를 활용하여 전처리
<br><br>
4차 : 원본 데이터 (raw data)에서 GroupId 별로 groupby 진행 후 각 group의 feature 평균값을 적용하여 전처리
