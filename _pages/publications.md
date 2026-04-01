---
layout: page
permalink: /publications/
title: publications
description: 
nav: true
nav_order: 1
---

Authors are ordered alphabetically by last name unless an asterisk(*) is indicated.

See also [Google Scholar](https://scholar.google.com/citations?hl=ko&user=CDOzdzcAAAAJ).

<!-- _pages/publications.md -->
<div class="publications">

<h2>peer-reviewed</h2>
{% bibliography -f {{ site.scholar.bibliography }} --query @*[category!=preprint] %}

<h2>preprints</h2>
{% bibliography -f {{ site.scholar.bibliography }} --query @*[category=preprint] %}

</div>
