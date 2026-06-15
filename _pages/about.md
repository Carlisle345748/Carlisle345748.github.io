---
permalink: /
title: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a Research Scientist at [Meta MRS](https://github.com/meta-recsys) (Modern Recommendation System). My research interest is building scalable machine learning models for intelligent information systems, including recommender systems, ranking models, and agentic AI.

My current work focuses on developing large scale machine learning models for recommendation systems, with an emphasis on user behavior modeling, retrieval, ranking, and real-world deployment. I also conduct research on trustworthy AI agents for information reasoning, evidence retrieval, and misinformation detection.



<h2 id="research-interests">Research interests</h2>

Recommendation Systems, Large Language Models, AI Agents

<h2 id="publications">Publications</h2>

<ol class="compact-publications">
{% assign sorted_publications = site.publications | sort: "order" %}
{% for post in sorted_publications %}
  <li>
    <span class="compact-publications__title"><a href="{% if post.paperurl %}{{ post.paperurl }}{% else %}{{ post.url | relative_url }}{% endif %}">{{ post.title }}</a></span><br />
    <span class="compact-publications__citation">{{ post.citation | replace: "Zikun Cui", "<strong>Zikun Cui</strong>" }}</span>
  </li>
{% endfor %}
</ol>

<h2 id="peer-review">Services</h2>

Reviewer
- Transactions on Information Systems
- Multimedia Systems
- Neural Processing Letters
- Information Technology and Control
- Internet Technology Letters
- Transactions on Consumer Electronics

<h2 id="education">Background</h2>

<div class="cv-entry">
  <div class="cv-entry__main">
    <strong>Stanford University</strong>, Stanford, CA<br />
    Master of Science - MS<br />
  </div>
  <div class="cv-entry__date">Sep 2021 - Jun 2023</div>
</div>

<div class="cv-entry">
  <div class="cv-entry__main">
    <strong>Sun Yat-sen University</strong>, Guangzhou, China<br />
    Bachelor of Engineering - BE<br />
  </div>
  <div class="cv-entry__date">Sep 2016 - Jul 2020</div>
</div>