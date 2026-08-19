---
layout: default
title: Publications
permalink: /publications/
---

<section class="section">
  <h2 class="section__heading">preprints</h2>
  {% for pub in site.data.publications %}
    {% if pub.category == "preprint" %}
      {% include pub-item.html pub=pub show_thumb=true %}
    {% endif %}
  {% endfor %}
</section>

<section class="section">
  <h2 class="section__heading">conference</h2>
  {% for pub in site.data.publications %}
    {% if pub.category == "conference" %}
      {% include pub-item.html pub=pub show_thumb=true %}
    {% endif %}
  {% endfor %}
</section>

<section class="section">
  <h2 class="section__heading">journal</h2>
  {% for pub in site.data.publications %}
    {% if pub.category == "journal" %}
      {% include pub-item.html pub=pub show_thumb=true %}
    {% endif %}
  {% endfor %}
</section>
