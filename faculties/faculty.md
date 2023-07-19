---
title: "{{ name }}"
draft: false

# Job rank 職階
rank: "{{ rank }}" # 教授 | 准教授 | 助教 | ...

# Laboratory group
la_group: "{{ group }}" # 分子化学 | 物質化学 | 反応化学

# Laboratory
laboratory: "{{ 研究室 }}"

# page title background image
bg_image: "images/banner/bg1.jpg"

# meta description ~100 letters in Japanese
description : "{{ description_en }}"

# teacher portrait
image: "images/faculty/anonymous.png"

# course 今のところ不使用
# course: ["分子化学"]
# biography or slogan
# bio: "京都府出身、理論物理化学部屋。"

# interest
interest: ["{{ tag1_en }}", "{{ tag2_en }}", "{{ tag3_en }}"]
# contact info
{{ contact_yaml }}

- name : "{{ 研究室 }}"
  icon : "ti-world" # icon pack : https://themify.me/themify-icons
  link : "{{ 研究室URL }}"

- name : "3-1-1 Tsushima-Naka, Kita Ward, Okayama City, Okayama 700-8530"
  icon : "ti-location-pin" # icon pack : https://themify.me/themify-icons
  link : "#"

# type
type: "faculty"
---
