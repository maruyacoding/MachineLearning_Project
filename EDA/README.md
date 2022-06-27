## 어떤 문제를 해결하기 위해 EDA를 진행했는지?

- PUBG 배틀그라운드 플레이어의 데이터를 통한 승률 예측 (회귀, regression)

## EDA

- 1차 : 내가 맡은 columns(longestKill, headshotKills, KillStreaks, Kills, DBNOs, damageDealt)에 대한 데이터를 확인한다.
  -  kills count와 관련있는 데이터를 분포(distplot)를 확인한다.
  -  longestKill이 증가함에 따라 headshotKills가 증가함을 확인
  -  KillStreaks가 Kills에 포함되고 상관계수가 0.8로 높으므로 drop을 하기로 결정
  -  DBNOs의 대부분 데이터가 0에 있음을 확인
  -  damageDealt의 대부분 데이터가 0에 있음을 확인
<br>

- 2차 : Kaggle 참조 + 내생각을 합하여 전체적인 columns 및 데이터를 확인하여 이상치를 제거한다.
  - totalDistance columns 생성 후 totalDistance가 0인데 kills가 있는 경우 이상치
  - longestkills, walkDistance, swimDistance, rideDistance 이상치 확인
  - kill 관련 column 이상치 확인
