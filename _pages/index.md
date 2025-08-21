---
layout: page
title: Home
id: home
permalink: /
---

# Willkommen! 🌱

<p style="padding: 3em 1em; background: #f5f7ff; border-radius: 8px;">
  Werfen Sie einen Blick auf <span style="font-weight: bold">[[Your first note]]</span> um mit Ihrer Erkundung zu beginnen.
</p>

Diese digitale Gartenvorlage ist kostenlos, quelloffen und [und hier auf GitHub verfügbar.](https://github.com/maximevaillancourt/digital-garden-jekyll-template).

Der einfachste Weg, um loszulegen, besteht darin, diese [Schritt-für-Schritt-Anleitung zu lesen, in der erklärt wird, wie Sie dies von Grund auf neu einrichten](https://maximevaillancourt.com/blog/setting-up-your-own-digital-garden-with-jekyll).

**Kürzlich aktualisierte Notizen**
<ul>
  {% assign recent_notes = site.notes | sort: "last_modified_at_timestamp" | reverse %}
  {% for note in recent_notes limit: 5 %}
    <li>
      {{ note.last_modified_at | date: "%Y-%m-%d" }} — <a class="internal-link" href="{{ site.baseurl }}{{ note.url }}">{{ note.title }}</a>
    </li>
  {% endfor %}
</ul>

<style>
  .wrapper {
    max-width: 46em;
  }
</style>
