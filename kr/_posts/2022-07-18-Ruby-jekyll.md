---
# multilingual page pair id, this must pair with translations of this page. (This name must be unique)
lng_pair: id_ruby_1
title: "한글추가방법"

# post specific
# if not specified, .name will be used from _data/owner/[language].yml
#author: ""
# multiple category is not supported
category: Ruby
# multiple tag entries are possible
tags: [jekyll]
# thumbnail image for post
img: ":post_pic1.jpg"
# disable comments on this page
#comments_disable: true

# publish date
date: 2022-07-18 20:47:35 +0900

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
#작업 순서
<hr>

1. data/lang폴더에 kr.yml추가<br>


2. _site/posts에 한글로 된 컨텐츠 추가<br>


3. data/conf/main.yml에
   <br>language_switch_lang_list: [en, ja, kr] 추가

<hr>
문제점  <br>

1. 이 글을 조회할 때는 옆에 언어 switch버튼이 안뜸
2. 목록 보기 버튼이 없음
<hr>

생각해볼 점<br>

1. 글을 어떤 식으로 관리할지. 예를들면 블로그라는 카테고리가 하나이고
   그 안에 글을 관리하려면 파일 이름을 모두 동일하게 달고
   그 안에서 제목을 따로 달아서 내용을 구분하는 방법 등

2. markup Language를 편하게 작성할 수 있는 프로그램을 따로 쓸 것인가 <br>
   간단하게 작성하면서 그냥 markup Language의 사용법을 익힐 것인가<br>
   (일단 후자로 가기로)
{%- include util/auto-content-generator.liquid -%}

<!-- outline-start -->
<hr>
#Jekyll

<!-- outline-end -->
