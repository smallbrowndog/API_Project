# Smart Finder

## 1. 개요
이번 프로젝트에서 사용할 API의 종류에는 네이버의 CLOVA Chatbot(챗봇서비스), 네이버 이미지 검색 의 2개의 API와
구글의 Vision API(구글 이미지 검색) API를 활용할것이다.

위 API를 통해 구현하고자 하는것은 내가 원하는 제품을 챗봇이 추천해주기도 하고 챗봇을 통해
원하는 제품을 이미지 검색하여 네이버와 구글의 검색결과를 취사선택해 쇼핑몰과 연결 할 수 있는 서비스를 구현하고자 한다.

이 서비스는 AiTEMS를 통해 사용자의 취향을 분석하여 사용자가 원하는 제품 _Ex)코트_ 를 입력했을때 코트에 대한 추천 상품이
열거되고 어떠한 제품의 사진은 있지만 정확한 제품을 찾지 못할때 이미지 검색을 통해 유사한 제품이나 동일한 제품을 찾아 쇼핑몰에
접속 할 수 있도록 하는 서비스를 구현할 예정이다.

## 2. 활용한 인공지능 API
### 2.1 API의 입력과 출력
해당 서비스의 입력은 2가지방식이 있다.
  1. 텍스트 형식으로 내가 원하는 제품을 입력
  2. 이미지 파일을 챗봇에게 전달해 입력

앞의 입력이 있게 되면 쇼핑몰 링크를 URL형식으로 추천 제품을 사용자에게 출력

### 2.2 Smart Finder 서비스에서 사용할 API
- 네이버
  - CLOVA Chatbot(챗봇서비스)
    - CLOVA Chatbot 엔진은 문맥, 문장, 단어 간 미세한 차이를 구분할 수 있고 잘못 입력된 단어를 정확하게 인식
  - 네이버 이미지 검색
    - 네이버에서 제공하는 이미지 검색 서비스로 이미지를 검색하고 네이버 쇼핑과 연동하여 URL 출력
- 구글
  - Vision API(구글 이미지 검색)
    - 구글에서 제공하는 이미지 검색 서비스로 이미지를 검색하고 startswith로 구글 쇼핑링크를 연동해 URL 출력

이미지 검색 API가 두가지가 들어간 것은 네이버를 선호하는 소비자와 구글을 선호하는 소비자가 각각 존재하기 때문에
선택지를 소비자에게 제공하는 측면에서 두가지 이미지 검색 API를 이용하기로 결정하였다.
## 3. 웹페이지 구축

### 3.1 출력문
### 3.2 추가내용
### 3.3 웹페이지 구성

## 4. 실행결과
