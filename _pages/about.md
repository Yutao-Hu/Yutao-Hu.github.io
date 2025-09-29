---
permalink: /
title: "🙌🏼 About Me"
excerpt: "About Me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a Research Fellow at Nanyang Technological University (NTU), working with [Prof. Yang Liu](https://personal.ntu.edu.sg/yangliu/). In addition, I am a Postdoctoral Researcher at Huazhong University of Science and Technology (HUST), jointly supervised by [Prof. Deqing Zou](http://faculty.hust.edu.cn/zoudeqing/zh_CN/index.htm), [Prof. Ruixuan Li](https://idc.hust.edu.cn/rxli/chinese/index.htm), and [Prof. Fu Cai](http://faculty.hust.edu.cn/fucai/zh_CN/more/1623241/jsjjgd/index.htm).

I received my Ph.D. from the School of Cyberspace Security, HUST in June 2024, advised by [Prof. Deqing Zou](http://faculty.hust.edu.cn/zoudeqing/zh_CN/index.htm) and [Assoc. Prof. Yueming Wu](https://wu-yueming.github.io/). Before that, I obtained my B.S. from China University of Geosciences (Wuhan) in 2019, mentored by [Prof. Jun Song](https://grzy.cug.edu.cn/songjun/zh_CN/index.htm).

🌬 **Research Interests**
- Software Engineering  
- Software Security  
- Large Language Models (LLMs)  
- Software Engineering **for/with** AI  

💌 **Contact:** yutaohu@hust.edu.cn

---

## 📑 Publications
{: #publications }
(* *Equal Contribution*, # *Corresponding Author*)

{%- assign pubs = site.publications
  | where_exp: "p", "p.short and p.short != ''"
  | sort: "date" | reverse -%}

{%- for p in pubs -%}
- {%- if p.paperurl -%}[{{ p.short }}]({{ p.paperurl }}){%- else -%}{{ p.short }}{%- endif -%}
{%- endfor -%}

---

## Talks {#talks}
{%- for post in site.talks reversed limit:5 -%}
  {% include archive-single.html %}
{%- endfor %}
<p><a href="{{ '/talks/' | relative_url }}">More talks →</a></p>

---

## Teaching {#teaching}
{%- for post in site.teaching reversed limit:5 -%}
  {% include archive-single.html %}
{%- endfor %}
<p><a href="{{ '/teaching/' | relative_url }}">All courses →</a></p>

---

## Portfolio {#portfolio}
{%- for post in site.portfolio reversed limit:6 -%}
  {% include archive-single.html %}
{%- endfor %}
<p><a href="{{ '/portfolio/' | relative_url }}">See more projects →</a></p>

---

## Blog {#blog}
{%- for post in site.posts limit:5 -%}
  {% include archive-single.html %}
{%- endfor %}
<p><a href="{{ '/year-archive/' | relative_url }}">All posts →</a></p>

---

## CV {#cv}
You can find my full **CV** here: <a href="{{ '/cv/' | relative_url }}">CV →</a>
