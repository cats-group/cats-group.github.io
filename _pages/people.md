---
layout: page
permalink: /people/
title: People
description: CATS lab members
nav: true
nav_order: 4

team_members:
  - name: Julia Mendelsohn
    role: Principal Investigator (PI)
    image: prof_pic.jpg
    website: https://juliamendelsohn.github.io
    bluesky: https://bsky.app/profile/jmendelsohn2.bsky.social
    linkedin: https://www.linkedin.com/in/julia-mendelsohn-48aa5326/

  - name: Liancheng Gong (Krystal)
    role: PhD Student
    image: krystal_gong.png
    website: https://krystalgong.github.io/

  - name: Phuong-Anh Nguyen-Le (Kem)
    role: PhD Student
    image: kem_nguyen_le.jpg
    website: https://kemnguyenle.github.io/
    twitter: https://x.com/KemNguyenLe
    linkedin: https://www.linkedin.com/in/kem-nguyen-le/

  - name: Surendra Kumar Chandrasekaran
    role: MS Student
    image: surendra_chandrasekaran.jpeg
    linkedin: https://www.linkedin.com/in/surendra-kumar-c/

  - name: Ashwath David
    role: MS Student
    image: ashwath_david.png
    website: https://adx-coder.github.io/
    linkedin: https://www.linkedin.com/in/ashwath-david

  - name: Tanaya Joshi
    role: MS Student
    image: tanaya_joshi.jpeg
    linkedin: https://www.linkedin.com/in/tanayajoshi25/

  - name: Ilayda Dogan
    role: Undergraduate Student
    image: ilayda_dogan.png
    linkedin: https://www.linkedin.com/in/ilayda-dogan-id1/

  - name: Jeremy Zhao
    role: Undergraduate Student
    image: jeremy_zhao.jpg
    linkedin: https://www.linkedin.com/in/jeremy-zhao-a504b2280




alumni:
  - Coming soon....
---


<div class="row row-cols-1 row-cols-md-2 row-cols-lg-3 g-5 people-grid">
  {% for person in page.team_members %}
    {% include member_card.liquid person=person %}
  {% endfor %}
</div>

{% if page.alumni and page.alumni.size > 0 %}
  <h2 class="mt-5">Alumni</h2>
  <ul>
    {% for alum in page.alumni %}
      <li>{{ alum }}</li>
    {% endfor %}
  </ul>
{% endif %}
