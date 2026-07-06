---
layout: page
title: Projects
---

These are the projects I've been building since I started out as a software engineering student, and the personal work I've carried on with after graduation.

Feel free to give me feedback — via GitHub issues, LinkedIn, or however you like. As I figure out AI and my own skillset, I genuinely want to know whether my learning experience is paying off, and what I could do better with AI integration, researching my own problems, or anything in between.

{% assign personal = site.projects | where: "category", "personal" | sort: "order" %}
{% assign opensource = site.projects | where: "category", "open-source" | sort: "order" %}
{% assign contract = site.projects | where: "category", "contract" | sort: "order" %}

## Personal Projects

<div class="project-grid">
{% for project in personal %}{% include project-card.html project=project %}{% endfor %}
</div>

## Open Source Contributions

I've sought out projects I care about and contributed via PRs. Both sites below are run by people I know, and I helped out to gain real-world experience.

<div class="project-grid">
{% for project in opensource %}{% include project-card.html project=project %}{% endfor %}
</div>

## Contract Work

Getting an ABN thanks to my first client, I worked on a project forked to my GitHub where I have reviewed the codebase thanks to AI, checked out the wireframes, tasks and ReadME before being told to use the app. From the app, I turn bugs into issues and eventually PRs reviewed as quickly and effectively so the app continues reaching the ideal state

<div class="project-grid">
{% for project in contract %}{% include project-card.html project=project %}{% endfor %}
</div>
