---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true

---
<!--{% include base_path %}-->


## Journal Articles

{% for post in site.journalpubs reversed %}
  {% include archive-single.html %}
{% endfor %}

## Conference Proceedings

{% for post in site.confpublications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Preprints under Review/in Preparation

{% for post in site.preprints reversed %}
  {% include archive-single.html %}
{% endfor %}

## Working Papers

{% for post in site.working reversed %}
  {% include archive-single.html %}
{% endfor %}

<!--You can also find my articles on <u><a href="https://scholar.google.com/citations?authuser=1&user=t0m62eQAAAAJ">my Google Scholar profile</a>.</u>-->
