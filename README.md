# Contact App
주소록 App 프로젝트 README.md
<br/>

# 📚 목차

- [1.프로젝트 소개](#1.-프로젝트-소개)
- [2. About 팀](#2.-About-팀)
- [3.앱 시연 영상](#앱-시연영상)
- [4.제작과정](#제작-과정)
  
# 📝 1. 프로젝트 소개

## 프로젝트 소개
> 구현한 기능

1. Contact 
- TabLayout, ViewPager2, FloatingActionButton
- TabSwitch 클릭이벤트 전달

2. Contact List 
- RecyclerView, Adapter
- 연락처 리스트 출력, 좋아요 시 즐겨찾기 등록

3. Contact Mypage, Contact Detail
- ClipboardManager, PopupMenu, Intent
- 전화, 문자, 링크(인터넷) 및 Copy 복사

4. Contact Dialog, Schedule Dialog
- DialogFragment 
- 유효성 검사, 갤러리 이미지 선택

## 와이어프레임(Figma)
  ![image](https://github.com/BanDalKang/CONTACT-APP/assets/77070839/8c93a87b-b0c0-49ce-ab72-d7a80421fcd6)


# 👩‍👧‍👧 2. About 팀 

<table>
  <tbody>
    <tr>
      <td align="center"><a href="https://github.com/rlaxodud214"><img src="https://github.com/BanDalKang/CONTACT-APP/assets/77070839/4cd02ec3-8af1-4b70-b163-60c497d42f9e"
      heigt="50px" width="50px"/><br /><sub><b>팀장: 김태영 </b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/BanDalKang"><img src="https://github.com/SeoHeaYun/One-Project/assets/159236003/44e2ebc9-c476-46a4-8295-a03833d226a3" 
       heigt="50px" width="50px"/><br /><sub><b>팀원 : 강현정 </b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/cococo35"><img src="https://github.com/BanDalKang/CONTACT-APP/assets/77070839/97a894fd-a540-4312-bd68-4785ab5b1ad9"
       height="60px" width="50px";/><br /><sub><b>팀원: 김태준 </b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/seoyoung19920921"><img src="https://github.com/SeoHeaYun/One-Project/assets/159236003/076e2da2-ee9e-4dac-872b-4450cb22a9d7"
       height="60px"width="50px;" alt=""/><br /><sub><b>팀원: 정서영 </b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/jihyung97"><img src="https://github.com/BanDalKang/CONTACT-APP/assets/77070839/9b66aff7-d236-4933-9bdb-19200769411b"
       height="60px"width="50px;" alt=""/><br /><sub><b>팀원: 유지형 </b></sub></a><br /></td>
     <tr/>
  </tbody>
</table>

## 팀플랜
- Git 브랜치 룰 & 전략
  - develop branch push 금지 설정
  - git branch 간의 merge는 무조건 pull request 통해서 한다
  - git pr은 팀원 1명 이상의 승인이 있어야 merge가 가능하다.
  - branch 명 : feat/기능 구현 페이지 명 , refactor/기능 구현 페이지 명
    

- Git 컨벤션
  - "커밋 타입: 커밋 내용"
  - feat: 새로운 기능 추가
  - fix: 버그 수정, 병합 시 충돌 해결
  - refactor: 1) 코드 간소화, 중복된 로직 제거 2) 파일의 삭제, 이동 및 이름 변경
  - add: resource등 파일 추가
  - style: 사용자 UI 디자인 변경시
  - etc..

# ⚙️ 3. 앱 시연영상
![Video Label](http://img.youtube.com/vi/hREJZcteeOg/0.jpg)</br>
(https://www.youtube.com/watch?v=hREJZcteeOg)


# 📜 4. 제작과정
## 타임라인
- 4/22: 프로젝트 기획
  - 구현사항 분석
  - 와이어 프레임 구상
  - UI & UX 디자인
  - 기술 스택 선정
  - 역할분배
- 4/22 ~ 4/24: 개발
  - Git과 칸반보드를 활용한 의견 문서화 및 공유
- 4/24: 테스트
  - 코드 병합 후, 기능 테스트 & 리펙토링
- 4/25: MERGE
  - Main 브랜치에 merge 후 시연영상 제작
 
