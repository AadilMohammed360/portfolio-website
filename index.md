---
layout: default
title: Home
---

<div class="portfolio">
  <section class="hero" aria-labelledby="hero-title">
    <div class="hero-copy">
      <p class="eyebrow"><span class="status-dot" aria-hidden="true"></span> Python full-stack developer</p>
      <h1 id="hero-title">I build web apps that make complex things <span>feel simple.</span></h1>
      <p class="hero-intro">From robust Python backends to thoughtful, accessible interfaces, I turn good ideas into useful products.</p>
      <div class="hero-actions">
        <a class="button button-primary" href="#projects">Explore my work <span aria-hidden="true">↘</span></a>
        <a class="button button-secondary" href="#contact">Let’s talk</a>
      </div>
      <p class="hero-note">Currently open to new opportunities</p>
    </div>
    <div class="code-card">
      <div class="code-card-top">
        <span class="window-dots" aria-hidden="true"><i></i><i></i><i></i></span>
        <span>hello.py</span>
        <span class="code-language">PY</span>
      </div>
      <pre><code><span class="code-muted">01</span> <span class="code-keyword">class</span> <span class="code-type">Developer</span>:
<span class="code-muted">02</span>     <span class="code-keyword">def</span> <span class="code-function">build</span>(self, idea):
<span class="code-muted">03</span>         <span class="code-keyword">return</span> Product(
<span class="code-muted">04</span>             backend=<span class="code-string">"Python"</span>,
<span class="code-muted">05</span>             frontend=<span class="code-string">"thoughtful"</span>,
<span class="code-muted">06</span>             quality=<span class="code-string">"built-in"</span>,
<span class="code-muted">07</span>         )
<span class="code-muted">08</span>
<span class="code-muted">09</span> app = Developer().<span class="code-function">build</span>(idea)</code></pre>
      <div class="code-card-footer"><span class="terminal-prompt" aria-hidden="true">›</span> Shipping useful things, one commit at a time.</div>
    </div>
    <a class="scroll-cue" href="#about"><span aria-hidden="true">↓</span> Scroll to explore</a>
  </section>

  <section class="content-section about-section" id="about" aria-labelledby="about-title">
    <div class="section-heading">
      <p class="eyebrow">A little about me</p>
      <h2 id="about-title">Good software starts with <span>good questions.</span></h2>
    </div>
    <div class="about-copy">
      <p>I’m a Python full-stack developer who enjoys shaping ideas into dependable, easy-to-use web experiences. I care about clean APIs, maintainable code, and the small interface details that make a product feel right.</p>
      <p>This is your space to introduce yourself. Add a little about the problems you like solving, the work you’re proud of, and what you’re looking for next.</p>
    </div>
  </section>

  <section class="content-section projects-section" id="projects" aria-labelledby="projects-title">
    <div class="section-heading section-heading-row">
      <div>
        <p class="eyebrow">Selected work</p>
        <h2 id="projects-title">A few things I’ve <span>been building.</span></h2>
      </div>
      <p class="section-aside">Replace these starter cards with your own projects, screenshots, and links.</p>
    </div>
    <div class="project-grid">
      <article class="project-card">
        <div class="project-art project-art-api" aria-hidden="true"><span class="art-bracket">{ }</span><span class="art-label">REST API</span></div>
        <div class="project-details">
          <p class="project-type">BACKEND · STARTER CARD</p>
          <h3>Your API project</h3>
          <p>Describe a Python API you built, the problem it solves, and a technical decision you’re proud of.</p>
          <ul class="tag-list" aria-label="Suggested technologies"><li>Python</li><li>FastAPI</li><li>PostgreSQL</li></ul>
        </div>
      </article>
      <article class="project-card">
        <div class="project-art project-art-web" aria-hidden="true"><span class="art-window"><i></i><i></i><i></i><b></b><b></b><b></b></span><span class="art-label">WEB APP</span></div>
        <div class="project-details">
          <p class="project-type">FULL STACK · STARTER CARD</p>
          <h3>Your full-stack app</h3>
          <p>Showcase an end-to-end product: what users can do, how you approached it, and what you learned.</p>
          <ul class="tag-list" aria-label="Suggested technologies"><li>Django</li><li>React</li><li>Docker</li></ul>
        </div>
      </article>
      <article class="project-card">
        <div class="project-art project-art-data" aria-hidden="true"><span class="art-chart"><i></i><i></i><i></i><i></i><i></i></span><span class="art-label">DATA</span></div>
        <div class="project-details">
          <p class="project-type">AUTOMATION · STARTER CARD</p>
          <h3>Your automation tool</h3>
          <p>Highlight a script, integration, or dashboard that saves time or makes useful information easier to find.</p>
          <ul class="tag-list" aria-label="Suggested technologies"><li>Python</li><li>Celery</li><li>Redis</li></ul>
        </div>
      </article>
    </div>
  </section>

  <section class="content-section skills-section" aria-labelledby="skills-title">
    <div class="section-heading">
      <p class="eyebrow">Tools of the trade</p>
      <h2 id="skills-title">A stack built for <span>the whole picture.</span></h2>
    </div>
    <div class="skills-grid">
      <div class="skill-group"><span class="skill-number">01</span><h3>Backend</h3><p>Python · Django · FastAPI · REST APIs</p></div>
      <div class="skill-group"><span class="skill-number">02</span><h3>Frontend</h3><p>JavaScript · React · HTML · CSS</p></div>
      <div class="skill-group"><span class="skill-number">03</span><h3>Data &amp; storage</h3><p>PostgreSQL · Redis · SQL · ORMs</p></div>
      <div class="skill-group"><span class="skill-number">04</span><h3>Delivery</h3><p>Git · Docker · CI/CD · Cloud platforms</p></div>
    </div>
    <p class="skills-note">Edit this list to match the tools you actually use.</p>
  </section>

  <section class="contact-section" id="contact" aria-labelledby="contact-title">
    <p class="eyebrow">Have something in mind?</p>
    <h2 id="contact-title">Let’s make it <span>real.</span></h2>
    <p>Have a role, project, or interesting problem to discuss? I’d love to hear from you.</p>
    <a class="button button-primary" href="mailto:hello@example.com">Get in touch <span aria-hidden="true">↗</span></a>
    <div class="social-links">
      <a href="https://github.com/your-username">GitHub <span aria-hidden="true">↗</span></a>
      <a href="https://www.linkedin.com/in/your-username/">LinkedIn <span aria-hidden="true">↗</span></a>
    </div>
  </section>
</div>
