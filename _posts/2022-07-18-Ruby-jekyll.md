---
# multilingual page pair id, this must pair with translations of this page. (This name must be unique)
lng_pair: id_ruby_1
title: "the way to add lang"

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
#task order
<hr>

1. add <b>kr.yml</b> to <b>data/lang</b>  <br>


2. add post to _site/posts by kr<br>


3. add language_switch_lang_list: [en, kr]
   <br> to data/conf/main.yml

<hr>
problem  <br>

1. no switch button on some blogs
2. no list button
<hr>

need to think<br>

1. how to manage blogs.
common title, categories and so on.

2. the way or program to use markup language

{%- include util/auto-content-generator.liquid -%}

<!-- outline-start -->

#Jekyll

<!-- outline-end -->

