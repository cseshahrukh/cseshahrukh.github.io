---
permalink: /photography/
title: "Photography"
author_profile: true
---

{% include base_path %}

<div style="text-align: justify; font-size: 14px;">
A few moments I've captured through my lens.
</div>

{% assign photos = site.static_files | where_exp: "file", "file.path contains '/images/photography/'" | sort: "path" | reverse %}

{% if photos.size > 0 %}
<div class="photo-grid">
  {% for photo in photos %}
    {% assign ext = photo.extname | downcase %}
    {% if ext == ".jpg" or ext == ".jpeg" or ext == ".png" or ext == ".gif" or ext == ".webp" %}
      <a href="{{ base_path }}{{ photo.path }}" title="{{ photo.basename | replace: '-', ' ' | replace: '_', ' ' }}">
        <img src="{{ base_path }}{{ photo.path }}" alt="{{ photo.basename | replace: '-', ' ' | replace: '_', ' ' }}" loading="lazy">
      </a>
    {% endif %}
  {% endfor %}
</div>
{% else %}
<p style="font-size: 14px;"><em>Photos coming soon.</em></p>
{% endif %}
