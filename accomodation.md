---
title: Accommodations
layout: default
permalink: /accommodation/
---

<section class="accommodation-hero">
  <p class="accommodation-eyebrow">Plan your stay</p>
  <h1>Accommodation</h1>
  <p class="accommodation-lede">
    Participants can stay either in Garching, close to the venue, or in Munich city centre.
    Garching offers the shortest commute, while Munich provides a wider range of hotels, restaurants, and evening activities.
  </p>
</section>

<section class="accommodation-section">
  <div class="section-heading-row">
    <div>
      <p class="accommodation-eyebrow">Closest to the venue</p>
      <h2>Garching</h2>
    </div>
    <p class="section-heading-copy">
      Recommended for participants who want the shortest commute to the TUM Institute for Advanced Study.
    </p>
  </div>

  <div class="hotel-grid">
    <article class="hotel-card">
      <div class="hotel-badge">Distance and travel time TBA</div>
      <h3>Hotel option (premium)</h3>
      <p class="hotel-type">Closest option · Higher price range</p>
      <p>Modern business hotel directly in Garching with excellent access to the TUM campus.</p>
    </article>

    <article class="hotel-card">
      <div class="hotel-badge">Distance and travel time TBA</div>
      <h3>Hotel option (budget)</h3>
      <p class="hotel-type">Budget option</p>
      <p>Simple and affordable accommodation with convenient public transport connections.</p>
    </article>

    <article class="hotel-card">
      <div class="hotel-badge">Distance and travel time TBA</div>
      <h3>Hotel option (balanced)</h3>
      <p class="hotel-type">Balanced option</p>
      <p>Comfortable mid-range hotel combining accessibility, comfort, and reasonable pricing.</p>
    </article>
  </div>
</section>

<section class="accommodation-section">
  <div class="section-heading-row">
    <div>
      <p class="accommodation-eyebrow">City centre stay</p>
      <h2>Munich</h2>
    </div>
    <p class="section-heading-copy">
      Munich is further from the venue than Garching, but many convenient hotels are located directly on the U6 line, providing straightforward access to the summer school.
    </p>
  </div>

  <div class="hotel-grid">
    <article class="hotel-card">
      <div class="hotel-badge">Distance and travel time TBA</div>
      <h3>Hotel option (premium)</h3>
      <p class="hotel-type">Premium option</p>
      <p>Luxury accommodation close to Munich Central Station and city attractions.</p>
    </article>

    <article class="hotel-card">
      <div class="hotel-badge">Distance and travel time TBA</div>
      <h3>Hotel option (balanced)</h3>
      <p class="hotel-type">Balanced option</p>
      <p>Reliable mid-range hotel in the city centre with excellent public transport access.</p>
    </article>

    <article class="hotel-card">
      <div class="hotel-badge">Distance and travel time TBA</div>
      <h3>Hotel option (budget)</h3>
      <p class="hotel-type">Budget option</p>
      <p>Affordable accommodation within easy reach of Munich's main transport hubs.</p>
    </article>
  </div>
</section>

<section class="transport-warning" aria-label="Transport notice">
  <strong>Important transport notice</strong>
  <p>
    We recommend choosing accommodation on the northern section of the U6 line.
    South of Sendlinger Tor, service interruptions and replacement transport are currently occurring.
    For this reason, we do not recommend booking accommodation further south on the U6 route.
  </p>
</section>

<style>
.accommodation-hero {
  margin: 0 0 2rem;
  padding: clamp(2rem,5vw,4rem);
  border-radius: 30px;
  background: linear-gradient(135deg,#111827,#1f2937 60%,#374151);
  color: white;
  box-shadow: 0 24px 60px rgba(15,23,42,.18);
}

.accommodation-eyebrow {
  margin: 0 0 .6rem;
  color: #fbbf24;
  font-size: .78rem;
  font-weight: 900;
  letter-spacing: .14em;
  text-transform: uppercase;
}

.accommodation-hero h1 {
  margin: 0;
  font-size: clamp(2.5rem,7vw,5rem);
}

.accommodation-lede {
  max-width: 850px;
  color: #e5e7eb;
  line-height: 1.7;
}

.accommodation-section {
  margin: 3rem 0;
}

.section-heading-row {
  display:flex;
  justify-content:space-between;
  gap:2rem;
  margin-bottom:1.5rem;
}

.section-heading-copy {
  max-width:420px;
  color:#4b5563;
}

.hotel-grid {
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
  gap:1rem;
}

.hotel-card {
  padding:1.4rem;
  border-radius:24px;
  border:1px solid #e5e7eb;
  background:linear-gradient(180deg,#fff,#f8fafc);
  box-shadow:0 14px 34px rgba(15,23,42,.07);
}

.hotel-card h3 {
  margin:.8rem 0 .4rem;
}

.hotel-badge {
  display:inline-flex;
  padding:.45rem .75rem;
  border-radius:999px;
  background:#111827;
  color:white;
  font-size:.78rem;
  font-weight:800;
}

.hotel-type {
  color:#92400e;
  font-weight:700;
}

.transport-warning {
  margin:3rem 0;
  padding:1.4rem;
  border-radius:24px;
  border:1px solid #f59e0b;
  background:#fffbeb;
  color:#92400e;
}

.transport-warning strong {
  display:block;
  margin-bottom:.5rem;
}

@media (max-width:760px) {
  .section-heading-row {
    display:block;
  }

  .section-heading-copy {
    margin-top:.75rem;
  }
}
</style>