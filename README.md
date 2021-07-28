# project1
fifa19 게임 데이터셋을 이용한 축구선수 Wage 예측
----------------------
![KakaoTalk_20210604_171524692_01](https://github.com/erdosnumber0/project_fifa/blob/main/project1.png)
- ppt: (https://www.slideshare.net/secret/5IOuP2ROm7zJ6y)
-----------------

### 1. About: 

- 개인 프로젝트
- 기간: 21.02.01 ~ 21.02.24
- Stacks
```
- Language: Python
- IDE : Jupyter Notebook, Pycharm
- Library: Pandas, Numpy, Matplotlib, Seaborn, Statsmodels, Scikit-learn
```

----------------------------

### 2. 이슈: 

축구 선수의 Wage는 어떤 요소에 영향을 받을까?

----------------------------

### 3. 프로젝트 과정:

- fifa19 게임 데이터셋에서 각 칼럼의 의미를 분석, Club, Overall를 이용하여 파생변수 생성. 
- Ensemble Algorithm: 불평등한 Wage분포를 극복하고 예측하기 위해 XGBoost와 LightGBM 사용
- 추가 시행: 종속변수 Wage를 분위 회귀 분석(Quantile regression) 시행                 



