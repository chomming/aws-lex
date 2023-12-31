## Amazon Lex의 기능
- 대화형 인터페이스를 구축하는 완전 관리형 AI 서비스
<br/></br>

## Amazon Lex의 구성요소
- Intent(의도)
  - 사용자가 수행하고자 하는 작업
    - 날씨를 알고 싶다.
- Utterance(발화)
  - 의도를 트리거하는 사용자 입력
    - 오늘 서울 날시 알려줘.
- Slot(슬롯)
  - 수행할 때 필요한 정보
    - 날씨, 지역 등
- Fulfillment(이행)
  - 수행하는 방법
    - AWS Lambda
<br/></br>

## Amazon Lex & Connect 통합
- Lex 자동 음성 인식(ASR), 자연어 처리 및 인식(NLU) 기능 활용
  - ASR
    - Automatic Speech Recognition
    - 자동 음성 인식
    - 음성 신호를 입력으로 받아들여 텍스트로 변환하는 기술
    - 단계
      - 1단계 : 음성 신호의 특징 추출
        - 푸리에 변환 사용하여 음성 신호를 주파수 영역으로 변환 --> 주파수 스펙트럼에서 특징적인 정보 추출
      - 2단계 : 음성 신호의 특징 벡터를 입력으로 받아들여 음소 단위로 분할
        - 음소 인식 모델 사용하여 음성 신호 --> 음소 단위로 변환
      - 3단계 : 음소 시퀀스 --> 텍스트
        - 언어 모델과 결합하여 음성 신호를 텍스트로 해석
  - NLU
    - Natural Language Understanding
    - 자연어를 이해하여 특정 task를 풀 수 있는 모델이 정보 처리 자동화를 하는 것
      - task
        - 문법 검사 : 자동 문법 교정
        - 감성 분석 : 상품, 서비스 리뷰 데이터 긍/부정 판별
        - 문장 유사성 : 유사 문서 클러스터
        - 추론 : 자동 내부 및 회계 검사
<br/></br>

## Amazon Lex 구축 과정
- 대화 흐름
  - 샘플 표현
  - 초기 응답
  - 슬롯
  - 슬롯 값
<br/></br>
