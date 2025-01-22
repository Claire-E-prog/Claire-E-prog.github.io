---
---
layout: default
title: My Portfolio
---

# Welcome to My Portfolio

Here, you can explore my projects, check out their code repositories, and view detailed descriptions.

## Projects
{% for project in site.data.projects %}
### {{ project.name }}
![{{ project.name }}](assets/images/{{ project.image }})
**Description**: {{ project.description }}

[GitHub Repository]({{ project.github }})
{% endfor %}

