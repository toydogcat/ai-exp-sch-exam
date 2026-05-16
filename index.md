---
layout: archive
permalink: /
title: "Latest Posts"
---

<div class="hero-section">
  <h1>歡迎來到大考心得分享站</h1>
  <p>掌握最新學測與分科測驗趨勢，分享最高效的讀書計畫與心理計量科學。</p>
</div>

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
