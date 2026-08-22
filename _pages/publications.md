---
title: "Publications"
layout: gridlay
sitemap: false
permalink: /publications/
---
## Publications
<input type="text" class="pub-search" id="pubSearch" placeholder="Filter by title, author, or year...">
<div class="section-card" id="pubList">
<h3>Refereed Conference Proceedings</h3>
{% bibliography --query @inproceedings %}
<h3>Thesis</h3>
{% bibliography --query @mastersthesis %}
</div>
