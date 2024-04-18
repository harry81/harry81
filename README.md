# 최현민(Choi Hyunmin)
- Django backend developer
- chharry@gmail.com
- [linkedin](https://www.linkedin.com/in/chharry/)


## 업무 경험

### [ODK](https://www.ondemandkorea.com/)(22.12 ~ Present)
회사
- 비디오 컨텐츠 제공 시스템에서 발생하는 성능 이슈 원인 분석 및 응답 시간 개선
- 북미에 있는 한인 사용자를 대상으로 한국 영상 컨텐츠를 제공하는 OTT 서비스

역할: 백엔드 개발자
- 비디오 컨텐츠 제공 시스템에서 발생하는 성능 이슈 원인 분석 및 응답 시간 개선 
  - Newrelic / sentry 에서 request 별 처리시간 찾아 분석
  - Django의 orm에서 놓치기 쉬운 N+1 문제(select_related, prefetch_related 로 해결)
  - 쿼리 판단 조건 순서를 조정하여 부하를 줄임
- Django Rest Framework 를 이용한 api 구성 
  - Framework 에 의존하여 신뢰할 수 있는 코드관리
- 안정적인 서비스 제공을 위한 장애 대응 및 운용
- 콘텐츠 curation cache 효율화
  - 사용자가 처음에 접근하는 landing 페이지에 사용자별로 다른 내용을 보여준다.
  - 사용자별, 언어별로 cache 로 관리하기에 부담이 크고, 실시간 데이터가 아니므로 ux
적으로 문제
  - 선택적으로 계산이 필요한 부분을 제외한 내용만 cache 하는 패턴으로 적용하여 자원
활용도 향상
- 개선 및 개발 기능
  - 방송 편성표 api 를 구성하여 모바일 클라이언트에 제공
  - 최초 페이지 접근시 노출되는 carousel 개선(기본적으로 cache 사용하고 사용자별로 차이가 필요한 부분은 추가적으로 갱신)
  - Whisper 활용하여 영상에서 자막 생성
- Skills: Django, Docker, Django ORM query tuning, git, AWS, AWS Batch

### [Linewalks](https://linewalks.com/)(22.05 ~ 현재)
회사
- 의료 데이터 분석 툴을 병원에 제공 B2B 서비스 
역할: 백엔드 개발자
- Flask 기반 시각화를 오픈소스 코드 활용하여 병원 데이터를 대시보드로 구현
- Docker compose 활용하여 개발 환경 구축 및 배포

### [Deepnatural](https://deepnatural.ai/)(21.01 ~ 22.04)
회사
- ML 학습 데이터를 클라우드 라벨링 B2C / 백엔드 개발자 / 1년 4개월
- Django admin 응용하여 내부 사용자가 사용하는 기능 추가
  
역할: 백엔드 개발자
- git flow를 소개하여 안정적인 코드 배포에 기여
- Celery task 적용하여 주기적인 작업을 django 로 관리
- MLOps 스쿼드에 참여하여 일괄 학습 및 예측 프로세스 도입(AWS batch 적용)
  - 예) 스피커 클러스터링
- 운용환경에서 반복적으로 발생하는 deadlock 이슈 부분 해결

### [어니언스](https://www.papricacare.com/)(20.01 ~ 21.01)
- 사용자의 처방전 기반 의약 정보 제공(iOS, Android) B2C / 백엔드 개발자 / 12개월
- Agile 프로세스 소개하여, 피드백 적용 시간 단축
- python fabfile 이용하여 배포 과정 자동화\
- AWS 환경에 백엔드 서버 구축(ElasticBeanstalk) / Google vision OCR API 적용
- Social 계정 인증(naver, facebook, apple)
- FE 개발자와 협업하여 필요한 endpoint API 개발 및 유지보수

### [코노랩스](https://about.kono.ai/)(18.06 ~ 19.11)
- Slack bot 구현, 사용자 메시지 안에서 시간,장소 추출하여 일정 생성 B2B / 백엔드 개발자 / 1년 5개월
- 스크럼 프로세스 소개
- local, staging, prod 환경을 구분하여 안정적인 개발 환경 구축
- unit test 필요성 전파 및 적용
- error reporting 환경 적용하여 사용자 오류 실시간 감지 및 대응에 노력
- AWS NLP와 Slack chatbot 서비스 연동

### 타운 컴퍼니(17.10 ~ 18.05)
- 공동 구매 e-commerce 서비스 구축 / BE 개발자 / 7개월
- HTTP method 에 대응하는 endpoint 구축 노력(PATCH, PUT)
- staging, prod 환경 분리 및 적용
- Elasticbeanstalk 적용하여 무중단 배포 환경 구축

### [Truffls](https://truffls.de/en/)(16.03 ~ 16.08)
- Android와 iOS 클라이언트가 필요한 API 디자인 및 개발
- 내부 사용자가 사용하는 admin 페이지 유지 보수
- Django FMS 을 이용하여 비즈니스 로직 상태 관리
- Django ORM 을 응용하여 통계자료 추출

### [요기요](https://www.yogiyo.co.kr/mobile/#/)(14.01 ~ 16.02)
- FE client를 위한 Endpoint 생성
- 내부 사용자를 위한 Django admin 페이지 기능 개발
- Smart TV에서 배달 가능

### WindRiver(11.01 ~ 12.04)

### 포스코 ICT(08.4 ~ 10.10)

## 교육
- 학사: 충남대학교 컴퓨터 전공 (00.03 ~ 08.2)

## 기술
- Django, Python
- Git
- Emacs
- Test Driver Development
- Scrum
- Docker, Docker compose
- AWS, Elasticbeanstalk


## 포트폴리오
- [Mediciary](https://play.google.com/store/apps/details?id=com.hoodpub.mediciary)
  - 처방전, 약봉투, 의료 기록을 분석하여 사용자에게 쉽게 설명
  - 기술
    - [Django](https://www.djangoproject.com/)
    - [Flutter ](https://flutter.dev/)
    - [Elastic Beanstalk](https://docs.aws.amazon.com/ko_kr/elasticbeanstalk/latest/dg/Welcome.html)
    - [Google vision API](https://cloud.google.com/vision?hl=ko)
    - [ChatGPT api](https://platform.openai.com/docs/api-reference)
  - 2023.12 ~ 
- [유튜브 댓글 분석기](http://analysis.hoodpub.com/)
  
## 교육 경험
- [Django 1:1 과외](https://kmong.com/@%ED%98%84%EB%AF%BC)
- [파이썬 전자책](https://kmong.com/gig/300713)
