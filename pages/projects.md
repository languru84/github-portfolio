---
layout: default
title: Projects
permalink: /projects/
---

# Projects

Below are my selected projects. Edit the list in `_data/projects.yml`.

{% for p in site.data.projects %}
## {{ p.name }}
{{ p.one_liner }}

- **Tech:** {{ p.tech }}
- **Highlights:** {{ p.highlights }}
- **Repo:** {{ p.repo }}
{% endfor %}
