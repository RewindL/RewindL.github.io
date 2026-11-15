---
permalink: /
title: "About Me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<section class="home-section" id="about-me" markdown="1">
I am currently an algorithm engineer at Alibaba Cloud Intelligence, where my work spans three core areas: **Multimodal LLM post-training**, **Agent Reasoning & Harness**, and **Efficient Inference**. I received my Master's and Bachelor's degrees from the School of Computer Science and Engineering, Sun Yat-sen University (SYSU). My research interests include mllm post-training (e.g. RL, OPD), multi-agent harness and data synthesis, and the broader goal of building more capable and efficient multimodal large language models.
</section>

<section class="home-section" id="news" markdown="1">
<h2 id="news-heading">🔥 News</h2>

- [2026.11] 🎉 Two papers submitted to CVPR 2027
- [2026.09] 🎉 One paper accepted to EMNLP 2026
- [2026.05] 🎉 Three papers accepted to ICML 2026
- [2026.04] One paper accepted by ACL 2026 Findings
- [2025.08] One paper accepted by TOG (Proceedings of SIGGRAPH Asia 2025)
- [2024.06] I joined Alibaba Cloud Intelligence as an algorithm engineer
- [2023.05] I joined Alibaba Cloud Intelligence as an algorithm intern
- [2023.05] One paper accepted by International Journal of Computer Vision (IJCV)
- [2023.05] One paper accepted by TOG (Proceedings of SIGGRAPH 2023)
- [2023.03] One paper accepted by Computer Graphics Forum
</section>

<section class="home-section" id="publications" markdown="1">
<h2 id="publications-heading">📄 Publications</h2>

<p class="pub-legend"><sup>♣</sup> First Student Author</p>

{% assign pubs = site.publications | sort: "order" %}
{% for pub in pubs %}{% include paper-box.html pub=pub %}{% endfor %}
</section>