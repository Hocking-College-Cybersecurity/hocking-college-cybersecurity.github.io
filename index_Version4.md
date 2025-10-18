---
layout: default
title: "Cybersecurity Program — Hocking College"
permalink: /
---

<section class="hero">
  <div class="hero-inner">
    <h2>Cybersecurity Program — Hocking College</h2>
    <p class="lead">We prepare students for industry roles with hands-on labs, projects, and professional portfolios designed for employers.</p>
    <p><a class="btn" href="#portfolios">See Student Portfolios</a></p>
  </div>
</section>

<section class="highlights">
  <h3>Program Highlights</h3>
  <ul class="highlights-list">
    <li>Two-year A.A.S. in Cybersecurity</li>
    <li>Industry certifications aligned — CompTIA Security+, Network+</li>
    <li>Capstone projects, labs, and professional portfolio development</li>
  </ul>
</section>

<section id="portfolios" class="portfolios">
  <h3>Student Portfolios</h3>
  <p class="muted">Click any card to open the student's portfolio (public GitHub repos only).</p>

  <div class="student-grid">
    {% if site.data.students and site.data.students.size > 0 %}
      {% for student in site.data.students %}
        {% include student-card.html student=student %}
      {% endfor %}
    {% else %}
      <p>No portfolios found yet. Students should add the repository topic <code>cyber-portfolio</code> to their portfolio repo.</p>
    {% endif %}
  </div>
</section>

<section id="contact" class="contact">
  <h3>Contact</h3>
  <p>Program Director: Norma DePriest — email: <a href="mailto:depriestn@hocking.edu">depriestn@hocking.edu</a></p>
  <p>Want your class portfolios listed? Ask students to add <code>cyber-portfolio</code> as a repository topic and ensure the repo is public (or provide consent if private).</p>
</section>