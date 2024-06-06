---
layout: post
title: Endorsements
description: Trusted and supported by community members, elected leaders, and organizations
image: assets/images/endorsements.jpg
nav-menu: true
---  
### Elected Officials

“As a fellow AANHPI woman, I know how hard Emily has worked to bring that lens to local government, creating a seat at the table for people who feel left out by their city. I’m honored to support her in continuing that work to build an inclusive Mountain View.”  
&mdash; Former California State Controller Betty Yee  
  
“Emily is a tireless advocate and expert on the most pressing issue in our state and region: the affordability and availability of housing. I am proud to endorse her because she understands what it takes to collaborate with partners at all levels to create and implement comprehensive strategies to tackle this crisis and so many more.”  
&mdash; California State Senator Josh Becker, District 13  
  
“Emily is an open minded, inquisitive, thoughtful and compassionate leader who is extremely qualified to serve the Mountain View Community!”  
&mdash; Former Mayor Mike Kasperzak
  
|      |      |
| ---: | :--- |
{%- for boardmember in site.data.endorsements.main %}
| {{boardmember.name}} | {{boardmember.organization}} {% if boardmember.title %} <span class="spacer"></span>**{{boardmember.title | strip }}** {% endif %} |
{%- endfor %}
{: .endorsement-table}


### Boardmembers and Commissioners

|      |      |
| ---: | :--- |
{%- for boardmember in site.data.endorsements.boards %}
| {{boardmember.name}} | {{boardmember.organization}} {% if boardmember.title %} <span class="spacer"></span>**{{boardmember.title | strip }}** {% endif %} |
{%- endfor %}
{: .endorsement-table}

### Community Leaders

<ul class="endorsement-cloud">
{% for member in site.data.endorsements.community -%}
<li> {{member.name}} </li>
{% endfor %}
</ul>


*(Titles for identification purposes only)*