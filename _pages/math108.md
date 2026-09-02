---
title: "MATH 108 — Elementary Probability and Statistics"
permalink: /teaching/math108/
layout: single
author_profile: false
---

<p class="course-meta">
  Ramapo College of New Jersey · 2025–2026
</p>

<p>
  Selected lecture notes, homework assignments, syllabus, and course materials
  for <strong>MATH 108: Elementary Probability and Statistics</strong>.
</p>

<!-- Course Documents -->
<div class="teaching-week" style="margin-top: 2rem; margin-bottom: 1.5rem;">
  <h3>Course Documents</h3>
  <div class="teaching-links">
    <a href="{{ '/files/teaching/ramapo/math108/week1/MATH108-syllabus.pdf' | relative_url }}"
       target="_blank"
       rel="noopener noreferrer">
      Syllabus
    </a>
    <a href="{{ '/files/teaching/ramapo/math108/week1/homework1.pdf' | relative_url }}"
       target="_blank"
       rel="noopener noreferrer">
      Homework 1
    </a>
  </div>
</div>

<!-- Lecture Notes (1-12) -->
<div class="teaching-week" style="margin-bottom: 2rem;">
  <h3>Lecture Notes</h3>
  <div class="teaching-links">
    <!-- Lecture 1 (uses unique file naming) -->
    <a href="{{ '/files/teaching/ramapo/math108/week1/lecture-notes1.pdf' | relative_url }}"
       target="_blank"
       rel="noopener noreferrer">
      Lecture 1
    </a>

    <!-- Lectures 2 to 12 -->
    {% for i in (2..12) %}
    <a href="{{ '/files/teaching/ramapo/math108/week1/math_108_lecture_' | append: i | append: '.pdf' | relative_url }}"
       target="_blank"
       rel="noopener noreferrer">
      Lecture {{ i }}
    </a>
    {% endfor %}
  </div>
</div>

<p class="teaching-back-link" style="margin-top: 2.75rem;">
  <a href="{{ '/teaching/' | relative_url }}">
    <i class="fas fa-arrow-left"></i> Back to Teaching Portfolio
  </a>
</p>
