---
layout: default
title: First Issue
---

{% capture homepage-content %}{% include issue01.md %}{% endcapture %}
{{ homepage-content | markdownify }}

{% include toc.html issue=site.issue01 %}