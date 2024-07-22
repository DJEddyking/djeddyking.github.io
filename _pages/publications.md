---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<div style="display: flex; align-items: flex-start;">
  <img src="./dingjin.jpg" alt="image description" style="width: 200px;">
  <p>This is some text that will appear next to the image.</p>
</div>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
