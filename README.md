# KUAIA_hackathon
2022.01에 고려대학교 산업경영공학과에서 주관한 KUAIA 해커톤에 관한 파일입니다.

여러 파일들이 혼재되어 있어 나중에 정리할 예정입니다.

## 프로젝트 내용
- 서울이 점점 고도의 도시화가 이루어지고 있고, 상권의 수와 규모 역시 늘어나고 있으나, 코로나 등의 이유로 폐업.
- 토지 가격 상승으로 인한 높은 임대료
- 새로운 상권 형성과 매출 예측의 결과가 중요해짐
- ###  데이터에 기반한 상권 분석이 필요


## 고려 사항
- 지하철, 학교, 편의시설과의 인접한 정도를 바탕으로 매출 예측
- 고매출 상권의 시각화, 인접 상권의 수월한 비교 가능
- 시각화; 지도와 중첩하여 예상 매출 파악
- 각종 시설과 건축물의 빠른 입지 결정에 도움

## 모델 개요
![image](https://github.com/PrayPrey/KUAIA_hackathon/assets/73458088/65a5b4bf-7dfc-4522-a413-8492c6ffbf10)
![image](https://github.com/PrayPrey/KUAIA_hackathon/assets/73458088/8579b400-ae40-430c-91d6-605dd9df936c)

## 데이터 전처리
![image](https://github.com/PrayPrey/KUAIA_hackathon/assets/73458088/26d62526-98b3-4153-a7ce-09034078c101)
![image](https://github.com/PrayPrey/KUAIA_hackathon/assets/73458088/d566bd25-dd92-483a-bf1c-de3a0a0b8e70)
![image](https://github.com/PrayPrey/KUAIA_hackathon/assets/73458088/284269c7-dfee-49ec-9589-7368bc69133d)
![image](https://github.com/PrayPrey/KUAIA_hackathon/assets/73458088/2b9c92fd-1672-4f5c-91e0-37cb35412127)

## 전체 모델 구조 (XGBoost)
![image](https://github.com/PrayPrey/KUAIA_hackathon/assets/73458088/1f000849-dc1b-417e-89df-6c7d59dccabd)
![image](https://github.com/PrayPrey/KUAIA_hackathon/assets/73458088/8780c235-e79e-4c16-ba73-475f7dd979ad)


## 최종 결과물 
### New_variable.ipynb 파일은 전처리 및 서비스 구현 결과 예시가 들어가 있습니다
### Regression_Model.ipynb 파일에는 실제 모델 학습 코드가 들어가 있습니다 (여러 모델 학습 시도 및 하이퍼파라미터 튜닝)
### Integrated 파일에서는 자율적인 분석을 진행하였습니다. (정리되지 않는 EDA)
### 최종 결과물 예시는 html 파일로부터 알 수 있습니다.
![image](https://github.com/PrayPrey/KUAIA_hackathon/assets/73458088/a39a8dd1-22b4-4419-9763-87a3b68c1aef)
![image](https://github.com/PrayPrey/KUAIA_hackathon/assets/73458088/6e8715aa-2ba7-4d7d-95f2-ae63010bab93)


