---
layout: page
permalink: /join-us/
title: "Join Us"
---

{% for job in site.jobs %}
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