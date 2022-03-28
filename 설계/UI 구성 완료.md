## UI 구성

### 만들 페이지MAIN(미완)

![img](https://lh5.googleusercontent.com/xQ4XeCprJ7eBMOBq2eNmq_n5iFK35i1sz_ZVVQOOzR8RkAEVjFIbTzZZhQkLECSt4dufjtEehKuLil-0rs34_lF7lcIWYdWZcC6AVGYEwOj5MendOyO17PcMbpkmJyLw9xbNJZjx)![img](https://lh5.googleusercontent.com/tidU6O6Q_HYKB4T0eWpEn_HBeLsmSe2Z0oABoPsVrGns_vpRsrWSvdtMyrAgeM01h5uFPdyBpM6Vh4SVu7q8uRH7-B9TqLdhF5W41G-BqNRkj6BpmuZWp8iTvcsGFeEHHk4Uq_Dj)

### 유기동물 현황

- 카테고리(품종별, 지역별)에 따른 유기동물 데이터 뿌리기
  - 네비게이션 제이쿼리로 해서 드롭다운 형식으로 하기
- 유기동물 보호소 조회(지도 API를 통해서 제공)
  - 네이버 API 쓰기로 함
  - 안 되면 구글맵으로
  - 회원가입 때 사용한 세션값의 주소로 가장 가까운 보호소 조회해주기

### Blog

- 카테고리(입양 후기, {묶음})전체보기
- 입양 후기
- {자유게시판, 지역별 정보 나눔} 합치기
- 글 쓰기 페이지
- 머릿말 달기 기능 추가하기 

### 리퍼블릭과 함께하는 이들

- 리퍼블릭과 함께하는 수의사 (이름), 한 명만
- 리퍼블릭과 함께하는 동물권 행동(카라 소개)

### 로그인

- 세션값을 통해서 지역별 정보 나눔에서 자신의 지역에 따른 게시글 먼저 보여주기
- 세션값을 통해서 보호소 조회할 때 자신의 지역에 따른 보호소 먼저 보여주기
- 세션값은 회원가입할 때 사용한 주소를 가져오기

### 회원가입



1. 지금 정한대로 가고
2. 나중에 API 받을 때 카테고리에 있어서 다시 의논한다.
3. 나중에 여유가 되면 동물병원 조회까지 해보자.
4. 프론트는 지금 수준으로 가자.