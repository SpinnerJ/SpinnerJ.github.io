---
layout: default
title: Jeff Spinner - Portfolio
---

<header>
  <h1>Welcome to Jeff Spinner’s Portfolio</h1>
  <p>Explore my work and personal interests.</p>
</header>

<div class="container">
  <!-- Personal Section -->
  <div class="section-option" onclick="toggleDropdown('personalDropdown')">
    Personal
  </div>
  <div id="personalDropdown" class="dropdown-content">
    <a href="{{ '/personal/blog/' | relative_url }}">Blog</a>
    <a href="{{ '/personal/music/' | relative_url }}">Music</a>
    <a href="{{ '/personal/art/' | relative_url }}">Art</a>
    <a href="{{ '/personal/writing/' | relative_url }}">Writing</a>
    <a href="{{ '/personal/games/' | relative_url }}">Games</a>
  </div>

  <!-- Professional Section -->
  <div class="section-option" onclick="toggleDropdown('professionalDropdown')">
    Professional
  </div>
  <div id="professionalDropdown" class="dropdown-content">
    <a href="{{ '/professional/projects/' | relative_url }}">Projects</a>
    <a href="{{ '/professional/experience/' | relative_url }}">Experience</a>
    <a href="{{ '/professional/skills/' | relative_url }}">Skills</a>
    <a href="{{ '/professional/testimonials/' | relative_url }}">Testimonials</a>
    <a href="{{ '/professional/contact/' | relative_url }}">Contact</a>
  </div>
</div>

<footer>
  &copy; 2024 Jeffrey Spinner. All rights reserved.
</footer>
