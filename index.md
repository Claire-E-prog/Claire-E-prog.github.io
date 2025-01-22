## Projects

{% for project in site.data.projects %}
### {{ project.name }}
![{{ project.name }}](assets/images/{{ project.image }})
**Description**: {{ project.description }}

[GitHub Repository]({{ project.github }})  
---
{% endfor %}
