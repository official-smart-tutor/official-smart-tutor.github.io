---
layout: home
---

<section id="team">
  <h2>{{ site.data.ui-text[site.locale].team.title }}</h2>
  <div class="faq-list">
    {% for faq in site.data.ui-text[site.locale].team.text %}
      <div class="faq-item">
        <h3>{{ faq.question }}</h3>
        <p>{{ faq.answer }}</p>
      </div>
    {% endfor %}
  </div>
</section>