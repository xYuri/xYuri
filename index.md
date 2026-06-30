---
layout: default
title: Yuri A. Wolf
---

{% capture readme_content %}{% include_relative README.md %}{% endcapture %}
{{ readme_content | replace: '### [Full Bio](https://xyuri.github.io/xYuri)', '' | markdownify }}

---

{% capture recent_projects_content %}{% include_relative RECENT_PROJECTS.md %}{% endcapture %}
{{ recent_projects_content | markdownify }}
