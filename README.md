# Flower-Recommendation-System

1.꽃 추천 시스템 소개
------------------------
꽃 추천 시스템은 꽃말을 검색하거나 상황과 받는 사람에 따라 이에 해당하는 꽃을 추천해주는 시스템이다.

2.문제
------------
### 2.1 필요성
```
꽃을 선물할 떄 꽃말도 중요하다.
꽃말은 꽃이 가진 특징, 성질 등에 의거해서 상징적 의미를 부여한 것이다.
그렇기 때문에 선물을 할 경우, 상황에 맞는 꽃말을 가진 꽃을 선물해준다면 받는 사람의 행복은 배가 될 것이다.
```
### 2.2 사례
```
꽃 추천 시스템은 이전사례가 존재하지 않는다.
대부분 사이트나 어플리케이션에서 꽃 이름만 검색이 가능하고 
꽃말을 검색하여 꽃을 찾는 사이트나 어플리케이션이 존재하지 않는다.
```
### 2.3 입력과  출력
```
1. input -> 꽃말 | ouput -> 꽃
내가 찾고 싶은 꽃말을 입력하면 결과로 꽃이 나온다.
ex> 사랑과 관련된 꽃을 찾고 싶어서 '사랑'을 검색하면 결과로 '순결한 사랑'이라는 의미를 가진 상사화가 출력된다.

2. input -> 상황 | ouput -> 꽃
상황에 맞는 꽃을 추천해준다.

3. input -> 받는 사람 | ouput -> 꽃
받는 사람에 따른 꽃을 추천해준다.
```

3.해결방법
-----------
### 3.1 순서도
![Alt text](/8주차 순서도.png "flow chart")

### 3.2 데이터 수집방법
```
농촌진흥청의 꽃말사전에서 꽃이름과 꽃말을 크롤링해서 csv파일로 저장한다.
```
