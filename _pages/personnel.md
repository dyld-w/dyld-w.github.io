---
layout: page
permalink: /personnel/
title: Personnel
description:
nav: true
nav_order: 2
display_categories: [Director, Postdoctoral Fellow, Graduate Student, Postbac Research Assistant, Undergraduate Research Assistant]
horizontal: true
---

<!-- inspired by _pages/projects.md -->
<!-- Using template pages designed for projects to display people, hence calss="projects" -->

<div class="projects">
  <!-- Render Current Personnel -->
  {% include personnel_section.liquid personnel=site.personnel alum=false categories=page.display_categories horizontal=page.horizontal %}
</div>

<br />
<br />

<!-- Render Alumni -->
<div class="projects">
  <h2>Alumni</h2>
  {% include personnel_section.liquid personnel=site.personnel alum=true categories=page.display_categories horizontal=page.horizontal %}
</div>
