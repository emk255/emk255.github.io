---
layout: page
permalink: /cv/
title: cv
nav: true
nav_order: 4
---

{% assign cv_pdf = '/assets/pdf/ElliotKim_CV.pdf' | relative_url %}

<p><a href="{{ cv_pdf }}" download>Download CV (PDF)</a></p>

<object data="{{ cv_pdf }}" type="application/pdf" aria-label="Elliot Kim's CV" style="width: 100%; height: 80vh;">
  <p><a href="{{ cv_pdf }}">Open CV (PDF)</a></p>
</object>
