# 🍷 Somme

> 팀 프로젝트 와인 판매 사이트 Somme<br>
와인을 마셔보고 싶지만, 낯설어서 도전을 못해본 경험이 있나요?<br>
그런 당신을 위한 쉽고, 간편한 맞춤 와인 사이트 ‘Somme’입니다.
<hr>

## 😎 팀원 소개

강예진 | 김하늘 | 최지은 | 홍미지
---|---|---|---|
![예진](https://user-images.githubusercontent.com/108658971/201602638-4fdc5ed9-6a13-41d0-9263-55b4c7396176.png)|![하늘](https://user-images.githubusercontent.com/118153241/201795460-999efd95-bcd9-481a-bcab-70e3a566c2c6.jpg)|![지은](https://user-images.githubusercontent.com/108658971/201602234-5c09e1b4-9a28-4050-9626-7909ef901885.png)|![미지](https://user-images.githubusercontent.com/108658971/201602230-6d2ec90b-5f72-4c2c-a4cc-a0bcc23a9cd1.png)

## 📌 프로젝트 설명
프로젝트명 'Somme'은 와인을 보관하며 안전성을 보증해주는 직업에서 차용한 이름입니다.<br>
와인을 잘 몰라도 쉽게 접근할 수 있도록 사이트 내에서 제공하는 취향별 와인 추천 서비스를 통해 간단하게 와인을 추천 받을 수 있습니다.
또한 리뷰와 댓글, 좋아요 기능을 통해 사용자끼리 의견 공유하여 다양한 정보를 얻고 실시간 채팅으로 제품에 대한 궁금함을 쉽고 빠르게 해소할 수 있습니다.

## 🛠 기능
<details>
    <summary>강예진</summary>

### Product
![product1](https://user-images.githubusercontent.com/80384316/201865323-1a3a8e2e-4440-4535-a1bf-5033a43c60b8.gif)
*  각 상품을 종류와 국가로 나눠서 상품분류 DB 설계
*  상품 장바구니 추가/삭제 기능
*  Main의 best 와인 상품 정렬 기능
*  원하는 조건별 상품 정렬기능
<br>
    
### Cart
![cart1](https://user-images.githubusercontent.com/80384316/201865320-700a21d0-8817-4bb1-b424-985ddc306b8a.gif)
*  제품 수량 변경 기능
*  선택상품 삭제/장바구니 비우기 기능
<br>
    
### Order
![order](https://user-images.githubusercontent.com/80384316/201865318-939ab25c-f2ac-4827-bceb-c4b61208cc67.gif)
*  5만원 이상 구매 시 무료 배송 기능
*  결제 API를 활용한 결제 기능
*  관리자 승인을 통한 무통장 입금/방문 결제 기능
<br>
    
### 마이페이지 > 주문/반품 내역
![member_order](https://user-images.githubusercontent.com/80384316/201865312-4e6f51de-1bc5-4fba-b5da-003f4eceb450.gif)
*  회원별 주문 취소/반품 신청 기능
*  회원별 주문정보/주문상세, 반품정보/반품상세 조회 기능
<br>
    
### ADMIN > order 
![admin](https://user-images.githubusercontent.com/80384316/201865301-8134f327-8c19-4fcf-bfdf-e2a3983bb429.gif)
* 주문 리스트
    *  회원별 입금 확인을 통한 주문처리 기능
    *  미처리된 주문 목록 정렬 및 페이징 기능
    *  주문자명/상품명/처리여부에 따른 검색 기능
* 반품 리스트
    *  회원별 상품 확인을 통한 반품처리 기능
    *  미처리된 반품 목록 정렬 및 페이징 기능
    *  주문자명/상품명/처리여부에 따른 검색 기능
<br>

</details>
<details>
    <summary>김하늘</summary>

### 회원가입
![가입33](https://user-images.githubusercontent.com/118319662/202108709-aeb1aadd-c7fe-4501-9a29-ae71314de23d.gif)
*  회원가입 기능
*  문자메세지를 통한 본인인증 기능
<br>

### 로그인
![로그인22](https://user-images.githubusercontent.com/118319662/202108712-7218785f-baf6-4c1e-ba3f-62cfd237116a.gif)
*  카카오 로그인 api를 활용한 로그인 기능
*  일반 로그인/관리자 로그인 구분
<br>

### 아이디/비밀번호 찾기
![아디비번22](https://user-images.githubusercontent.com/118319662/202108697-a83c8e83-2055-4a59-883e-3baa37408d55.gif)
*  회원 정보를 입력하여 아이디/비밀번호 찾기
<br>

### 마이페이지>회원정보
![수정22](https://user-images.githubusercontent.com/118319662/202108702-3482aed2-bc88-4d26-81f5-fc129d2a319a.gif)
*  회원의 가입 정보 조회기능
*  회원정보 수정/탈퇴 시 비밀번호 확인
*  회원정보 수정/탈퇴 기능
<br>

</details>
<details>
    <summary>최지은</summary>

### 취향별 추천    
![취향별추천](https://user-images.githubusercontent.com/108658971/201853136-347bc7cc-c891-417e-94e9-e17e889f3534.gif)    
* 선택한 항목에 맞춘 제품 추천 기능
* 참여한 인원 카운팅 기능
* 추천된 제품의 상세페이지 연결
    
### 게시판    
![리뷰](https://user-images.githubusercontent.com/108658971/201853145-63e11dd7-a98e-4c18-9e34-3cc869b4552a.gif)    
* Q&A, 리뷰 CRUD/검색/페이징/사진업로드
* 공지사항 첨부파일 다운로드 기능
* 관심있는 리뷰 좋아요 추가/삭제 기능
* 댓글, 리댓글 추가/삭제 기능
* 댓글, 리댓글, 좋아요 게시글별 총 개수 
* Q&A 문답 기능
* 상세페이지의 이전글/다음글 이동 기능
* 이벤트 배너 연결된 페이지 이동 기능
    
### 관리자    
![관리자 Q A](https://user-images.githubusercontent.com/108658971/201854192-871bbcce-c534-42b6-a972-559b203de98d.gif)    
* 게시글 현황 확인 및 조회
* 각 작성글, 댓글 삭제 권한
* 공지사항, 이벤트 CRUD/페이징/사진,파일업로드
* 메인의 이벤트배너 등록/해제 기능
* 베스트리뷰 등록/해제 기능
* Q&A 답변 작성/수정 기능
    
### 메인
* 지도 API활용 매장 위치 확인
<br>
</details>
<details>
    <summary>홍미지</summary>

### Intro<br>
![인트로](https://user-images.githubusercontent.com/118153241/201851535-dbf901b1-7486-4d16-9c01-31084a03ebb8.gif)
* 연령 확인 안내 페이지
    
### Search<br>
![검색](https://user-images.githubusercontent.com/118153241/201851548-6dce2397-6ec3-444a-87f5-658943fb9864.gif)
* 상품 검색 기능(한글명, 영문명)
    
### ADMIN > Product<br>
![관리자상품](https://user-images.githubusercontent.com/118153241/201851528-0979c5b9-189a-4dd8-9b02-148df2680ccb.gif)
* 상품 등록 시 필수 정보 유효성 검사
* 상품 이미지 업로드
* 베스트와인으로 설정 시 메인페이지에 상품 등록 
* 상품 수정 기능
* 상품 전체 및 선택 삭제 기능
* 상품명/상품명+영문명/종류/국가에 따른 검색 기능 (대소문자 구분 없음)
* 페이징 처리 기능
    
### ETC<br>
![채팅](https://user-images.githubusercontent.com/118153241/201851544-c10d0776-efaf-407b-882d-53e4f521f496.gif)
* 채팅 API 활용해 사용자들끼리 다양한 정보 공유 가능
</details>

<hr>

![와인쇼핑몰](https://user-images.githubusercontent.com/108658971/201612754-15dda315-80c7-4b57-aac2-1f66c7f36e54.png)

<!-- 사진: 프로세스 정의서 <프로젝트 설명서 첨부> -->

## ✨ 데모 화면

<img src = "https://user-images.githubusercontent.com/118153241/201815134-109365e0-a534-489a-b693-9a62599a7662.JPG" width="100%" height="40%"> | <img src = "https://user-images.githubusercontent.com/118153241/201819133-2c88dffe-8abe-4fe3-a0c8-eed226ca40d1.JPG" width="100%" height="40%"> | <img src = "https://user-images.githubusercontent.com/118153241/201819514-ebf06def-2862-4051-bb96-2902df052c32.JPG" width="100%" height="40%">
:---:|:---:|:---:|
**인트로** | **로그인** | **메인화면**
![상품 목록](https://user-images.githubusercontent.com/80384316/201819775-50e672b3-84be-42f1-994e-948e684f40ce.png) | ![베스트 리뷰 목록](https://user-images.githubusercontent.com/80384316/201821542-43a866af-c04f-4c42-a629-9076dd08f905.png) | ![리뷰 상세](https://user-images.githubusercontent.com/80384316/201821548-0be63e0e-b8a2-449e-9f1c-1c973e7ff204.png)
**상품 목록** | **베스트 리뷰 목록** | **리뷰 상세**
![주문 상세](https://user-images.githubusercontent.com/108658971/201819415-9132275b-688a-499c-92af-81bf1f8c7b9b.png) | ![장바구니](https://user-images.githubusercontent.com/108658971/201819418-d2aedf78-99df-4b98-a0bb-f76e093e1f21.png) | ![주문목록](https://user-images.githubusercontent.com/108658971/201819420-87e6f548-c10b-480f-8965-eddeaaa32232.png)
**주문 목록** | **장바구니** | **주문 상세**
![취향별추천](https://user-images.githubusercontent.com/108658971/201817809-baa6a897-84c9-4c4f-9a23-97bf77085c4d.png) | ![채팅](https://user-images.githubusercontent.com/118153241/201857032-a898e3b9-8abc-413f-b44f-daaac33d0ca4.JPG) | ![관리자페이지](https://user-images.githubusercontent.com/108658971/201817309-d53864c0-1638-46d3-bb87-2f8f77c23f66.png)
**취향별 추천** | **채팅** | **관리자**


## 🔎 프로젝트 설치 및 실행 방법
[somme 어플리케이션 배포.pptx](https://github.com/kangyeajin/somme/files/10018827/somme.pptx)
<!-- (배포메뉴얼) (ppt 링크 첨부) -->

## 💻 개발 언어 및 활용 기술

* <b>사용언어 및 프레임 워크</b>
  *  ` JAVA `
  * ` Spring Framework `
  * ` jsp ` ` jstl ` ` EL `

* <b>웹 표준 및 프론트</b>
  *  ` html5 ` ` css3 ` ` JavaScript `
  *  ` jQuery ` ` Ajax `
 
* <b>DB</b>
  *  ` Oracle11 ` 
  *  ` MyBatis ` 

* <b>API</b>
  *  ` KakaoMap ` ` Kakao Login REST API ` 
  *  ` i'mport(이니시스 pay) `
  *  ` Dongle chat(html5) `

* <b>Tools</b>
  *  ` Git ` ` Eclipse IDE ` ` VS code ` ` STS `

* <b>Server</b>
  *  ` Apache Tomcat ` 
