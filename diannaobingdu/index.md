---
layout: diannaobingdu/default
title: 电脑病毒(提取码:1234)
---

# 电脑病毒(提取码:1234)

{% for f in site.data.files %}
<div class="card">
  <a href="{{ f.url }}" target="_blank" rel="noopener">
    <i class="bi bi-filetype-{{ f.icon }}"></i>
    {{ f.name }}
  </a>
</div>
{% endfor %}