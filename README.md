# 2025-glocal-mentoring
2025 하나금융TI ESG 성장 프렌즈 : Glocal Leaders - 인천진산과학고등학교


### [강의자료 Notion 페이지](https://www.notion.so/Glocal-Leaders-1f0d86ea13aa809da42cc3d9a5f65133)

#### 사전 준비

0.  사전 준비 (개발 실습 환경 구축 : Git/GitHub, Python, VSCode 설치)

#### 5/16 (금) : 파이썬 문법 배우기

1. 멘토링 소개

2.  파이썬 배우기 - 기초 문법

3.  파이썬 배우기 - 모듈과 라이브러리, 가상환경 설정

4.  파이썬 배우기 - 활용

---

과제 - (1) 파이썬 문법 연습 / (2) 파이썬 라이브러리 활용 USGS (미국 지질조사국) 지진 데이터 처리

<aside>
💡

**5월 멘토링 리뷰**
1) 노트북에 파이썬 개발환경을 구성하고 기초 문법을 익혔습니다.

    근데, 실습때 파이썬 소스 파일이 `.ipynb`? `.py`? 무슨 차이 인가요??

       **- `.py`** 은 그냥 파이썬 소스 코드만 쭉~ 적는 파이썬 코드 파일

       **- `.ipynb`** 은 `설명`도 쓰고, `코드`도 쓰고, `실행 결과`도 함께 볼 수 있는 jupyter notebook 파일

   ⇒  즉, `.ipynb`는 **설명 + 코드 + 출력**을 모두 한눈에 볼 수 있어서 **공부하고 실습하기 좋다!**

2) 파이썬 가상환경 **`.venv`**를 구성하고 **`pip install`** 패키지 관리자 명령어로 **`모듈과 라이브러리`**를 설치 및 활용해보았습니다.

  갑자기 왜? **`.venv`** 가상환경을 사용하나요?
  ⇒ 가상 환경은 **프로젝트**(**VScode 작업 폴더**)별로 **독립된 파이썬 환경**을 제공하여 **패키지 간의 충돌을 방지**합니다. 가상환경이 아닌, 노트북 자체에 여러가지 모듈과 패키지가 설치된다면, 같은 PC내 여러 다른 파이썬 개발 프로젝트간 버전 충돌 등 문제가 생길 수 있습니다.

**3) 저는 파이썬 문법을 더 자세히 배우고 익히고 싶어요!!**
    ⇒ (1) 유튜브 강의
        (2) Chat GPT 활용 질문하기
        **(3) 알고리즘 문제를 Python으로 풀어보기 (추천)**
          - 프로그래머스 코딩테스트 연습 문제 0, 1, 2 단계 문제 풀어보기

[](https://school.programmers.co.kr/learn/challenges?order=recent)

</aside>

#### 6/13 (금) :  Git/Github 활용하기 / 데이터 분석 기초

5. Git/Github 활용하기

1. 데이터 분석 기초

과제 - (3) 공공데이터분석 기온 / Github 업로드 

<aside>
💡

**[ 파이썬 데이터 분석을 활용한 연구 계획 세우기 ]**

- 이태까지 배운 파이썬 활용 지식을 활용하여 **`지구과학`**, **`환경`**, **`에너지`** 관련 분야 데이터 연구계획을 세워봅시다.
    - **기초 데이터 수집**
    (공공데이터 포털, 기상청 날씨마루, 미국 지질조사국, 직접 연구한 데이터 등등)
    - **해당 데이터를 활용한 주제 선정**
    - **선정한 데이터의 특성을 파악하기 (속성, Null(결측치), 이상치)**
    - **필요한 데이터 전처리**
        - pandas를 활용하여 프로그래밍으로 전처리 (원본 데이터 수정 X)
        - .csv파일 Excell에서 열어서 직접 수기로 데이터를 정제하기
        (결측치, 이상치, 필요한 속성값 필터링 등)
    - **데이터 탐색 및 시각화**
        - **파이썬 라이브러리를 활용한 `히스토그램`**, **`기술통계`, `상자도표`, `상관분석`, `산점도` 데이터 시각화**
        - 각 분석하는 데이터의 컬럼(속성)간 상관관계 등을 히스토그램/상자도표/산점도 등으로 시각화하여 분석
    - **(심화)** 데이터에 적합한 통계적 분석 및 기계 학습(머신러닝) 알고리즘 도입 및 예측 활용
        - 각 팀별 주제에 따라, 전처리가 완료되어 데이터 시각화를 통해 파악된 정규화된 데이터의 특성을 확인하고, 이에 맞는 알고리즘 선정 (선형 회귀 분석 / 머신러닝 알고리즘 등)
        
        | 범주 | 목표·특징 | 대표 알고리즘 |
        | --- | --- | --- |
        | **지도학습** | X→y 예측 | 선형/로지스틱 회귀, SVM, 트리·앙상블, k-NN, 신경망 |
        | **비지도학습** | 패턴·구조 탐색 | K-means, DBSCAN, PCA, t-SNE, Apriori |
        | **강화학습** | 보상 최대화 정책 | Q-learning, DQN, PPO, A3C |
        | **딥러닝 특화** | 이미지·언어·시퀀스 등 고차원 데이터 | CNN, LSTM, Transformer, GNN |
        
        <aside>
        💡
        
        각 조의 조장은 **`Notion`** - **`공동 Workspace`**를 만들고, 조원에게 공유하여 **`Notion`**을 활용하여 팀 협업에 활용해보세요.
        
        </aside>
        
</aside>

---

공공데이터포털 공공 데이터 분석 활용 사례

[공공데이터 포털](https://www.data.go.kr/tcs/puc/selectPublicUseCaseListView.do)

##### 기상청 날씨마루 데이터 분석 자료

[Python을 활용한 분석](https://bd.kma.go.kr/kma2020/dta/edu/KBP57200_Python.do?pageNum=5&menuCd=F040303000)

**기상데이터 활용 사례**

1. ASOS(지상관측자료)를 활용한 증발량 산출식 분석 사례
    
    [Example_Evaporation_Calculation_Model_python.pdf](attachment:ef940790-876f-4c4f-baeb-55cb84314c4b:Example_Evaporation_Calculation_Model_python.pdf)
    
2. ASOS(종관기상관측) 자료를 활용한 서리 발생 모형 분석 사례
    
    [Example_Frost_Calculation_Model_python.pdf](attachment:a480b938-9a3b-40ad-ba3a-59a7518c5e3b:Example_Frost_Calculation_Model_python.pdf)
    
3. ASOS(종관기상관측) 자료를 활용한 적조 발생 모형 분석 사례
    
    [Example_redtide_Calculation_Model_python.pdf](attachment:39a4cdb3-78d9-4a76-bf9e-68dc729b31c0:Example_redtide_Calculation_Model_python.pdf)
    
4. AWS(방재기상관측) 자료를 활용한 고속도로 사고위험 분석사례
    
    [Example_Traffic_Calculation_Model_python.pdf](attachment:3b992afd-17e7-4a12-9d0f-a58067d0a00a:Example_Traffic_Calculation_Model_python.pdf)
    
5. 날씨 데이터를 활용한 태양광 발전량 예측
    
    [2022_Python_Edu_training.pdf](attachment:9c88c16a-46f1-4b24-a493-680d3cde27ea:2022_Python_Edu_training.pdf)
    

#### 8/22(금) : API 와 서버
#### 9/5 : 청라 데이터 센터 방문 / 중간 발표회
#### 9/19(금) : 데이터분석 API 서버 / 폭염 데이터 분석 웹 서비스
7.  API 서버, 데이터분석 서버, 폭염데이터분석 서비스