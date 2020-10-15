---
layout: page
title: "PowerShell User Groups"
---

## Table of Contents
* [North-America](#north-america)
* [Europe](#europe)
* [Asia Pacific](#asia-pacific)
* [Africa](#africa)

### North America
{% for usergroup in site.powershell %}
  {% if usergroup.region == 'North America' %}
    {% include usergroup.md %}
  {% endif %}
{% endfor %}

### Europe
{% for usergroup in site.powershell %}
  {% if usergroup.region == 'Europe' %}
    {% include usergroup.md %}
  {% endif %}
{% endfor %}