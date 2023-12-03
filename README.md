# MBTI matching social app / M친톡 - MBTI를 이용한 친구 찾기 톡!

## 프로젝트 소개
MBTI 친구 톡의 줄임말인 M친톡은 MBTI를 이용해서 자신의 MBTI와 상성이 잘 맞는 친구나 이성을 매칭을 시켜주는 소셜 앱입니다.

## 프로젝트 상세 

### 개발기간
23.10.10 ~ 23.11.17

### 시연 영상
[영상 보기](https://drive.google.com/file/d/1Kwgsahq4zV414lMSXAA0sujLGkYtqP3u/view)

### 와이어 프레임
![스크린샷 2023-11-21 201338](https://github.com/6pleasant-MBTITalk/MBTI_Talk/assets/139088072/ccbd3536-33ec-4538-98dd-f000a962f044)

[Figma](https://www.figma.com/file/QXM0DdeFpzehGclrY0fI9p/1?type=design&node-id=0-1&mode=design)

### 개발자

<table>
 <tr>
   <td align="center">팀장</td>
   <td align="center">부팀장</td>
   <td align="center">팀원</td>
   <td align="center">팀원</td>
   <td align="center">팀원</td>
 </tr>
 <tr>
      <td align="center">장재원</td>
      <td align="center">이도연</td>
      <td align="center">임도형</td>
      <td align="center">황진주</td>
      <td align="center">이진혁</td>
   </tr>
 <tr>
      <td align="center"><a href="https://github.com/jang0710">깃허브</a></td>
      <td align="center"><a href="https://github.com/byu-rin">깃허브</a></td>
      <td align="center"><a href="https://github.com/limduh">깃허브</a></td>
      <td align="center"><a href="https://github.com/jinjoo1">깃허브</a></td>
      <td align="center"><a href="https://github.com/jh4016">깃허브</a></td>
   </tr>
 <tr>
      <td align="center"><a href="https://velog.io/@janga19">블로그</a></td>
      <td align="center"><a href="https://velog.io/@simon3397">블로그</a></td>
      <td align="center"><a href="https://duhyoung-tom.tistory.com/">블로그</a></td>
      <td align="center"><a href="https://vjinjoov.tistory.com/">블로그</a></td>
      <td align="center"><a href="https://velog.io/@jh4016">블로그</a></td>

   </tr>
   </table>

   ## 주요 기능
### LoginActivity
* 작업자 : 임두형
* google login 기능과 회원가입, 이메일을 통한 비밀번호 찾기 기능

### BottomActivity, UI 디자인
* 작업자 : 황진주
* 전반적인 레이아웃 디자인과 BottomBar를 통한 Fragment 전환과 디자인을 담당
### Friend Find/List Fragment, DetailActivity
* 작업자 : 이도연
* 리스트를 누르면 DetailActivity로 이동, 사용자의 정보와 친구추가, 채팅, 차단기능 표시
* Friend Find 에서 MBTI 알고리즘을 이용해 상성에 따른 하트 갯수를 분배 및 리스트 위치조정
* 친구 추가시 Friend list에 표시
* 친구 차단시 Friend list에서 없어지고 차단 목록에 표시
* 필터 기능을 통한 원하는 친구를 필터링
* 필터가 되지않으면 검색 결과가 없음 이미지 출력
* 친구 리스트에 친구가 없으면 친구 없음 이미지 출력
### PostFragment
* 작업자 : 장재원
* 검색기능을 통해 원하는 게시물 검색 가능
* 게시물 수정시 게시물 내용과 이미지 수정 가능
* 필터 기능을 통해 좋아요한 게시물과 나의 게시물, 모든 게시물을 필터링
* 게시물 프로필을 누르면 상세 페이지로 이동
### ChatFragment
* 작업자 : 이진혁
* 채팅방을 만들어서 1대1 채팅 가능
* 실시간 채팅 기능, 시간 표시
* 마지막으로 채팅한 기록을 리스트에 표시
### MyproflieFragment
* 작업자: 황진주, 이도연, 임두형, 장재원
* 내 사용자 정보 출력
* MBTI 정보 수정/검사 기능
* 차단한 사용자 목록 관리
* 회원탈퇴, 로그아웃 기능 

