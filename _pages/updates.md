---
layout: archive
title: "Updates"
permalink: /updates/
author_profile: true
---

{% for update in site.data.updates %}
{{ update.date }}<br>
{{ update.content }}

{% endfor %}
