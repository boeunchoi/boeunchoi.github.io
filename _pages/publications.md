---
layout: page
permalink: /publications/
title: publications
description:
nav: true
nav_order: 4
---

Full list of my publications can be found in [ADS](<https://ui.adsabs.harvard.edu/search/filter_author_facet_hier_fq_author=AND&filter_author_facet_hier_fq_author=author_facet_hier%3A%221%2FChoi%2C%20B%2FChoi%2C%20Bo-Eun%22&fq=%7B!type%3Daqp%20v%3D%24fq_database%7D&fq=%7B!type%3Daqp%20v%3D%24fq_author%7D&fq_author=(author_facet_hier%3A%221%2FChoi%2C%20B%2FChoi%2C%20Bo-Eun%22)&fq_database=database%3A%20astronomy&q=author%3A(%22Choi%2C%20Bo-Eun%22)&sort=date%20desc%2C%20bibcode%20desc&p_=0>).

<!-- _pages/publications.md -->

### First-author papers

<div class="publications">
{% bibliography -f {{ site.scholar.bibliography }} --query @*[first_author=true]* %}
</div>

## Co-author papers

<div class="publications">
{% bibliography -f {{ site.scholar.bibliography }} --query @*[first_author=false]* %}
</div>
