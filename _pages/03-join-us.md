---
layout: page
permalink: /join-us/
title: "Join Us"
---

{% assign open_positions = site.jobs | where: 'position', 'open' %}
{% for job in open_positions %}
<div class="job-item">
  <a href="{{ site.baseurl }}{{ job.id }}">
    <span>
      <h2>{{ job.title }}</h2>
      <div>
        <ul>
          <li>{{ job.location }}</li>
        </ul>
      </div>
    </span>
</a>
</div>
{% endfor %}

{% assign filled_positions = site.jobs | where: 'position', 'filled' %}
{% for job in filled_positions %}
<div class="job-item">
  <a href="{{ site.baseurl }}{{ job.id }}">
    <span>
      <h2>{{ job.title }} (Position Filled)</h2>
      <div>
        <ul>
          <li>{{ job.location }}</li>
        </ul>
      </div>
    </span>
</a>
</div>
{% endfor %}