---
permalink: /
title: "Shutong Chen (陈疏桐)"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
Hello! I am a Ph.D. candidate in the Department of Engineering at [King’s College London](https://www.kcl.ac.uk/), London, United Kingdom, under the supervision of [Prof. Yansha Deng](https://www.kcl.ac.uk/people/yansha-deng), and in collaboration with Toshiba Europe Ltd., where I am co-supervised by [Dr. Adnan Aijaz](https://adnanaijaz.com/) and [Dr. Yichao Jin](https://scholar.google.com/citations?user=prcqwqAAAAAJ&hl=en).

Prior to this, I obtained my Master’s degree in Internet Engineering from [the Department of Electronic and Electrical Engineering at University College London](https://www.ucl.ac.uk/engineering/electronic-electrical-engineering) in 2023 under the supervision of [Prof. Miguel Rio](https://www.ee.ucl.ac.uk/~uczamjr/), and my Bachelor’s degree in Communication Engineering from [the School of Microelectronics and Communication Engineering at Chongqing University](http://www.ccee.cqu.edu.cn/NewEnglish/Home.htm) in 2022 under the supervision of [Prof. Zhengchuan Chen](https://scholar.google.com/citations?user=ZxsMQYgAAAAJ&hl=en).

My research interests include:
- **Goal-oriented Semantic Communications**
- **Digital Twin for Robotics**
- **Large Language Models**
- Age of Information (Previous)

Feel free to drop me an **email (shutong.chen@kcl.ac.uk)** or add me on **Steam (889940925)** if you have any questions (▰˘◡˘▰). 

Education
======
* Ph.D in AI for Wireless Communications, King's College London, 2023.9 - 2027.8 (expected)
* M.S. in Internet Engineering, University College London, 2022.9 - 2023.9
* B.S. in Communication Engineering, Chongqing University, 2018.9 - 2022.6

Publication
======
{% assign papers_all = site.data.papers %}
{% for paper in papers_all %}
<table>
  <tr>
    <td width="280">
      <a href="{{ paper.arxiv }}">
        <img src="{{ paper.image }}" width="270">
      </a>
    </td>
    <td>
      <b>{{ forloop.index }}. {{ paper.title }}</b><br>
      {{ paper.authors }}<br>
      {{ paper.venue }}<br>
      <span style="color:#CC5500">
        <b>{{ paper.tag | split: ":" | first }}</b>:
        <i>{{ paper.tag | split: ":" | last | strip }}</i>
      </span><br>
      <span style="color:green">{{ paper.summary }}</span><br>
      <img src="{{ '/accessories/pdf.jpg' | relative_url }}" width="12">
      <a href="{{ paper.pdf }}">PDF</a>
      {% if paper.code %}
        | <img src="{{ '/accessories/github_icon.jpg' | relative_url }}" width="15">
        <a href="{{ paper.code }}">Code</a>
      {% endif %}
    </td>
  </tr>
</table>
{% endfor %}


  <hr>


<br>
<br>

<script type='text/javascript' id='mapmyvisitors' src='https://mapmyvisitors.com/map.js?cl=080808&w=a&t=tt&d=Kr3JHIfobUwIgjI4JxqkPRYD_sy2RNiE17Mo4HRNhF0&co=ffffff&cmo=3acc3a&cmn=ff5353&ct=808080'></script>
