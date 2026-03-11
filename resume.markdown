---
layout: page
title: Resume
pdf_file: /assets/Resume.pdf
---
Resume video:
<video width= "100%" height="100%" controls autoplay loop muted><source src="{{ '/assets/Resume.mp4' | relative_url }}" type="video/mp4">
</video>

Resume PDF:

{% pdf {{ page.pdf_file | relative_url }} no_link %}