# 🌿농부심 - 농부의 마음


## 🖥️ 프로젝트 소개

농부들의 자부심 **"농부심"**
- 지역농부간 소통 +  지역농부와 지역소비자 연결을 위한 Web 플랫폼

    ◦  농부간 정보공유 / 소통을 위한 기능 제공 

    ◦  농부 개인을 위한 기능 제공 ( 농작물입출금내역 / 영농일지)

    ◦  농장체험 프로그램 및 지역농산물 거래 중개

	→  유저구분( 농부 / 일반) 을 통한 상이한 기능 제공

<img src="https://github.com/fara2828/my-nongbushim/assets/121650362/7d3d78f6-64a9-4267-a3bc-24b0a8801157" width="60%" height="60%">

## 🗓 개발 기간
22.12.30 - 23.01.25


## 🧑‍🤝‍🧑 팀원
- 이상민: 통합 검색기능 (추천검색어, 게시판 전체검색) , 마이페이지(농부) - 영농일지(CRUD) , 입출금관리(CRUD)
- 서지연: 로그인, 로그아웃, 회원가입, 마이페이지(정보수정, 작성글조회, 찜 관리)
- 송누리: 농장 전체 리스트(지역별, 키워드 검색), 농장 상세 조회 페이지, 정보 공유 게시판(CRUD), 농장 정보 등록/수정/삭제
- 이영준: 프로그램 전체 리스트, 프로그램등록(농부만), 프로그램상세조회(회원 신청), 참여프로그램 조회, 프로그램 후기 게시판
- 김승혜: 농작물 거래 게시판(CRUD), 비밀댓글
- 황승필: 파머게시판(CRUD)-내농작물자랑, 질문게시판, 멘토멘티구하기, 농사노하우공유게시판

**※ 각자 담당 기능에 대해 Full-stack으로 구현 (DB - BE - FE)**





## ⚙️ Tech Stack

- Back-end:
  <div>
     <img src="https://img.shields.io/badge/Java-007396?style=flat&logo=Java&logoColor=white" />
     <img src="https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=Spring&logoColor=white"/>
  </div>  
- DB:
  <div>    
    <img src="https://img.shields.io/badge/ORACLE-F80000?style=flat-square&logo=oracle&logoColor=white"/>
    <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=MySQL&logoColor=white"/>
    <img src="https://img.shields.io/badge/Mybatis-purple?style=flat-square&logo=Mybatis&logoColor=red"/>
  </div>
- Front-end:
  <div>
    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
  </div>
- Others:
  <div>
   <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=HTML5&logoColor=white" />
   <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=CSS3&logoColor=white" />
   <img src="https://img.shields.io/badge/jQuery-0769AD?style=flat-square&logo=jQuery&logoColor=white"/>
   <img src="https://img.shields.io/badge/Apache Tomcat-F8DC75?style=flat-square&logo=apachetomcat&logoColor=white">  
  </div>    

---
<img src="https://github.com/fara2828/my-nongbushim/assets/121650362/b7bd7ed2-025a-4547-ad69-88c276fd2d2e" width="60%" height="60%">


---

## ⭐️ Usecase Diagram

<img src="https://github.com/fara2828/go-for-it/assets/121650362/97831728-6a2f-40a9-b8f8-736b3481d956" width="60%" height="60%">

## 👉 ERD 

<img src="https://github.com/fara2828/my-nongbushim/assets/121650362/9003e5b6-82f4-4fb6-894a-653fd783bc2e" width="60%" height="60%">

## 📚 요구사항 명세서


## 나의 담당기능
  **※ 담당 기능 Full-stack으로 구현 (DB - BE - FE)**


- 입출금내역
    - 가계부 작성 / 수정 / 삭제 (CRUD)
        - 다중 첨부파일
    - 월별 수입 / 지출 /  합계 캘린더 조회
        - 사용자 입력 Data를 달력 시각화하여 조회 (FullCalendar Library)
    - 기간 / 카테고리별 수입 / 지출 내역 조회
        - 엑셀 다운로드 (SheetJS Library)
- 영농일지
    - 상세기능 상동(입출금내역과 동일)
    
- 통합 검색
    - 추천검색어
        - 사용자 keyup과 연동한 추천검색어 띄워주기
        - 총 6개 테이블 data 조회 결과 표기
    - 게시판 전체검색
        - 검색결과 게시판별 조회

## 담당 파일트리
1. Back-end
<img src="https://github.com/fara2828/my-nongbushim/assets/121650362/e8f3dbfa-b44d-4669-99f3-35b3427c35cb"  width="20%"/>
 
2. Front-end
<img src="https://github.com/fara2828/my-nongbushim/assets/121650362/aafcb3e2-41d5-4de6-b91c-79b6a12aa68d" width="50%"/>
    
3. MyBatis Mapper 
<img src="https://github.com/fara2828/my-nongbushim/assets/121650362/b7ac317e-58d7-4bc5-bc51-55de3983d916" width="40%"/>  

## 🖥 시연영상



1. 입출금내역
- 월별 수입 / 지출 /  합계 캘린더 조회
<img src="https://github.com/fara2828/my-nongbushim/assets/121650362/83740b66-a03f-48f1-a60c-ba7f5a852217" width="60%" height="60%">

- 기간 / 카테고리별 수입 / 지출 내역 조회  
<img src="https://github.com/fara2828/my-nongbushim/assets/121650362/f2f28690-a790-4046-983e-c885baa24e14"  width="60%" height="60%">
  
- 작성 / 수정 / 삭제 (CRUD)    
<img src="https://github.com/fara2828/my-nongbushim/assets/121650362/7c2cbf40-aa06-4e1c-9d50-8c4accddef4d" width="60%" height="60%">
<img src="https://github.com/fara2828/my-nongbushim/assets/121650362/d5735154-bada-4d50-b926-4cd3a4de7658" width="60%" height="60%">
  



2. 영농일지
    - 상세기능 상동(입출금내역과 동일)
    
<img src="https://github.com/fara2828/my-nongbushim/assets/121650362/9bd69cf7-5e0d-44f8-8448-8963bf566e7e" width="60%" height="60%">
<img src="https://github.com/fara2828/my-nongbushim/assets/121650362/4c09f59d-b28e-4215-9512-1809699cc5b9" width="60%" height="60%">
<img src="https://github.com/fara2828/my-nongbushim/assets/121650362/768a1f3b-a314-48b4-ada4-db69ffb20035" width="60%" height="60%">
<img src="https://github.com/fara2828/my-nongbushim/assets/121650362/5f7bca2e-1e89-4ffc-8a28-86d020a16a98" width="60%" height="60%">


3. 통합 검색
- 추천검색어
<img src="https://github.com/fara2828/my-nongbushim/assets/121650362/91eb6a15-ee52-4248-9cd0-f9e52f12fc70" width="60%" height="60%">

- 게시판 전체검색
<img src="https://github.com/fara2828/my-nongbushim/assets/121650362/693cf7db-eb34-4f6d-8cb8-3a80abbf0c23" width="60%" height="60%">



