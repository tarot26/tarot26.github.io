---
title: Organisers
layout: default
permalink: /organisation/
---
<section class="org-hero" aria-labelledby="org-title">
  <p class="org-eyebrow">TAROT 2026 team</p>
  <h1 id="org-title">Organisers</h1>
  <p class="org-lede">Meet the steering, organising, local, and publicity teams behind TAROT 2026.</p>
</section>

<style>
.org-hero {
  position: relative;
  overflow: hidden;
  margin: 0 0 2rem;
  padding: clamp(2rem, 5vw, 4rem);
  border: 1px solid #e5e7eb;
  border-radius: 30px;
  background:
    radial-gradient(circle at 12% 6%, rgba(245, 158, 11, 0.22), transparent 30%),
    radial-gradient(circle at 88% 12%, rgba(14, 165, 233, 0.14), transparent 28%),
    linear-gradient(135deg, #111827, #1f2937 58%, #374151);
  color: #fff;
  box-shadow: 0 24px 60px rgba(15, 23, 42, 0.18);
}

.org-hero::after {
  content: "";
  position: absolute;
  inset: auto -7rem -8rem auto;
  width: 18rem;
  height: 18rem;
  border-radius: 999px;
  background: rgba(255, 255, 255, 0.08);
  pointer-events: none;
}

.org-eyebrow {
  margin: 0 0 0.7rem;
  color: #fbbf24;
  font-size: 0.78rem;
  font-weight: 900;
  letter-spacing: 0.14em;
  text-transform: uppercase;
}

.org-hero h1 {
  margin: 0;
  color: #fff;
  font-size: clamp(2.6rem, 8vw, 5.2rem);
  line-height: 0.95;
  letter-spacing: -0.07em;
}

.org-lede {
  max-width: 780px;
  margin: 1.1rem 0 0;
  color: #e5e7eb;
  font-size: clamp(1.05rem, 2vw, 1.25rem);
  line-height: 1.65;
}

.org-section {
  margin: 2.5rem 0;
}

.section-heading-row {
  display: flex;
  align-items: end;
  justify-content: space-between;
  gap: 1.5rem;
  margin-bottom: 1.35rem;
}

.section-heading-row .org-eyebrow {
  color: #92400e;
}

.section-heading-row h2 {
  margin: 0;
  color: #111827;
  font-size: clamp(1.8rem, 4vw, 2.6rem);
  line-height: 1.05;
  letter-spacing: -0.05em;
}

.section-heading-copy {
  max-width: 430px;
  margin: 0;
  color: #4b5563;
  line-height: 1.55;
}

.org-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(min(100%, 300px), 1fr));
  gap: 1.15rem;
  margin: 0;
}

.org-card {
  position: relative;
  height: 100%;
  overflow: hidden;
  border: 1px solid rgba(229, 231, 235, 0.92);
  border-radius: 26px;
  background:
    radial-gradient(circle at top right, rgba(14, 165, 233, 0.08), transparent 30%),
    linear-gradient(180deg, rgba(255, 255, 255, 0.98), rgba(248, 250, 252, 0.96));
  box-shadow: 0 16px 40px rgba(15, 23, 42, 0.075);
  transition: transform 0.18s ease, box-shadow 0.18s ease, border-color 0.18s ease;
}

.org-card::before {
  content: "";
  position: absolute;
  inset: 0 0 auto;
  height: 5px;
  background: linear-gradient(90deg, #f59e0b, #38bdf8, #111827);
  opacity: 0.75;
}


.org-card-affiliation-placeholder {
  background:
    radial-gradient(circle at 86% 18%, rgba(15, 23, 42, 0.08), transparent 30%),
    linear-gradient(180deg, rgba(255, 255, 255, 0.99), rgba(248, 250, 252, 0.96));
}

.org-card-affiliation-placeholder .org-link::after {
  content: "Affiliation logo pending";
  position: absolute;
  right: 1rem;
  bottom: 0.45rem;
  z-index: -1;
  display: grid;
  place-items: center;
  width: clamp(6rem, 16vw, 9rem);
  aspect-ratio: 1;
  padding: 0.9rem;
  border: 2px dashed rgba(15, 23, 42, 0.12);
  border-radius: 28px;
  color: rgba(15, 23, 42, 0.18);
  font-size: 0.72rem;
  font-weight: 900;
  line-height: 1.15;
  letter-spacing: 0.08em;
  text-align: center;
  text-transform: uppercase;
  pointer-events: none;
  transform: rotate(-6deg);
}

.org-link {
  position: relative;
  z-index: 1;
  display: grid;
  grid-template-columns: auto minmax(0, 1fr);
  gap: 1rem;
  align-items: flex-start;
  height: 100%;
  padding: 1.25rem;
  color: inherit;
  text-decoration: none;
}

.org-link:focus-visible {
  outline: 3px solid #f59e0b;
  outline-offset: -6px;
  border-radius: 26px;
}

.org-photo {
  width: 78px;
  height: 78px;
  object-fit: cover;
  border-radius: 24px;
  flex: 0 0 auto;
  box-shadow: 0 14px 28px rgba(15, 23, 42, 0.16);
}

.org-body {
  min-width: 0;
  padding-bottom: 1.25rem;
}

.org-name {
  margin: 0 0 0.4rem;
  color: #111827;
  font-size: clamp(1.05rem, 2vw, 1.2rem);
  line-height: 1.2;
  letter-spacing: -0.03em;
}

.org-role {
  display: inline-flex;
  margin: 0 0 0.65rem;
  padding: 0.22rem 0.6rem;
  border-radius: 999px;
  background: #e0f2fe;
  color: #075985;
  font-size: 0.74rem;
  font-weight: 900;
  letter-spacing: 0.08em;
  text-transform: uppercase;
}

.org-affiliation {
  margin: 0.15rem 0 0;
  color: #4b5563;
  font-size: 0.92rem;
  line-height: 1.38;
}

.org-card-contact {
  background:
    radial-gradient(circle at top right, rgba(245, 158, 11, 0.1), transparent 30%),
    linear-gradient(180deg, #ffffff, #f8fafc);
}


.org-link-contact {
  align-items: center;
  min-height: 112px;
}

.org-icon-email {
  width: 38px;
  height: 38px;
  object-fit: contain;
  flex: 0 0 auto;
  filter: drop-shadow(0 8px 14px rgba(15, 23, 42, 0.12));
}

.org-contact-action {
  display: inline-flex;
  margin: 0.35rem 0 0;
  padding: 0.24rem 0.65rem;
  border-radius: 999px;
  background: #f3f4f6;
  color: #374151;
  font-size: 0.78rem;
  font-weight: 900;
}

@media (max-width: 760px) {
  .section-heading-row {
    display: block;
  }

  .section-heading-copy {
    margin-top: 0.75rem;
  }

  .org-grid {
    grid-template-columns: 1fr;
  }
}

@media (max-width: 520px) {
  .org-hero {
    border-radius: 22px;
  }

  .org-link {
    grid-template-columns: auto minmax(0, 1fr);
    align-items: flex-start;
    gap: 0.85rem;
    padding: 1rem;
  }

  .org-link-contact {
    grid-template-columns: auto minmax(0, 1fr);
    align-items: center;
  }

  .org-photo {
    width: 64px;
    height: 64px;
    border-radius: 18px;
  }


  .org-body {
    padding-bottom: 1.4rem;
  }

  .org-name {
    font-size: 1rem;
  }

  .org-role {
    margin-bottom: 0.5rem;
    font-size: 0.68rem;
  }

  .org-affiliation {
    font-size: 0.86rem;
  }

  .org-card-affiliation-placeholder .org-link::after {
    right: 0.7rem;
    bottom: 0.25rem;
    width: 6rem;
    border-radius: 22px;
    font-size: 0.62rem;
  }
}

@media (prefers-reduced-motion: reduce) {
  .org-card {
    transition: none;
  }
}
</style>

<section class="org-section" aria-labelledby="organising-title">
  <div class="section-heading-row">
    <div>
      <p class="org-eyebrow">Core team</p>
      <h2 id="organising-title">Organising Committee</h2>
    </div>
  </div>
<div class="org-grid">
  <!-- Alessio Gambi -->
  <div class="org-card">
    <a href="https://publications.ait.ac.at/en/persons/alessio-gambi" target="_blank" rel="noopener noreferrer" class="org-link">
      <img class="org-photo" src="{{ '/assets/img/org/alessio-gambi.webp' | relative_url }}" alt="Dr. Alessio Gambi">
      <div class="org-body">
        <h3 class="org-name">Dr. Alessio Gambi</h3>
        <p class="org-role">Organizer</p>
        <p class="org-affiliation">Austrian Institute of Technology (AIT), Austria</p>
        <p class="org-affiliation">The Italian Institute of Artificial Intelligence for Industry (AI4I), Italy</p>
      </div>
    </a>
  </div>

  <!-- Andrea Stocco -->
  <div class="org-card">
    <a href="https://tsigalko18.github.io" target="_blank" rel="noopener noreferrer" class="org-link">
      <img class="org-photo" src="{{ '/assets/img/org/andrea-stocco.jpg' | relative_url }}" alt="Prof. Andrea Stocco">
      <div class="org-body">
        <h3 class="org-name">Prof. Andrea Stocco</h3>
        <p class="org-role">Organizer</p>
        <p class="org-affiliation">Technical University of Munich (TUM) and Fortiss, Germany</p>
      </div>
    </a>
  </div>
</div>
</section>

<section class="org-section" aria-labelledby="local-title">
  <div class="section-heading-row">
    <div>
      <p class="org-eyebrow">Munich operations</p>
      <h2 id="local-title">Local Committee</h2>
    </div>
  </div>
<div class="org-grid">
  <!-- Severin Kacianka -->
  <div class="org-card">
    <a href="https://kacianka.at" target="_blank" rel="noopener noreferrer" class="org-link">
      <img class="org-photo" src="{{ '/assets/img/org/severin.jpg' | relative_url }}" alt="Dr. Severin Kacianka">
      <div class="org-body">
        <h3 class="org-name">Dr. Severin Kacianka</h3>
        <p class="org-role">Organizer</p>
        <p class="org-affiliation">Technical University of Munich (TUM) and Fortiss, Germany</p>
      </div>
    </a>
  </div>

  <!-- Stefano Carlo Lambertenghi -->
  <div class="org-card">
    <a href="https://www.fortiss.org/ergebnisse/publikationen/autor/stefano-carlo-lambertenghi" target="_blank" rel="noopener noreferrer" class="org-link">
      <img class="org-photo" src="{{ '/assets/img/org/stefano-Lambertenghi.jpg' | relative_url }}" alt="Stefano Carlo Lambertenghi">
      <div class="org-body">
        <h3 class="org-name">Stefano Carlo Lambertenghi</h3>
        <p class="org-role">Web Chair</p>
        <p class="org-affiliation">Technical University of Munich (TUM) and Fortiss, Germany</p>
      </div>
    </a>
  </div>
</div>
</section>

<section class="org-section" aria-labelledby="publicity-title">
  <div class="section-heading-row">
    <div>
      <p class="org-eyebrow">Visibility</p>
      <h2 id="publicity-title">Publicity Chairs</h2>
    </div>
  </div>
<div class="org-grid">
  <!-- Ezio Bartocci -->
  <div class="org-card">
    <a href="https://www.linkedin.com/in/ezio-bartocci" target="_blank" rel="noopener noreferrer" class="org-link">
      <img class="org-photo" src="{{ '/assets/img/org/ezio.jpg' | relative_url }}" alt="Prof. Ezio Bartocci">
      <div class="org-body">
        <h3 class="org-name">Prof. Ezio Bartocci</h3>
        <p class="org-role">Publicity Chair</p>
        <p class="org-affiliation">Technical University of Wien (TUW), Austria</p>
      </div>
    </a>
  </div>

  <!-- Valeria Morra -->
  <div class="org-card">
    <a href="https://www.linkedin.com/in/valeria-morra-02684b16b/" target="_blank" rel="noopener noreferrer" class="org-link">
      <img class="org-photo" src="{{ '/assets/img/org/valeria.jpg' | relative_url }}" alt="Valeria Morra">
      <div class="org-body">
        <h3 class="org-name">Valeria Morra</h3>
        <p class="org-role">Publicity Chair</p>
        <p class="org-affiliation">Institute for Advanced Study (IAS), Italy</p>
      </div>
    </a>
  </div>
</div>
</section>

<section class="org-section" aria-labelledby="steering-title">
  <div class="section-heading-row">
    <div>
      <p class="org-eyebrow">Governance</p>
      <h2 id="steering-title">Steering Committee</h2>
    </div>
  </div>
<div class="org-grid">
  <div class="org-card">
    <a href="http://www-public.imtbs-tsp.eu/~cavalli/index.html" target="_blank" rel="noopener noreferrer" class="org-link">
      <img class="org-photo" src="{{ '/assets/img/org/ana-cavalli.png' | relative_url }}" alt="Dr. Ana Cavalli">
      <div class="org-body">
        <h3 class="org-name">Prof. Ana Cavalli</h3>
        <p class="org-role">Steering Committee</p>
        <p class="org-affiliation">Télécom SudParis, France</p>
      </div>
    </a>
  </div>

  <div class="org-card">
    <a href="https://robhierons.github.io" target="_blank" rel="noopener noreferrer" class="org-link">
      <img class="org-photo" src="{{ '/assets/img/org/rob-hierons.jpg' | relative_url }}" alt="Dr. Rob Hierons">
      <div class="org-body">
        <h3 class="org-name">Prof. Rob Hierons</h3>
        <p class="org-role">Steering Committee</p>
        <p class="org-affiliation">The University of Sheffield, UK</p>
      </div>
    </a>
  </div>

  <div class="org-card">
    <a href="https://antares.sip.ucm.es/manolo/" target="_blank" rel="noopener noreferrer" class="org-link">
      <img class="org-photo" src="{{ '/assets/img/org/manuel-nunez.jpg' | relative_url }}" alt="Manuel Nunez">
      <div class="org-body">
        <h3 class="org-name">Prof. Manuel Nunez</h3>
        <p class="org-role">Steering Committee</p>
        <p class="org-affiliation">Universidad Complutense de Madrid, Spain</p>
      </div>
    </a>
  </div>
</div>
</section>

<section class="org-section org-contact-section" aria-labelledby="contacts-title">
  <div class="section-heading-row">
    <div>
      <p class="org-eyebrow">Get in touch</p>
      <h2 id="contacts-title">Contacts</h2>
    </div>
    <p class="section-heading-copy">For questions about participation, logistics, or the programme, contact the organising team.</p>
  </div>
<div class="org-grid">
  <!-- Alessio Gambi -->
  <div class="org-card org-card-contact">
    <a href="mailto:alessio.gambi@ait.ac.at" class="org-link org-link-contact" aria-label="Email Dr. Alessio Gambi">
      <img class="org-icon-email" src="{{ '/assets/img/icons/email.webp' | relative_url }}" alt="Email icon" width="32" height="32">
      <div class="org-body">
        <h3 class="org-name">Dr. Alessio Gambi</h3>
        <p class="org-contact-action">Email Alessio</p>
      </div>
    </a>
  </div>

  <!-- Andrea Stocco -->
  <div class="org-card org-card-contact">
    <a href="mailto:andrea.stocco@tum.de" class="org-link org-link-contact" aria-label="Email Prof. Andrea Stocco">
      <img class="org-icon-email" src="{{ '/assets/img/icons/email.webp' | relative_url }}" alt="Email icon" width="32" height="32">
      <div class="org-body">
        <h3 class="org-name">Prof. Dr. Andrea Stocco</h3>
        <p class="org-contact-action">Email Andrea</p>
      </div>
    </a>
  </div>
</div>
</section>
