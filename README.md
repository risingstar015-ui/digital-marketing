<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Open Access Social Platform — Home & Overview</title>
  <meta name="description" content="Home, project overview, and navigation for the Open Access Social Platform multi-page prototype." />
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet"/>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.css" rel="stylesheet"/>
  <style>
    :root { --brand: #0d6efd; --brand-ink: #0a58ca; }
    body { scroll-behavior: smooth; }
    .hero { background: linear-gradient(180deg, #f8fbff 0%, #ffffff 100%); }
    .rounded-2xl { border-radius: 1.25rem; }
    .shadow-soft { box-shadow: 0 10px 30px rgba(13,110,253,.08); }
    .card h5 { font-weight: 700; }
    .toc a { text-decoration: none; }
    .kbd { border:1px solid #dee2e6; border-bottom-width:2px; padding:.15rem .35rem; border-radius:.375rem; font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace; }
    .navbar-nav .nav-link.active { font-weight: bold; color: var(--brand) !important; }
    footer a { color: inherit; }
  </style>
</head>
<body>
  <!-- NAVBAR -->
  <nav class="navbar navbar-expand-lg bg-white border-bottom sticky-top">
    <div class="container py-2">
      <a class="navbar-brand d-flex align-items-center" href="index.html">
        <i class="bi bi-hash fs-3 me-2 text-primary"></i>
        <span class="fw-bold">Open Access Social</span>
      </a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#nav" aria-controls="nav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div id="nav" class="collapse navbar-collapse">
        <ul class="navbar-nav ms-auto gap-lg-2">
          <li class="nav-item"><a class="nav-link active" href="index.html">Overview</a></li>
          <li class="nav-item"><a class="nav-link" href="demo.html">UI Demo</a></li>
          <li class="nav-item"><a class="nav-link" href="architecture.html">Architecture</a></li>
          <li class="nav-item"><a class="nav-link" href="security.html">Security & Legal</a></li>
          <li class="nav-item"><a class="nav-link" href="evaluation.html">Evaluation</a></li>
          <li class="nav-item"><a class="nav-link" href="roadmap.html">Roadmap</a></li>
          <li class="nav-item"><a class="nav-link" href="references.html">References</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- HERO -->
  <header class="hero">
    <div class="container py-5">
      <div class="row align-items-center g-4">
        <div class="col-lg-6">
          <h1 class="display-5 fw-bold">Prototype Social Media Website</h1>
          <p class="lead text-secondary">A responsive, accessible, and secure design concept — documented and showcased as a GitHub Pages site.</p>
          <div class="d-flex gap-2 flex-wrap">
            <a class="btn btn-primary btn-lg" href="demo.html"><i class="bi bi-play-circle me-2"></i>Try UI Demo</a>
            <a class="btn btn-outline-primary btn-lg" href="architecture.html"><i class="bi bi-diagram-3 me-2"></i>See Architecture</a>
          </div>
          <p class="text-muted small mt-3">Note: GitHub Pages is static hosting. Dynamic examples here are simulated in the browser for demonstration.</p>
        </div>
        <div class="col-lg-6">
          <div id="heroCarousel" class="carousel slide rounded-2xl overflow-hidden shadow-soft" data-bs-ride="carousel">
            <div class="carousel-inner">
              <div class="carousel-item active"><img class="w-100" src="https://picsum.photos/1200/600?random=21" alt="feed"/></div>
              <div class="carousel-item"><img class="w-100" src="https://picsum.photos/1200/600?random=22" alt="profile"/></div>
              <div class="carousel-item"><img class="w-100" src="https://picsum.photos/1200/600?random=23" alt="responsive"/></div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </header>

  <section class="py-5">
    <div class="container">
      <div class="row g-4">
        <div class="col-lg-8">
          <h2 class="fw-bold mb-3">Overview</h2>
          <p>This multi-page site summarizes the planning, design rationale, implementation notes, and evaluation of a prototype social media platform. It emphasizes usability, responsiveness, accessibility, and core features such as registration, login, posting, commenting, likes, and profile management.</p>
          <div class="alert alert-primary">Explore each page for interactive demos, architecture, security notes, and more. Navigation links are at the top.</div>
          <h5 class="mt-4">Navigation flow (high‑level)</h5>
          <img src="https://mermaid.ink/img/pako:eNpFj0FqwzAMhu_StVxkFQ2w4BC3EJqH4WYbKkKZtYJ9hUSdYjP--2qbiD2Zb6bTGBiUgZg4p1Rr2wA6QfcwTbs3Tj7gZcGJXXT4yjv7PpKj0huGJkwjV7yWzj9rN6k8JqEJ8WfF9x2C6kVJvUve3gihWTruE3qv4QwD8u9hXwUVyJv7L8aKXGfZY7-wlR6wQz2g" alt="Site navigation flowchart" class="img-fluid border rounded-2xl"/>
        </div>
        <div class="col-lg-4">
          <div class="card shadow-soft border-0 sticky-top" style="top:6rem">
            <div class="card-body">
              <h5 class="card-title">Explore Other Pages</h5>
              <nav class="toc small d-grid gap-2">
                <a href="demo.html">UI Demo</a>
                <a href="architecture.html">Architecture</a>
                <a href="security.html">Security & Legal</a>
                <a href="evaluation.html">Evaluation</a>
                <a href="roadmap.html">Roadmap</a>
                <a href="references.html">References</a>
              </nav>
            </div>
          </div>
        </div>
      </div>
    </div>
    
  </section>

  <footer class="py-4 border-top bg-white">
    <div class="container d-flex flex-wrap justify-content-between align-items-center gap-2">
      <span class="small">© <span id="year"></span> Open Access Social (Prototype)</span>
      <div class="small">
        <span class="me-2">Keyboard tips:</span>
        <span class="kbd">g</span> then <span class="kbd">o</span> → Overview
        <span class="ms-2 kbd">g</span> then <span class="kbd">d</span> → Demo
      </div>
    </div>
  </footer>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
