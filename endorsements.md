---
layout: post
title: Endorsements
description: Trusted and supported by community members, elected leaders, and organizations
image: assets/images/endorsements.jpg
nav-menu: true
---  
### Elected Officials

<!-- Keeps the existing style but moves the data to data -->
{% for endorsement in site.data.endorsements.quotes %}
"{{endorsement.quote}}"  
&mdash; {{endorsement.endorser}}
{% endfor %}
  
|      |      |      |
| ---: | :--- | ---: |
{%- for boardmember in site.data.endorsements.main %}
| {{boardmember.name}} | {% if boardmember.title %} **{{boardmember.title | strip }}** {% endif %} | {{boardmember.organization}} |
{%- endfor %}
{: .endorsement-table}

### Boardmembers and Commissioners

|      |      |      |
| ---: | :--- | ---: |
{%- for boardmember in site.data.endorsements.boards %}
| {{boardmember.name}} | {% if boardmember.title %} **{{boardmember.title | strip }}** {% endif %} | {{boardmember.organization}} |
{%- endfor %}
{: .endorsement-table}

### Community Leaders

<ul class="endorsement-cloud">
{% for member in site.data.endorsements.community -%}
<li> {{member.name}} </li>
{% endfor %}
</ul>


*(Titles for identification purposes only)*