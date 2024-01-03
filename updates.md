---
layout: page
excerpt: "What have I been up to recently?"
title: Latest Updates
---

{% for update in site.data.updates %}
- {{update.update}}				    
{% endfor %}