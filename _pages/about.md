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

Hi! I’m Zhongxiao (Clara) Cong. I'm a first-year CS Ph.D. student at Cornell university, advised by [Prof. Andrew Owens](https://andrewowens.com/).

Previously, I was a master student in the Robotics Institute at Carnegie Mellon University, working with [Prof. Shubham Tulsiani](https://shubhtuls.github.io/) and [Prof. Matthew O'Toole](https://www.cs.cmu.edu/~motoole2/). I obtained my B.Eng. in Computer Science at ShanghaiTech University. During Spring 2023, I was an exchange student at MIT, where I joined the Medical Vision Group under the supervision of [Prof. Polina Golland](https://people.csail.mit.edu/polina/) and was mentored by [Dr. Neel Dey](https://www.neeldey.com/). I couldn’t be more grateful for their invaluable insights and support.

Always happy to chat about research!

<span class='anchor' id='research'></span>

<!-- # Research

I am generally interested in <b>Computer Vision</b>, <b>Graphics</b>, and <b>Machine Learning</b>, with a focus on <b> 3D Vision</b> and <b>Neural Rendering</b>. 
 -->


<span class='anchor' id='-publications'></span>

# Publications

<style type="text/css">
	/* .paper_metadata a {
		text-decoration: none!important;
		color: #494e52;
	} */
    .paper_metadata a {
    color: #1a4b8b;        /* darkred */
    text-decoration: none; 
    }

    .paper_metadata a:hover {
        color:rgb(252, 147, 61);    
        text-decoration: none;
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

<!-- <span class='anchor' id='-honors-and-awards'></span> -->

<!-- # Selected Awards -->
<!-- - *2024.06* Shanghai Outstanding Graduates -->
<!-- - *2023.06* ShanghaiTech International Exchange Program Scholarship -->
<!-- - *2022.12* ShanghaiTech Merit Student -->
<!-- - *2022.11* The Outstanding Individual of ShanghaiTech Career Trek Program -->
<!-- - *2021.11* The Outstanding Individual of ShanghaiTech Social Practice Project -->


<!-- <span class='anchor' id='-teachings'></span>

# Teaching
<p style="color: #A5A4A4">Teaching is one of my FAVORITE ways of learning :D</p>

- *2024.03 - 2024.06*, TOEFL Teaching Assistant, El Fuego Education Services.
- *2022.09 - 2023.01*, Teaching Assistant in Algorithm and Data Structures, ShanghaiTech University. -->
