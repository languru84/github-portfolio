---
layout: default
title: Home
---

# {{ site.author.name }}
**Senior Solution & AI Architect** • Full-Stack • Azure • Enterprise Delivery

> I design and deliver scalable enterprise platforms, lead cross-functional teams, and embed AI/NLP capabilities into real-world workflows.

## What I do
- **Solution & Application Architecture:** microservices, integration, performance, reliability
- **Full-Stack Delivery:** Angular/JavaScript, Java/Spring Boot, SQL/PL-SQL
- **Cloud & DevOps:** Azure, CI/CD, governance, cost optimisation
- **AI & Intelligent Solutions:** language translation, NLP-driven automation

## Featured Projects
{% for p in site.data.projects %}
### {{ p.name }}
{{ p.one_liner }}

- Tech: {{ p.tech }}
- Highlights: {{ p.highlights }}
- Repo: {{ p.repo }}
{% endfor %}

## Experience Snapshot
- Led delivery teams of **30–40+** members across geographies
- Improved service performance by **~40%** (Elastic modernisation)
- Enabled **~300K cost savings** via workshop process optimisation
- Digitised paper workflows saving **~30 mins per user per day**
- Converted time tracking from **5-day batch** to **real-time**

## Certifications
- Azure AI Engineer Associate (example)
- Azure AI Fundamentals (example)
- Power Platform Functional Consultant (example)

## Contact
- Email: **{{ site.author.email }}**
- LinkedIn: {{ site.author.linkedin }}
- GitHub: {{ site.author.github }}
