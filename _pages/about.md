---
title: "About"
layout: gridlay
sitemap: false
permalink: /about/
---

## About 


{% for member in site.data.pi %}

<div class="row">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="30%" style="float: left" />
  <h3>{{ member.name }}</h3>
  <i style="font-size:20px">{{ member.info }}</i><br>

  {% if member.website %}<a href="{{ member.website }}" target="_blank"><i class="fa fa-home fa-3x"></i></a> {% endif %}
  {% if member.email %}<a href="mailto:{{ member.email }}" target="_blank"><i class="fa fa-envelope-square fa-3x"></i></a> {% endif %}
  {% if member.scholar %} <a href="{{ member.scholar }}" target="_blank"><i class="ai ai-google-scholar-square ai-3x"></i></a> {% endif %}
  {% if member.cv %} <a href="{{ member.cv }}" target="_blank"><i class="ai ai-cv-square ai-3x"></i></a> {% endif %}
  {% if member.github %} <a href="{{ member.github }}" target="_blank"><i class="fa fa-github-square fa-3x"></i></a> {% endif %}
  {% if member.researchgate %} <a href="{{ member.researchgate }}" target="_blank"><i class="ai ai-researchgate-square ai-3x"></i></a> {% endif %}
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

  {% if member.number_educ == 6 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  <li> {{ member.education6 }} </li>
  {% endif %}

  </ul>
</div>

{% endfor %}

## Sketch

Dr. Li, Xue is committed to promoting the research on the interpretability of artificial intelligence and giving the current popular deep learning techniques a rigorous and reliable mathematical analysis. He will graduate from the Harbin Institute of Technology before September 2023 and is currently applying for a postdoctoral position.

{% if site.data.awards %}

## Thesis Title
Ph.D.<br>

Explaining and designing the message passing mechanism in graph neural networks

M.S.<br>

Harbin financial forecast based on the grey forecasting model

B.S. <br>

An intelligent online teaching system

## Awards

{% for award in site.data.awards %}
* {{ award.name }}
{% endfor %}

{% endif %}

## Collaborators

**Yuanzhi Cheng:** My mentor. He is currently a Professor at the Harbin Institute of technology. He received his Ph.D. through the joint training of Osaka University and Harbin In- stitute of Technology in 2007. His research interests are concentrated on machine learning, image processing, and computer vision. He has published over 50 journal papers in IEEE Trans. Image. Pro- cess, IEEE Trans. Biomed. Eng, IEEE J. Biomed. Health Inform, Med. Image Anal, Pattern Recognition, etc.



**Yehuda Koren**:  He is a staff research scientist at Google. Prior to this, he was a senior research scientist at Yahoo! Research and a principal staff member of AT&T Labs-Research. He received the Ph.D. degree in computer science from The Weizmann Institute. His main research interests are recommender systems, data mining, machine learning, and information visualization. He led the team that won the two progress awards in the Netflix Prize competition, and was part of the team which won the Netflix Grand Prize. 



**Mehak Khan**: She is working as a Senior Researcher (Post-Doc) at Oslo Metropolitan University, where my research focuses on Graph Neural Networks and related algorithms for Citation Networks.



**Shinichi Tamura**: (IEEE life fellow) He received B.S., M.S., and Ph.D. degrees in electrical engineering from Osaka University, Osaka, Japan, in 1966, 1968, and 1971, respectively. He was a Professor at the Graduate School of Medicine, the Graduate School of Information Science and Technology, and the Center for Advanced Medical Engineering and Informatics at Osaka University. After retiring from Osaka University in 2007, he joined NBL Co., Ltd, and is now a Director with NBL Technovator Co., Ltd.







