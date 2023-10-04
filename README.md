
## School : yonsei university
## major: digital analytics
## data scientist

### 대학원 진행연구
______
### 데이터 합성 판별 알고리즘
설명: x-ray 합성데이터를 판별할 수 있는 알고리즘 구현, 직접 dcgan, ddpm 으로 이미지 합성을 시행, ddpm 특성상 노이즈를 주고 다시 빼는 학습을 통해 이미지 생성, 이 특성을 활요하여 통계적 특성을 사용한 starex 알고리즘 개발, resnet50 기존 분류모델보다, 합성 판변 분야에서 computation cost가 극도로 절약되고, 더 우수한 성을 보임


### 크론질병  attention based multiple instance learning
설명:내시경 이미지 특성상, 환자당 이미지가 20~30장 이미지가 나옴, 각각 환자마다 이미지 개수가 다르고 라벨도 bag 단위의 라벨만 있고 개별 이미지에 대한 라벨링이 안된 weakly supervised 상태에서, attention based multiple instance learning 으로 연구진행

### 크론질병  classification model
설명:크론질병 내시경 이미지를 이용하여 분류 모델을 구현, resnet 50 vggnet 기본적인 모델을 사용했고, 기본적으로 resnet50사용
추가적으로 bag단위로 묶는 resnet50도 시도, 논문화를 위한 gradcam 같은 작업 진행

### 이미지 clustering and image classification

내시경 이미지를 resnet 50으로 feature 추출이후에 clustering을 진행 k_means 등 다양한 clustering 작업하였고
cluster 안에서 다시 resnet50으로 분류모델 구현후 성능비교 이 연구를 통해 내시경 이미지 에는 노이즈 많은 이미지들이 많은데, 불필요한 이미지들 끼리 cluster 되기를 기대하였음

학부 진행해본 프로젝트
----
### 심장질환 예측 모델
설명: kaggle에서. heart disease데이터를 사용하였습니다. 성별 나이 심전도 혈압 등이 있습니다. 
K-NN, 로지스틱리그레션, SVC, 가우시안, 의사결정나무 등 여러 알고리즘을 사용하고 파라미터도
바꿔보고 가장 좋은 알고리즘을 사용하여서 심장 질환 분류 모델을 만들고 혼동행렬도 그려 결과
를 확인했습니다.

### 피부질환 인식 아이폰 어플리케이션
설명: 프로메테우스 해커톤에 참여했을 때 진행한 프로젝트입니다. 피부암 7종류 이미지 데이터를
구했고, cnn을 이용하여서 학습시켰습니다. 이번 해커톤은 모델뿐만 아니라 서비스까지 구현해야
해서, 모델을 구현 후 프론트는swift 서버는 장고, 데이터베이스는 mysql을 사용하여서 아이폰 어
플리케이션을 구현하였습니다. 여기 팀에서 제가 주로 담당한 것은 cnn으로 모델구현과, 백엔드
를 도왔습니다.

### 주가예측 모델
설명:비트코인 데이트를 가져와 cnn으로 미래 주가를 예측하는 프로젝트였습니다. 데이트를 그래
프화 시켰고 cnn으로 다음날 상승 보합 하락 라벨링후에 학습시켰습니다. 이번 프로젝트에서는
데이터는 저희가 직접구했고, 데이터를 차트화시키고 라벨링도 직접했습니다. 주가예측에 대한 성
과는 좋지는 않았습니다.

### 월 이동인구 예측
설명:기업 kt 코치님들과 진행하는 ai-x선도인재양성과정중에 진행된 프로젝트입니다. 2017년부터
2021년도까지 매일 시간단위의 kt통신망을 통해얻은 이동인구 데이터를 이용하여서, 2022년도 2
월의 인구수를 예측하는 프로젝트였습니다. RMSE로 평가하였고, kaggle competiton으로 진행되었
습니다. 계속 설날에 인구수가 급변하고, 코로나등 다양한 요인들이 많아서, 정확한 예측이 어려
웠지만, python shift함수로 다양한 독립변수를 만들면서 요일은 맞추게하고, 설날 부분과 매년 초
부분을 조정하고 해서 rmse를 많이 낮출 수 있었고, 딥러닝, 다중선형회기, 랜덤포레스트, xgboost 
다양한 알고리즘을 사용해 보았는데, 딥러닝이 가장 결과가 안좋았고, 다중선형회귀랑, xgboost가
좋았습니다. 오히려 여기서는 특이값을 제거하는 데이터 전처리 그리고 후처리가 더 중요한 프로
젝트였습니다.
 
<!---
min-program/min-program is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
