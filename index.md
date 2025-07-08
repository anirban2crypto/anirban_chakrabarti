---
layout: default
title: "Anirban Chakrabarti"
---

# Anirban Chakrabarti
_PhD Candidate, Indian Institute of Science_  
[GitHub](https://github.com/anirban2crypto) • [Email](mailto:anirban2chakrabarti@gmail.com)

## Summary
PhD student... *(You can pull this from your LaTeX abstract)*

## Education
{% for item in site.data.cv.education %}
**{{ item.degree }}**, _{{ item.institution }}_  
{{ item.duration }}  
{{ item.details }}
{% endfor %}

## Research Projects
{% for item in site.data.cv.research %}
- **{{ item.title }}**: {{ item.description }} *(Status: {{ item.status }})*
{% endfor %}

## Experience
{% for item in site.data.cv.experience %}
### {{ item.role }}, {{ item.company }}
{{ item.duration }}  
{{ item.details }}
{% endfor %}