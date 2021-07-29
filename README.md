# 정학제

### 기본 정보

- 이메일: jhj13062015@gmail.com
- Github: https://github.com/Hott-J
- [숭실대학교 스마트시스템소프트웨어학과](http://smartsw.ssu.ac.kr/) 2015/03 ~ 2021/08
- 숭실대학교 빅데이터 연구실 2019/03 ~ 2019/11
  - Android, BLE
- 파낙토스 뇌과학 연구소 2019/07 ~ 2019/08
  - Node MCU와 Android BLE 코드 개선 
  
### 기술 스택
- 프론트엔드
  - HTML, CSS : 읽기와 간단한 수준의 프론트 구현 가능.
  - JavaScript : async, await, promise와 OPEN API를 활용한 채팅봇을 개발해봄.
- 백엔드
  - Node.js: 채팅봇 개발 경험. API 데이터들을 소비자 니즈에 맞게 가공함.
  - Java(Spring): 간단한 게시판 구현. ORM으로 주문 서비스 개발해봄.
  - Database(MySQL): 간단한 쿼리문 작성 해봄.
  - DevOps: Google Cloud Platform, Docker, Jenkins를 이용한 CI/CD 구축 해보며 공부중에 있음.
  - RabbitMQ: 대용량 처리를 위해 적용하며 공부중에 있음.
- 기타
  - Git : 스터디와 개인 프로젝트에 적극 활용중.
  - OPEN API 활용: 직접 OPEN API들을 사용하면서, 보완점과 취약점들에 대해 충분히 생각해봄. **소비자 니즈에 맞게끔 활용한 경험이 많음**  
   
### 프로젝트

- [FifaOnline4 Chatting Bot](https://github.com/Hott-J/FifaOnline4-Chat-Bot)
  - 기술 스택: JavaScript, MessengerBotR, KaKao Developer API, Nexon Open API, Event Queue
  - 기간: 2020.07 ~ ing
  - 설명
    - 넥슨 API와 카카오 API를 소비자 니즈에 맞게끔 데이터를 가공하여 활용한 피파온라인4 채팅봇.
    - 멀티스레드에 안전하도록 요청을 큐에 하나씩 넣고 하나씩 뺌.
    - 요청이 rampup 될시, 타임아웃에 의한 요청들이 버려지는 현상에 대해 개선중에 있음.

- [맛집 찾기 채팅봇](https://github.com/Hott-J/Find-TastyFood-ChatBot)
  - 기술 스택: JavaScript, MessengerBotR, KaKao Developer API, Crawling
  - 기간: 2020.07 ~ 2020.08
  - 설명
    - 맛집 홈페이지를 크롤링하여 카카오 디벨로퍼 템플릿 기능과 연동.
    - 검색결과가 없을 경우, 예외처리를 통해 공백이 반환되도록 함.
    - 기존 코드에서 유지보수가 쉽게 수정을 함.

- [Naver Clova AI Chatting Bot](https://github.com/Hott-J/Naver-clover-Api-ChatBot)
  - 기술 스택: JavaScript, MessengerBotR, Naver Open API
  - 기간: 2020.07 ~ 2020.08
  - 설명
    - Naver Clova Open API를 활용함.
    - 네이버 파파고 번역 API를 이용해 번역 AI 채팅봇 구현.
    - 네이버 얼굴인식과 닮은 꼴 API를 이용해 이 두가지를 조합하여 얼굴인식 및 닮은꼴을 분석해주는 AI 채팅봇 구현.
    
- [Face Mask Detection](https://github.com/Hott-J/Face-Mask-Detection)
  - 기술 스택: OpenCV, Tensorflow, keras, Computer Vision, Deep Learing, Streamlit, Google Teachable Machine
  - 기간: 2020.08 ~ 2020.11
  - 설명
    - 기존의 마스크 모델(2구분)에서 턱스크까지 구분하고자 3모델로 개선해봄.
        - 모델 생성시 Google Teachable Machine 활용
    - Streamlit을 이용해 간단한 마스크 탐지 웹앱을 구현.

- [카페 웹 서비스](https://github.com/FullCamp-Study/Cafe-WebService)
  - 기술 스택: Java(Spring), ORM(JPA), MySQL
  - 기간: 2021.02 ~ ing
  - 설명
    - JPA를 이용한 도메인 설계 및 엔티티 구축.
    - 단위 테스트 진행하며 개발중에 있음.

- [Restful API 설계 및 배포]()
  - 기술 스택: Java(Spring), PostgreSql, Nginx, Docker, GCP, RabbitMQ, Jenkins
  - 기간: 2021.04 ~ ing
  - 설명
    - RESTFul API 설계
    - Google Cloud Platform
    - RabbitMQ로 대용량 메시지 처리
    - Nginx를 앞단에 두어 로드밸런싱
    - Jenkins로 배포
    
### 스터디
- [스프링 스터디](https://github.com/Hott-J/Spring-Study)
  - 기간: 2021.01 ~ 2021.02
  - 진행 방식
    - 매주 1회 온/오프라인으로 돌아가면서 공부한 내용 발표.
    - 서로 모르는 것 질문하고 답변하며 피드백.
    - Git으로 스터디 진행과정 관리함.

- [면접 스터디](https://github.com/Parkyunhwan/BackEnd_Study)
  - 기간: 2021.04 ~ ing
  - 진행 방식
    - 매주 1회 온라인으로 2:2 방식으로 면접관 & 면접자 방식으로 진행.
    - Git으로 스터디 진행과정 관리함.

### 외부 활동
- 삼성SDS 동계 알고리즘 수료
    - 2020.02 ~ 2020.03

### 자격증
- 삼성 SW Expert A
