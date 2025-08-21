---
layout: page
title: Start
id: home
permalink: /
---

# Willkommen! 🌱


**Kürzlich aktualisierte Notizen**
<ul>
  {% assign recent_notes = site.notes | sort: "last_modified_at_timestamp" | reverse %}
  {% for note in recent_notes limit: 15 %}
    <li>
      {{ note.last_modified_at | date: "%Y-%m-%d"}} — <a class="internal-link" href="{{ site.baseurl }}{{ note.url }}">{{ note.title }}</a>
    </li>
  {% endfor %}
</ul>

<style>
  .wrapper {
    max-width: 46em;
  }
</style>

