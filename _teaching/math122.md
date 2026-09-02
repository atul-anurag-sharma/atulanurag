---
layout: single
title: "MATH 122 — Calculus II"
collection: teaching
type: "Course"
permalink: /teaching/math122/
venue: "Ramapo College of New Jersey"
author_profile: false
---

<p class="course-meta">
  Ramapo College of New Jersey · Summer 2026
</p>

<p>
  Selected lecture notes, syllabus, and course materials for
  <strong>MATH 122: Calculus II</strong>.
</p>

<!-- Course Documents -->
<div class="teaching-week" style="margin-top: 2rem; margin-bottom: 1.5rem;">
  <h3>Course Materials</h3>
  <div class="teaching-links">
    <a href="{{ '/files/teaching/ramapo/math122/math_122_summer_2026_syllabus.pdf' | relative_url }}"
       target="_blank"
       rel="noopener noreferrer">
      Syllabus
    </a>
  </div>
</div>

<!-- Lecture Notes -->
<div class="teaching-week" style="margin-bottom: 2rem;">
  <h3>Lecture Notes</h3>
  <div class="teaching-links">
    {% for i in (1..6) %}
    <a href="{{ '/files/teaching/ramapo/math122/Lecture' | append: i | append: '.pdf' | relative_url }}"
       target="_blank"
       rel="noopener noreferrer">
      Lecture {{ i }}
    </a>
    {% endfor %}
  </div>
</div>

<p class="teaching-back-link" style="margin-top: 2.75rem;">
  <a href="{{ '/teaching/ramapo/' | relative_url }}">
    <i class="fas fa-arrow-left"></i> Back to Ramapo Courses
  </a>
</p>
