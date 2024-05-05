# MBTI 톡 - 커뮤니케이션 서비스 <br>(배포 완료)
> ## MBTI톡은 자신의 MBTI와 상성이 잘 맞는 친구 매칭 서비스
> 23.10.10 ~ 23.11.17

## 시연 영상
[영상 보기](https://drive.google.com/file/d/1Kwgsahq4zV414lMSXAA0sujLGkYtqP3u/view)

## 와이어 프레임
![스크린샷 2023-11-21 201338](https://github.com/6pleasant-MBTITalk/MBTI_Talk/assets/139088072/ccbd3536-33ec-4538-98dd-f000a962f044)

[Figma](https://www.figma.com/file/QXM0DdeFpzehGclrY0fI9p/1?type=design&node-id=0-1&mode=design)

## 개발자

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

<br><br>

----------

# 주요 기능

<br>

## LoginActivity
* 작업자 : 임두형
* google login 기능과 회원가입, 이메일을 통한 비밀번호 찾기 기능

<br><br>

## BottomActivity, UI 디자인
* 작업자 : 황진주
* 레이아웃 디자인과 및 bottom navigation

<br><br>

## Friend Find/List Fragment, DetailActivity
* 작업자 : 이도연
* 사용자의 정보와 친구추가, 채팅, 차단기능
* MBTI 알고리즘 통해, 상성에 따른 하트 갯수를 분배 및 리스트 위치조정
* 검색 필터링

<br><br>

## PostFragment
* 작업자 : 장재원
* 검색기능을 통해 원하는 게시물 검색 가능
* 게시물 수정시 게시물 내용과 이미지 수정 가능
* 필터 기능을 통해 좋아요한 게시물과 나의 게시물, 모든 게시물을 필터링
* 게시물 프로필을 누르면 상세 페이지로 이동

<br><br>
  
## ChatFragment
* 작업자 : 이진혁
* 채팅방을 만들어서 1대1 채팅 가능
* 실시간 채팅 기능, 시간 표시
* 마지막으로 채팅한 기록을 리스트에 표시

<br><br>
  
## MyproflieFragment
* 작업자: 황진주, 이도연, 임두형, 장재원
* 내 사용자 정보 출력
* MBTI 정보 수정/검사 기능
* 차단한 사용자 목록 관리
* 회원탈퇴, 로그아웃 기능

------------

<br>

# 사용된 기술 및 라이브러리

## Firebase Authentication
>사용자 인증 정보 관리<br>
>로그인 시, 사용자의 인증 상태 관리

<br>

## Glide
>네트워크 이미지를 비동기적으로 로드하고, 이미지 뷰에 표시 <br>
>DetailActivity에서 사용자 프로필 이미지를 처리할 때 사용

<br>

## FireBase Realtime Database
>사용자 정보, 친구 목록, 차단 목록 등을 저장하고 실시간으로 업데이트<br>
>FriendFindFragment에서는 사용자의 데이터를 불러오고, DetailActivity에서는 선택된 사용자의 상세 정보를 조회

<br>

## Firebase Storage
>사용자 프로필 이미지와 같은 미디어 파일 처리<br>
>DetailActivity에서 프로필 사진 표시

## Firebase Realtime Database
>실시간 데이터베이스를 사용하여 채팅 데이터를 실시간으로 처리<br>
>채팅방 목록과 메시지를 데이터베이스에서 불러오거나 업데이트

<br>

## LocalDateTime, DateTimeFormatter
> 메시지의 전송 시각 처리<br>
> 메시지의 시각 정보를 사용자에게 익숙한 형태로 표시 (00:00)



