---
layout: post
title: Media
description: Emily in the Media
# image: assets/images/endorsements.jpg
nav-menu: true
---  

<!-- Video -->
<iframe width="742" height="480" src="https://www.youtube.com/embed/pfsNW134p4c" title="Candidate for Mountain View City Council - Emily Ann Ramos" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Photos

{% include media-gallery.html photos=site.data.media.photos %}

[Download a printable window sign](/assets/images/media/LawnSign_PrintableAtHome.pdf){:target="_blank"} so you can place it in your window!

## Articles

{% for article in site.data.media.articles -%}

- [{{ article.title }}]({{ article.url }})
{% endfor %}
