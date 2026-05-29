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

<section class="accommodation-map-section" aria-labelledby="accommodation-map-title">
  <div class="section-heading-row">
    <div>
      <p class="accommodation-eyebrow">Accommodation map</p>
      <h2 id="accommodation-map-title">Where to stay</h2>
    </div>
    <p class="section-heading-copy">
      Garching is closest to the venue. Munich city options are further away but can still be convenient when located on the U6 line.
    </p>
  </div>

  <div class="stay-map-real" aria-label="Interactive accommodation map showing Munich, the U6 line, Garching, the Courtyard hotel, and the TUM-IAS venue">
    <svg class="stay-map-svg" viewBox="0 0 1200 600" preserveAspectRatio="xMidYMid meet" aria-hidden="true" focusable="false">
      <defs>
        <filter id="routeGlow" x="-50%" y="-50%" width="200%" height="200%">
          <feGaussianBlur stdDeviation="7" result="blur"/>
          <feMerge>
            <feMergeNode in="blur"/>
            <feMergeNode in="SourceGraphic"/>
          </feMerge>
        </filter>
      </defs>

      <rect width="1200" height="600" rx="34" fill="#020617"/>


      <g class="map-contours map-contours-marienplatz" aria-hidden="true">
        <path d="M179 430 C223 383 308 373 374 409 C436 443 468 514 438 570 C410 623 334 644 263 622 C193 600 145 546 148 487 C150 461 160 443 179 430Z"/>
        <path d="M209 447 C244 415 308 409 355 434 C400 458 423 511 402 553 C381 593 323 609 270 591 C218 574 183 534 185 491 C186 471 195 457 209 447Z"/>
        <path d="M238 466 C262 447 306 445 339 462 C370 479 386 516 371 544 C356 573 316 584 278 571 C242 559 217 530 219 500 C220 485 227 474 238 466Z"/>
      </g>

      <path class="map-u6-line map-u6-line-soft" d="M430 78 C390 92 368 112 360 142 C330 152 318 220 306 342 C300 402 292 496 275 535"/>
      <path class="map-u6-line" d="M430 78 C390 92 368 112 360 142 C330 152 318 220 306 342 C300 402 292 496 275 535"/>
      <g class="map-u6-logo" transform="translate(335 275)">
        <rect x="-28" y="-20" width="56" height="40" rx="10"/>
        <text x="0" y="8">U6</text>
      </g>

      <g class="map-stop map-stop-venue" transform="translate(430 78)">
        <circle r="18"/>
        <text class="map-mobile-label" x="-36" y="7">TUM Campus</text>
      </g>
      <g class="map-stop" transform="translate(306 342)">
        <circle r="11"/>
        <text class="map-mobile-label" x="-36" y="7">Nordfriedhof</text>
      </g>
      <g class="map-stop" transform="translate(300 402)">
        <circle r="11"/>
        <text class="map-mobile-label" x="-36" y="7">Münchner Freiheit</text>
      </g>
      <g class="map-stop" transform="translate(292 496)">
        <circle r="11"/>
        <text class="map-mobile-label" x="-36" y="7">Marienplatz</text>
      </g>
      <g class="map-stop map-stop-warning" transform="translate(275 535)">
        <circle r="16"/>
        <text class="map-mobile-label" x="-36" y="7">Sendlinger Tor</text>
      </g>
    </svg>
    <button class="map-area-bubble map-area-bubble-venue is-active" type="button" data-area="venue" aria-controls="stay-map-panel" aria-pressed="true">
      <span>★</span>
      TUM Campus
    </button>
    <button class="map-area-bubble map-area-bubble-nordfriedhof" type="button" data-area="nordfriedhof" aria-controls="stay-map-panel" aria-pressed="false">
      Nordfriedhof
    </button>
    <button class="map-area-bubble map-area-bubble-freiheit" type="button" data-area="freiheit" aria-controls="stay-map-panel" aria-pressed="false">
      Münchner Freiheit
    </button>
    <button class="map-area-bubble map-area-bubble-marienplatz" type="button" data-area="marienplatz" aria-controls="stay-map-panel" aria-pressed="false">
      Marienplatz
    </button>
    <button class="map-area-bubble map-area-bubble-sendlinger" type="button" data-area="sendlinger" aria-controls="stay-map-panel" aria-pressed="false">
      <span class="map-works-icon" aria-hidden="true">⚠</span>
      Sendlinger Tor
    </button>

    <aside id="stay-map-panel" class="stay-map-panel" aria-live="polite">
      <div class="stay-map-panel-photo stay-map-panel-photo-venue" role="img" aria-label="TUM campus and Garching research campus visual"></div>
      <div class="stay-map-panel-content">
        <p class="stay-map-panel-kicker">Selected area</p>
        <h3>TUM Campus Garching</h3>
        <p>The summer school venue and Courtyard by Marriott Munich Garching are located on the campus. This is the most convenient choice for participants who want the shortest commute.</p>
        <dl>
          <div><dt>Best for</dt><dd>Shortest commute</dd></div>
          <div><dt>Hotel focus</dt><dd>Courtyard + Stellaris</dd></div>
        </dl>
        <a class="stay-map-panel-link" href="#garching-hotels">View details</a>
      </div>
    </aside>
  </div>


</section>

<section id="tum-campus-hotels" class="accommodation-section area-detail-section">
  <div class="section-heading-row">
    <div>
      <p class="accommodation-eyebrow">Closest to the venue</p>
      <h2>TUM Campus Garching</h2>
    </div>
    <p class="section-heading-copy">
      Recommended for participants who want to stay directly on the research campus and keep the commute as short as possible.
    </p>
  </div>

  <div class="hotel-grid">
    <article class="hotel-card hotel-card-featured">
      <div class="hotel-photo hotel-photo-courtyard" role="img" aria-label="Courtyard by Marriott Munich Garching hotel exterior placeholder image">
        <span>Premium</span>
      </div>
      <div class="hotel-card-body">
        <div class="hotel-badge">Approx. 300 m · ~4 min walk to TUM-IAS</div>
        <h3>Courtyard by Marriott Munich Garching</h3>
        <p class="hotel-type">Closest option · Higher price range</p>
        <p>Modern business hotel on the Garching research campus, within a short walking distance of the TUM-IAS venue.</p>
        <div class="hotel-actions">
          <a href="https://www.marriott.com/de/hotels/muccg-courtyard-munich-garching/overview/" target="_blank" rel="noopener noreferrer">Website</a>
          <a href="https://www.google.com/maps/search/?api=1&query=Courtyard%20by%20Marriott%20Munich%20Garching" target="_blank" rel="noopener noreferrer">Maps</a>
        </div>
      </div>
    </article>

    <article class="hotel-card hotel-card-featured">
      <div class="hotel-photo hotel-photo-stellaris" role="img" aria-label="Stellaris Apartment Hotel exterior">
        <span>Serviced apartments</span>
      </div>
      <div class="hotel-card-body">
        <div class="hotel-badge">Approx. 300 m · ~4 min walk to TUM-IAS</div>
        <h3>Stellaris Apartment Hotel</h3>
        <p class="hotel-type">Campus option · Serviced apartments</p>
        <p>Apartment-style accommodation directly on TUM Campus Garching, close to the U6 station and the TUM-IAS venue.</p>
        <div class="hotel-actions">
          <a href="https://www.stellaris-apartment.de/en/home" target="_blank" rel="noopener noreferrer">Website</a>
          <a href="https://www.google.com/maps/search/?api=1&query=Stellaris%20Apartment%20Hotel%20Garching" target="_blank" rel="noopener noreferrer">Maps</a>
        </div>
      </div>
    </article>
  </div>
</section>


<section id="inner-munich-areas" class="accommodation-section area-detail-section">
  <div class="section-heading-row">
    <div>
      <p class="accommodation-eyebrow">U6 city areas</p>
      <h2>Inner Munich</h2>
    </div>
    <p class="section-heading-copy">
      These areas are further from the venue than Garching, but they remain convenient when located on the U6 line. For now, we describe the areas rather than listing specific hotels.
    </p>
  </div>

  <div class="area-grid">
    <article id="nordfriedhof-area" class="area-card">
      <span class="area-time">~14 min from venue</span>
      <h3>Nordfriedhof</h3>
      <p>A practical northern Munich area on the U6 corridor, close to several technology offices and business districts, including Microsoft, Amazon, and IBM locations.</p>
    </article>

    <article id="freiheit-area" class="area-card">
      <span class="area-time">~18 min from venue</span>
      <h3>Münchner Freiheit</h3>
      <p>A lively area with many evening options, restaurants, cafés, and bars. Good for participants who want easy dinners and social activities after lectures.</p>
    </article>

    <article id="marienplatz-area" class="area-card">
      <span class="area-time">~22 min from venue</span>
      <h3>Marienplatz</h3>
      <p>The historical city centre of Munich. Best for participants who prefer sightseeing, central hotels, and direct access to the old town.</p>
    </article>

    <article id="sendlinger-area" class="area-card area-card-warning">
      <span class="area-time">Further south</span>
      <h3>Sendlinger Tor and beyond</h3>
      <p>Sendlinger Tor marks the point after which we do not recommend booking accommodation because U6 service interruptions and replacement transport are currently occurring further south.</p>
    </article>
  </div>
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

.accommodation-map-section {
  margin: 3rem 0;
}

.stay-map-real {
  position: relative;
  min-height: 560px;
  overflow: hidden;
  border: 1px solid rgba(226,232,240,.9);
  border-radius: 32px;
  background: linear-gradient(135deg,#020617,#0f172a 54%,#1f2937);
  box-shadow: 0 28px 70px rgba(15,23,42,.22);
}

.stay-map-real::before {
  content: "";
  position: absolute;
  inset: 1rem;
  border: 1px solid rgba(255,255,255,.08);
  border-radius: 24px;
  pointer-events: none;
  z-index: 1;
}

.stay-map-svg {
  display: block;
  width: 100%;
  height: 560px;
}

.map-contours {
  fill: none;
  stroke: rgba(148, 163, 184, 0.18);
  stroke-width: 2;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.map-contours path:nth-child(2) {
  stroke: rgba(148, 163, 184, 0.24);
}

.map-contours path:nth-child(3) {
  stroke: rgba(251, 191, 36, 0.22);
}


.map-contours-marienplatz {
  filter: drop-shadow(0 0 18px rgba(56, 189, 248, 0.08));
}


.map-u6-line {
  fill: none;
  stroke-linecap: round;
}

.map-u6-line {
  fill: none;
  stroke: #0065bd;
  stroke-width: 13;
  stroke-linecap: round;
  filter: url(#routeGlow);
}

.map-u6-line-soft {
  fill: none;
  stroke: rgba(0,101,189,.28);
  stroke-width: 36;
  stroke-linecap: round;
  filter: none;
}

.map-u6-logo rect {
  fill: #0065bd;
  stroke: rgba(255,255,255,.72);
  stroke-width: 2;
  filter: url(#routeGlow);
}


.map-u6-logo text {
  fill: #fff;
  font-size: 20px;
  font-weight: 900;
  text-anchor: middle;
}


.map-stop circle {
  fill: #fff;
  stroke: #38bdf8;
  stroke-width: 6;
}

.map-stop-warning circle {
  stroke: #f59e0b;
}

.map-stop text {
  fill: rgba(255,255,255,.82);
  font-weight: 900;
}

.map-stop text {
  font-size: 18px;
  text-anchor: end;
}

.map-mobile-label {
  display: none;
}
.map-stop-venue circle {
  fill: #fbbf24;
  stroke: rgba(255,255,255,.9);
}

.map-area-bubble {
  position: absolute;
  z-index: 4;
  display: inline-flex;
  align-items: center;
  gap: .35rem;
  min-height: 34px;
  padding: .34rem .62rem;
  border: 1px solid rgba(255,255,255,.22);
  border-radius: 999px;
  background: rgba(15,23,42,.76);
  color: #fff;
  font-size: .76rem;
  font-weight: 900;
  letter-spacing: .02em;
  white-space: nowrap;
  min-width: 178px;
  transform: translate(-100%, -50%);
  cursor: pointer;
  box-shadow: 0 14px 34px rgba(2,6,23,.28);
  backdrop-filter: blur(14px);
  -webkit-backdrop-filter: blur(14px);
  transition: transform .18s ease, background .18s ease, border-color .18s ease, box-shadow .18s ease;
  justify-content: flex-end;
  margin-left: -18px;
}

.map-area-bubble span {
  color: #fbbf24;
}
.map-works-icon {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  width: 1.25rem;
  height: 1.25rem;
  border-radius: 999px;
  background: #f59e0b;
  color: #111827 !important;
  font-size: .78rem;
  font-weight: 900;
}

.map-area-bubble:hover,
.map-area-bubble:focus-visible,
.map-area-bubble.is-active {
  transform: translate(-100%, calc(-50% - 2px));
  border-color: rgba(251,191,36,.86);
  background: rgba(2,6,23,.94);
  box-shadow: 0 20px 48px rgba(2,6,23,.38);
}

.map-area-bubble:focus-visible {
  outline: 3px solid #f59e0b;
  outline-offset: 3px;
}

.map-area-bubble.is-active::after {
  content: "";
  position: absolute;
  right: -.38rem;
  top: 50%;
  width: .75rem;
  height: .75rem;
  background: #fbbf24;
  border-radius: 999px;
  transform: translateY(-50%);
  box-shadow: 0 0 0 6px rgba(251,191,36,.16);
}

.map-area-bubble-venue { left: 35.833%; top: 13%; }
.map-area-bubble-nordfriedhof { left: 25.5%; top: 57%; }
.map-area-bubble-freiheit { left: 25%; top: 67%; }
.map-area-bubble-marienplatz { left: 24.333%; top: 82.667%; }
.map-area-bubble-sendlinger { left: 22.917%; top: 89.167%; }

.stay-map-panel {
  position: absolute;
  top: 1.25rem;
  right: 1.25rem;
  bottom: 1.25rem;
  z-index: 5;
  width: min(360px, 36%);
  overflow: hidden;
  border: 1px solid rgba(255,255,255,.18);
  border-radius: 24px;
  background: rgba(255,255,255,.95);
  color: #111827;
  box-shadow: 0 28px 70px rgba(2,6,23,.32);
  backdrop-filter: blur(18px);
  -webkit-backdrop-filter: blur(18px);
}

.stay-map-panel-photo {
  min-height: 110px;
  background-image:
    linear-gradient(180deg, rgba(15,23,42,.08), rgba(15,23,42,.64)),
    url("https://images.unsplash.com/photo-1562774053-701939374585?auto=format&fit=crop&w=1200&q=80");
  background-size: cover;
  background-position: center;
  border-radius: 24px 24px 0 0;
}

.stay-map-panel-content {
  padding: .85rem;
}

.stay-map-panel-link {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  min-height: 36px;
  margin-top: .65rem;
  padding: .48rem .85rem;
  border-radius: 999px;
  background: #111827;
  color: #fff;
  font-size: .8rem;
  font-weight: 900;
  text-decoration: none;
}

.stay-map-panel-link::after {
  content: "↓";
  margin-left: .45rem;
}

.stay-map-panel-link:focus-visible {
  outline: 3px solid #f59e0b;
  outline-offset: 3px;
}

.area-detail-section,
.area-card {
  scroll-margin-top: 110px;
}

.stay-map-panel-kicker {
  margin: 0 0 .35rem;
  color: #92400e;
  font-size: .72rem;
  font-weight: 900;
  letter-spacing: .12em;
  text-transform: uppercase;
}

.stay-map-panel h3 {
  margin: 0 0 .5rem;
  font-size: 1.08rem;
  letter-spacing: -.03em;
}

.stay-map-panel p {
  margin: 0;
  color: #374151;
  font-size: .88rem;
  line-height: 1.45;
}

.stay-map-panel dl {
  display: grid;
  gap: .38rem;
  margin: .65rem 0 0;
}

.stay-map-panel dl div {
  display: grid;
  gap: .1rem;
  padding: .5rem .6rem;
  border-radius: 14px;
  background: #f8fafc;
  border: 1px solid #e5e7eb;
}

.stay-map-panel dt {
  color: #6b7280;
  font-size: .72rem;
  font-weight: 900;
  letter-spacing: .08em;
  text-transform: uppercase;
}

.stay-map-panel dd {
  margin: 0;
  color: #111827;
  font-weight: 800;
}

.stay-map-panel-photo-venue {
  background-image:
    linear-gradient(180deg, rgba(15,23,42,.08), rgba(15,23,42,.64)),
    url("{{ '/assets/img/hero_garching.webp' | relative_url }}");
}

.stay-map-panel-photo-garching {
  background-image:
    linear-gradient(180deg, rgba(15,23,42,.08), rgba(15,23,42,.64)),
    url("https://images.unsplash.com/photo-1494526585095-c41746248156?auto=format&fit=crop&w=1200&q=80");
}

.stay-map-panel-photo-nordfriedhof {
  background-image:
    linear-gradient(180deg, rgba(15,23,42,.08), rgba(15,23,42,.64)),
    url("{{ '/assets/img/attractions/03-higlight-towers.jpg.webp' | relative_url }}");
}

.stay-map-panel-photo-freiheit {
  background-image:
    linear-gradient(180deg, rgba(15,23,42,.08), rgba(15,23,42,.64)),
    url("https://images.unsplash.com/photo-1514933651103-005eec06c04b?auto=format&fit=crop&w=1200&q=80");
}

.stay-map-panel-photo-marienplatz {
  background-image:
    linear-gradient(180deg, rgba(15,23,42,.08), rgba(15,23,42,.64)),
    url("https://images.unsplash.com/photo-1595867818082-083862f3d630?auto=format&fit=crop&w=1200&q=80");
}

.stay-map-panel-photo-sendlinger {
  background-image:
    linear-gradient(180deg, rgba(15,23,42,.08), rgba(15,23,42,.64)),
    url("{{ '/assets/img/attractions/36637939-bahn-an-einer-haltestelle-in-muenchen-2udcnx11qnea.jpg' | relative_url }}");
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

.area-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit,minmax(240px,1fr));
  gap: 1rem;
}

.area-card {
  padding: 1.35rem;
  border: 1px solid #e5e7eb;
  border-radius: 24px;
  background: linear-gradient(180deg,#fff,#f8fafc);
  box-shadow: 0 14px 34px rgba(15,23,42,.07);
}

.area-card-warning {
  border-color: #f59e0b;
  background: #fffbeb;
}

.area-time {
  display: inline-flex;
  margin-bottom: .75rem;
  padding: .38rem .7rem;
  border-radius: 999px;
  background: #111827;
  color: #fff;
  font-size: .75rem;
  font-weight: 900;
}

.area-card h3 {
  margin: 0 0 .5rem;
}

.area-card p {
  margin: 0;
  color: #374151;
  line-height: 1.65;
}

.area-card-warning p,
.area-card-warning h3 {
  color: #92400e;
}

.hotel-card {
  position: relative;
  overflow: hidden;
  border-radius: 24px;
  border: 1px solid #e5e7eb;
  background: linear-gradient(180deg,#fff,#f8fafc);
  box-shadow: 0 14px 34px rgba(15,23,42,.07);
  transition: transform .18s ease, box-shadow .18s ease, border-color .18s ease;
}

.hotel-card:hover {
  transform: translateY(-4px);
  border-color: #cbd5e1;
  box-shadow: 0 24px 58px rgba(15,23,42,.12);
}

.hotel-photo {
  position: relative;
  min-height: 170px;
  background:
    radial-gradient(circle at 18% 18%, rgba(245,158,11,.22), transparent 28%),
    radial-gradient(circle at 88% 20%, rgba(14,165,233,.2), transparent 28%),
    linear-gradient(135deg,#111827,#374151);
}

.hotel-photo::after {
  content: "";
  position: absolute;
  inset: 0;
  background: linear-gradient(180deg, transparent 28%, rgba(15,23,42,.72));
}

.hotel-photo span {
  position: absolute;
  left: 1rem;
  bottom: 1rem;
  z-index: 1;
  color: #fff;
  font-size: .8rem;
  font-weight: 900;
  letter-spacing: .12em;
  text-transform: uppercase;
}

.hotel-photo-courtyard {
  background-image:
    linear-gradient(180deg, rgba(15,23,42,.08), rgba(15,23,42,.72)),
    url("https://cache.marriott.com/content/dam/marriott-renditions/MUCCG/muccg-exterior-2777-hor-feat.jpg?downsize=1920px:*&interpolation=progressive-bilinear&output-quality=70");
  background-size: cover;
  background-position: center;
}

.hotel-photo.hotel-photo-stellaris {
  background-image:
    linear-gradient(180deg, rgba(15,23,42,.08), rgba(15,23,42,.72)),
    url("{{ '/assets/img/attractions/terrasse_1920x1000.jpg.webp' | relative_url }}");
  background-size: cover;
  background-position: center;
}

.hotel-photo-budget {
  background-image:
    linear-gradient(180deg, rgba(15,23,42,.08), rgba(15,23,42,.72)),
    url("https://images.unsplash.com/photo-1564501049412-61c2a3083791?auto=format&fit=crop&w=1200&q=80");
  background-size: cover;
  background-position: center;
}

.hotel-photo-balanced {
  background-image:
    linear-gradient(180deg, rgba(15,23,42,.08), rgba(15,23,42,.72)),
    url("https://images.unsplash.com/photo-1551882547-ff40c63fe5fa?auto=format&fit=crop&w=1200&q=80");
  background-size: cover;
  background-position: center;
}

.hotel-photo-munich-premium {
  background-image:
    linear-gradient(180deg, rgba(15,23,42,.08), rgba(15,23,42,.72)),
    url("https://images.unsplash.com/photo-1590490360182-c33d57733427?auto=format&fit=crop&w=1200&q=80");
  background-size: cover;
  background-position: center;
}

.hotel-photo-munich-balanced {
  background-image:
    linear-gradient(180deg, rgba(15,23,42,.08), rgba(15,23,42,.72)),
    url("https://images.unsplash.com/photo-1518005020951-eccb494ad742?auto=format&fit=crop&w=1200&q=80");
  background-size: cover;
  background-position: center;
}

.hotel-photo-munich-budget {
  background-image:
    linear-gradient(180deg, rgba(15,23,42,.08), rgba(15,23,42,.72)),
    url("https://images.unsplash.com/photo-1563911302283-d2bc129e7570?auto=format&fit=crop&w=1200&q=80");
  background-size: cover;
  background-position: center;
}

.hotel-card-body {
  padding: 1.25rem;
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

.hotel-actions {
  display: flex;
  flex-wrap: wrap;
  gap: .55rem;
  margin-top: 1rem;
}

.hotel-actions a,
.hotel-actions span {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  min-height: 38px;
  padding: .44rem .8rem;
  border-radius: 999px;
  font-size: .78rem;
  font-weight: 900;
  text-decoration: none;
}

.hotel-actions a:first-child {
  background: #111827;
  color: #fff;
}

.hotel-actions a:last-child {
  border: 1px solid #d1d5db;
  background: #fff;
  color: #111827;
}

.hotel-actions a:focus-visible {
  outline: 3px solid #f59e0b;
  outline-offset: 3px;
}

.hotel-actions-disabled span {
  border: 1px solid #e5e7eb;
  background: #f8fafc;
  color: #6b7280;
}


@media (max-width:760px) {
  .section-heading-row {
    display:block;
  }

  .section-heading-copy {
    margin-top:.75rem;
  }

  .stay-map-real {
    display: block;
    min-height: 0;
    padding: .85rem;
    overflow: hidden;
  }

  .stay-map-real::before {
    inset: .6rem;
    width: auto;
    border-radius: 22px;
  }

  .stay-map-svg {
    display: block;
    width: 100%;
    max-width: none;
    height: 440px;
    border-radius: 20px;
    background: #020617;
  }

  .map-mobile-label {
    display: block;
    fill: rgba(255,255,255,.9);
    font-size: 28px;
    font-weight: 900;
    text-anchor: end;
  }

  .map-contours {
    stroke-width: 2.8;
  }

  .map-u6-line {
    stroke-width: 16;
  }

  .map-u6-line-soft {
    stroke-width: 42;
  }

  .map-area-bubble {
    position: relative;
    left: auto;
    top: auto;
    z-index: 6;
    width: auto;
    min-width: 0;
    max-width: none;
    min-height: 42px;
    margin: .85rem .35rem 0 0;
    padding: .58rem .75rem;
    white-space: normal;
    justify-content: flex-start;
    transform: none;
    font-size: .78rem;
  }

  .map-area-bubble:hover,
  .map-area-bubble:focus-visible,
  .map-area-bubble.is-active {
    transform: translateY(-1px);
  }

  .map-area-bubble.is-active::after {
    display: none;
  }

  .map-area-bubble.is-active {
    box-shadow: inset 0 0 0 2px rgba(251,191,36,.72), 0 14px 34px rgba(2,6,23,.28);
  }

  .map-area-bubble-venue,
  .map-area-bubble-nordfriedhof,
  .map-area-bubble-freiheit,
  .map-area-bubble-marienplatz,
  .map-area-bubble-sendlinger {
    left: auto;
    top: auto;
  }

  .stay-map-panel {
    position: relative;
    top: auto;
    right: auto;
    bottom: auto;
    width: 100%;
    min-width: 0;
    margin: 1rem 0 0;
    max-height: none;
    overflow: hidden;
  }

  .stay-map-panel-photo {
    min-height: 150px;
  }
}

</style>

<script>
document.addEventListener('DOMContentLoaded', function () {
  var panel = document.getElementById('stay-map-panel');
  var buttons = document.querySelectorAll('.map-area-bubble[data-area]');
  if (!panel || !buttons.length) return;

  var mapSvg = document.querySelector('.stay-map-svg');
  var mobileQuery = window.matchMedia('(max-width: 760px)');

  function updateMapViewBox() {
    if (!mapSvg) return;
    if (mobileQuery.matches) {
      mapSvg.setAttribute('viewBox', '85 35 530 535');
      mapSvg.setAttribute('preserveAspectRatio', 'xMidYMid meet');
    } else {
      mapSvg.setAttribute('viewBox', '0 0 1200 600');
      mapSvg.setAttribute('preserveAspectRatio', 'xMidYMid meet');
    }
  }

  updateMapViewBox();
  if (mobileQuery.addEventListener) {
    mobileQuery.addEventListener('change', updateMapViewBox);
  } else if (mobileQuery.addListener) {
    mobileQuery.addListener(updateMapViewBox);
  }

  var photo = panel.querySelector('.stay-map-panel-photo');
  var kicker = panel.querySelector('.stay-map-panel-kicker');
  var title = panel.querySelector('h3');
  var text = panel.querySelector('p:not(.stay-map-panel-kicker)');
  var details = panel.querySelector('dl');
  var detailLink = panel.querySelector('.stay-map-panel-link');

  var areas = {
    venue: {
      title: 'TUM Campus Garching',
      text: 'The summer school venue and Courtyard by Marriott Munich Garching are located on the campus. This is the most convenient choice for participants who want the shortest commute.',
      photo: 'stay-map-panel-photo-venue',
      link: '#tum-campus-hotels',
      facts: [['Best for', 'Shortest commute'], ['Hotel focus', 'Courtyard + Stellaris']]
    },
    nordfriedhof: {
      title: 'Nordfriedhof',
      text: 'A practical northern Munich area on the U6 corridor, close to several technology offices and business districts, including Microsoft, Amazon, and IBM locations.',
      photo: 'stay-map-panel-photo-nordfriedhof',
      link: '#nordfriedhof-area',
      facts: [['Best for', 'City stay, close to campus']]
    },
    freiheit: {
      title: 'Münchner Freiheit',
      text: 'A lively area with restaurants, cafés, bars, and evening options. Good for participants who want social activities after lectures.',
      photo: 'stay-map-panel-photo-freiheit',
      link: '#freiheit-area',
      facts: [['Best for', 'Evening life']]
    },
    marienplatz: {
      title: 'Marienplatz',
      text: 'The historical city centre of Munich. Best for participants who prefer sightseeing, central hotels, and direct access to the old town.',
      photo: 'stay-map-panel-photo-marienplatz',
      link: '#marienplatz-area',
      facts: [['Best for', 'City centre and sightseeing']]
    },
    sendlinger: {
      title: 'Sendlinger Tor and beyond',
      text: 'This marks the point after which we do not recommend booking accommodation because U6 service interruptions and replacement transport are currently occurring further south.',
      photo: 'stay-map-panel-photo-sendlinger',
      link: '#sendlinger-area',
      facts: [['Recommendation', 'Avoid further south'], ['Reason', 'Active U6 interruptions']]
    }
  };

  function render(areaKey) {
    var area = areas[areaKey];
    if (!area) return;
    title.textContent = area.title;
    text.textContent = area.text;
    kicker.textContent = 'Selected area';
    photo.className = 'stay-map-panel-photo ' + area.photo;
    if (detailLink) detailLink.setAttribute('href', area.link || '#garching-hotels');
    details.innerHTML = area.facts.map(function (fact) {
      return '<div><dt>' + fact[0] + '</dt><dd>' + fact[1] + '</dd></div>';
    }).join('');
  }

  buttons.forEach(function (button) {
    button.addEventListener('click', function () {
      buttons.forEach(function (other) {
        other.classList.remove('is-active');
        other.setAttribute('aria-pressed', 'false');
      });
      button.classList.add('is-active');
      button.setAttribute('aria-pressed', 'true');
      render(button.getAttribute('data-area'));
    });
  });
});
</script>
