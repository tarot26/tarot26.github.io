---
title: Home
layout: default
permalink: /
---

<!-- Hero Section -->
<section class="hero hero-home">
  <img src="{{ '/assets/img/hero.jpg' | relative_url }}" alt="TAROT Summer School banner">

  <div class="hero-overlay-home">
    <div class="hero-content-home">
      <p class="hero-kicker">
        21st Edition · Munich · 13–17 July 2026
      </p>

      <h1>TAROT Summer School 2026</h1>

      <p class="hero-topic">
        Testing, Validation, and Security of AI-enabled Systems
      </p>

      <div class="hero-tags">
        <span>DNN Testing</span>
        <span>LLMs &amp; VLMs</span>
        <span>Autonomous Systems</span>
        <span>Runtime Verification</span>
        <span>AI Safety</span>
      </div>

      <div class="hero-actions">
        <a href="{{ '/school/program/' | relative_url }}" class="hero-btn hero-btn-primary">
          View Program
        </a>

        <a href="{{ '/school/lecturers/' | relative_url }}" class="hero-btn hero-btn-secondary">
          Meet the Speakers
        </a>
      </div>
    </div>
  </div>
</section>

<!-- Welcome -->
<section class="home-section">
  <div class="content content-narrow text-justify">
    <h2>Welcome</h2>

    <p>
      TAROT (Training And Research On Testing) is a network created to foster the mobility of students, faculty members, and research scientists working in the field of testing of software and communication systems.
    </p>

    <p>
      Now in its <strong>21st edition</strong>, the TAROT Summer School brings together lecturers, researchers, students, and industry practitioners from across Europe for one week of presentations, discussions, and networking.
    </p>

    <p>
      The 2026 edition focuses on <strong>Testing, Validation, and Security of AI-enabled Systems</strong>, including DNN-, VLM-, and LLM-based systems, autonomous systems, runtime verification, robustness, and AI safety.
    </p>

    <p>
      Participants will attend tutorials and invited talks by internationally recognized experts from academia and industry, while PhD and master's students will also have the opportunity to present and discuss their ongoing research.
    </p>

    <p>
      The organizers and local committee are looking forward to welcoming you to Munich.
    </p>
  </div>
</section>

<!-- Highlights -->
<section class="home-section home-section-alt">
  <div class="content">
    <h2 class="section-title-center">Why Attend?</h2>

    <div class="highlights-grid">
      <article class="highlight-card">
        <div class="highlight-icon">🎓</div>
        <h3>Learn from experts</h3>
        <p>
          Attend lectures and tutorials by leading researchers and practitioners in software testing, AI safety, and verification.
        </p>
      </article>

      <article class="highlight-card">
        <div class="highlight-icon">🤝</div>
        <h3>Meet the community</h3>
        <p>
          Connect with PhD students, researchers, and industry experts from across Europe and beyond.
        </p>
      </article>

      <article class="highlight-card">
        <div class="highlight-icon">🧠</div>
        <h3>Focus on trustworthy AI</h3>
        <p>
          Explore current research challenges in testing, robustness, validation, and security of AI-enabled systems.
        </p>
      </article>

      <article class="highlight-card">
        <div class="highlight-icon">📍</div>
        <h3>Experience Munich &amp; TUM</h3>
        <p>
          Join the summer school at the Technical University of Munich in the TUM-IAS Building at Garching campus.
        </p>
      </article>
    </div>
  </div>
</section>

<!-- Flyer -->
<section class="home-section">
  <div class="content content-narrow text-center">
    <h2>Flyer</h2>

    <p>
      Download the official TAROT 2026 flyer.
    </p>

    <a href="{{ '/assets/img/flyer.pdf' | relative_url }}" download="flyer.pdf" class="hero-btn hero-btn-primary">
      Download Flyer
    </a>
  </div>
</section>

.  
<style>
body,
.site-header {
  background: #f8fafc;
}

.site-header {
  box-shadow: none;
  border-bottom: 1px solid #e5e7eb;
}
.hero-home {
  position: relative;
  overflow: hidden;
  border-radius: 24px;
  margin-bottom: 2.5rem;
  min-height: 520px;
  display: block;
}

.hero-home img {
  width: 100%;
  height: 520px;
  object-fit: cover;
  display: block;
}

.hero-overlay-home {
  position: absolute !important;
  inset: 0 !important;
  z-index: 1;
  display: flex !important;
  justify-content: center;
  align-items: center;
  padding: 3rem 1.5rem;
  background:
    linear-gradient(135deg, rgba(2, 6, 23, 0.82), rgba(3, 105, 161, 0.45));
  color: #fff;
  text-align: center;
  box-sizing: border-box;
  width: 100%;
  height: 100%;
  transform: none !important;
}

.hero-content-home {
  width: min(100%, 1100px);
  margin: 0 auto;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

.hero-kicker {
  margin: 0 0 1rem;
  font-size: 0.92rem;
  font-weight: 700;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  color: #bae6fd;
}

.hero-overlay-home h1 {
  margin: 0;
  max-width: 950px;
  font-size: clamp(2.6rem, 5vw, 4.5rem);
  line-height: 1.05;
  font-weight: 800;
}

.hero-topic {
  margin-top: 1.25rem;
  max-width: 780px;
  font-size: 1.2rem;
  line-height: 1.6;
  color: rgba(255,255,255,0.92);
  text-align: center;
}

.hero-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.65rem;
  margin-top: 1.5rem;
  justify-content: center;
}

.hero-tags span {
  padding: 0.45rem 0.8rem;
  border-radius: 999px;
  background: rgba(255,255,255,0.14);
  border: 1px solid rgba(255,255,255,0.18);
  backdrop-filter: blur(8px);
  font-size: 0.88rem;
  font-weight: 700;
}

.hero-actions {
  display: flex;
  flex-wrap: wrap;
  gap: 0.9rem;
  margin-top: 2rem;
  justify-content: center;
}

.hero-btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  padding: 0.9rem 1.35rem;
  border-radius: 999px;
  text-decoration: none;
  font-weight: 700;
  transition: transform 0.18s ease, box-shadow 0.18s ease, background 0.18s ease;
}

.hero-btn:hover {
  transform: translateY(-2px);
}

.hero-btn-primary {
  background: #38bdf8;
  color: #082f49;
  box-shadow: 0 14px 28px rgba(56, 189, 248, 0.25);
}

.hero-btn-primary:hover {
  background: #7dd3fc;
}

.hero-btn-secondary {
  background: rgba(255,255,255,0.12);
  color: #fff;
  border: 1px solid rgba(255,255,255,0.2);
  backdrop-filter: blur(8px);
}

.home-section {
  margin: 3rem 0;
}

.home-section-alt {
  padding: 3rem 0;
}

.content-narrow {
  max-width: 850px;
}

.section-title-center {
  text-align: center;
  margin-bottom: 2rem;
}

.highlights-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
  gap: 1rem;
}

.highlight-card {
  padding: 1.4rem;
  border: 1px solid #e5e7eb;
  border-radius: 18px;
  background: #fff;
  box-shadow: 0 12px 28px rgba(15, 23, 42, 0.05);
  transition: transform 0.18s ease, box-shadow 0.18s ease;
}

.highlight-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 18px 36px rgba(15, 23, 42, 0.1);
}

.highlight-icon {
  font-size: 1.8rem;
  margin-bottom: 0.75rem;
}

.highlight-card h3 {
  margin-top: 0;
  margin-bottom: 0.65rem;
}

.highlight-card p {
  margin: 0;
  color: #4b5563;
  line-height: 1.6;
}

.text-center {
  text-align: center;
}

@media (max-width: 700px) {
  .hero-home {
    min-height: 480px;
    border-radius: 18px;
  }

  .hero-home img {
    height: 480px;
  }

  .hero-overlay-home {
    padding: 2rem 1.25rem;
    align-items: center;
    text-align: center;
  }
  .hero-content-home {
    width: 100%;
  }

  .hero-topic {
    font-size: 1rem;
  }

  .hero-actions {
    width: 100%;
    flex-direction: column;
    align-items: center;
  }

  .hero-btn {
    width: 100%;
  }
}
</style>
