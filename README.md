# INYROGRAM

**앱 이름** : Inyrogram

**주제** : Instagram 카피 앱

**제작 기간** : 2020.01 ~ 2020.02

**팀원**

- [jiminAn(안지민)](https://github.com/jiminAn)
- [sja3410(안선정)](https://github.com/sja3410)
- [Rudy-009(이승준)](https://github.com/Rudy-009)
- [yoonho0922(안윤호)](https://github.com/yoonho0922)
- [limjustin(임재영)](https://github.com/limjustin)

----------

**1. 앱 제작 동기**

실제 Instagram 앱 내의 다양한 기능들을 프로그래밍을 통해 직접 구현함으로써, 기능 구현 알고리즘에 대한 이해도를 돕고 향후 앱 제작에 있어서 심화된 기술을 사용할 수 있도록 연구하는 프로젝트

----------

**2. 기능**

- **회원가입 및 로그인** : Firebase Authentication 기능을 활용하여 사용자 정보 등록 및 로그인 가능

- **메인 피드** : 사용자가 작성한 사진 및 글이 메인 피드에 표시

- **글 업로드 기능** : 사진, 글을 업로드하여 하나의 피드 생성 가능

- **팔로우 / 팔로워 기능** : 다른 사람의 계정을 팔로우 할 수 있고, 누가 자신을 팔로우했는지 확인 가능

- **사용자 프로필 검색** : 검색을 통하여 Firebase 내에 등록되어 있는 계정들을 확인 가능

- **마이페이지** : 프로필 사진, 게시물 수, 팔로우 / 팔로워 수, 자신이 올린 게시물 확인 가능

----------

**3. 상세 기능 다이어그램**

![image](https://user-images.githubusercontent.com/55044278/94835585-db683f80-044c-11eb-873f-768e2b6f9bc1.png)
![image](https://user-images.githubusercontent.com/55044278/94835610-e327e400-044c-11eb-960a-26a6f3f64c3e.png)

----------

**4. 사용 프로그램**

- **Android Studio** : JAVA 코드로 프로그램 기능 구현

- **Firebase** : Cloud Firestore를 데이터베이스 사용

----------

**5. 앱 실행 화면**

- **시작 화면**
  - 2초동안 시작 화면 로딩하도록 구현
  
  - Inyrogram의 로고와 글귀가 표시
  
    <img src = "https://user-images.githubusercontent.com/55044278/94837312-0f446480-044f-11eb-9840-5b9f97d6deee.png" height = "500px">

<br>

- **메인 피드 화면**
  - 사용자가 직접 작성한 글, 사용자가 팔로우한 사람의 글이 메인 피드에 표시
  
  - Cloud Firebase에서 데이터 로드
  
    <img src = "https://user-images.githubusercontent.com/55044278/94837603-6fd3a180-044f-11eb-98f7-3b2619e54bef.png" height = "500px">

<br>

- **팔로우 / 팔로워 화면**
  
  - 어느 계정의 사람이 자신을 팔로우 했는지, 혹은 내가 누구를 팔로우 했는지 확인 가능
  
  - 팔로우 / 팔로워 수의 변화 有
  
    <img src = "https://user-images.githubusercontent.com/55044278/94837741-9a255f00-044f-11eb-8c80-a6d48dc1abc8.png" height = "500px">

<br>

- **프로필 검색 화면**
  - 사용자의 아이디를 검색하면, 조건에 맞는 아이디가 ListView 형식으로 표시
  
  - 자신 외의 계정들은 '팔로잉' 버튼이 존재
  
    <img src = "https://user-images.githubusercontent.com/55044278/94888591-97a92080-04b4-11eb-96c9-937dec5dcce9.png" height = "500px">
  
    
  
    <img src = "https://user-images.githubusercontent.com/55044278/94838434-89c1b400-0450-11eb-91ab-35b58fb4ccce.png" height = "500px">

<br>

- **마이페이지 화면**
  - 사용자 정보 확인 가능
  
    <img src = "https://user-images.githubusercontent.com/55044278/94837944-d5279280-044f-11eb-93e6-73ad42dc50b9.png" height = "500px">

----------

6. **한계점 (구현하지 못한 기능)**
   - 좋아요 / 댓글 기능
   
     - 확장 : 사진을 두 번 클릭해도 '좋아요'가 눌러지는 기능
     
   - DM(Direct Message) 기능
   
   - 알림 기능
