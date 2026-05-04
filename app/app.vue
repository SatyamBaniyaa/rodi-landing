<template>
  <main class="page">
    <section class="hero">
      <nav class="nav" aria-label="Primary navigation">
        <a class="brand" href="#" aria-label="Rodi home">
          <span class="brand-mark">R</span>
          <span>Rodi</span>
        </a>

        <div class="nav-links">
          <a href="#work">Work</a>
          <a href="#services">Services</a>
          <a href="#contact">Contact</a>
        </div>
      </nav>

      <div class="hero-grid">
        <div class="hero-copy">
          <p class="eyebrow">Reliable digital craft for growing teams</p>
          <h1>Launch a sharper web presence without slowing your business down.</h1>
          <p class="lede">
            Rodi helps founders and local brands turn scattered ideas into fast,
            polished websites that feel simple to use and easy to maintain.
          </p>

          <div class="actions">
            <a class="button primary" href="#contact">Start a project</a>
            <a class="button secondary" href="#work">View work</a>
          </div>
        </div>

        <div class="showcase" aria-label="Project preview">
          <div class="showcase-header">
            <span></span>
            <span></span>
            <span></span>
          </div>
          <div class="showcase-body">
            <div class="metric">
              <strong>3.2s</strong>
              <span>Average load time improved</span>
            </div>
            <div class="chart">
              <span style="--height: 44%"></span>
              <span style="--height: 68%"></span>
              <span style="--height: 58%"></span>
              <span style="--height: 86%"></span>
              <span style="--height: 74%"></span>
            </div>
            <div class="status-list">
              <p><i></i>Brand story clarified</p>
              <p><i></i>Mobile flow tightened</p>
              <p><i></i>Launch checklist ready</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section id="services" class="section">
      <div class="section-heading">
        <p class="eyebrow">Services</p>
        <h2>Everything needed for a clean first impression.</h2>
      </div>

      <div class="service-grid">
        <article>
          <span>01</span>
          <h3>Landing pages</h3>
          <p>Clear messaging, responsive layouts, and conversion-focused page flow.</p>
        </article>
        <article>
          <span>02</span>
          <h3>Brand refresh</h3>
          <p>Visual direction, color systems, and reusable components for consistency.</p>
        </article>
        <article>
          <span>03</span>
          <h3>Launch support</h3>
          <p>Performance checks, deployment setup, and practical handoff guidance.</p>
        </article>
      </div>
    </section>

    <section id="work" class="split-section">
      <div>
        <p class="eyebrow">Approach</p>
        <h2>Focused, fast, and built around what your customers need next.</h2>
      </div>

      <div class="steps">
        <p><strong>Discover</strong> Shape the core message and page goals.</p>
        <p><strong>Design</strong> Create a visual system that fits the brand.</p>
        <p><strong>Build</strong> Ship a responsive site with production-ready details.</p>
      </div>
    </section>

    <section id="contact" class="contact">
      <div>
        <p class="eyebrow">Ready when you are</p>
        <h2>Tell Rodi what you want to launch.</h2>
      </div>
      <a class="button primary" href="mailto:hello@rodi.studio">hello@rodi.studio</a>
    </section>
  </main>
</template>

<style>
:root {
  color: #17211b;
  background: #f7f3ea;
  font-family:
    Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI",
    sans-serif;
}

* {
  box-sizing: border-box;
}

body {
  margin: 0;
}

a {
  color: inherit;
  text-decoration: none;
}

.page {
  min-height: 100vh;
  background:
    linear-gradient(135deg, rgba(49, 119, 84, 0.18), transparent 38%),
    linear-gradient(315deg, rgba(223, 131, 80, 0.18), transparent 42%),
    #f7f3ea;
}

.hero,
.section,
.split-section,
.contact {
  width: min(1120px, calc(100% - 40px));
  margin: 0 auto;
}

.hero {
  min-height: 86vh;
  padding: 28px 0 64px;
}

.nav,
.hero-grid,
.split-section,
.contact {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 32px;
}

.brand,
.nav-links,
.actions {
  display: flex;
  align-items: center;
}

.brand {
  gap: 10px;
  font-weight: 800;
  font-size: 1.08rem;
}

.brand-mark {
  display: grid;
  width: 38px;
  height: 38px;
  place-items: center;
  border-radius: 8px;
  color: #fffaf0;
  background: #264f3c;
}

.nav-links {
  gap: 24px;
  color: #4e5f54;
  font-size: 0.95rem;
}

.hero-grid {
  min-height: calc(86vh - 96px);
  padding-top: 48px;
}

.hero-copy {
  max-width: 630px;
}

.eyebrow {
  margin: 0 0 14px;
  color: #b45b38;
  font-size: 0.78rem;
  font-weight: 800;
  letter-spacing: 0;
  text-transform: uppercase;
}

h1,
h2,
h3,
p {
  margin-top: 0;
}

h1 {
  max-width: 700px;
  margin-bottom: 22px;
  font-size: clamp(3rem, 8vw, 5.9rem);
  line-height: 0.95;
  letter-spacing: 0;
}

h2 {
  margin-bottom: 0;
  font-size: clamp(2rem, 5vw, 3.5rem);
  line-height: 1;
  letter-spacing: 0;
}

h3 {
  margin-bottom: 10px;
  font-size: 1.25rem;
}

.lede {
  max-width: 560px;
  color: #4e5f54;
  font-size: 1.18rem;
  line-height: 1.7;
}

.actions {
  flex-wrap: wrap;
  gap: 14px;
  margin-top: 34px;
}

.button {
  display: inline-flex;
  min-height: 48px;
  align-items: center;
  justify-content: center;
  border-radius: 8px;
  padding: 0 20px;
  font-weight: 800;
}

.primary {
  color: #fffaf0;
  background: #264f3c;
}

.secondary {
  border: 1px solid rgba(38, 79, 60, 0.2);
  color: #264f3c;
  background: rgba(255, 250, 240, 0.58);
}

.showcase {
  width: min(390px, 100%);
  overflow: hidden;
  border: 1px solid rgba(38, 79, 60, 0.14);
  border-radius: 8px;
  background: rgba(255, 250, 240, 0.82);
  box-shadow: 0 24px 70px rgba(44, 58, 49, 0.18);
}

.showcase-header {
  display: flex;
  gap: 8px;
  padding: 16px;
  background: #264f3c;
}

.showcase-header span {
  width: 10px;
  height: 10px;
  border-radius: 999px;
  background: #f3c47f;
}

.showcase-body {
  padding: 24px;
}

.metric {
  display: grid;
  gap: 4px;
}

.metric strong {
  font-size: 3.4rem;
  line-height: 1;
}

.metric span,
.status-list {
  color: #637167;
}

.chart {
  display: flex;
  height: 160px;
  align-items: end;
  gap: 12px;
  margin: 28px 0;
}

.chart span {
  width: 100%;
  height: var(--height);
  border-radius: 8px 8px 0 0;
  background: linear-gradient(180deg, #df8350, #4f8a66);
}

.status-list {
  display: grid;
  gap: 12px;
}

.status-list p {
  display: flex;
  align-items: center;
  gap: 10px;
  margin: 0;
}

.status-list i {
  width: 9px;
  height: 9px;
  border-radius: 999px;
  background: #4f8a66;
}

.section,
.split-section,
.contact {
  padding: 74px 0;
}

.section-heading {
  max-width: 620px;
  margin-bottom: 34px;
}

.service-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 18px;
}

.service-grid article {
  min-height: 220px;
  padding: 26px;
  border: 1px solid rgba(38, 79, 60, 0.14);
  border-radius: 8px;
  background: rgba(255, 250, 240, 0.65);
}

.service-grid span {
  display: inline-block;
  margin-bottom: 40px;
  color: #b45b38;
  font-weight: 800;
}

.service-grid p,
.steps {
  color: #4e5f54;
  line-height: 1.6;
}

.split-section {
  align-items: flex-start;
  border-top: 1px solid rgba(38, 79, 60, 0.16);
}

.split-section > div:first-child {
  max-width: 560px;
}

.steps {
  display: grid;
  width: min(430px, 100%);
  gap: 18px;
}

.steps p {
  margin: 0;
  padding-bottom: 18px;
  border-bottom: 1px solid rgba(38, 79, 60, 0.16);
}

.steps strong {
  display: block;
  color: #17211b;
}

.contact {
  margin-bottom: 40px;
  border-radius: 8px;
  padding: 42px;
  color: #fffaf0;
  background: #17211b;
}

.contact .eyebrow {
  color: #f3c47f;
}

.contact h2 {
  max-width: 620px;
}

.contact .primary {
  flex-shrink: 0;
  color: #17211b;
  background: #f3c47f;
}

@media (max-width: 840px) {
  .hero,
  .section,
  .split-section,
  .contact {
    width: min(100% - 28px, 1120px);
  }

  .nav {
    align-items: flex-start;
  }

  .nav-links {
    gap: 14px;
    font-size: 0.88rem;
  }

  .hero-grid,
  .split-section,
  .contact {
    flex-direction: column;
    align-items: stretch;
  }

  .hero-grid {
    min-height: auto;
  }

  .showcase {
    width: 100%;
  }

  .service-grid {
    grid-template-columns: 1fr;
  }

  .contact {
    padding: 30px 22px;
  }
}

@media (max-width: 520px) {
  .nav-links {
    display: none;
  }

  .hero {
    padding-top: 18px;
  }

  h1 {
    font-size: 3rem;
  }

  .button {
    width: 100%;
  }
}
</style>
