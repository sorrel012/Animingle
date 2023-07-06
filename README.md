## 🐶동물과 사람들이 어울리는 공간을 만들어주는 펫 관련 플랫폼😸<br>
![image](https://github.com/Maengmo/Animingle/assets/115568532/1bd4aadc-eb3b-4719-ae68-fefdff8fb1bd)

<br>

## ⁉ 프로그램 소개
  <p>"애니밍글"은 다양한 반려동물 관련 기능을 한 플랫폼에 통합하여 반려동물을 사랑하는 사람들에게 편리한 서비스와 정보를 제공합니다.</p>
  <p>이를 통해 반려동물을 키우는 인구수의 증가에 따른 수요 발전 가능성을 확보하고, 반려동물에 대한 정보성 부족을 해결하여 더 나은 반려동물 생활을 도모합니다.</p>
  <p> 또한, 유기동물 보호와 1인가구 증가로 인한 반려동물 케어서비스의 필요도를 충족시키는 역할을 수행합니다.</p>
  
  <br>
  
## ✔ 기획 의도
- 병원 및 약국 관련 정보 시스템 개발
  - 동물 병원 및 약국의 위치, 영업시간, 전화번호 등을 제공하여 반려동물 주인들이 편리하게 정보를 얻을 수 있습니다.<br><br>

- 애견 카페 정보 제공 및 예약 서비스 개발
  - 애견 카페의 위치, 메뉴, 예약 가능 여부 등을 제공하여 반려동물과 함께 어울릴 수 있는 공간을 찾을 수 있습니다.<br><br>

- 수의사 상담 서비스 개발
  - 온라인으로 수의사와 상담이 가능하며, 반려동물의 건강과 관련된 질문에 대한 전문적인 답변을 얻을 수 있습니다.<br><br>

- 실종 동물 찾기 서비스 개발
  - 실종된 반려동물의 정보를 등록하고, 지도를 통해 실종 동물을 찾을 수 있는 기능을 제공합니다.<br><br>

- 반려동물 사진 공유 및 소통의 창구 개발
  - 반려동물 사진 공유, 글 작성 등 커뮤니티 기능을 제공하여 반려동물을 사랑하는 사람들끼리 소통할 수 있는 공간을 제공합니다.<br><br>

- 펫 용품 중고거래 서비스 개발
  - 반려동물 용품 중고거래를 위한 플랫폼을 제공하여 사용하지 않는 용품의 재활용과 저렴한 가격으로 용품을 구매할 수 있도록 합니다.<br><br>

- 다양한 유기동물에 대한 현황 제공 및 입양 안내 개발
  - 유기동물 보호센터에서 입양 가능한 동물의 정보를 제공하고, 입양 절차와 안내를 제공하여 유기동물에 대한 관심을 증진시킵니다.<br><br>

- 펫시터 구하기 및 산책 친구 매칭 서비스 개발
  - 펫시터를 찾는 사람들과 펫시터로 활동하고 싶은 사람들을 연결시켜줌으로써 반려동물을 케어해줄 수 있는 도움을 제공합니다.
  - 산책 친구를 찾는 서비스를 통해 반려동물과 함께 즐거운 산책을 할 수 있는 파트너를 찾을 수 있습니다.  

<br>

## 📆 개발 기간
- 2023.05.24 - 2023.06.09

<br>

## 🖥 개발 환경
### ✔ 사용 언어
- JAVA (JDK 11), SQL, HTML, CSS, JavaScript(jQuery), JSP
### ✔ 사용 기술
- JDBC, Ajax, Servlets, Bootstrap
### ✔ DB
- Oracle 11g Enterprise
### ✔ IDE
- Eclipse 2021-03, SQL Developer,
### ✔ Server
- Apache Tomcat – 8.5.40

<br>

## 📁 ERD 
#### 논리
![ERD-논리](https://github.com/Maengmo/Animingle/assets/115568532/2b98ba25-44e6-47b7-a5d0-30a02fd5f355)

#### 물리
![ERD-물리](https://github.com/Maengmo/Animingle/assets/115568532/9def05b7-7a0c-4dcc-81ee-f50135092984)

<br>

## 🖥 실행 화면

#### 1️⃣ 메인
- 구현 내용 : 애니밍글 부팅 시, 처음으로 나타나는 화면으로 헤더와, 풋터를 구성하고 그 안에 content요소들을 넣었습니다. 해당 요소들을 클릭 시 각각의 Url로 이동하게 되고, transition을 통해 시간에 따라 배너가 이동하도록 구현하였습니다.<br>
![image](https://github.com/Maengmo/Animingle/assets/117720344/ecbdd68c-64b0-48d3-95fb-de81faa03a03)
<br>

#### 2️⃣ 로그인 & 소셜 로그인
- 구현 내용 : 일반 회원인지 관리자 회원인지를 각각의 테이블에 쿼리를 날려 체크합니다. 만약, 일반회원일 경우 펫시터 회원인지, 수의사 회원읜지 여부를 체크하고 결과에 알맞은 세션을 발급합니다.<br>
![image](https://github.com/Maengmo/Animingle/assets/117720344/a1736f79-5ba0-46ea-be31-d3897adc5fd2)
<br>

#### 3️⃣ 회원 가입
- 구현 내용 : keyUp 이벤트를 통해 입력한 값이 정규식에 알맞은이지 검사를 합니다. 검사 결과에 따라 사용자에게 실시간 유효성 여부를 알려주고, 유효성 검사 후 문제가 없다면 회원가입이 정상적으로 진행이 완료됩니다.<br>
![image](https://github.com/Maengmo/Animingle/assets/117720344/d6f6f814-22be-4571-9889-dd48ce1f64cb)
<br>

#### 4️⃣ 병원/약국 찾기 - 리스트 보기
- 구현 내용 : 카카오맵 API를 활용하여 만든 기능으로, 라디오 버튼으로 병원가 약국 중 하나를 선택합니다. 지도를 움직일 때 마다 dragend 함수를 통해 맵의 값을 가져와 해당 위치에 해당하는 병원, 약국 정보들을 Ajax를 통해 DB처리를 한 후 마커를 찍어줍니다. 추가적으로, 위성모드, 실시간 교통 모드, 자전거 도로 정보 등 다양한 서비스를 제공합니다.<br>
![image](https://github.com/Maengmo/Animingle/assets/117720344/10f9ca4c-4ec5-4f65-be29-d9518119ed11)
<br>

#### 5️⃣ 병원/약국 찾기 - 상세보기 및 리뷰 작성
- 구현 내용 :  내용 : 왼쪽 리스트 중 원하는 요소를 클릭 시, 해당 요소의 색깔을 변화를 주고, 옆으로 해당 요소들을 띄워주도록 하였습니다. 해당 과정에서 지도가 밀리는 현상이 발생 하였지만, zindex를 통해 해결 하였습니다. 또한, 해당 요소들의 정보들을 Ajax를 통해 처리하고, 리뷰 작성 시 해당 정보들을 토대로 Json 형식으로 받아 insert하도록 하였습니다.<br>
![image](https://github.com/Maengmo/Animingle/assets/117720344/b7c95750-bcd0-4e18-8118-002d31e081e5)
<br>

#### 6️⃣ 당신을 기다려요
- 구현 내용 :  내용 : 입양 할 수 있는 유기동물의 목록을 확인할 수 있습니다. 목록에는 사진, 이름, 품종, 성별 등을 간단하게 확인할 수 있습니다. 유기동물에 대한 정보는 서울시공공데이터 API를 이용하여 데이터를 가져오고 필요한 정보들을 JSON으로 처리하였습니다.<br>
![image](https://github.com/Maengmo/Animingle/assets/117720344/245b5e38-3bb0-4ffc-849e-02522632d720)
<br>

#### 7️⃣ 우리가족을 찾아 주세요
- 구현 내용 : 동물을 잃어버렸거나 주인을 잃어버린 동물을 찾아주는 게시판입니다. 글을 작성할 때 작성자는 글 내용과 함께 지도에 마커를 찍어 잃어버린 곳의 위치를 표시하여 작성할 수 있습니다.<br>
![image](https://github.com/Maengmo/Animingle/assets/117720344/8e875f4a-8eb6-45d3-ad6a-b0f6960fbb6c)
<br>

#### 8️⃣ 산책 친구
- 구현 내용 : 구하고 싶은 글쓴이가 원하는 산책 경로를 지도에 표시하고, 산책할 반려동물의 종과 산책 가능한 시간대 등을 작성하여 글을 게시합니다. 글쓴이와 함께 산책을 하고 싶다면 소켓으로 구현한, 채팅하기 버튼을 클릭하여 채팅으로 대화를 주고 받을 수 있습니다.<br>
![image](https://github.com/Maengmo/Animingle/assets/117720344/0de7839d-bea6-48af-a1b5-9ab96cc5471c)
<br>

#### 9️⃣ 와글와글
- 구현 내용 : 와글와글 게시판은 기본적인 게시판 CRUD 기능과 페이징 기능, 검색 기능, 말머리 필터 기능 등을 이용한 가장 대표적인 게시판입니다. 글 작성 시 ck에디터를 활용하여, 글 작성자가 자신의 게시글을 자유롭게 꾸밀 수 있고, 이미지 첨부 또한 자유롭게 할 수 있습니다.<br>
![image](https://github.com/Maengmo/Animingle/assets/117720344/b5369636-e97e-4cc7-8330-beb224e4dee2)
<br>

#### 1️⃣0️⃣ 펫시터 구하기
- 구현 내용 : 펫시터를 모집하는 글은 모든 회원이 작성할 수 있습니다. 그러나 펫시터 신청은 펫시터 인증이 완료된 회원만 신청이 가능합니다. 마음에 드는 펫시터가 있다면 화면에서 맡기기 버튼을 눌러 펫시터를 고를 수 있고, 선택한 펫시터 신청서에 채팅하기 버튼이 활성화 됩니다.<br>
![image](https://github.com/Maengmo/Animingle/assets/117720344/f4932d78-8146-48cc-b9c7-ebe9e622feff)
<br>

#### 1️⃣1️⃣ 마이페이지
- 구현 내용 : 마이페이지에는 회원정보, 펫시터 프로필, 펫시터 모집내역, 인증센터, 내 문의사항 기능이 있습니다. 각각의 기능에서도 기본적인 CRUD 기능이 들어 가 있어 다양한 서비스를 제공하고 있습니다.
![image](https://github.com/Maengmo/Animingle/assets/117720344/0787169e-d1d4-4ab5-857a-d33ad0e0e014)




