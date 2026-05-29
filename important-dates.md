---
title: Important dates
layout: default
permalink: /important-dates/
---

<section class="dates-hero" aria-labelledby="dates-title">
  <p class="dates-eyebrow">TAROT 2026 schedule</p>
  <h1 id="dates-title">Important Dates</h1>
  <p class="dates-lede">
    Plan your participation for TAROT 2026. The school dates are confirmed, while
    registration opening, and final programme will be published at a later date.
  </p>
</section>

<section class="dates-section" aria-labelledby="main-dates-title">
  <div class="section-heading-row">
    <div>
      <p class="dates-eyebrow">Summer school</p>
      <h2 id="main-dates-title">Main event dates</h2>
    </div>
    <p class="section-heading-copy">
      The school will take place over five days of lectures, student activities,
      networking sessions, lunches, coffee breaks, and social events.
    </p>
  </div>

  <div class="date-card" role="group" aria-label="TAROT 2026 event dates">
    <div class="date-badge" aria-hidden="true">
      <span>July</span>
      <strong>2026</strong>
    </div>

    <div class="date-content">
      <p class="date-label">Official school dates</p>
      <h3>13 July 2026 – 17 July 2026</h3>
      <p>
        TAROT 2026 will bring together researchers, practitioners, and students
        for a full week dedicated to software testing, verification,
        trustworthy AI, and autonomous systems. Registration is expected to include
        access to the school, coffee breaks, lunches, and social events.
      </p>
    </div>
  </div>
</section>

<section class="dates-section dates-updates" aria-labelledby="updates-title">
  <div>
    <p class="dates-eyebrow">More information soon</p>
    <h2 id="updates-title">Upcoming announcements</h2>
  </div>

  <div class="updates-grid">
    <article class="update-card">
      <p class="update-kicker">Registration</p>
      <h3>Registration opening</h3>
      <p>Pre-registration is available now; full registration and payment details will be announced soon.</p>
    </article>


    <article class="update-card">
      <p class="update-kicker">Travel</p>
      <h3>Venue &amp; logistics</h3>
      <p>We have added our accommodation picks close to the venue. Hotel options closer to Munich city centre will be updated soon.</p>
    </article>
  </div>
</section>

<style>
.dates-hero {
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

.dates-hero::after {
  content: "";
  position: absolute;
  inset: auto -7rem -8rem auto;
  width: 18rem;
  height: 18rem;
  border-radius: 999px;
  background: rgba(255, 255, 255, 0.08);
  pointer-events: none;
}

.dates-eyebrow {
  margin: 0 0 0.7rem;
  color: #fbbf24;
  font-size: 0.78rem;
  font-weight: 900;
  letter-spacing: 0.14em;
  text-transform: uppercase;
}

.dates-hero h1 {
  margin: 0;
  color: #fff;
  font-size: clamp(2.6rem, 8vw, 5.2rem);
  line-height: 0.95;
  letter-spacing: -0.07em;
}

.dates-lede {
  max-width: 760px;
  margin: 1.1rem 0 0;
  color: #e5e7eb;
  font-size: clamp(1.05rem, 2vw, 1.25rem);
  line-height: 1.65;
}

.dates-section {
  margin: 2.5rem 0;
}

.section-heading-row {
  display: flex;
  align-items: end;
  justify-content: space-between;
  gap: 1.5rem;
  margin-bottom: 1.5rem;
}

.section-heading-row .dates-eyebrow {
  color: #92400e;
}

.section-heading-row h2,
.dates-updates h2 {
  margin: 0;
  color: #111827;
  font-size: clamp(1.8rem, 4vw, 2.5rem);
  line-height: 1.05;
  letter-spacing: -0.05em;
}

.section-heading-copy {
  max-width: 400px;
  margin: 0;
  color: #4b5563;
  line-height: 1.55;
}

.date-card {
  display: grid;
  grid-template-columns: auto minmax(0, 1fr);
  gap: 1.5rem;
  align-items: center;
  padding: clamp(1.4rem, 4vw, 2rem);
  border: 1px solid rgba(229, 231, 235, 0.95);
  border-radius: 28px;
  background:
    radial-gradient(circle at top right, rgba(14, 165, 233, 0.08), transparent 30%),
    linear-gradient(180deg, rgba(255, 255, 255, 0.98), rgba(248, 250, 252, 0.96));
  box-shadow: 0 20px 48px rgba(15, 23, 42, 0.08);
}

.date-badge {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  width: clamp(110px, 14vw, 150px);
  aspect-ratio: 1;
  border-radius: 30px;
  background: linear-gradient(135deg, #111827, #374151);
  color: #fff;
  box-shadow: 0 20px 40px rgba(15, 23, 42, 0.18);
}

.date-badge span {
  color: #d1d5db;
  font-size: 0.82rem;
  font-weight: 900;
  letter-spacing: 0.14em;
  text-transform: uppercase;
}

.date-badge strong {
  margin-top: 0.35rem;
  font-size: clamp(1.7rem, 4vw, 2.4rem);
  line-height: 1;
  letter-spacing: -0.05em;
}

.date-content {
  min-width: 0;
}

.date-label {
  margin: 0 0 0.5rem;
  color: #92400e;
  font-size: 0.78rem;
  font-weight: 900;
  letter-spacing: 0.14em;
  text-transform: uppercase;
}

.date-content h3 {
  margin: 0;
  color: #111827;
  font-size: clamp(1.6rem, 4vw, 2.7rem);
  line-height: 1.05;
  letter-spacing: -0.06em;
}

.date-content p:last-child {
  margin: 1rem 0 0;
  color: #4b5563;
  font-size: 1rem;
  line-height: 1.7;
}

.dates-updates {
  padding: clamp(1.5rem, 4vw, 2.2rem);
  border: 1px solid #e5e7eb;
  border-radius: 30px;
  background:
    radial-gradient(circle at bottom left, rgba(245, 158, 11, 0.1), transparent 30%),
    linear-gradient(180deg, #ffffff, #f8fafc);
}

.updates-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(min(100%, 240px), 1fr));
  gap: 1rem;
  margin-top: 1.5rem;
}

.update-card {
  position: relative;
  overflow: hidden;
  padding: 1.25rem;
  border: 1px solid rgba(229, 231, 235, 0.92);
  border-radius: 22px;
  background: rgba(255, 255, 255, 0.88);
  box-shadow: 0 12px 30px rgba(15, 23, 42, 0.06);
  transition: transform 0.18s ease, box-shadow 0.18s ease, border-color 0.18s ease;
}

.update-card::before {
  content: "";
  position: absolute;
  inset: 0 0 auto;
  height: 4px;
  background: linear-gradient(90deg, #f59e0b, #38bdf8);
}

.update-card:hover {
  transform: translateY(-4px);
  border-color: #cbd5e1;
  box-shadow: 0 22px 50px rgba(15, 23, 42, 0.12);
}

.update-kicker {
  margin: 0 0 0.45rem;
  color: #92400e;
  font-size: 0.74rem;
  font-weight: 900;
  letter-spacing: 0.12em;
  text-transform: uppercase;
}

.update-card h3 {
  margin: 0;
  color: #111827;
  font-size: 1.2rem;
  letter-spacing: -0.03em;
}

.update-card p:last-child {
  margin: 0.8rem 0 0;
  color: #4b5563;
  line-height: 1.6;
}

@media (max-width: 760px) {
  .section-heading-row {
    display: block;
  }

  .section-heading-copy {
    margin-top: 0.75rem;
  }

  .date-card {
    grid-template-columns: 1fr;
  }
}

@media (max-width: 520px) {
  .dates-hero,
  .dates-updates,
  .date-card {
    border-radius: 22px;
  }

  .date-badge {
    width: 120px;
  }
}

@media (prefers-reduced-motion: reduce) {
  .update-card {
    transition: none;
  }

  .update-card:hover {
    transform: none;
  }
}
</style>
