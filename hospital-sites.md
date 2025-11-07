---
title: Hospital Sites
layout: base
date: 2024-12-02
---

# Hospital Sites
American women worked at these hospital sites during the Spanish Civil War. 

{% assign pages-for-cards = site.pages | where_exp: "page", "page.path contains 'hospitals/'" %}

{% include card-grid.html cards = pages-for-cards %}

<br style="clear: both">
