---
layout: page
title: Publications
description: "Peer-reviewed papers, workshops, and preprints from the CATS Lab"
permalink: /publications/
---

<header class="cats-page-header">
  <h1>Publications</h1>
  <p>Peer-reviewed papers, workshops, and preprints</p>
</header>

<div class="container py-5">

  {% assign pubs_by_year = site.data.publications | group_by: "year" | sort: "name" | reverse %}

  {% for year_group in pubs_by_year %}
  <div class="mb-5">
    <div class="pub-year-label">{{ year_group.name }}</div>
    <div class="d-flex flex-column gap-3">
      {% for pub in year_group.items %}
        {% include pub_card.html pub=pub %}
      {% endfor %}
    </div>
  </div>
  {% endfor %}

</div>
