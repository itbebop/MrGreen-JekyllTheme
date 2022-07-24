---
# multilingual page pair id, this must pair with translations of this page. (This name must be unique)
lng_pair: id_React_1
title: "React 기본 세팅"

# post specific
# if not specified, .name will be used from _data/owner/[language].yml
#author: ""
# multiple category is not supported
category: React
# multiple tag entries are possible
tags: [Setting]
# thumbnail image for post
img: ":post_pic1.jpg"
# disable comments on this page
#comments_disable: true

# publish date
date: 2022-07-24 17:12 +0900

# seo
# if not specified, date will be used.
#meta_modify_date: 2021-10-14 18:47:35 +0900
# check the meta_common_description in _data/owner/[language].yml
#meta_description: ""

# optional
# if you enabled image_viewer_posts you don't need to enable this. This is only if image_viewer_posts = false
#image_viewer_on: true
# if you enabled image_lazy_loader_posts you don't need to enable this. This is only if image_lazy_loader_posts = false
#image_lazy_loader_on: true
# exclude from on site search
#on_site_search_exclude: true
# exclude from search engines
#search_engine_exclude: true
# to disable this page, simply set published: false or delete this file
#published: false
---

{%- comment -%} Please delete below and place your page content here {%- endcomment -%}
<h2>작업 순서</h2>
<hr>

1. Node.js 설치, 버전 확인
   1.1. Node.js 공식 사이트에서 <LTS 버전> 버튼을 눌러서 다운 & 설치
   1.2. 설치 확인
    * 명령프롬프트에서 버전 확인
      > node -v


2. npm 설치, 확인
   2.1. npx란 1회성으로 최신 버전의 노드 패키지를 내려받아 설치시켜주는 노드 패키지. <br>
  따라서 npx는 npm으로 설치해야한다.
   2.2. 설치 명령어
    * 명령프롬프트에서
      > npm install npx -g 생략.. + npx@10.2.2
      > added 293 packages from 654 contriburos in 11.548s

    2.3. 설치확인
    * 명령프롬프트에서
      > npm -v


3. 프로젝트 폴더 생성
    * 명령 프롬프트에서
      > npx create-react-app movie _app_2022


4. vscode.git 설치


5. vscode에서 폴더 선택


6. README.md 파일 수정


7. package.json 파일 수정
  * 명령 프롬프트
    > test : "react-scrips test"
    > eject":"react-scrips eject"

  * 윗 부분 삭제


8. 리액트 앱 실행
  * 명령 프롬프트
    > npm start

  # 에러
  * 명령 프롬프트
    > npm ERR! code ENOENT
    npm ERR! syscall open
    npm ERR! path C:\/package.json
    npm ERR! errno -4058
    npm ERR! enoent ENOENT: no such file or directory, open 'C:\package.json'
    npm ERR! enoent This is related to npm not being able to find a file.
    npm ERR! enoent
    npm ERR! A complete log of this run can be found in:
    npm ERR!     C:\Users\icicl\AppData\Local\npm-cache\_logs\2022-05-14T03_56_35_700Z-debug-0.log

  <br>
  - 이건 package.json파일을 못찾는다는 내용이었음
  - 기존에 리액트 설치한 (package.json이 있는)폴더에서 cmd 실행해서 <br>
  npm start를 하면 실행됨
  <br>

9. 리액트 앱 종료
  * 명령 프롬프트
    > Ctrl + C

<br>
10. vscode 통합 터미널 실행방법
  - 메뉴 / 터미널/ 새터미널
  - 단축키 : Ctrl+Shif+`


{%- include util/auto-content-generator.liquid -%}

<!-- outline-start -->
<hr>
#Setup

<!-- outline-end -->
