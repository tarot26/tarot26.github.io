---
title: Registration
layout: default
permalink: /registration/
---


<section class="registration-hero" aria-labelledby="registration-title">
  <p class="registration-eyebrow">Join TAROT 2026</p>
  <h1 id="registration-title">Registration</h1>
  <p class="registration-lede">
    The registration for TAROT 2026 closed on 30 June 2026.
  </p>
</section>

<section class="registration-section registration-intro" aria-labelledby="included-title">
  <div>
    <p class="registration-eyebrow">What is included</p>
    <h2 id="included-title">Your registration covers</h2>
  </div>

  <ul class="included-grid" aria-label="Registration fee includes">
    <li>Access to the Summer School</li>
    <li>Coffee breaks</li>
    <li>Lunches</li>
    <li>Social events</li>
  </ul>
</section>

<aside class="registration-alert" aria-label="Accommodation note">
  <strong>Accommodation is not included.</strong>
  <span>Please check the accommodation page for possible accommodation options.</span>
</aside>

<section class="registration-section" aria-labelledby="fees-title">
  <div class="section-heading-row">
    <div>
      <p class="registration-eyebrow">Fees</p>
      <h2 id="fees-title">Registration Fees</h2>
    </div>
    <p class="section-heading-copy">
      The following fees apply for TAROT 2026. 
    </p>
  </div>

  <div class="pricing-grid">
    <article class="pricing-card student" aria-labelledby="student-fee-title">
      <p class="pricing-kicker">Academic participants</p>
      <h3 id="student-fee-title">Student</h3>
      <p class="price-main"><span>€450</span> regular</p>
    </article>

    <article class="pricing-card professional" aria-labelledby="professional-fee-title">
      <p class="pricing-kicker">Industry &amp; professionals</p>
      <h3 id="professional-fee-title">Professional</h3>
      <p class="price-main"><span>€600</span> regular</p>
    </article>
  </div>
</section>

<!--
<section class="registration-section registration-form-section" aria-labelledby="form-title">
  <div class="section-heading-row">
    <div>
      <p class="registration-eyebrow">Pre-registration</p>
      <h2 id="form-title">Pre-registration form</h2>
    </div>
    <p class="section-heading-copy">
      Please use the form below to let us know if you wish to present your work and bring a poster!
    </p>
  </div>

  <div class="registration-form-embed">
    <iframe src="https://docs.google.com/forms/d/e/1FAIpQLSdmjvVVrbAmy0Wh_ozhDfkXYL2k5-KHO1t-h-cTloPHfTeqLA/viewform?embedded=true" title="TAROT 2026 pre-registration form" loading="lazy" width="100%" height="1878" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>
  </div>
</section>
-->

<style>
.registration-hero {
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

.registration-hero::after {
  content: "";
  position: absolute;
  inset: auto -7rem -8rem auto;
  width: 18rem;
  height: 18rem;
  border-radius: 999px;
  background: rgba(255, 255, 255, 0.08);
  pointer-events: none;
}

.registration-eyebrow {
  margin: 0 0 0.7rem;
  color: #fbbf24;
  font-size: 0.78rem;
  font-weight: 900;
  letter-spacing: 0.14em;
  text-transform: uppercase;
}

.registration-hero h1 {
  margin: 0;
  color: #fff;
  font-size: clamp(2.6rem, 8vw, 5.2rem);
  line-height: 0.95;
  letter-spacing: -0.07em;
}

.registration-lede {
  max-width: 780px;
  margin: 1.1rem 0 0;
  color: #e5e7eb;
  font-size: clamp(1.05rem, 2vw, 1.25rem);
  line-height: 1.65;
}

.registration-section {
  margin: 2.5rem 0;
}

.registration-intro {
  display: grid;
  grid-template-columns: minmax(220px, 0.8fr) minmax(0, 1.4fr);
  gap: clamp(1rem, 4vw, 2rem);
  align-items: start;
  padding: clamp(1.4rem, 4vw, 2rem);
  border: 1px solid #e5e7eb;
  border-radius: 28px;
  background:
    radial-gradient(circle at top right, rgba(245, 158, 11, 0.1), transparent 30%),
    linear-gradient(180deg, #ffffff, #f8fafc);
}

.registration-intro .registration-eyebrow,
.section-heading-row .registration-eyebrow {
  color: #92400e;
}

.registration-intro h2,
.section-heading-row h2 {
  margin: 0;
  color: #111827;
  font-size: clamp(1.8rem, 4vw, 2.5rem);
  line-height: 1.05;
  letter-spacing: -0.05em;
}

.included-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
  gap: 0.75rem;
  margin: 0;
  padding: 0;
  list-style: none;
}

.included-grid li {
  position: relative;
  min-height: 58px;
  padding: 1rem 1rem 1rem 2.45rem;
  border: 1px solid rgba(229, 231, 235, 0.92);
  border-radius: 18px;
  background: rgba(255, 255, 255, 0.9);
  color: #111827;
  font-weight: 800;
  line-height: 1.35;
  box-shadow: 0 10px 24px rgba(15, 23, 42, 0.055);
}

.included-grid li::before {
  content: "✓";
  position: absolute;
  left: 1rem;
  top: 1rem;
  color: #059669;
  font-weight: 900;
}

.registration-alert {
  display: flex;
  gap: 0.6rem;
  align-items: flex-start;
  margin: 1.5rem 0 2.5rem;
  padding: 1rem 1.15rem;
  border: 1px solid #fde68a;
  border-left: 5px solid #f59e0b;
  border-radius: 18px;
  background: #fffbeb;
  color: #78350f;
  line-height: 1.55;
}

.registration-alert strong {
  color: #111827;
  white-space: nowrap;
}

.section-heading-row {
  display: flex;
  align-items: end;
  justify-content: space-between;
  gap: 1.5rem;
  margin-bottom: 1.5rem;
}

.section-heading-copy {
  max-width: 420px;
  margin: 0;
  color: #4b5563;
  line-height: 1.55;
}

.pricing-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 1.25rem;
}

.pricing-card {
  position: relative;
  overflow: hidden;
  padding: clamp(1.4rem, 4vw, 2rem);
  border: 1px solid rgba(229, 231, 235, 0.92);
  border-radius: 28px;
  background:
    radial-gradient(circle at top right, rgba(14, 165, 233, 0.08), transparent 30%),
    linear-gradient(180deg, rgba(255, 255, 255, 0.98), rgba(248, 250, 252, 0.96));
  box-shadow: 0 18px 45px rgba(15, 23, 42, 0.08);
  transition: transform 0.18s ease, box-shadow 0.18s ease, border-color 0.18s ease;
}

.pricing-card::before {
  content: "";
  position: absolute;
  inset: 0 0 auto;
  height: 6px;
  background: linear-gradient(90deg, #f59e0b, #38bdf8, #111827);
}

.pricing-card:hover {
  transform: translateY(-5px);
  border-color: #cbd5e1;
  box-shadow: 0 30px 70px rgba(15, 23, 42, 0.14);
}

.pricing-kicker {
  margin: 0 0 0.5rem;
  color: #92400e;
  font-size: 0.76rem;
  font-weight: 900;
  letter-spacing: 0.12em;
  text-transform: uppercase;
}

.pricing-card h3 {
  margin: 0;
  color: #111827;
  font-size: clamp(1.7rem, 4vw, 2.35rem);
  line-height: 1;
  letter-spacing: -0.06em;
}

.price-main {
  margin: 1rem 0 0.65rem;
  color: #4b5563;
  font-weight: 800;
}

.price-main span {
  display: block;
  margin-bottom: 0.2rem;
  color: #111827;
  font-size: clamp(2.1rem, 5vw, 3rem);
  font-weight: 900;
  line-height: 1;
  letter-spacing: -0.07em;
}

.price-secondary {
  display: inline-flex;
  margin: 0;
  padding: 0.42rem 0.72rem;
  border-radius: 999px;
  background: #f3f4f6;
  color: #4b5563;
  font-size: 0.9rem;
  font-weight: 800;
}

.price-secondary strong {
  margin-right: 0.35rem;
  color: #111827;
}

.registration-form-section {
  padding: clamp(1.4rem, 4vw, 2rem);
  border: 1px solid #e5e7eb;
  border-radius: 30px;
  background:
    radial-gradient(circle at bottom left, rgba(245, 158, 11, 0.1), transparent 30%),
    linear-gradient(180deg, #ffffff, #f8fafc);
}

.registration-form-embed {
  overflow: hidden;
  border: 1px solid rgba(229, 231, 235, 0.95);
  border-radius: 24px;
  background: #fff;
  box-shadow: 0 20px 50px rgba(15, 23, 42, 0.1);
}

.registration-form-embed iframe {
  display: block;
  width: 100%;
  max-width: 100%;
  height: min(1878px, 78vh);
  min-height: 720px;
  border: 0;
}

@media (max-width: 760px) {
  .registration-intro,
  .section-heading-row,
  .pricing-grid {
    display: block;
  }

  .included-grid,
  .pricing-grid {
    display: grid;
    grid-template-columns: 1fr;
  }

  .section-heading-copy {
    margin-top: 0.75rem;
  }

  .pricing-card + .pricing-card {
    margin-top: 1rem;
  }

  .registration-alert {
    display: block;
  }

  .registration-alert strong {
    display: block;
    margin-bottom: 0.25rem;
    white-space: normal;
  }
}

@media (max-width: 520px) {
  .registration-hero,
  .registration-intro,
  .pricing-card,
  .registration-form-section,
  .registration-form-embed {
    border-radius: 22px;
  }

  .registration-form-embed iframe {
    min-height: 640px;
  }
}

@media (prefers-reduced-motion: reduce) {
  .pricing-card {
    transition: none;
  }

  .pricing-card:hover {
    transform: none;
  }
}
</style>
