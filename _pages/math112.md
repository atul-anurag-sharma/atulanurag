---
title: "MATH 112 — Calculus II"
permalink: /teaching/math112/
layout: single
author_profile: false
---

<p class="course-meta">
  New Jersey Institute of Technology · 2019–2023
</p>

<p>
  Selected lecture notes, problem sets, and course materials for
  <strong>MATH 112: Calculus II</strong>.
</p>

<!-- Course Notes -->
<div class="teaching-week" style="margin-top: 2rem; margin-bottom: 1.5rem;">
  <h3>Course Materials</h3>
  <div class="teaching-links">
    <a href="{{ '/files/teaching/njit/math112/CalculusII.pdf' | relative_url }}"
       target="_blank"
       rel="noopener noreferrer">
      Calculus II Notes
    </a>
  </div>
</div>

<!-- Problem Sets (I–IX) -->
<div class="teaching-week" style="margin-bottom: 2rem;">
  <h3>Problem Sets</h3>
  <div class="teaching-links">
    {% assign roman_numerals = "I,II,III,IV,V,VI,VII,VIII,IX" | split: "," %}
    {% for r in roman_numerals %}
    <a href="{{ '/files/teaching/njit/math112/Problem-Set-' | append: r | append: '.pdf' | relative_url }}"
       target="_blank"
       rel="noopener noreferrer">
      Problem Set {{ r }}
    </a>
    {% endfor %}
  </div>
</div>

<p class="teaching-back-link" style="margin-top: 2.75rem;">
  <a href="{{ '/teaching/njit/' | relative_url }}">
    <i class="fas fa-arrow-left"></i> Back to NJIT Courses
  </a>
</p>
