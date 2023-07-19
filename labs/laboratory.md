---
title: "{{ name_en }}"
draft: false

# page title background image
bg_image: "images/banner/bg1.jpg"

# meta description ~100 letters in Japanese
description : "{{ description_en }}"

# Research image
image: "images/research/research-6.jpg"

# interest

# taxonomy
la_categories: "{{ group }}" # 分子化学 | 物質化学 | 反応化学
keywords: ["{{ tag1_en }}", "{{ tag2_en }}", "{{ tag3_en }}"]
faculties:
  kongo : Prof. Rikishi KONGO
  kongo : Prof. Rikishi KONGO

# contact info
{{ contact_yaml }}

- name : "{{ 研究室 }}"
  icon : "ti-world" # icon pack : https://themify.me/themify-icons
  link : "{{ 研究室URL }}"

- name : "3-1-1 Tsushima-Naka, Kita Ward, Okayama City, Okayama 700-8530"
  icon : "ti-location-pin" # icon pack : https://themify.me/themify-icons
  link : "#"

# type
type: "laboratory"
---
