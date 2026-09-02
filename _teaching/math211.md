---
layout: single
title: "MATH 211 — Elementary Statistics"
collection: teaching
type: "Course"
permalink: /teaching/math211/
venue: "Lander University"
author_profile: false
---

<p class="course-meta">
  Lander University · Fall 2026
</p>

<p>
  Selected lecture notes, syllabus, and course materials for
  <strong>MATH 211: Elementary Statistics</strong>.
</p>

<!-- Course Materials -->
<div class="teaching-section">
  <h2>Course Materials</h2>
  <div class="teaching-links">
    <a href="{{ '/files/teaching/lander/math211/MATH211_11A_Fall_2026_Syllabus.pdf' | relative_url }}"
       target="_blank"
       rel="noopener noreferrer">
      Syllabus
    </a>
  </div>
</div>

<!-- Lecture Notes -->
<div class="teaching-section">
  <h2>Lecture Notes</h2>
  <div class="teaching-links">
    {% for i in (1..7) %}
    <a href="{{ '/files/teaching/lander/math211/Lecture' | append: i | append: '.pdf' | relative_url }}"
       target="_blank"
       rel="noopener noreferrer">
      Lecture {{ i }}
    </a>
    {% endfor %}
  </div>
</div>

<p class="course-back-link" style="margin-top: 2.5rem;">
  <a href="{{ '/teaching/lander/' | relative_url }}">
    ← Back to Lander Courses
  </a>
</p>
