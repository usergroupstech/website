---
layout: page
title: "PowerShell User Groups"
---

## Table of Contents
* [North-America](#north-america)
* [Europe](#europe)
* [Asia Pacific](#asia-pacific)
* [Africa](#africa)

### Europe
{% include table-start.html %}
{% for usergroup in site.powershell %}
  {% if usergroup.region == 'Europe' %}
    {% include usergroup.html %}
  {% endif %}
{% endfor %}
{% include table-stop.html %}

### North America
{% include table-start.html %}
{% for usergroup in site.powershell %}
  {% if usergroup.region == 'North America' %}
    {% include usergroup.html %}
  {% endif %}
{% endfor %}
{% include table-stop.html %}