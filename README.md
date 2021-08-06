# <div align="center">:hatched_chick:  Welcome to MOIRA :hatched_chick: </div>
 ![moiralogo](https://user-images.githubusercontent.com/78129881/128320108-a399c821-5969-42ae-95c6-3dd394bf519f.jpg) 

## :heavy_check_mark: 소개
     'MOIRA'는 취향기반 관심사 커뮤니티로써, 각각의 카테고리별로 (운동,맛집,스터디,축제) 
    일회성 모임을 주선하는 플랫폼입니다.

## :heavy_check_mark: 기획의도
    워라밸이 중요한 시대에, 여가및 취미활동에서 관심 분야가 맞는 사람들끼리의 모임을 만들고 싶었습니다. 
    각 관심사별로 다양한 기능을 제공하며 운동,맛집,스터디,축제등의 카테고리로 분류하였습니다.

## :heavy_check_mark: 시연영상  (클릭시 영상이 재생됩니다)
[![MOIRA (팀프로젝트) 시연영상입니다.](https://img.youtube.com/vi/dtqxmdyglAA/0.jpg)](https://www.youtube.com/watch?v=dtqxmdyglAA) <br></br>
00:00 ~ 00:16 메인페이지 <br></br>
00:16 ~ 00:34 로그인(소셜로그인) & 로그아웃 <br></br>
00:35 ~ 01:04 회원가입 <br></br>
01:05 ~ 01:41 모임- 맛집 메인페이지 <br></br>
01:42 ~ 02:17 모임- 맛집모임글 작성페이지 <br></br>
02:18 ~ 모임- 맛집모임글 상세페이지 <br></br>

## :heavy_check_mark: 주요 개발 내용
    - Java 기반의 Spring MVC 서버 백엔드 개발
    - SVN을 통한 형상 관리
    - 웹캠을 통한 AI 모션인식
    - 스터디 플래너를 통한 일정관리
    - 웹소켓을 이용한 채팅 서비스 구현 (개인/ 단체 채팅)
    - 카카오맵 API를 통한 현재 내주변맛집 표시, 셀렉트박스를 통한 맛집 자동 검색 등
    - 카카오, 구글 오픈 API를 이용한 소셜로그인   (OAuth) 
    - 맛집 별점등록 기능
## :heavy_check_mark: 프로젝트 총평 및 기여한 부분
    1. 진행해본 프로젝트중 가장 완성도가 높은 서비스
 
    -  개인프로젝트를 진행했을 당시, 소셜로그인의 구현에 실패했었습니다. 
    이번 프로젝트에서 구글과 카카오톡 API를 정밀하게  분석하며 소셜로그인을 구현했습니다. 

    2. 사용자들이 편리하게 이용할 서비스들로 구성
 
    -  사용자 입장에서 어떤 기능이필요할지 생각해봤습니다. 
    카카오맵을 이용한 맛집정보와 위치 표시, 맛집 일정관리등의 기능을 구현했습니다.
## :heavy_check_mark: 웹 URL
   :house: https://moira1.iptime.org:8443/meet/  

   :house: https://moira1.iptime.org:8443/meet/taste/home 
## :heavy_check_mark: 제작 기간 ( 7주 - 2021/6/15 ~ 8/3 )
![제작기간](https://user-images.githubusercontent.com/78129881/128327027-41283cd8-407f-4499-9df5-26e053af5872.jpg)
## :heavy_check_mark: Overview
### 0. 메인페이지
![팀1-메인](https://user-images.githubusercontent.com/78129881/128335055-263f2803-f30d-4ca6-b2c9-440ef914ea21.jpg)
<div align="center"> 부트스트랩을 이용한 moira 메인 페이지입니다. </div>

### 1. 유저 로그인 (소셜 로그인)
![팀-로그인](https://user-images.githubusercontent.com/78129881/128335078-9b0f3c69-eeeb-4d93-b134-662d8568b87b.jpg)
<div align="center"> 카카오와 구글 API를 이용한 소셜로그인 구현 (OAuth)</div>

### 2. 모임게시판
![팀-모임게시판](https://user-images.githubusercontent.com/78129881/128335143-8e508e9a-bc18-4109-878f-35f95284c04b.jpg)
<div align="center"> 각 카테고리별로 모임을 조회할수 있습니다. </div>

### 3. 맛집 메인페이지
![팀-맛집메인1](https://user-images.githubusercontent.com/78129881/128335148-d9c5b65c-5d2c-4655-9568-5c8a0dee0a3c.jpg)
![팀-맛집메인2](https://user-images.githubusercontent.com/78129881/128338587-ff16f638-a694-41f4-b8aa-889d30e97e9a.jpg)
![팀-맛집메인3](https://user-images.githubusercontent.com/78129881/128338595-9701581f-fe96-49a4-aedb-258f94d23b36.jpg)
![팀-맛집메인4](https://user-images.githubusercontent.com/78129881/128338597-8cd3d690-0c70-4775-9706-9fac284e2fa8.jpg)
<div align="center"> 부트스트랩을 이용한 맛집 메인 페이지입니다. </div>

### 4. 위치기반 서비스 가이드라인 페이지
![티메위치기반](https://user-images.githubusercontent.com/78129881/128335404-ad136f05-1bf8-4615-b206-73f994f18b4f.jpg)
<div align="center"> 현재 내 위치가 보이지 않을시, 안내를 도와주는 위치서비스 이용방법 페이지입니다. </div>

### 5. 맛집모임 글 작성 페이지
![팀-맛집글작성1](https://user-images.githubusercontent.com/78129881/128335172-85f12efa-2a2d-40ae-8be5-0accd132979c.jpg)
![팀-맛집글작성2](https://user-images.githubusercontent.com/78129881/128338632-1eb2a087-d048-4ab3-b705-29a36e8c105c.jpg)
![맛집작성글4](https://user-images.githubusercontent.com/78129881/128338648-89d9a36b-8092-48bf-917f-7491a94bfca9.jpg)
<div align="center"> 맛집 모임글에만 존재하는 맛집리스트 일정추가 기능입니다. </div>

### 6. 맛집모임 글 상세 페이지
![팀-맛집글상세1](https://user-images.githubusercontent.com/78129881/128335209-89e9e772-8215-4d9e-a064-d22666729e90.jpg)
![팀-맛집글상세2](https://user-images.githubusercontent.com/78129881/128338676-6607df4a-62e4-4713-b9e7-6f0474e421b2.jpg)
![팀-맛집글상세3-별점기능](https://user-images.githubusercontent.com/78129881/128338678-20456bee-6eff-4150-ad74-17610dac01a1.jpg)
<div align="center"> 게시글 상세페이지에는 DB에 저장된 위도,경도값을 불러와 맵에 마커로 표시되며, 별점 기능으로 후기를 작성할수 있습니다. </div>

### 7. 마이페이지 모집 글 내역
![팀-마이페이지모집글내역](https://user-images.githubusercontent.com/78129881/128335233-862a926f-98e8-4842-9936-c4acb5422719.jpg)
<div align="center"> 마이페이지에서는 자신이 개설한모임과 신청한모임, 참여중인 모임, 완료중인 모임을 확인할수 있습니다. </div>

## :heavy_check_mark: ERD
![table_erd_수정_210804](https://user-images.githubusercontent.com/78129881/128328964-0ee64b71-e73f-463a-9136-0188ea0f3469.png)

## :heavy_check_mark: Tech stack
![backendd](https://user-images.githubusercontent.com/78129881/128328994-d3bb1f68-f9c9-4801-8a28-174cc019d885.jpg)

## :heavy_check_mark: 담당 기능
![담당기능shot](https://user-images.githubusercontent.com/78129881/128327825-b828bdb7-1c3d-4bdf-9ec3-dca2b8c9e1cb.jpg)
## :heavy_check_mark: 역할 분배
![역할분배](https://user-images.githubusercontent.com/78129881/128328175-c8569457-6135-4457-8b7a-7140d831eac0.jpg)


 # <div align="center"> :sparkles: 봐주셔서 감사합니다. :sparkles: </div>

