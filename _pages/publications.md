---
layout: page
permalink: /publications/
title: publications
description: Lista publikacji naukowych, które zapisuje na później do polecania.
nav: false
nav_order: 1
---

<!-- _pages/publications.md -->

{% if site.search_enabled %}
<input type="text" id="bibsearch" spellcheck="false" autocomplete="off" class="search bibsearch-form-input" placeholder="Type to filter">
{% endif %}

<div class="publications">

{% bibliography %}

</div>
