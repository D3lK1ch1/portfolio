---
layout: home
---

## Hi, I'm Delia — Software Developer

I build practical tools across full-stack web, desktop, mobile, and automation — focused on real workflows, not over-engineered systems. Based in Malaysia, available for contract and freelance work.

**Stack:** C#, Python, TypeScript, React, PHP, Rust

---

### A few things I've built

{% assign featured = site.projects | sort: "order" | slice: 0, 3 %}
<div class="project-grid">
{% for project in featured %}{% include project-card.html project=project %}{% endfor %}
</div>

<div class="home-cta">
  <a href="{{'/services/' | relative_url }}" class="services-cta">What I can build for you →</a>
  <a href="{{ '/projects/' | relative_url }}"  class="services-cta services-cta--outline">All projects →</a>
</div>
