---
# multilingual page pair id, this must pair with translations of this page. (This name must be unique)
lng_pair: id_React_2
title: "Git Setting"

# post specific
# if not specified, .name will be used from _data/owner/[language].yml
#author: ""
# multiple category is not supported
category: React
# multiple tag entries are possible
tags: [Setting]
# thumbnail image for post
img: ":post_pic2.jpg"
# disable comments on this page
#comments_disable: true

# publish date
date: 2022-07-27 23:12 +0900

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
#리액트 앱 업로드
<hr>

1. 로컬 저장소 초기화
  * 명령프롬프트
     > git init
     > Initialized empty Git repository in ...이나
    > Reinitialized existing Git repository in .. 이라는 메세지 뜨면 성공

2. 깃허브에 저장소 만들기
   1. Create a New Repository
   2. Repository name : movie_app_2022\
   3. Desciption : React Js Fundamentals couse 2022
<br>

3. 깃허브 저장소에 리액트 앱 업로드
  * 명령프롬프트
    > git remote add origin github.com/[계정 이름]/movie_app_2022.git
    > git add
    > git commit -m "02-2 깃허브에 리액트 앱 업로드"
    > git push origin master

4. 깃허브 저장소 확인

<hr>

#리액트 앱 초기 설정
<hr>
1. 필요없는 파일 삭제
  * src 폴더
    App.css
    App.test.js
    index.css
    logo.svg
    seviceWorker.js
    setupTests.js
    package-lock.json

2. index.js 파일 중
  reportWebVitals(); 이 부분을 남기니까 index.css없다고 에러남
  이것까지 교재와 동일하게 삭제함

  * App.js 부분
  > return
    <div> .. </div>

  라고 해서 에러남
  > return (
    <div> .. </div>
   )

  라고 하면 에러 안나옴




{%- include util/auto-content-generator.liquid -%}

<!-- outline-start -->

#Git

<!-- outline-end -->
