# 프로젝트명

SpendScan

# 프로젝트 목적

영수증 이미지를 업로드하면
Gemini Vision이 분석하여

- 날짜
- 상호명
- 금액
- 카테고리

를 추출하고 가계부 형태로 저장한다.

# 개발환경

Google Colab
Python

# 사용기술

Gemini Vision
Pandas

# 기능

1. 이미지 업로드
2. 영수증 분석
3. CSV 저장
4. 내역 조회

# 출력 형식

{
    "date":"",
    "store":"",
    "amount":0,
    "category":""
}
