---
layout: page
permalink: /research/
title: research
description:
nav: true
nav_order: 2
---

### preprints ###
<div class="publications">

  {% bibliography --group_by none --query @*[preprint=true]* %}

</div>

### publications ###

<!-- _pages/publications.md  -->
<div class="publications">

  {% bibliography --group_by none --query @*[preprint=false]* %}

</div>




