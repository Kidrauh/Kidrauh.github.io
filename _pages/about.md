---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

Hi! I am a senior undergraduate student majoring in Computer Science at ShanghaiTech University. I was an exchange student at MIT in Spring 2023. I am currently an undergraduate researcher in PLUS lab, ShanghaiTech University, advised by [Prof. Xuming He](https://faculty.sist.shanghaitech.edu.cn/faculty/hexm/index.html). During my exchange at MIT, I was fortunate to join Medical Vision Group and work with [Prof. Polina Golland](https://people.csail.mit.edu/polina/) and [Dr. Neel Dey](https://www.neeldey.com/).

My research interest includes computer vision and deep learning. My goal is to enhance the interpretability and dependability of models, striving to create agents capable of generalizing in diverse environments, with applications on medical vision, autonomous driving, etc.

In my spare time, I find joy in playing basketball and capturing moments through photography.

<span class='anchor' id='-publications'></span>

# Publications

<style type="text/css">
	.paper_metadata a {
		text-decoration: none!important;
		color: #494e52;
	}
	table, th, td {
		border: 0px solid black;
	}
	table.pub_table {
		width: 100%;
		font-size: 12pt;
	}
	td.pub_td1 {
		width: 19%;
	}
	td.pub_td2 {
		width: 67%;
	}
	span.subbullet {
		font-size: 11pt;
		margin-left: 20px
	}
	oral {
		font-weight: bold;
		color: red;
	}


</style>

{% include publications %}

<span class='anchor' id='-education'></span>

# Education

{% include education %}

<!-- <span class='anchor' id='-project'></span>

# Selected Projects

{% include projects %} -->

<span class='anchor' id='-honors-and-awards'></span>

# Honors and Awards
- *2023.06* ShanghaiTech International Exchange Program Scholarship
- *2022.12* ShanghaiTech Merit Student, 2021-2022
- *2021.12* ShanghaiTech Outstanding Student, 2020-2021
- *2022.11* The Outstanding Individual of ShanghaiTech Career Trek Program
- *2021.11* The Outstanding Individual of ShanghaiTech Social Practice Project


<span class='anchor' id='-teachings'></span>

# Teaching

- *2022.09 - 2023.01*, Teaching Assistant in Algorithm and Data Structures, ShanghaiTech University.
