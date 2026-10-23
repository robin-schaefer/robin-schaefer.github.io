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
    <div class="refined-side">
      <img class="refined-portrait" src="{{ '/assets/images/profile.jpg' | relative_url }}" alt="Robin Schaefer" />
      <p class="refined-social">
      <a href="https://arxiv.org/a/0000-0001-9728-2371.html" aria-label="arXiv" title="arXiv"><span class="refined-icon" style="--icon: url('{{ '/assets/logo/arxiv.svg' | relative_url }}')"></span></a>
      <a href="https://scholar.google.de/citations?user=NX7j0dsAAAAJ&hl=en" aria-label="Google Scholar" title="Google Scholar"><span class="refined-icon" style="--icon: url('{{ '/assets/logo/googlescholar.svg' | relative_url }}')"></span></a>
      <a href="https://github.com/robin-schaefer" aria-label="GitHub" title="GitHub"><span class="refined-icon" style="--icon: url('{{ '/assets/logo/github.svg' | relative_url }}')"></span></a>
      <a href="https://www.linkedin.com/in/TODO" aria-label="LinkedIn" title="LinkedIn"><span class="refined-icon" style="--icon: url('{{ '/assets/logo/linkedin.svg' | relative_url }}')"></span></a>
      <a href="https://orcid.org/0000-0001-9728-2371" aria-label="ORCID" title="ORCID"><span class="refined-icon" style="--icon: url('{{ '/assets/logo/orcid.svg' | relative_url }}')"></span></a>
      </p>
    </div>
    <div>
      <section class="refined-intro">
        <h1>Robin Schaefer</h1>
        <p class="refined-role">Computational Physicist</p>
        <p>Hi, I’m Robin Schaefer, a condensed matter theorist currently working in <a href="https://yao.physics.harvard.edu/">Norman Yao’s lab</a> at <a href="https://www.physics.harvard.edu/">Harvard University</a>.</p>
        <p>My research focuses on frustrated magnetism, nonequilibrium dynamics, and chaos. I develop numerical methods for quantum many-body systems and use them to connect theory with experiment. One example is the search for quantum spin ice in dipolar-octupolar pyrochlores.</p>
      </section>

      <section class="refined-software">
        <h2>DanceQ</h2>
        <p>My computational efforts have resulted in the development of <a href="https://gitlab.com/DanceQ/danceq">DanceQ</a>, a high-performance C++ library for exact diagonalization of Hamiltonian and Lindbladian systems. It is designed for scalability using OpenMP and MPI.</p>
        <p><a href="https://gitlab.com/DanceQ/danceq">Source code</a> · <a href="https://danceq.gitlab.io/danceq/index.html">Documentation</a></p>
      </section>

      <section class="refined-software">
        <h2>PyGFMC</h2>
        <p>I also develop <a href="https://github.com/robin-schaefer/PyGFMC">PyGFMC</a>, a <a href="https://github.com/jax-ml/jax">JAX</a>-based Green’s function Monte Carlo code for sign-problem-free quantum lattice models. On GPUs it reaches nearly <strong>three orders of magnitude</strong> higher throughput than on CPUs. It is compatible with <a href="https://www.netket.org">NetKet</a>, enabling arbitrary neural quantum states as guides.</p>
        <p><a href="https://github.com/robin-schaefer/PyGFMC">Source code</a> · <a href="https://robin-schaefer.github.io/PyGFMC/">Documentation</a></p>
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
