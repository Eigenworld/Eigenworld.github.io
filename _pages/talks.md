---
title: "Talks"
layout: gridlay
sitemap: false
permalink: /talks/
---

# Talks

{% if site.data.invited_talks %}
## Invited Talks and Seminars

{% for publi in site.data.invited_talks %}
* {{ publi.name }}
{% endfor %}
{% endif %}

