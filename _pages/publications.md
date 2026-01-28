---
layout: page
permalink: /publications/
title: Publications
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

<!-- {% include bib_search.liquid %} -->




<div class="publications">
  {% bibliography --query @*[category=stat] %}
</div>


<br><br>
#### Working Papers


<div class="publications">
  {% bibliography --query @*[category=working] %}
</div>

<br><br>
#### Application Papers


<div class="publications">
  {% bibliography --query @*[category=application] %}
</div>