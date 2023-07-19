---
title: "{{ 氏名 }}"
draft: false

# Job rank 職階
rank: "{{ 職階 }}" # 教授 | 准教授 | 助教 | ...

# Laboratory group
la_group: "{{ 領域 }}" # 分子化学 | 物質化学 | 反応化学

# Laboratory
laboratory: "{{ 研究室 }}"

# page title background image
bg_image: "images/banner/bg1.jpg"

# meta description ~100 letters in Japanese
description : "{{ description }}"

# teacher portrait
image: "images/faculty/anonymous.png"

# course 今のところ不使用
# course: ["分子化学"]
# biography or slogan
# bio: "京都府出身、理論物理化学部屋。"

# interest
interest: ["{{ tag1 }}", "{{ tag2 }}", "{{ tag3 }}"]
# contact info
{{ contact_yaml }}

- name : "{{ 研究室 }}"
  icon : "ti-world" # icon pack : https://themify.me/themify-icons
  link : "{{ 研究室URL }}"

- name : "700-8530 岡山県岡山市津島中3－1－1 {{ 居室場所 }}"
  icon : "ti-location-pin" # icon pack : https://themify.me/themify-icons
  link : "#"

# type
type: "faculty"
---
