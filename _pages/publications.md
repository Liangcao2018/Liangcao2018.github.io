---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<style>
.pub-stats {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(160px, 1fr));
  gap: 12px;
  margin: 20px 0 28px;
}
.pub-stat {
  text-align: center;
  background: linear-gradient(135deg, #ebf4ff 0%, #e2ecf7 100%);
  border-radius: 8px;
  padding: 16px 12px;
}
.pub-stat .number {
  font-size: 1.8em;
  font-weight: 700;
  color: #2c5282;
  display: block;
}
.pub-stat .label {
  font-size: 0.8em;
  color: #4a5568;
  font-weight: 500;
}
</style>

<div class="pub-stats">
  <div class="pub-stat">
    <span class="number">48+</span>
    <span class="label">Total Publications</span>
  </div>
  <div class="pub-stat">
    <span class="number">34</span>
    <span class="label">Journal Articles</span>
  </div>
  <div class="pub-stat">
    <span class="number">14</span>
    <span class="label">Conference Papers</span>
  </div>
  <div class="pub-stat">
    <span class="number">3</span>
    <span class="label">CCF-A (1st Author)</span>
  </div>
</div>

You can also find my articles on [my Google Scholar profile](https://scholar.google.com/citations?user=4BylVnYAAAAJ&hl=en).

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
