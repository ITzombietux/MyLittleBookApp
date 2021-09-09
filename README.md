# 마이리틀북앱 스크린샷을 보기 위한 레포지토리입니다.
---

## 홈 탭
<img src= https://user-images.githubusercontent.com/39956881/132652960-821c1f35-d023-4473-a34c-bb332f097ae9.jpg width="200" height="400"/> <img src= https://user-images.githubusercontent.com/39956881/132656628-f665f7d1-7eba-410c-a9d1-0562c9a311d4.jpeg width="200" height="400"/> <img src= https://user-images.githubusercontent.com/39956881/132656689-ed69a40f-d70c-4a96-b7d9-57e6ea5c6118.jpeg width="200" height="400"/>



- 홈 탭의 섹션은 collectionView DiffableDatasource를 사용.
- 읽던 책으로 바로 이동할 수 있는 미니 플레이어를 만들기 위하여 Container ViewController를 사용.
- 미니 플레이어 데이터 저장을 위해 UserDefaults 사용.
- app delegate ,메인 Tab Bar Controller를 사용하여 사용자 행동, 기록 등을 저장, 관리하는 객체를 관리하는 용도로 사용하여 객체의 상태가 꼬이지 않게 설계
- 우상단 검색 버튼을 눌러 책 제목, 작가 검색 기능 제공.

---

## 카테고리 탭

<img src= https://user-images.githubusercontent.com/39956881/132657059-18485d95-cff3-446f-9d99-b136c243dc17.jpeg width="200" height="400"/> <img src= https://user-images.githubusercontent.com/39956881/132657071-75c3ef9e-a60e-4ccc-8796-dee312e21d01.jpeg width="200" height="400"/>


- 카테고리 탭의 섹션은 collectionView DiffableDatasource를 사용.
- collectionView 크르롤 시 셀 프리패칭, 재사용성, 사용자 경험을 고려한 애니메이션 제공

---

## 내서재 탭

<img src= https://user-images.githubusercontent.com/39956881/132658075-2be26ebf-cfca-4d4a-95ba-ac0cc290b30d.jpeg width="200" height="400"/> <img src= https://user-images.githubusercontent.com/39956881/132658091-d1a44436-8524-46aa-b65b-f1fbc2e68a63.jpeg width="200" height="400"/> <img src= https://user-images.githubusercontent.com/39956881/132658100-a7cf3a1c-ce96-4096-88ff-4f7864512b20.jpeg width="200" height="400"/>


- Custom Segmented Control을 개발하여 하나의 viewController에서 세그먼트가 바뀌면 데이터도 변할 수 있게 설계
- 하나의 Cell을 재사용할 수 있게 Xib파일로 설계

---

## 더보기 탭

<img src= https://user-images.githubusercontent.com/39956881/132658506-cc1f5e5f-219e-4e02-870f-a129d1d8e40f.jpeg width="200" height="400"/> <img src= https://user-images.githubusercontent.com/39956881/132659020-8bc09ea2-de1d-4fb0-94dc-257afccca1c5.jpeg width="200" height="400"/> <img src= https://user-images.githubusercontent.com/39956881/132659040-9e91a95f-ffc8-44b4-a63a-119f9efc6369.jpeg width="200" height="400"/>
<img src= https://user-images.githubusercontent.com/39956881/132659043-1939246d-afc5-4001-9a40-b6eeb084259c.jpeg width="200" height="400"/> <img src= https://user-images.githubusercontent.com/39956881/132659049-daccb1fc-05db-4198-b490-6d8b42e5fbdd.jpeg width="200" height="400"/> <img src= https://user-images.githubusercontent.com/39956881/132659052-5ac721d6-d125-4697-8807-65a85ace9d21.jpeg width="200" height="400"/>

- 책 읽기 외 중요한 사용자 정보, 로그인, 로그아웃, 포인트 결제, 구독 결제 등을 UI/UX를 고려하여 설계, 개발

---

## 책소개 뷰

<img src= https://user-images.githubusercontent.com/39956881/132659483-8723f6b8-bac2-4376-ac19-f9d375414684.jpeg width="200" height="400"/> <img src= https://user-images.githubusercontent.com/39956881/132659489-0857f282-e0f8-4a2a-942f-f594b0d32bf7.jpeg width="200" height="400"/> <img src= https://user-images.githubusercontent.com/39956881/132659505-44fcc4f6-d7f7-4ec0-8903-d4a9956290eb.jpeg width="200" height="400"/> <img src= https://user-images.githubusercontent.com/39956881/132659832-28f03037-2d9e-4ed9-a653-06efb6f37fe2.jpeg idth="200" height="400"/>

- scollView를 사용하여 책 정보 데이터에 맞게 뷰의 높이를 지정하도록 설계
- 책 마다 다른 데이터 정보를 표시하기 위해 Factory 메서드를 사용한 다형성 적용.
- 페이스북, 인스타그램 API를 연결하여 책 정보 공유

---

## 책 읽기 뷰

<img src= https://user-images.githubusercontent.com/39956881/132660391-569aa2b1-dd2b-4ac9-bb1c-4c24a02bc407.jpeg width="200" height="400"/> <img src= https://user-images.githubusercontent.com/39956881/132660400-39d17f0f-3bb2-4afb-91ea-6b4edd98a3e9.jpeg width="200" height="400"/> <img src= https://user-images.githubusercontent.com/39956881/132660404-46593201-4c38-4fe6-9f7f-69cc49c98fc2.jpeg width="200" height="400"/> <img src= https://user-images.githubusercontent.com/39956881/132660412-08f97014-ae09-4c16-a0d9-52d5a92865d4.jpeg width="200" height="400"/> <img src= https://user-images.githubusercontent.com/39956881/132660422-b3dcad15-c956-423e-a997-3bf3b9f0a275.jpeg width="200" height="400"/>

- WKWebKit을 사용하여 서버에서 책 페이지를 불러오도록 설계
- javascript 함수를 연결하여 폰트 사이즈, 페이지 배경 등 교체할 수 있게 설계.
- FirstResponder를 고려하여 페이지 상하 스크롤, 드래그, 좌우 화면 터치하여 페이지 넘김 등 사용자 경험에 맞게 설계
- 목차, 책갈피, 메모 등 CRUD를 고려한 RestAPI 통신




