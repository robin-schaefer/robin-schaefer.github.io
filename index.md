---
layout: refined-home
---

<header class="refined-header">
  <a class="refined-site-name" href="{{ '/' | relative_url }}">Robin Schaefer</a>
  <nav class="refined-nav" aria-label="Primary navigation">
    <a href="{{ '/cv/' | relative_url }}">CV</a>
    <a href="{{ '/pub/' | relative_url }}">Publications</a>
  </nav>
</header>

<main class="refined-main">
  <section class="refined-profile">
    <img class="refined-portrait" src="{{ '/assets/images/profile.jpg' | relative_url }}" alt="Robin Schaefer" />
    <div>
      <section class="refined-intro">
        <h1>Robin Schaefer</h1>
        <p class="refined-role">Computational Physicist</p>
        <p>Hi, I’m Robin Schaefer, a condensed matter theorist currently working in <a href="https://yao.physics.harvard.edu/">Norman Yao’s lab</a> at <a href="https://www.physics.harvard.edu/">Harvard University</a>.</p>
        <p>My focus lies on frustrated magnetism, non-equilibrium dynamics, and chaos. In my research I develop numerical methods for quantum many-body systems and that I use to connect theory with experiment such as the search for quantum spin ice in dipolar-octupolar pyrochlores.</p>
      </section>

      <section class="refined-software">
        <h2>DanceQ</h2>
        <p>My computational efforts have resulted in the development of <a href="https://gitlab.com/DanceQ/danceq">DanceQ</a>, a high-performance C++ library for exact diagonalization of Hamiltonian and Lindbladian systems. It is designed for scalability using OpenMP and MPI.</p>
        <p><a href="https://gitlab.com/DanceQ/danceq">Source code</a> · <a href="https://danceq.gitlab.io/danceq/index.html">Documentation</a></p>
      </section>
    </div>
  </section>

  <p class="refined-page-links">
    <a href="{{ '/cv/' | relative_url }}">Curriculum vitae</a>
    <a href="{{ '/pub/' | relative_url }}">Publications</a>
  </p>
</main>

<footer class="refined-footer">
  <span>Robin Schaefer</span>
  <a href="mailto:robin_schaefer@fas.harvard.edu">robin_schaefer@fas.harvard.edu</a>
</footer>
