---
layout: page
title: Team
description: "Meet the members of the CATS Lab at the University of Maryland"
permalink: /team/
---

<header class="cats-page-header">
  <h1>Our Team</h1>
  <p>The people behind the research</p>
</header>

<div class="container py-5">

  <!-- Faculty -->
  {% assign faculty = site.data.team | where: "group", "faculty" %}
  {% if faculty.size > 0 %}
  <h2 class="team-group-title">Faculty</h2>
  <div class="row row-cols-1 row-cols-sm-2 row-cols-md-3 row-cols-lg-4 g-4 mb-5">
    {% for m in faculty %}
    <div class="col">
      {% include member_card.html member=m %}
    </div>
    {% endfor %}
  </div>
  {% endif %}

  <!-- PhD Students -->
  {% assign phd = site.data.team | where: "group", "phd" %}
  {% if phd.size > 0 %}
  <h2 class="team-group-title">PhD Students</h2>
  <div class="row row-cols-1 row-cols-sm-2 row-cols-md-3 row-cols-lg-4 g-4 mb-5">
    {% for m in phd %}
    <div class="col">
      {% include member_card.html member=m %}
    </div>
    {% endfor %}
  </div>
  {% endif %}

  <!-- Master's Students -->
  {% assign masters = site.data.team | where: "group", "masters" %}
  {% if masters.size > 0 %}
  <h2 class="team-group-title">Master's Students</h2>
  <div class="row row-cols-1 row-cols-sm-2 row-cols-md-3 row-cols-lg-4 g-4 mb-5">
    {% for m in masters %}
    <div class="col">
      {% include member_card.html member=m %}
    </div>
    {% endfor %}
  </div>
  {% endif %}

  <!-- Undergrad Researchers -->
  {% assign undergrad = site.data.team | where: "group", "undergrad" %}
  {% if undergrad.size > 0 %}
  <h2 class="team-group-title">Undergraduate Researchers</h2>
  <div class="row row-cols-1 row-cols-sm-2 row-cols-md-3 row-cols-lg-4 g-4 mb-5">
    {% for m in undergrad %}
    <div class="col">
      {% include member_card.html member=m %}
    </div>
    {% endfor %}
  </div>
  {% endif %}

  <!-- Alumni -->
  {% assign alumni = site.data.team | where: "group", "alumni" %}
  {% if alumni.size > 0 %}
  <h2 class="team-group-title">Alumni</h2>
  <div class="row row-cols-1 row-cols-sm-2 row-cols-md-3 row-cols-lg-4 g-4 mb-4">
    {% for m in alumni %}
    <div class="col">
      {% include member_card.html member=m %}
    </div>
    {% endfor %}
  </div>
  {% endif %}

</div>
