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

# About me

Hi! I'm a Master’s student in Computer Vision at the School of Computer Science, Carnegie Mellon University. 

I obtained my B.Eng. in Computer Science at ShanghaiTech University, where I worked on domain generalization and vision-language models under the supervision of [Prof. Xuming He](https://faculty.sist.shanghaitech.edu.cn/faculty/hexm/index.html). I was an exchange student at MIT in Spring 2023, where I was fortunate to join Medical Vision Group and work with [Prof. Polina Golland](https://people.csail.mit.edu/polina/) and [Dr. Neel Dey](https://www.neeldey.com/) on medical image analysis with neural rendering.

In my spare time, I find joy in playing basketball and capturing moments through photography.

<span class='anchor' id='research'></span>

# Research

My research interests include <b>Computer Vision</b>, <b>Machine Learning</b> and <b>Robotics</b>, with a focus on <b>Domain Generalization, Multimodal Learning, Neural Rendering, and Vision-Language Models</b>.
My goal is to enable AI to perceive and interact with the world like humans by improving the interpretability and reliability of models, with applications in autonomous driving, medical vision, etc.


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
- *2024.06* Shanghai Outstanding Graduates
- *2023.06* ShanghaiTech International Exchange Program Scholarship
- *2022.12* ShanghaiTech Merit Student, 2021-2022
- *2022.11* The Outstanding Individual of ShanghaiTech Career Trek Program
- *2021.11* The Outstanding Individual of ShanghaiTech Social Practice Project


<span class='anchor' id='-teachings'></span>

# Teaching
<p style="color: #A5A4A4">Teaching is one of my FAVORITE ways of learning :D</p>

- *2024.03 - 2024.06*, TOEFL Teaching Assistant, El Fuego Education Services.
- *2022.09 - 2023.01*, Teaching Assistant in Algorithm and Data Structures, ShanghaiTech University.
