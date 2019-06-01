## Dacon Data analysis compitition with USW.2019 

```##Dacon Data analysis 1st compitition with USW. 타이타닉 : 과연 누가 살아남았을까

RMS 타이타닉은 역사상 가장 유명한 난파선 중 하나입니다.

1912년 4월 15일, 타이타닉은 항해중 빙산과의 충돌로 인해 침몰합니다. 탑승인원 2224명 중 1502명이 사망한 비극적인 사건이었고, 선박의 안전규정을 개선시키는 계기가 되었습니다.

이 과제에서는 여러분은 어떤 종류의 사람들이 많이 살아남았는지에 대한 분석을 해야 합니다.
그리고 머신러닝을 이용해 어떤 승객이 생존했을지 예측해보세요. 

제출 : 2019년 4월 27 일 AM 0시 ~ 
2019년 5 월 24 일 PM 24시 (UTC +9) 

제출한 예측 결과물은 Area Under Curve(AUC)로 평가합니다(평가는 게시된 데이터셋만을 기준으로 합니다).
AUC가 높은 순으로 상위 5명에 대해서는 코드 검증를 진행합니다. 

[Files]
① train.csv : 타이타닉 탑승자들 중 일부의 인적정보와 생존 여부 데이터
② test.csv: 타이타닉 탑승자들 중 일부(train set의 탑승자 제외)의 인적정보 데이터
③ gender_submission.csv : submission 파일의 예시

[Data fields]
① train.csv - 타이타닉 탑승자들 중 일부의 인적정보와 생존 여부 데이터

PassengerId : 탑승객의 고유 아이디
Survival : 생존유무(0: 사망, 1: 생존)
Pclass : 등실의 등급
Name : 이름
Sex : 성별
Age : 나이
Sibsp : 함께 탑승한 형제자매, 아내 남편의 수
Parch: 함께 탑승한 부모, 자식의 수
Ticket: 티켓번호
Fare: 티켓의 요금
Cabin: 객실번호
Embarked: 배에 탑승한 위치(C = Cherbourg, Q = Queenstown, S = Southampton)

③ gender_submission.csv - submission 파일의 예시

PassengerId : 탑승객의 고유 아이디
Survived : 생존여부에 대한 예측치 ```



## Dacon Data analysis 2nd compitition with USW. 축구 데이터 : 누가 이길 것인가

토토 중 가장 인기 있는 종목인 축구 데이터입니다.

토토를 한다고 생각하고 어떤 팀이 이겼을 지 예측해보세요! 

제출 : 2019년 5월 31 일 AM 0시 ~ 
2019년 6 월 21 일 PM 24시 (UTC +9) 


제출한 예측 결과물은 Area Under Curve(AUC)로 평가합니다(평가는 게시된 데이터셋만을 기준으로 합니다).
AUC가 높은 순으로 상위 5명에 대해서는 코드 검증를 진행합니다. 이는 치팅의 위험을 방지하기 위함으로 검증절차는 아래와 같습니다. 

Data	[Files]
① toto_train.csv : 각 경기별 기본 정보와 승패정보
② toto_test.csv: 각 경기별(train set의 경기 제외)의 기본정보 데이터
③ analyst_pick.csv: 경기별로 와이즈 토토(wisetoto.com)의 분석위원들이 어떤 예측을 했는지 데이터
③ submission.csv : submission 파일의 예시

[Data fields]
① toto_train.csv - 각 경기별 기본 정보와 승패정보

game_id: 게임별 고유 아이디
date: 경기 날짜
win_percentage: 경기별로 사람들이 어떤 선택을 했고 각각의 배당률이 어떻게 되는지 정보
home_team: 홈 팀의 정보
away_team: 원정 팀의 정보
home_team_recent_10: 홈 팀의 최근 10경기 성적
away_team_recent_10: 원정 팀의 최근10경기 성적
result: 결과 (1: 홈 팀 승, 0: 원정 팀 승)


③ analyst_pick.csv - 경기별로 와이즈 토토(wisetoto.com)의 분석위원들이 어떤 예측을 했는지 데이터

game_id: 게임별 고유 아이디
analyst: 분석위원
choosed: 분석위원의 예측(1: 홈 팀 승, 0.5: 무승부, 0:원정 팀 승)

③ submission.csv - submission 파일의 예시

game_id: 게임별 고유 아이디
result : 예측한 결과값 기입 
Caution	① 대회 및 수상에 관련된 일정과 규칙은 상황에 따라서 변동이 있을 수 있습니다. 공지 및 업데이트를 확인하시기 바랍니다.
② 인간 예측, 수기 입력, API연동, 검색 등을 통해서 submission 제출 시 실격 처리 및 랭킹에서 제외됩니다.
③ 외부 데이터는 사용 금지입니다. 
