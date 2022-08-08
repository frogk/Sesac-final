# 🌱CBP 프로젝트

Sesac 프론트엔드 실무 프로젝트 과정의 최종 팀 프로젝트로 기업으로부터 의뢰를 받아 원하는 사이트를 제작하는 프로젝트입니다.<br><br>
저희는 **엑스퍼트컨설팅**의 의뢰로 **기업에 입사하게 된 신입사원의 온보딩 교육을 위한 사이트**를 제작하게 되었습니다.

<br><br>

## 📌프로젝트 개요

* 진행 날짜 - 2022.07.04 ~ 2022.08.03
* 목적 - 엑스퍼트컨설팅 케미버스 홈페이지 제작
* 사이트 소개 - 최종 합격한 신입사원들이 입사 전 필요한 정보를 얻는 **Connect with** 페이지와 입사 후 사번으로 로그인하여 본격적인 온보딩 교육을 받을 수 있는 **On & Up** 페이지로 나뉘어진 사이트입니다.

| Connect With | <img src="https://s3.us-west-2.amazonaws.com/secure.notion-static.com/f17af8e4-fb5f-45e1-b71f-eee2f1c0dac4/%ED%99%94%EB%A9%B4_%EC%BA%A1%EC%B2%98_2022-08-08_034447.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220807%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220807T185803Z&X-Amz-Expires=86400&X-Amz-Signature=d5d66b65411432984cf6c4289138b77d0e5346d1af0796cf72e90789c46bb461&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22%25ED%2599%2594%25EB%25A9%25B4%2520%25EC%25BA%25A1%25EC%25B2%2598%25202022-08-08%2520034447.png%22&x-id=GetObject"> |
|---|---|
| **On & Up** | <img src="https://s3.us-west-2.amazonaws.com/secure.notion-static.com/39b8cee6-9d41-45f4-952f-39e31e7def81/%ED%99%94%EB%A9%B4_%EC%BA%A1%EC%B2%98_2022-08-08_034514.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220807%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220807T184942Z&X-Amz-Expires=86400&X-Amz-Signature=e7f926fae17c9743cc54f9b70559e948f5f46eb0a4d83473b9d58a02891f38b3&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22%25ED%2599%2594%25EB%25A9%25B4%2520%25EC%25BA%25A1%25EC%25B2%2598%25202022-08-08%2520034514.png%22&x-id=GetObject"> |

<br><br>

## 💻 주요 기능
* 로그인 기능 : 온보딩 교육을 받는 페이지는 로그인 없이 접근이 불가해야하기 때문에 로그인 기능이 필요합니다.
* 게시판 기능 : 공지사항을 확인할 수 있으며, 자기소개와 자유게시판이 있어 검색기능과 글쓰기, 수정하기,좋아요 기능이 포함되어 있습니다.
* 강의정보, 강의 일정, 강사와 관련된 정보를 확인할 수 있습니다.
* 신입사원들이 온보딩 교육 전과 후를 비교할 수 있는 진단 페이지가 있습니다. 그래프로 자신의 상태를 알 수 있습니다.
* 수업과 관련된 내용에 이용자가 작성하고 저장할 수 있는 페이지가 있습니다.
* On & Up 메인 페이지에서 지도의 각 건물을 클릭하여 해당하는 페이지로 이동할 수 있습니다.

<br><br>

## 🏃‍♀️ 실행하기

* 링크 : https://friendly-empanada-048c24.netlify.app/
* 로그인 계정 :
  ```
  아이디 : user01
  비밀번호 : 1234
  ```
<br><br>

## 😎 Team

* 김해리(조장)
* 오성흔
* 오채아
* 윤종협
* 임가을
* 정찬욱

<br><br>

## 🐸 나의 업무

* 게시판 기능을 구현하였습니다. 데이터를 불러와 map()을 이용해 반복으로 보여주었으며 페이지네이션을 구현했고 제목을 클릭하면 자세히 보기 기능을 구현했습니다.
* 강의정보 보여주기 페이지를 만들었습니다. 강의 url 복사기능, 달력으로 일정 확인하기, 강사 정보 확인 페이지를 만들었습니다.
* 전체적인 css를 수정했습니다. 제가 작업한 페이지 뿐 아니라 다른 조원들이 작업한 페이지에서 반응형이 적용되지 않거나 다른 css오류가 있는 경우 그것을 수정했습니다.

<br><br>

## 🐸 이번 프로젝트를 하며 적용해본 것

* axios로 데이터 불러오기
* 반응형 규격 잡기 (vw, vh, rem등의 규격을 언제 사용할지)
* map()을 이용하여 컴포넌트 재사용하기
* props로 값 내려주기
* scss를 이용. 색상과 폰트사이즈에서 변수를 사용하여 효율적으로 마크업함

<br><br>

## 🙏 이번 프로젝트에서 아쉬웠던 점/느낀점.

요구하는 기능은 다 구현했으나 시간적 여유가 없어 세부적인 부분을 완벽히 마무리 하지못한것이 아쉽습니다.<br>
작은 오류들과 모바일에서 생각처럼 보이지 않는 페이지가 몇몇 있는데 그것을 추후 리팩토링하여 다시 배포해 보고 싶습니다.<br><br>
또한, 푸터를 따로 작업하여 배포 직전 푸터를 합쳐보니 페이지 중앙에 배치되는 이슈가 있었습니다. 확인해보니 전체적인 페이지의 높이값이 잘못 적용되어 그런것이었습니다. <br> 페이지의 전체적인 틀을 잡을 때, html 마크업 구조를 정확하게 설계하여 작성하고 css를 적용해야한다는 것을 느꼈습니다.
