---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<!-- 
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %} -->

{% include base_path %}
<!-- ---

title: "Photos"
permalink: /portfolio/
author_profile: true
![avatar](http://Konic-NLP.github.io/images/pofile.png)
--- -->

<!-- ![avatar](http://Konic-NLP.github.io/images/pofile.png) -->

<!-- {% include base_path %} -->

{% for post in site.publications reversed %}
<!--   {% include archive-single.html %} -->
 {{content}}
<!--   {% include default.html %} -->
{% endfor %}
