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
    {% include usergroup.html %}
  {% endif %}
{% endfor %}

### Europe
{% for usergroup in site.powershell %}
  {% if usergroup.region == 'Europe' %}
    {% include usergroup.html %}
  {% endif %}
{% endfor %}

### Asia Pacific
{% for usergroup in site.powershell %}
  {% if usergroup.region == 'Asia Pacific' %}
    {% include usergroup.html %}
  {% endif %}
{% endfor %}

### Africa
{% for usergroup in site.powershell %}
  {% if usergroup.region == 'Africa' %}
    {% include usergroup.html %}
  {% endif %}
{% endfor %}