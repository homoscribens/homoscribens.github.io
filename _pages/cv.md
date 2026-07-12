---
layout: page
title: "Curriculum Vitae"
permalink: /cv/
intro: "Education and professional experience."
---
<section class="content-section" aria-labelledby="experience">
  <h2 id="experience">Experience</h2>
  <div class="cv-list">{% for item in site.data.cv.experience %}<article class="cv-row"><p class="cv-period">{{ item.period }}</p><div><h3>{{ item.role }}</h3><p class="cv-organization">{{ item.organization }}</p><p>{{ item.description }}</p></div></article>{% endfor %}</div>
</section>
<section class="content-section" aria-labelledby="education">
  <h2 id="education">Education</h2>
  <div class="cv-list">{% for item in site.data.cv.education %}<article class="cv-row"><p class="cv-period">{{ item.period }}</p><div><h3>{{ item.degree }}</h3><p>{{ item.institution }}</p></div></article>{% endfor %}</div>
</section>
