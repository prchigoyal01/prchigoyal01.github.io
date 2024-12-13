---
layout: page
permalink: /publications/
title: publications
description: 
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

<div class="publications">

{% bibliography --query "not @poster" %}

</div>

---

<!-- Posters Section -->

<div class="posters">


{% bibliography --query @poster %}

</div>

