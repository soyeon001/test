---
title: "CodeUp 사이트 문제 풀이"
layout: archive
permalink: categories/codeup
author_profile: true
sidebar_main: true
---

<!-- 공백이 포함되어 있는 카테고리 이름의 경우 site.categories.['a b c'] 이런식으로! -->

***

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=soyeon001&repo=coding-test)](https://github.com/soyeon001/coding-test)

{% assign posts = site.categories.CodeUp %}
{% for post in posts %} {% include archive-single2.html type=page.entries_layout %} {% endfor %}