---
layout: page
title: Organizers
permalink: /organizers/
---

<div class="cards">
{% for item in site.data.organizers.organizers %}
  <article class="card">
      <header><h2>{{ item.name }}</h2></header>
      <img
      src="{{ item.img }}"
      alt=" {{ item.name }} " />
      <p>{{ item.affiliation }}</p>
      </article>
{% endfor %}
</div>
<h1>Advisors</h1>
<div class="cards">
{% for item in site.data.organizers.advisors %}
  <article class="card">
      <header><h2>{{ item.name }}</h2></header>
      <img
      src="{{ item.img }}"
      alt=" {{ item.name }} " />
      <p>{{ item.affiliation }}</p>
      </article>
{% endfor %}
</div>