---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
redirect_from:
  - /publications
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% if author.orcid %}
  Check out my ORCID profile for a comprehensive list of my work: <u><a href="{{author.orcid}}">{{author.orcid}}</a>.</u>
{% endif %}

{% if author.researchgate %}
  Visit my ResearchGate profile for more insights: <u><a href="{{author.researchgate}}">{{author.researchgate}}</a>.</u>
{% endif %}

---

## Featured Publications

Highlighting some of my key contributions:

1. **Learning Extended Forecasts of Soil Water Content via Physically-Inspired Autoregressive Models**  
   *International Conference on Machine Learning Applications (ICMLA)*, 2024.  
   [DOI or link to the paper](#)  

2. **Maximum Likelihood Estimation of Stable ARX Models using Randomized Coordinate Descent**  
   *International Conference on Acoustics, Speech, and Signal Processing (ICASSP)*, 2025.  
   [DOI or link to the paper](#)

---

## Full List of Publications

{% include base_path %}

Below is the complete list of my publications, sorted by date:

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

---

## By Category

### **Journal Articles**
{% for post in site.publications %}
  {% if post.category == "journal" %}
    - [{{ post.title }}]({{ post.url }}) - *{{ post.journal }}*, {{ post.year }}
  {% endif %}
{% endfor %}

### **Conference Papers**
{% for post in site.publications %}
  {% if post.category == "conference" %}
    - [{{ post.title }}]({{ post.url }}) - Presented at *{{ post.conference }}*, {{ post.year }}
  {% endif %}
{% endfor %}

### **Books & Chapters**
{% for post in site.publications %}
  {% if post.category == "book" %}
    - [{{ post.title }}]({{ post.url }}) - In *{{ post.book }}*, {{ post.year }}
  {% endif %}
{% endfor %}

---

## Upcoming Work

Stay tuned for updates on upcoming publications:

- Accepted papers (details embargoed).
- In-progress manuscripts.

---

**Note:** For more details or access requests, feel free to contact me. Links to some articles may require institutional access or subscriptions.
