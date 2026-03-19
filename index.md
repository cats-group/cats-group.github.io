---
layout: home
title: Home
description: "Computational Analysis of Text and Society Lab at the University of Maryland"
permalink: /
---

<!-- Hero -->
<header class="cats-hero">
  <img src="{{ site.lab.logo | relative_url }}" alt="{{ site.lab.name }} logo" class="hero-logo" />
  <h1>Computational Analysis of<br>Text and Society</h1>
  <p class="lead">
    We develop computational methods to understand language, culture, and society —
    bridging NLP, social science, and AI at the University of Maryland.
  </p>
</header>

<!-- About -->
<section class="py-5" id="about">
  <div class="container">
    <h2 class="section-title">About the Lab</h2>
    <div class="row g-4">
      <div class="col-md-7">
        <p class="text-muted">
          The CATS Lab is an interdisciplinary research group at the
          <a href="https://umd.edu" target="_blank" rel="noopener">University of Maryland</a>.
          We use computational methods — natural language processing, machine learning, and
          data science — to study how language shapes and reflects social phenomena.
        </p>
        <p class="text-muted">
          Our work spans diverse topics including media framing, political discourse,
          misinformation detection, cultural analytics, and AI fairness. We care about
          building tools and publishing research that is both technically rigorous and
          socially meaningful.
        </p>
        <p class="text-muted">
          We actively collaborate across departments in Computer Science, Linguistics,
          Journalism, and Public Policy, and welcome students from all of these backgrounds.
        </p>
      </div>
      <div class="col-md-5">
        <div class="research-themes">
          <h3>Research Themes</h3>
          <ul>
            <li>Natural Language Processing &amp; Text Analysis</li>
            <li>Computational Social Science</li>
            <li>Misinformation &amp; Media Studies</li>
            <li>AI Fairness, Ethics &amp; Safety</li>
            <li>Cultural Analytics</li>
            <li>Political Discourse &amp; Framing</li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- Recent News -->
<section class="py-5 border-top" id="news">
  <div class="container">
    <h2 class="section-title">Recent News</h2>
    <div class="d-flex flex-column gap-3">
      {% for item in site.data.news %}
      <div class="news-card">
        <div class="news-date">{{ item.date }}</div>
        <h3>{{ item.title }}</h3>
        <p>{{ item.body | markdownify | remove: '<p>' | remove: '</p>' }}</p>
      </div>
      {% endfor %}
    </div>
  </div>
</section>
