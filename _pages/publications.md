---
layout: page
title: "Publications"
permalink: /publications/
intro: "Research papers, conference presentations, and awards."
---
<section class="content-section" aria-labelledby="international-publications">
  <h2 id="international-publications">International Conferences</h2>
  <div class="publication-list">{% assign publications = site.data.publications | where: "category", "international" %}{% for publication in publications %}{% include publication.html publication=publication %}{% endfor %}</div>
</section>
<section class="content-section" aria-labelledby="journal-publications">
  <h2 id="journal-publications">Journal Articles</h2>
  <div class="publication-list">{% assign publications = site.data.publications | where: "category", "journal" %}{% for publication in publications %}{% include publication.html publication=publication %}{% endfor %}</div>
</section>
<section class="content-section" aria-labelledby="domestic-publications">
  <h2 id="domestic-publications">Domestic Conferences</h2>
  <div class="publication-list">{% assign publications = site.data.publications | where: "category", "domestic" %}{% for publication in publications %}{% include publication.html publication=publication %}{% endfor %}</div>
</section>
