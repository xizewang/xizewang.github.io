---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on <a href="https://scholar.google.com/citations?user=25k04X0AAAAJ&hl=en">my Google Scholar profile</a>.

研究成果也可通过 <a href="https://scholar.google.com/citations?user=25k04X0AAAAJ&hl=en">我的谷歌学术页面</a> 查看。

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
