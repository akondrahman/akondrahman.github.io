---
layout: archive
title: ""
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}


2021
---
{% for post in site.publications reversed %}
  {% if post.year == 2021 %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

2020
---
{% for post in site.publications reversed %}
  {% if post.year == 2020 %}
     {% include archive-single.html %}
  {% endif %}
{% endfor %}

2019
---
{% for post in site.publications reversed %}
  {% if post.year == 2019 %}
     {% include archive-single.html %}
  {% endif %}
{% endfor %}

2018
---
{% for post in site.publications reversed %}
  {% if post.year == 2018 %}
     {% include archive-single.html %}
  {% endif %}
{% endfor %}

2017
---
{% for post in site.publications reversed %}
  {% if post.year == 2017 %}
     {% include archive-single.html %}
  {% endif %}
{% endfor %}

2016
---
{% for post in site.publications reversed %}
  {% if post.year == 2016 %}
     {% include archive-single.html %}
  {% endif %}
{% endfor %}

2015
---
{% for post in site.publications reversed %}
  {% if post.year == 2015 %}
     {% include archive-single.html %}
  {% endif %}
{% endfor %}

2011
---
{% for post in site.publications reversed %}
  {% if post.year == 2011 %}
     {% include archive-single.html %}
  {% endif %}
{% endfor %}

2010
---
{% for post in site.publications reversed %}
  {% if post.year == 2010 %}
     {% include archive-single.html %}
  {% endif %}
{% endfor %}
