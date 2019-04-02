---
layout: default
permalink: index.html
title: CNCTorture
description: "Test Files for CNC/CAM Development Testing and Bug Reporting"
---

## What's This

* Files for Development
* Files for Testing
* Files for Bug Reporting

{% capture site_tags %}{% for tag in site.tags %}{{ tag | first }}{% unless forloop.last %},{% endunless %}{% endfor %}{% endcapture %}
{% assign tags_list = site_tags | split:',' | sort %}


<ul class="slidetags">
  {% for item in (0..site.tags.size) %}{% unless forloop.last %}
    {% capture this_word %}{{ tags_list[item] | strip_newlines }}{% endcapture %}
    <li style="font-size:{{ site.tags[this_word].size | times: 100 | divided_by: site.tags.size | plus: 70 }}%"><a href="#{{ this_word }}">{{ this_word }} <span>{{ site.tags[this_word].size }}</span></a></li>
  {% endunless %}{% endfor %}
</ul>


