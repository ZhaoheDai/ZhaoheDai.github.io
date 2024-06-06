---
layout: archive
permalink: /people/
author_profile: false
---

{% include base_path %}

<img src='/images/bio-photo.jpg' width="200"><br>
## Dr. Yin Zhang 张寅
<a href="/cv/">Full CV</a>


### Education
* 2011.08-2015.07 &emsp;B.S. in Theoretical and Applied Mechanics, Peking University <br>Advisor: Prof. Huiling Duan
* 2015.08-2021.08 &emsp;Ph.D in Mechanical Engineering, Georgia Institute of Technology <br>Advisor: Prof. Ting Zhu

### Experience
* 2021.09-2023.01 &emsp;Postdoctoral Associate, Massachusetts Institute of Technology <br>Advisor: Prof. Ju Li
* 2023.03-now &emsp;&emsp;&ensp;Assistant Professor, Peking University

{% for post in site.people %}
  {% include archive-single.html %}
{% endfor %}

