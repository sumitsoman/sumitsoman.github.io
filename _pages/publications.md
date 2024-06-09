---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can find the complete list of articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

<h2>Selected Publications</h2>

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
