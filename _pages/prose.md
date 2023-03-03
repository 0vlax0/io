---
layout: archive
title: "Dislate prosístico"
permalink: /prose/
author_profile: false
---
<h1> <i class="fa-duotone fa-arrow-up-z-a"></i> Palabra y forma <i class="fa-duotone fa-arrow-down-a-z"></i></h1>

{% include base_path %}
{% for post in site.prose %}
  <i class="fa-thin fa-book-open-reader"></i> {% include archive-single.html %}
{% endfor %}
