# 인공지능과 컴퓨팅사고력
- 프라임칼리지 평생교육과정 일반교양 (2학점)

### 목차
- [1강. 인공지능의 의미](#1강-인공지능의-의미)
  - [인공지능이란?](#인공지능이란)
  - [기계학습이란?](#기계학습이란)
  - [신경망과 딥러닝이란?](#신경망과-딥러닝이란)

## 1강. 인공지능의 의미
### 인공지능이란?
- 인공지능의 접근 방법
  - **Symbolic AI** (**기호주의 인공지능**)
    - 규칙 기반 지식 표현
    - `예) IBM Deep Blue`
  - **Connectionist AI** (**연결주의 인공지능**)
    - 다른 말로 Non-Symbolic AI
    - Artificial Neural Networks (인공신경망)
      - 인간 두뇌에서 영감을 받은 계산 모델
      - 신경망: 퍼셉트론, 딥러닝
- 인공지능의 정의
  - **약 인공지능** (Weak AI)
    - "Machines can act as if they were intelligent"
    - 정의된 특정 목적을 달성하고 문제를 해결하는 능력
  - **강 인공지능** (Strong AI)
    - "Machines can actually thinking, not just simulating thinking"
    - 스스로 문제를 정의하고 해결, 지속적인 학습, 자아, 감정 등 인간이 가지는 광범위한 지적 능력을 포함
- 인공지능 구현의 판단 기준
  - **튜링 테스트** (Turing test)
    - A. Turing (1950) “Computing machinery and intelligence”
    - 사람과 구분하기 힘들 정도로 지능적 행동을 보이는지 확인
    - 지능적인 여부는 관심이 없고 사람의 행동을 얼마나 흉내 내는가를 고려
- 인공지능, 기계학습, 딥러닝의 관계  
  ![image](https://user-images.githubusercontent.com/61646760/177976883-296c4f66-fc7d-40ba-9be9-09a21ab85866.png)
  - **Artificial Intelligence** : 지능형 기계/프로그램의 제작과 관련된 분야
  - **Machine Learning** : 명시적으로 프로그래밍하지 않고도 학습할 수 있는 능력
  - **Deep Learning** : 심층 신경망에 기반한 학습 방법
### 기계학습이란?
- 기계학습에서의 주제
  - **분류** (Classification) : 입력된 데이터가 어떤 부류에 속하는지를 자동으로 판단하는 문제 (`e.g. 베이즈 분류기, K-NN, 신경망(MLP,CNN,LSTM), SVM, HMM 등`)
  - **군집화** (Clustering) : 데이터 집합을 서로 비슷한 몇 개의 그룹으로 묶는 문제 (`e.g. K-means, 신경망(SOM) 등`)
  - **회귀** (Regression) : 입력 변수와 출력 변수 사이의 매핑 관계를 분석
  - **예측** (Prediction) : 과거에 관찰된 데이터 집합의 특성을 분석, 새로 관찰될 데이터에 대해서 예측하는 문제
- 기계학습 시스템의 전반적인 구조  
  ![image](https://user-images.githubusercontent.com/61646760/177977281-7ee52cac-7192-4ae1-b681-c18bd7a78df9.png)
- 기계학습의 유형
  - **교사(supervised)** vs **비교사(unsupervised)**
    - 교사(지도) 학습 : 학습 시에 시스템이 내야 할 원하는 출력 값(target output)을 미리 알려주는 교사가 존재 → 분류, 회귀 문제
    - 비교사(비지도) 학습 : 학습 시에 원하는 출력 값에 대한 정보 없이 학습을 수행 → 군집화 문제
  - **강화 학습(reinforcement learning)** : 교사 신호가 보상(reward) 형태로 주어짐
  - 준지도 학습(semi-supervised learning)
  - 약 교사 학습(weakly supervised learning)
### 신경망과 딥러닝이란?
- 신경망과 딥러닝의 관계
  - **인공 신경망(artificial neural network)**
    - 생물학적 신경망을 모델링해서 수학적 함수로 표현한 것
    - 원하는 입출력 매핑 함수의 형태를 스스로 찾는 학습 능력을 가짐
    - 데이터를 이용하여 학습을 수행하므로 데이터 분석 툴로 사용
    - 학습 방식(데이터 분석 용도)에 따라 다양한 모델이 존재
  - **심층 신경망(Deep neural network)**
    - 발전된 형태의 신경망 모델들
    - 층상 구조 (입력층, 은닉층, 출력층)
    - 일방향의 정보 흐름
  - **심층 학습(Deep learning)** : 심층 신경망을 이용하여 데이터를 분석하는 기계학습 기술
- 대표적 신경망 모델
  - **퍼셉트론(Perceptron)**
    - Rosenblatt(1958)
    - 활성함수로 계단 함수 사용
    - 구조 : 단층, 전방향, 완전 연결
    - 학습 : 이진 입출력을 갖는 교사(지도) 학습
  - **다층 퍼셉트론(MLP, Multilayer Perceptron)**
    - 학습 → 교사 학습 + 오류 역전파 알고리즘

## 2강. 인공지능 서비스의 분류체계 및 사례
- 활용 영역
  - 문제 해결
  - 추론
  - 학습
  - 인식
- 서비스 사례
  - 언론, 방송
  - 금융, 제조, 서비스
  - 의료, 법률, 교통
- 군사, 게임, 스포츠
- 예술, 교육

## 3강. 인공지능 교육의 프레임워크
- AI 교육의 구분
  - **인공지능 사용자(AI Consumers)** : 일상생활에서 인공지능 서비스와 제품을 사용하여 자신의 문제를 해결할 수 있는 기본 소양
  - **인공지능 활용자(Workforce that uses AI)** : 자신의 직업과 진로 분야에서 인공지능을 활용 및 응용할 수 있는 역량
  - **인공지능 개발자(Workforce in AI)** : 인공지능 분야에서 일할 수 있는 역량
- 인공 지능에 대한 K-12 지침
  1. 인식 : 컴퓨터는 센서를 이용해 세상을 인식한다.
  2. 표현 및 추론 : 에이전트는 세상에 대한 표현을 만들고 이를 추론에 사용한다.
  3. 학습 : 컴퓨터는 데이터를 통해 학습한다.
  4. 자연스러운 상호작용 : 지능형 에이전트가 인간과 자연스럽게 상호 작용하기 위해서는 많은 종류의 지식이 필요하다.
  5. 사회적 영향 : 인공지능은 사회에 긍정적인 영향과 부정적인 영향을 미칠 수 있다.
- K-12 학생들을 지원하기 위한 지침
  1. 학생들이 블랙박스 내부에서 일어나는 일을 볼 수 있는 투명한 인공지능 demonstration을 사용하세요.
  2. 학생들이 인공지능 어플리케이션 안에서 일어나는 일들에 대한 정신 모델(mental model)을 구축할 수 있도록 도와주세요.
  3. 학생들이 인공지능 서비스를 사용하여 인공지능 어플리케이션을 개발하도록 장려해 주세요.
  
## 4강. 공공데이터 활용 1 - 인공지능과 빅데이터
- AI 서비스의 경쟁력을 결정하는 핵심 요소
  - 고성능 컴퓨팅
  - 서비스에 특화된 알고리즘
  - 분야별 빅데이터
- AI 학습에는
  - 일정량의 데이터가 필요
  - 데이터 품질에 따라 AI 성능이 결정
  - 과학기술, 의료, 교통, 금융, 유통 등 응용 산업에서 대량의 분야별 빅데이터가 절대적으로 필요
- 공공데이터포털

## 5강. 공공데이터 활용 2 - 인공지능과 데이터 시각화
- **데이터 시각화 (data visualization)**
  - 데이터를 분석하여 그 결과를 쉽게 이해할 수 있도록 시각적으로 표현하고 전달하는 과정
  - ‘도표’라는 수단을 통해 정보를 명확하고 효과적으로 전달하는 것, 즉 효과적으로 ‘What(Fact)’를 파악하는 것이다.
- **데이터 시각화 분석**
  - 데이터를 시각화하여 얻어낸 정보(Information)로부터 분석을 통하여 가치를 이끌어 내서 인사이트(Insight)를 추출하는 것
  - ‘What(Fact)’을 인지(시각화) 한 후에, ‘Why’를 파악함으로써 어떻게 해야 할지에 대한 Insight를 찾는 것 (분석)
- 차트 종류
  - Area Chart
  - Bar Chart
  - Bubble Chart
  - Column Chart
  - Donut Chart
  - Line Chart
  - Map Chart
  - Pie Chart
  - Spider Chart
  - Treemap Chart

## 6강. 인공지능 서비스 활용 1 - 음성 인식과 문자 인식
- **음성 인식(Speech Recognition)**
  - 사람이 말하는 음성 언어를 컴퓨터가 해석해 그 내용을 문자 데이터로 전환하는 처리
  - 동영상이나 오디오 자막을 자동으로 생성해 주는 분야에서 주로 활용

## 7강. 인공지능 서비스 활용 2 - 안면 인식(나이 인식)
- 안면 인식
  - 디지털 이미지에서 얼굴을 검출(Detection)한 뒤에 얼굴에서 눈, 코, 입, 점, 주름 등의 상대적 위치를 찾아(Localization)낸 뒤에 기존 정보와 매칭된 얼굴을 찾아내고 인식
  - 우리 일상에서는 생체인식 기술로 스마트폰의 잠금 해제제와 결제 시스템에 사용
  - 개인정보와 사생활 침해 논란
- **다층 퍼셉트론(MLP, Multilayer Perceptron)**
  - 대표적 안면 인식 신경망 모델
  - 학습 → 교사 학습 + 오류 역전파 알고리즘
- **CNN**
  - 합성곱 신경망, Convolution Neural Networks
  - 인간 뇌의 시각 피질에서 영감을 받은 이미지 데이터 처리를 위한 모델
  - LeNet, AlexNet, ZFNet, VGG, GoogLeNet(Inception Net), ResNet 등

## 8강. 인공지능 서비스 활용 3 - 감정 인식
- 인간의 감정을 인지하고 해석하는 단계를 넘어 사용자 환경(User Experience: UX)/사용자 인터페이스(User Interface: UI)를 통해 인공지능 감정의 범주까지 포함하는 인공감성지능(Artificial Emotional Intelligence: AEI)에 관한 연구 개발 진행
- 감정 인식 기술
  - 음악, 소리, 이미지, 비디오, 텍스트 등으로 감정 인식
  - SVM, LSTM을 갖는 RNN 등
- 감정 생성 기술
  - 외부 자극의 특정 패턴에 대해 즉각적이고 자동적인 감정 반응을 생성
  - WaveNet과 같은 Deep larning 기반의 연구
- 감정 증강 기술
  - 인간-컴퓨터 간의 대화를 위한 양방향 플랫폼
  - Emotional Augmented Machine Learning (감정유발 기계학습)
## 9강-11강. 머신러닝 모델 개발
- **클래스(class)**
  - 클래스는 학습 데이터의 묶음이며, 새롭게 들어온 데이터를 분류하는 기준
- **세대(Epoch)**
  - 입력한 데이터를 모두 몇 번씩 학습할 것인지 정하는 부분
  - 모든 데이터를 1번씩 학습하는 것을 1세대라고 함
  - 같은 문제라도 여러 번 풀어보면 실력이 늘어나듯 같은 데이터라고 해도 여러 번 학습하면 학습할수록 모델이 똑똑해짐
  - 대신 시간도 오래 걸림
- **배치 크기(Batch Size)**
  - 몇 개의 데이터를 학습하고 모델에 반영할지 정하는 부분
  - 문제를 풀고 답을 맞춰 봐야 맞았는지 틀렸는지를 알 수 있는 것처럼, 모든 데이터를 학습하지 않고도 중간중간 지금까지 학습한 내용을 모델에 반영시킴
  - 그것을 몇 개를 기준으로 할지 정함
- **학습률(Learning Rate)**
  - 학습한 내용을 모델에 반영할 때 학습에서 예상되는 에러를 얼마나 고려할 것인지 정하는 부분
  - 학습률은 조금만 변경해도 결과에 큰 영향을 주는 부분이니 조심해서 설정해야 함
- **검증 데이터 비율(Validation Rate)**
  - 입력한 데이터 중 어느 정도 비율을 학습한 모델을 검증하는 데에 사용할지 정하는 부분
  - 검증 데이터 비율을 0.25로 정했다면 10개의 데이터를 입력했을 때 6개는 학습용으로, 4개는 검증용으로 사용하겠다는 뜻임

## 12강. 로봇과 인공지능
- 지능형 로봇
  - 인공지능을 탑재하여 스스로 판단하여 행동하고 인간과 커뮤니케이션이 가능하며 자기 제어를 할 수 있는 전기전자 기계장치를 말한다.
- 교구 로봇
  - 수학, 과학, 공학, 기술 등의 교과 학습에 로봇을 교구로 활용하며 로봇을 직접 조립, 제작, 프로그래밍하는 활동을 말한다.
