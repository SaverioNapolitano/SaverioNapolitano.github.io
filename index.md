---
layout: default
title: Home
---

<section class="hero">
  <div class="wrapper hero-grid">
    <div class="hero-copy reveal">
      <p class="eyebrow">AI Engineering · Modena &amp; Sundsvall</p>
      <h1>Saverio Napolitano</h1>
      <p class="lead">
        Artificial Intelligence Engineering MSc student working across the
        breadth of AI — computer vision, language models, and applied AI from
        medicine to industrial settings.
      </p>
      <div class="cta-row">
        <a class="btn btn-primary" href="https://github.com/SaverioNapolitano" target="_blank" rel="noopener">View GitHub</a>
        <a class="btn btn-ghost" href="#projects">See projects</a>
      </div>
      <ul class="chips">
        <li>PyTorch</li>
        <li>Diffusers</li>
        <li>HuggingFace</li>
        <li>OpenCV</li>
        <li>Python · C++ · Java</li>
      </ul>
    </div>

    <aside class="hero-card reveal">
      <img src="{{ '/assets/pic.jpeg' | relative_url }}" alt="Saverio Napolitano" width="88" height="88" loading="lazy">
      <p class="card-label">Currently</p>
      <p class="card-text">
        MSc student exploring AI broadly — vision, language, and real-world
        applications — with a growing pull toward research.
      </p>
      <dl class="card-facts">
        <div><dt>Based in</dt><dd>Carpi, Italy</dd></div>
        <div><dt>Focus</dt><dd>Vision · Language · Applied AI</dd></div>
        <div><dt>Languages</dt><dd>IT (native) · EN (C1)</dd></div>
      </dl>
    </aside>
  </div>
</section>

<section id="about" class="section">
  <div class="wrapper">
    <div class="section-head reveal">
      <p class="kicker">About</p>
      <h2>Bridging research and engineering in applied AI.</h2>
    </div>
    <div class="about-grid">
      <p class="about-lead reveal">
        I'm a Master's student in Artificial Intelligence Engineering at the
        University of Modena and Reggio Emilia (Unimore), recently back from an
        Erasmus+ semester at Mid Sweden University in Sundsvall. My interests run
        across the whole field — computer vision, large language models, and
        applied AI in domains like medicine and industry. I like turning recent
        research into systems that actually run.
      </p>
      <div class="stat-row reveal">
        <div class="stat"><span class="stat-num">108<span>/110</span></span><span class="stat-label">BSc Computer Engineering</span></div>
        <div class="stat"><span class="stat-num">C1</span><span class="stat-label">English proficiency</span></div>
        <div class="stat"><span class="stat-num">2</span><span class="stat-label">Countries studied in</span></div>
      </div>
    </div>
  </div>
</section>

<section id="experience" class="section section-alt">
  <div class="wrapper">
    <div class="section-head reveal">
      <p class="kicker">Experience &amp; Education</p>
      <h2>A path across applied AI and international study.</h2>
    </div>

    <ol class="timeline">
      <li class="timeline-item reveal">
        <div class="timeline-period">Feb 2026 – May 2026</div>
        <div class="timeline-body">
          <h3>Machine Learning &amp; Computer Vision Intern</h3>
          <p class="timeline-org">Deep Vision Consulting — Modena, Italy</p>
          <p>
            Evaluated and prototyped state-of-the-art generative models.
            Fine-tuned diffusion models with LoRA and T2I adapters, built
            ComfyUI workflows for rapid prototyping, and integrated
            HuggingFace / Diffusers into custom pipelines.
          </p>
        </div>
      </li>
      <li class="timeline-item reveal">
        <div class="timeline-period">2024 – present</div>
        <div class="timeline-body">
          <h3>MSc, Artificial Intelligence Engineering</h3>
          <p class="timeline-org">University of Modena and Reggio Emilia (Unimore)</p>
          <p>Second-cycle degree in Computer Engineering, AI track.</p>
        </div>
      </li>
      <li class="timeline-item reveal">
        <div class="timeline-period">Sep 2025 – Jan 2026</div>
        <div class="timeline-body">
          <h3>Erasmus+ Exchange Semester</h3>
          <p class="timeline-org">Mid Sweden University (MIUN) — Sundsvall, Sweden</p>
          <p>One semester abroad through the Erasmus+ mobility program.</p>
        </div>
      </li>
      <li class="timeline-item reveal">
        <div class="timeline-period">2021 – 2024</div>
        <div class="timeline-body">
          <h3>BSc, Computer Engineering</h3>
          <p class="timeline-org">University of Modena and Reggio Emilia (Unimore)</p>
          <p>Final mark 108/110.</p>
        </div>
      </li>
    </ol>
  </div>
</section>

<section id="skills" class="section">
  <div class="wrapper">
    <div class="section-head reveal">
      <p class="kicker">Toolkit</p>
      <h2>What I build with.</h2>
    </div>
    <div class="skill-grid">
      <div class="skill-card reveal">
        <h3>Machine Learning</h3>
        <ul><li>PyTorch</li><li>Transformers</li><li>PEFT</li><li>Diffusers</li><li>HuggingFace</li><li>Scikit-Learn</li><li>OpenCV</li></ul>
      </div>
      <div class="skill-card reveal">
        <h3>Languages</h3>
        <ul><li>Python</li><li>C / C++</li><li>Java</li><li>SQL</li><li>Unix shell</li></ul>
      </div>
      <div class="skill-card reveal">
        <h3>Data &amp; Tooling</h3>
        <ul><li>NumPy &amp; Pandas</li><li>Matplotlib &amp; Seaborn</li><li>Git</li><li>ComfyUI</li><li>Jupyter</li></ul>
      </div>
    </div>
  </div>
</section>

<section id="projects" class="section section-alt">
  <div class="wrapper">
    <div class="section-head reveal">
      <p class="kicker">Projects</p>
      <h2>Selected work.</h2>
    </div>
    <div class="project-grid">
      <article class="project-card reveal">
        <h3>Counterfactual Generation</h3>
        <p>Counterfactual generation for representation learning in industrial time-series prognostics — accepted at IRAI 2026.</p>
        <span class="tag">Python · PyTorch</span>
        <a class="project-link" href="https://github.com/cigarsai/counterfactual-generation" target="_blank" rel="noopener">View on GitHub</a>
      </article>
      <article class="project-card reveal">
        <h3>TC-MIL</h3>
        <p>Depression detection from clinical interview transcripts (DAIC-WOZ) — interviews as bags of dialogue chunks, classified with a frozen sentence encoder and a gated-attention MIL head, with LoRA fine-tuning and cross-validation protocols.</p>
        <span class="tag">Python · PyTorch</span>
        <a class="project-link" href="https://github.com/SaverioNapolitano/tcmil" target="_blank" rel="noopener">View on GitHub</a>
      </article>
      <article class="project-card reveal">
        <h3>Stem-Searcher</h3>
        <p>Information-retrieval project for the "Gestione dell'informazione" course.</p>
        <span class="tag">Python</span>
        <a class="project-link" href="https://github.com/MrBigSlime/Stem-Searcher" target="_blank" rel="noopener">View on GitHub</a>
      </article>
      <article class="project-card reveal">
        <h3>D.I.A.G.R.A.M.</h3>
        <p>Computer-vision pipeline that turns photos of hand-drawn diagrams into editable digital versions — detects nodes and arrows, then generates D2 / Mermaid markup that renders back to clean graphics.</p>
        <span class="tag">Python · PyTorch</span>
        <a class="project-link" href="https://github.com/nricciardi/diagram" target="_blank" rel="noopener">View on GitHub</a>
      </article>
      <article class="project-card reveal">
        <h3>expirationdate</h3>
        <p>JavaFX desktop app for managing food at home — pantry, shopping list, and recipes backed by a MySQL database, with calendar reminders when products near their expiry date.</p>
        <span class="tag">Java · JavaFX</span>
        <a class="project-link" href="https://github.com/SaverioNapolitano/expirationdate" target="_blank" rel="noopener">View on GitHub</a>
      </article>
      <article class="project-card reveal">
        <h3>STYLEGUIDE</h3>
        <p>Stop Telling Your Lights Everything, Green Up Ideal Daily Environment.</p>
        <span class="tag">Research</span>
        <a class="project-link" href="https://github.com/SaverioNapolitano/STYLEGUIDE" target="_blank" rel="noopener">View on GitHub</a>
      </article>
    </div>
  </div>
</section>

<section id="service" class="section">
  <div class="wrapper">
    <div class="section-head reveal">
      <p class="kicker">Academic Service</p>
      <h2>Peer review.</h2>
    </div>
    <div class="project-grid">
      <article class="project-card reveal">
        <h3>Reviewer</h3>
        <p>Reviewed 2 papers for the IEEE International Conference on E-Learning in Industrial Electronics (ICELIE) 2026.</p>
        <span class="tag">Peer review</span>
      </article>
    </div>
  </div>
</section>

<section id="contact" class="section">
  <div class="wrapper">
    <div class="cta-panel reveal">
      <h2>Let's build something.</h2>
      <p>Open to conversations across AI — computer vision, language models, and applied AI — plus coursework collaborations and research experiments.</p>
      <div class="cta-row">
        <a class="btn btn-primary" href="mailto:saverio.napolitano@outlook.com">Email me</a>
        <a class="btn btn-ghost" href="https://github.com/SaverioNapolitano" target="_blank" rel="noopener">GitHub</a>
      </div>
    </div>
  </div>
</section>
