# ✨ KPMG Future Academy Al.Re
안녕하세요. **삼정 KPMG Future Academy 3기 Al.Re 팀**입니다. <br>
저희 팀은 일상생활 속 라이프스타일을 변화시키고자 모였습니다. <br>

**"""** <br>

한 끼를 만들어 먹기 위해서는 굉장히 복잡한 사고 과정이 따라옵니다.<br>
예를 들어, 어떤 음식을 만들지 정했다면 혹은 정해야 한다면 레시피를 찾아보고,<br>
내가 그 재료들을 가지고 있는지, 없다면 어디에서 사야하는지 확인하고,<br> 
또 구매한 재료가 남는다면 이 재료를 어떻게 처리해야 할지 생각해야 하죠.<br>

레시피는 유튜브나 블로그를 살펴보고, 재료는 쿠팡, 이마트 같은 이커머스 플랫폼을 돌아다니며 하나하나 검색하고,<br> 
쇼핑리스트에 있는 재료들을 장바구니에 넣고, 남는 재료를 기반으로 레시피를 다시 검색합니다.<br>  

그 모든 걸 우리가 ‘각각 따로’ 하고 있습니다.<br>
이건 너무 귀찮고, 너무 복잡하고, 너무 파편적인 흐름입니다.<br> 
그래서 저희는 여기서 문제를 발견했습니다.<br>

이 **모든 고민과 행동을 하나로 이어주는 서비스**는 왜 없을까?<br>	

**당신의 취향과 식재료를 바탕으로 메뉴를 제안**하고, **구매부터 요리까지의 여정을 하나의 흐름으로 연결**하고,**<br> 
장바구니에 담은 재료와 잔여 재료에 대한 레시피를 추천**하여 음식물 처리 고민을 줄여주고,<br> 
그게 바로 우리가 해결하고자 하는 문제입니다.<br>

당신의 라이프스타일을 바꿔줄 새로운 서비스<br>
'일상은 반복되지만 요리는 새로워야 하니깐'<br>
지금 바로 **AI.Re**를 만나보세요.<br>

**"""**

---------------------------------------

# 📃 프로젝트 계획서

## 1. 프로젝트 개요
- **프로젝트명** : Al.Re
- **목표** : 레시피 탐색부터 쇼핑까지, One-Stop AI 장바구니 서비스
- **기간** : 2025년 3월 19일 - 2025년 5월 17일

## 2. 프로젝트 일정
- **분석 및 설계** : 2025년 3월 19일 - 4월 11일
- **개발** : 2025년 4월 14일 - 5월 14일
- **발표** : 2025년 5월 17일

## 3. 팀 구성
|<center><img src="https://github.com/user-attachments/assets/d0037366-b2a7-4196-952b-136b5c1e2d2a" width="150" height="150"></center>|<center><img src="https://github.com/user-attachments/assets/cacea362-156c-45ce-8ca0-837fdc5216f9" width="150" height="130"></center>|<center><img src="https://github.com/user-attachments/assets/f46e5657-661f-477e-969e-c4cf783bc9de" width="150" height="150"></center>|<center><img src="https://github.com/user-attachments/assets/a3ac0397-d03c-4eda-881a-fa8f212614dc" width="150" height="150"></center>|<center><img src="https://github.com/user-attachments/assets/4183275d-b150-498c-b4cc-6b5853762d01" width="150" height="100"></center>|
|:---:|:---:|:---:|:---:|:---:|
|**이동현**|**홍동휘**|**강재연**|**문형균**|**김경은**|
|**Team Lead <br> CTO**|**Deputy Team Lead <br> UX Strategist**|**Data Engineer**|**Product Manager**|**Funnel Analyst**|

---------------------------------------

# 🍽️ 서비스 개요
![스크린샷(9)](https://github.com/user-attachments/assets/b518c9ff-4125-4cb8-9cd7-abd8d9c12580)

---------------------------------------

# 🛒 서비스 기능

## 1. LLM 및 행동 로그 기반, 레시피 & 재료 추천
- 초기 선호도 조사를 통해 사용자 선호 파악
- LLM 기반의 맥락 인지 추천 및 행동 로그 기반 개인화된 맞춤형 레시피·식재료 추천

## 2. 장바구니에 담은 재료 기반, 레시피 & 재료 추천
- 장바구니에 담긴 재료를 포함하고 있는 레시피 중 상위 3개를 소비자에게 추천
- 레시피에 필요한 추가 재료를 일괄 또는 선택적으로 장바구니에 담을 수 있는 기능 제공

## 3. 조리 후 남은 재료 기반, 레시피 & 재료 추천
- 장바구니에 담긴 재료를 기반으로 레시피 조리 후 남는 재료에 대한 양을 계산
- 해당 재료를 활용할 수 있는 레시피를 추가 추천하여 활용도를 극대화하고 반복적인 구매 유도

---------------------------------------

# ⚙️ 설치 및 실행 방법

## 1. Clone Repository
```bash
git clone https://github.com/lytt6649/Fa03-fin-Al.Re.git
cd market_service
```

## 2. Install Dependencies
```bash
pip install -r requirements.txt
```

## 3. Run Frontend
```bash
streamlit run main.py
```

---------------------------------------

# 🎬 서비스 튜트리얼

## 1. 사용자 최적화 및 레시피/재료 추천
https://github.com/user-attachments/assets/7a4c9a11-f73a-431b-bad4-4811da7445f7

## 2. Al.Re 봇 서비스
https://github.com/user-attachments/assets/896d2524-80a7-4bbc-a389-3b31f29cffa8

## 3. 운영관리 서비스
https://github.com/user-attachments/assets/2776ea7b-ed86-4099-b1f9-acc2da101a9b

---------------------------------------

# 🔗 서비스 아키텍처
![스크린샷(10)](https://github.com/user-attachments/assets/8915d3b5-0cce-4e36-a4bf-187d11b09715)




|Tech|Tool|
|:---:|---|
|Front-end|![Streamlit](https://img.shields.io/badge/Streamlit-%23FE4B4B.svg?style=for-the-badge&logo=streamlit&logoColor=white)|
|Back-end|![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)|
|DB|![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)|
|LLM|![ChatGPT](https://img.shields.io/badge/chatGPT-74aa9c?style=for-the-badge&logo=openai&logoColor=white)|
|BI|![Tableau](https://img.shields.io/badge/Tableau-%230C55A5.svg?style=for-the-badge&logo=Tableau&logoColor=white)|
|CI/CD|	![Jenkins](https://img.shields.io/badge/jenkins-%232C5263.svg?style=for-the-badge&logo=jenkins&logoColor=white)|
|IDE|![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)  ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)|
|ML|![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white)|
|Groupware|![Google Drive](https://img.shields.io/badge/Google%20Drive-4285F4?style=for-the-badge&logo=googledrive&logoColor=white)  ![Discord](https://img.shields.io/badge/Discord-%235865F2.svg?style=for-the-badge&logo=discord&logoColor=white) ![Google docs](https://img.shields.io/badge/Google%20Docs-4285F4?style=for-the-badge&logo=googledocs&logoColor=white) ![Google Slides](https://img.shields.io/badge/Google%20Slides-FBBC04?style=for-the-badge&logo=googleslides&logoColor=white)|

----------------------------------------

# 🗓️ WBS

## 1. 기획 및 조사
- 1.1. 주제 선정 및 서비스 정의
- 1.2. 경쟁 조사 및 문제 정의

## 2. 데이터베이스 구축
- 2.1. ERD 설계
- 2.2. MySQL 테이블 생성
- 2.2. 더미데이터 생성 및 테이블 구축  

## 3. 알고리즘 설계 및 인프라 구축
- 3.1. 추천 로직 및 VectorDB 비교 선정
- 3.2. 레시피 및 선호도 반영 로직 설계
- 3.3. 데이터 Vector 변환 (ChromaDB)

## 4. 핵심 기능 개발
- 4.1. Cold Start용 선호도 설문
- 4.2. 장바구니 기반 레시피 추천 기능
- 4.3. 사용자 선호도 기반 레시피 추천
- 4.4. 잔여재료 계산 및 레시피 추천
- 4.5. OpnAI API 활용 챗봇

## 5. 사용자 및 관리자 프로토타입 개발
- 5.1. 검색엔진 구현
- 5.2. 사용자 Streamlit UI/UX 구현
- 5.3. Jenkins 자동화 설정
- 5.4. 데이터 분석
- 5.5. Tableau 대시보드 작성
- 5.6. 관리자 Streamlit UI/UX 구현

## 6. 검수 및 배포 준비
- 6.1. PPT 제작
- 6.2. 최종 발표

-----------------------------------------

# 🗂️ 데이터 정의서
![스크린샷(11)](https://github.com/user-attachments/assets/25be33a9-7dfe-4a1c-b6a0-f244ec5f6fd5)

----------------------------------------

# 📓 최종 보고서

## 1. 프로젝트 개요
- **목표** : 레시피 탐색부터 쇼핑까지, One-Stop AI 장바구니 서비스
- **기간** : 2025년 3월 19일 - 2025년 5월 17일

## 2. 사용자 기대 효과
- 장바구니 재료 기반 자동 추천으로 선택 스트레스 감소
- 남은 재료까지 고려한 추천으로 재료 남비 감소 및 만족도 증가
- 앱 간 전환 없는 구조로 몰입감 상승

## 3. 운영사 기대 효과
- 장바구니 기반 추천으로 구매 전환율 증가 예상
- 로그 기반 행동 분석으로 고객 세그먼트별 리타켓팅 효율 증가
- 상품 회전율-구매빈도 높은 품목 자동 집계로 재고 최적화 가능

## 4. 향후 발전 사항 (AI Agent)
- 고도화된 개인맞춤형 레시피 추천
- 요리 도우미 역할 수행
- 장바구니 내 품목 자동 구매
- 상품 및 레시피 자동 탐색 및 입력

-----------------------------------------

# 📝 회고

## 1. 잘된 점
- **협업**: 팀원 간의 협업이 원활하게 이루어졌으며, 주기적인 피드백 세션이 유효했다.
- **일정 관리**: 프로젝트 일정에 맞춰 개발이 진행되었고, 큰 지연 없이 배포를 완료했다.

## 2. 개선할 점
- **초기 요구사항 정의 부족**: 초기 요구사항이 부족하여 개발 도중 변경 사항이 많았다.

## 3. 교훈
- **명확한 요구사항 정의**: 초기 단계에서 요구사항을 명확히 정리하는 것이 중요하다.
