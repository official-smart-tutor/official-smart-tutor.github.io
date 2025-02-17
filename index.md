---
layout: home
---

<h2>FAQs</h2>
<ul>
{% for faq in site.data.sitetext.team.text %}
  <li><strong>{{ faq.question }}</strong><br>{{ faq.answer }}</li>
{% endfor %}
</ul>