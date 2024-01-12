# heyDoctor

<h1>지역 산업 활성화를 위한 스타트업 지원프로그램 운영 - 'yeongae-somun'</h1>


<h2>1. 기획 의도</h2>
<img width="1088" alt="background" src="https://github.com/README-wmoon/study-html/assets/129862668/0a2d1ee9-5845-4464-9a73-2140baa7447d">

지역 청년들이 낮은 임금으로 인해 일자리를 찾아 서울 등 수도권으로 떠나고 있다. <strong>따라서 청년들이 지역을 외면하고 서울로 떠나는 것은</strong>일자리가 없기 때문이다. 
인구 위기에 대한 목소리가 계속해서 높아지는 가운데, 비수도권은 저출산율에 지방 이탈 문제까지 더해져 지방 소멸 위기라는 다소 심각한 상황에 놓여있다.<strong>신규 인력 채용 과정에 
기관이 서류전형을 직접 평가하는 등 기업의 입장을 고려하지 않을 경우 최적의 지원자를 뽑을 수 밖에 없는 상황이 오기떄문에</strong>우리는 이런 불피요함을 없애기 위해서 이런 프로젝트를 기획하였다.

</div>


<h2>2. 기대 효과</h2>
<img width="1088" alt="purpose" src="https://github.com/README-wmoon/study-html/assets/129862668/80c3e1bf-e8dd-44ed-8f66-a7221245eb6b"><br>
STEP 1. 양질의 일자리가 수도권에 집중되면서, 지역 청년들은 대학 진학 또는 취업 시기에 고향을 떠나 수도권으로 이동할 수밖에 없다br>
STEP 2. 수도권은 포화상태가 된 지 오래다.<br>
공공 기관과의 협력 강화을 통해 지자체나 정부 기관과의 협력을 통해 스타트업 지원 프로그램을 운영합니다 <br>
지역 특성과 잠재력을 고려하여 산업 육성을 위한 스타트업 지원 프로그램을 운영합니다 <br>


<h2>3. 프로젝트 사용 툴</h2>
- Java<br>
- Java Script<br>
- tomcat<br>
- jQuery<br>
- MyBatis<br>
- Spring Boot<br>
- Oracle<br>
- Visual Studio Code<br>
- JPA <br>
- DBeaver<br>
- Sourcetree<br>
- git, github<br>
- JSON<br>
- Ajax<br>
- JDK 11.0.15<br>

<h2>4. ERD</h2>
<img width="1004" alt="erd" src="https://github.com/README-wmoon/study-html/assets/129862668/def4b377-25db-4f52-98b2-50fd663c33dd">

  
<h2>5. 담당 업무</h2>
5-1 프론트엔드<br>
<img width="1243" alt="front" src="https://github.com/README-wmoon/study-html/assets/129862668/fb0197f4-c8be-46ce-b998-f3a247ae5774">

▶ 로그인
- 다른 방법으로 시작하는 법
- 로그인 모달창

▶ 메인페이지
- 메인페이지 보이기

▶ 회원가입
- 이메일 등록
- 이메일 발송 완료
- 비밀번호 변경

▶ 기업 마이페이지
- 기업 신청 내역
- 기업 계정 설정
- 기업 목록
- 투자글 목록
- 1일체험 목록

▶ 스타트업 페이지
- 스타트업 소개
- 사업 소개
- 창업 상품 소개
- 참여한 기업 목록
- 체험 소감서

▶ 일반회원 페이지
- 일반회원 계정 설정
- 자기소개 페이지
- 기업 또는 스타트업으로 전환
- 참여한 창업 상품 체험
- 체험 소감

▶ 쪽지
- 쪽지로 보내기

<br>
5-2 백엔드<br>
<img width="1288" alt="back" src="https://github.com/README-wmoon/study-html/assets/129862668/6e923cf9-88f1-46ce-ac62-1da006eafee6">


▶ 검색창
- 환자 전체 질문 목록 리스트
- 환자 질문 타이틀 검사

 

<h2>6. 느낀점</h2>
<h3>6-1. 어려웠던 부분</h3>
📌MVC도 어려웠지만, Controller부분이 어려웠었다. <br>
✔ 단계가 익숙하지 않아 mapper부터 controller까지 진행하는 것이 어려웠었다, 또한 Controller에서 쓰는 용법들이 어떻게 작용하는지 몰라서 많이 노력을 했었다.<br><br>
<br>


<h3>6-2. 문제를 해결했던 부분</h3>
<h4>📌검색창 클래스</h4>
🌩문제 상황🌩<br>
Spring boot에서 Test를 해봤을때 ibatis라는 에러가 걸려서 test를 할수 가 없었다.<br><br>
🚨문제 원인🚨 <br>
기능 구현에는 문제가 없었으나, test가 안되서 이게 제대로 되는지 안되는지 확인이 불가능 했다. <br><br>
🚀해결 방법🚀<br>
클래스에 @Param("search") Search keyword 라는 것을 넣어놧엇는데, @Param("search") 있는것을 삭제하였더니, 제대로 작동을 하였다. 
<br><br><br>




<h3>5-4. 총평</h3>
<h4>🌟 소통이 답이다. </h4>
항상 소통이 있어야 프로젝트 완성을 가능하게 할 수 있고, 소통이 없으면 모든 프로젝트가 망할 가능성이 있다. 그리고 강의를 듣거나 중요한 문제가 있을떄 혼자 하는것 보다는 함꼐 모여서 이것에 대해
소통을 하면서 찾아 가는것이 더 기억이 나고 중요하게 느낀다. 더 나아가 소통을 하며 하는 경험들이 면접을 조금더 잘 볼수 있는 원동력이 될 수 있다.





