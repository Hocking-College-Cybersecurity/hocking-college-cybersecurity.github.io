---
layout: default
title: "Cybersecurity Program — Hocking College"
permalink: /
---

<div class="hero-section">
  <h1>Cybersecurity Program</h1>
  <h2>Hocking College</h2>
  <p class="lead">
    We prepare students for industry roles with hands-on labs, projects, and professional portfolios designed for employers.
  </p>
  <a class="btn primary-btn" href="#portfolios">See Student Portfolios</a>
</div>

<hr class="section-divider">

<div class="highlights-section">
  <h2>Program Highlights</h2>
  <ul>
    <li>Two-year A.A.S. in Cybersecurity</li>
    <li>Industry certifications: CompTIA Security+, Network+</li>
    <li>Capstone projects, labs, and professional portfolio development</li>
  </ul>
</div>

<hr class="section-divider">

<div id="portfolios" class="portfolios-section">
  <h2>Student Portfolios</h2>
  <p class="muted">
    Click any card to open the student's portfolio (public GitHub repos only).
  </p>
  <div class="student-grid">
    {% if site.data.students and site.data.students.size > 0 %}
      {% for student in site.data.students %}
        {% include student-card.html student=student %}
      {% endfor %}
    {% else %}
      <p>No portfolios found yet. Students should add the repository topic <code>cyber-portfolio</code> to their portfolio repo.</p>
    {% endif %}
  </div>
</div>

<hr class="section-divider">

<div id="contact" class="contact-section">
  <h2>Contact</h2>
  <p>
    <strong>Program Director:</strong> Norma DePriest<br>
    <strong>Email:</strong> <a href="mailto:depriestn@hocking.edu">depriestn@hocking.edu</a>
  </p>
  <p>
    Want your class portfolios listed? Ask students to add <code>cyber-portfolio</code> as a repository topic and ensure the repo is public (or provide consent if private).
  </p>
</div>
