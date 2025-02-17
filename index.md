---
layout: home
---

## Frequently Asked Questions

{% for faq in site.data.sitetext.team.text %}
### **{{ faq.question }}**
{{ faq.answer }}

{% endfor %}