---
title: "MATH 106 — Introduction to Mathematical Modeling"
permalink: /teaching/math106/
layout: single
author_profile: false
---

<p class="course-meta">
  Ramapo College of New Jersey · 2025–2026
</p>

<p>
  Selected lecture notes, homework assignments, syllabus, and course materials
  for <strong>MATH 106: Introduction to Mathematical Modeling</strong>.
</p>

<!-- Syllabus -->
<div class="teaching-week" style="margin-top: 2rem; margin-bottom: 1.5rem;">
  <h3>Course Documents</h3>
  <div class="teaching-links">
    <a href="{{ '/files/teaching/ramapo/math106/week1/MATH106-syllabus.pdf' | relative_url }}"
       target="_blank"
       rel="noopener noreferrer">
      Syllabus
    </a>
  </div>
</div>

<!-- Lecture Notes (1-14) -->
<div class="teaching-week" style="margin-bottom: 1.5rem;">
  <h3>Lecture Notes</h3>
  <div class="teaching-links">
    <!-- Weeks 1 to 5 (2 lectures each, odd/even pairing) -->
    {% for w in (1..5) %}
      {% assign lec_b = w | times: 2 %}
      {% assign lec_a = lec_b | minus: 1 %}
      <a href="{{ '/files/teaching/ramapo/math106/week' | append: w | append: '/math_106_lecture_' | append: lec_a | append: '.pdf' | relative_url }}"
         target="_blank"
         rel="noopener noreferrer">
        Lecture {{ lec_a }}
      </a>
      <a href="{{ '/files/teaching/ramapo/math106/week' | append: w | append: '/math_106_lecture_' | append: lec_b | append: '.pdf' | relative_url }}"
         target="_blank"
         rel="noopener noreferrer">
        Lecture {{ lec_b }}
      </a>
    {% endfor %}

    <!-- Week 6 -->
    <a href="{{ '/files/teaching/ramapo/math106/week6/math_106_lecture_11.pdf' | relative_url }}"
       target="_blank"
       rel="noopener noreferrer">
      Lecture 11
    </a>
    <a href="{{ '/files/teaching/ramapo/math106/week6/math_106_lecture_12.pdf' | relative_url }}"
       target="_blank"
       rel="noopener noreferrer">
      Lecture 12
    </a>

    <!-- Week 7 -->
    <a href="{{ '/files/teaching/ramapo/math106/week7/math_106_lecture_13.pdf' | relative_url }}"
       target="_blank"
       rel="noopener noreferrer">
      Lecture 13
    </a>
    <a href="{{ '/files/teaching/ramapo/math106/week7/math_106_lecture_14.pdf' | relative_url }}"
       target="_blank"
       rel="noopener noreferrer">
      Lecture 14
    </a>
  </div>
</div>

<!-- Homework Assignments (1-5) -->
<div class="teaching-week" style="margin-bottom: 2rem;">
  <h3>Homework Assignments</h3>
  <div class="teaching-links">
    {% for i in (1..5) %}
    <a href="{{ '/files/teaching/ramapo/math106/week' | append: i | append: '/homework_' | append: i | append: '.pdf' | relative_url }}"
       target="_blank"
       rel="noopener noreferrer">
      Homework {{ i }}
    </a>
    {% endfor %}
  </div>
</div>

<p class="teaching-back-link" style="margin-top: 2.75rem;">
  <a href="{{ '/teaching/' | relative_url }}">
    <i class="fas fa-arrow-left"></i> Back to Teaching Portfolio
  </a>
</p>
