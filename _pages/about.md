---
permalink: /
title: "🙌🏼 About Me"
excerpt: "About Me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a Research Fellow at Nanyang Technological University (NTU), working with [Prof. Yang Liu](https://personal.ntu.edu.sg/yangliu/). In addition, I am a Postdoctoral Researcher at Huazhong University of Science and Technology (HUST), jointly supervised by [Prof. Deqing Zou](http://faculty.hust.edu.cn/zoudeqing/zh_CN/index.htm), [Prof. Ruixuan Li](https://idc.hust.edu.cn/rxli/chinese/index.htm), and [Prof. Cai Fu](http://faculty.hust.edu.cn/fucai/zh_CN/more/1623241/jsjjgd/index.htm).

I received my Ph.D. from the School of Cyberspace Security, HUST in June 2024, advised by [Prof. Deqing Zou](http://faculty.hust.edu.cn/zoudeqing/zh_CN/index.htm) and [Assoc. Prof. Yueming Wu](https://wu-yueming.github.io/). Before that, I obtained my B.S. from China University of Geosciences (Wuhan) in 2019, mentored by [Prof. Jun Song](https://grzy.cug.edu.cn/songjun/zh_CN/index.htm).

🌬 **Research Interests**
- Software Engineering  
- Software Security  
- Large Language Models (LLMs)  
- Software Engineering **for/with** AI  

💌 **Contact:** yutaohu@hust.edu.cn

---

## 📄 Publications
{: #publications }

<small><em>(# Equal Contribution, * Corresponding Author)</em></small>

{% assign pubs = site.publications | sort:'date' | reverse %}
{% for p in pubs %}
{% unless p.short == nil or p.short == '' %}
- {{ p.short }}{% if p.pdf or p.paperurl %} [\[Paper\]]({{ p.pdf | default: p.paperurl }}){% endif %}
{% endunless %}
{% endfor %}

---

## 🎓 Education
{: #education }

- *2019.9-2024.6*, **Ph.D.**, Cyberspace Security, School of Cyberspace Security, Huazhong University of Science and Technology (HUST)
- *2015.9-2019.6*, **B.S.**, Information Security, School of Computer Science, China University of Geosciences (Wuhan)

---

## ❣️ Services
{: #services }

- Journal Reviewer – IEEE Transactions on Software Engineering (TSE)
- Workshop Organizer - *Workshop on Software Genomics* (SWGeno), co-located with FSE 2026; submissions are welcome.

---

## 🏔️ Honors and Awards
{: #honors-and-awards }

- 2024 - **Hubei Province Program for Attracting Top-Tier Postdoctoral Talent**, Hubei Province 
- 2024 - **Outstanding Graduate (Class of 2024)**, Huazhong University of Science and Technology (HUST)
- 2022 - **China National Scholarship** 


