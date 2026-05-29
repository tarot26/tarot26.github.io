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
      A visual guide to the best accommodation zones along the U6 corridor, from the campus itself to selected city-centre areas.
    </p>
  </div>

  <div class="stay-map-real" aria-label="Interactive accommodation map showing Munich, the U6 line, Garching, the Courtyard hotel, and the TUM-IAS venue">
    <div class="map-compass" aria-hidden="true">
      <span>N</span>
    </div>
    <svg class="stay-map-svg" viewBox="0 0 1200 600" preserveAspectRatio="xMidYMid meet" aria-hidden="true" focusable="false">
      <defs>
        <filter id="routeGlow" x="-50%" y="-50%" width="200%" height="200%">
          <feGaussianBlur stdDeviation="7" result="blur"/>
          <feMerge>
            <feMergeNode in="blur"/>
            <feMergeNode in="SourceGraphic"/>
          </feMerge>
        </filter>
        <filter id="pinShadow" x="-80%" y="-80%" width="260%" height="260%">
          <feDropShadow dx="0" dy="10" stdDeviation="10" flood-color="rgba(2,6,23,.45)"/>
        </filter>
        <linearGradient id="u6Gradient" x1="0" y1="0" x2="0" y2="1">
          <stop offset="0%" stop-color="#38bdf8"/>
          <stop offset="45%" stop-color="#0065bd"/>
          <stop offset="100%" stop-color="#7dd3fc"/>
        </linearGradient>
        <radialGradient id="mapGoldGlow" cx="38%" cy="13%" r="44%">
          <stop offset="0%" stop-color="rgba(251,191,36,.22)"/>
          <stop offset="58%" stop-color="rgba(251,191,36,.06)"/>
          <stop offset="100%" stop-color="rgba(251,191,36,0)"/>
        </radialGradient>
        <radialGradient id="mapCityGlow" cx="26%" cy="82%" r="48%">
          <stop offset="0%" stop-color="rgba(56,189,248,.18)"/>
          <stop offset="62%" stop-color="rgba(56,189,248,.06)"/>
          <stop offset="100%" stop-color="rgba(56,189,248,0)"/>
        </radialGradient>
        <linearGradient id="mapPanelGradient" x1="0" y1="0" x2="1" y2="1">
          <stop offset="0%" stop-color="#020617"/>
          <stop offset="48%" stop-color="#0f172a"/>
          <stop offset="100%" stop-color="#111827"/>
        </linearGradient>
        <pattern id="mapFineGrid" width="44" height="44" patternUnits="userSpaceOnUse">
          <path d="M44 0H0V44" fill="none" stroke="rgba(255,255,255,.045)" stroke-width="1"/>
        </pattern>
      </defs>

      <rect width="1200" height="600" rx="34" fill="#0f172a"/>
      <path class="map-bg-arc map-bg-arc-one" d="M-80 520 C120 438 310 450 510 520 C735 600 945 575 1280 438"/>
      <path class="map-bg-arc map-bg-arc-two" d="M-90 112 C120 190 330 170 540 88 C760 4 980 42 1290 154"/>
      <path class="map-bg-arc map-bg-arc-three" d="M-70 318 C135 245 340 265 552 330 C785 402 1000 384 1270 286"/>
      <path class="map-bg-arc map-bg-arc-four" d="M-80 44 C165 92 340 48 545 18 C770 -16 980 8 1280 76"/>
      <path class="map-bg-arc map-bg-arc-five" d="M-90 586 C155 548 355 570 565 622 C785 676 1010 640 1290 540"/>

      
      

      

      <text class="map-bg-label map-bg-label-city" x="313" y="540">CITY</text>
      <text class="map-bg-label map-bg-label-city" x="313" y="560">CENTER</text>

      <g class="map-english-garden" transform="translate(0 -45)" aria-hidden="true">
        <path d="M396 210 C428 222 454 264 458 318 C462 378 442 440 414 462 C386 484 362 454 350 404 C338 344 350 232 396 210Z"/>
      </g>
      <text class="map-bg-label map-bg-label-garden" x="360" y="285">ENGLISH</text>
      <text class="map-bg-label map-bg-label-garden" x="360" y="305">GARDEN</text>


      <g class="map-contours map-contours-marienplatz" aria-hidden="true">
        <path d="M209 447 C244 415 308 409 355 434 C400 458 423 511 402 553 C381 593 323 609 270 591 C218 574 183 534 185 491 C186 471 195 457 209 447Z"/>
      </g>

      <path class="map-u6-line map-u6-line-soft" d="M430 78 C390 92 368 112 360 142 C330 152 318 220 306 342 C300 402 292 496 275 535"/>
      <path class="map-u6-line" d="M430 78 C390 92 368 112 360 142 C330 152 318 220 306 342 C300 402 292 496 275 535"/>
      <path class="map-u6-highlight" d="M430 78 C390 92 368 112 360 142 C330 152 318 220 306 342 C300 402 292 496 275 535"/>
      <g class="map-u6-logo" transform="translate(310 275)">
        <rect x="-28" y="-20" width="56" height="40" rx="10"/>
        <text x="0" y="8">U6</text>
      </g>

      <g class="map-stop map-stop-venue is-map-selected" data-area="venue" transform="translate(430 78)">
        <circle class="map-stop-halo" r="30"/>
        <circle r="14"/>
        <path class="map-star" d="M0 -7 L2.2 -2.2 L7 -2.2 L3.2 .9 L4.5 6.2 L0 3.2 L-4.5 6.2 L-3.2 .9 L-7 -2.2 L-2.2 -2.2 Z"/>
        <text class="map-mobile-label" x="-12" y="7">TUM Campus</text>
      </g>
      <g class="map-stop map-stop-garching" data-area="garching" transform="translate(360 142)">
        <circle r="10"/>
        <text class="map-mobile-label" x="-12" y="7">Garching</text>
      </g>
      <g class="map-stop" data-area="nordfriedhof" transform="translate(306 342)">
        <circle r="11"/>
        <text class="map-mobile-label" x="-12" y="7">Nordfriedhof</text>
      </g>
      <g class="map-stop" data-area="freiheit" transform="translate(300 402)">
        <circle r="11"/>
        <text class="map-mobile-label" x="-12" y="7">Münchner Freiheit</text>
      </g>
      <g class="map-stop" data-area="marienplatz" transform="translate(289 493)">
        <circle r="11"/>
        <text class="map-mobile-label" x="-7" y="7">Marienplatz</text>
      </g>
      <g class="map-stop map-stop-warning" data-area="sendlinger" transform="translate(275 535)">
        <circle class="map-stop-halo map-stop-halo-warning" r="32"/>
        <circle r="16"/>
        <text class="map-warning-mark" x="0" y="6">!</text>
        <text class="map-mobile-label" x="-12" y="7">Sendlinger Tor</text>
      </g>
    </svg>
    <div class="map-area-buttons" aria-label="Accommodation areas">
      <button class="map-area-bubble map-area-bubble-venue is-active" type="button" data-area="venue" aria-controls="stay-map-panel" aria-pressed="true">
        <span>★</span>
        TUM Campus
      </button>
      <button class="map-area-bubble map-area-bubble-garching" type="button" data-area="garching" aria-controls="stay-map-panel" aria-pressed="false">

      Garching

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
    </div>

    <aside id="stay-map-panel" class="stay-map-panel" aria-live="polite">
      <div class="stay-map-panel-photo stay-map-panel-photo-venue" role="img" aria-label="TUM campus and Garching research campus visual"></div>
      <div class="stay-map-panel-content">
        <p class="stay-map-panel-kicker">Selected area</p>
        <h3>TUM Campus Garching</h3>
        <p>The summer school venue and the closest hotels are located directly on the research campus. Choose this area for the most effortless stay.</p>
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
<section id="garching-area" class="accommodation-section area-detail-section">
  <div class="section-heading-row">
    <div>
      <p class="accommodation-eyebrow">Closest town</p>
      <h2>Garching</h2>
    </div>
    <p class="section-heading-copy">
      A convenient option just south of the research campus, with direct U6 access to both TUM Campus Garching and Munich city centre.
    </p>
  </div>

  <div class="hotel-grid">
    <article class="hotel-card">
      <div class="hotel-photo hotel-photo-ibis-garching" role="img" aria-label="ibis München Garching hotel image">
        <span>Budget</span>
      </div>
      <div class="hotel-card-body">
        <div class="hotel-badge">Approx. 2 U6 stops · ~15 min to campus</div>
        <h3>ibis München Garching</h3>
        <p class="hotel-type">Budget-friendly · Practical stay</p>
        <p>One of the budget options in Garching: simple, practical, and well suited for participants who want to keep accommodation costs lower while staying on the U6 corridor.</p>
        <div class="hotel-actions">
          <a href="https://all.accor.com/hotel/3679/index.en.shtml" target="_blank" rel="noopener noreferrer">Website</a>
          <a href="https://www.google.com/maps/search/?api=1&query=ibis%20M%C3%BCnchen%20Garching" target="_blank" rel="noopener noreferrer">Maps</a>
        </div>
      </div>
    </article>

    <article class="hotel-card">
      <div class="hotel-photo hotel-photo-motel-one-garching" role="img" aria-label="Motel One München-Garching hotel image">
        <span>Design hotel</span>
      </div>
      <div class="hotel-card-body">
        <div class="hotel-badge">Approx. 2 U6 stops · ~15 min to campus</div>
        <h3>Motel One München-Garching</h3>
        <p class="hotel-type">Design hotel · Good value</p>
        <p>A more polished design-hotel option near the U6: still practical for the campus, but with a stronger style and comfort focus than the budget hotels.</p>
        <div class="hotel-actions">
          <a href="https://www.motel-one.com/de/hotels/muenchen/hotel-muenchen-garching/" target="_blank" rel="noopener noreferrer">Website</a>
          <a href="https://www.google.com/maps/search/?api=1&query=Motel%20One%20M%C3%BCnchen-Garching" target="_blank" rel="noopener noreferrer">Maps</a>
        </div>
      </div>
    </article>

    <article class="hotel-card">
      <div class="hotel-photo hotel-photo-bb-garching" role="img" aria-label="B&B HOTEL Munich-Garching hotel image">
        <span>Simple stay</span>
      </div>
      <div class="hotel-card-body">
        <div class="hotel-badge">Approx. 2 U6 stops · ~15 min to campus</div>
        <h3>B&amp;B HOTEL Munich-Garching</h3>
        <p class="hotel-type">Affordable · Modern rooms</p>
        <p>Another clear budget choice in Garching, offering straightforward modern rooms for participants who mainly need an affordable, reliable base near the U6.</p>
        <div class="hotel-actions">
          <a href="https://www.hotel-bb.com/en/hotel/muenchen-garching" target="_blank" rel="noopener noreferrer">Website</a>
          <a href="https://www.google.com/maps/search/?api=1&query=B%26B%20HOTEL%20Munich-Garching" target="_blank" rel="noopener noreferrer">Maps</a>
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
  position: relative;
  overflow: hidden;
  margin: 0 0 2rem;
  padding: clamp(2.2rem,5vw,4.4rem);
  border-radius: 34px;
  background:
    radial-gradient(circle at 82% 20%, rgba(251,191,36,.32), transparent 26%),
    radial-gradient(circle at 14% 85%, rgba(56,189,248,.24), transparent 34%),
    linear-gradient(135deg,#020617,#111827 58%,#334155);
  color: white;
  box-shadow: 0 30px 80px rgba(15,23,42,.24);
}

.accommodation-hero::before {
  content: "";
  position: absolute;
  inset: 1rem;
  border: 1px solid rgba(255,255,255,.12);
  border-radius: 26px;
  pointer-events: none;
}

.accommodation-hero::after {
  content: "";
  position: absolute;
  right: -8rem;
  bottom: -10rem;
  width: 26rem;
  height: 26rem;
  border-radius: 999px;
  background: rgba(255,255,255,.07);
  filter: blur(2px);
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
  min-height: 0;
  overflow: hidden;
  border: 1px solid rgba(226,232,240,.85);
  border-radius: 36px;
  background: #0f172a;
  box-shadow: 0 36px 90px rgba(15,23,42,.3);
  isolation: isolate;
}

.map-area-buttons {
  position: relative;
  z-index: 9;
  display: flex;
  flex-wrap: wrap;
  justify-content: flex-start;
  align-items: flex-start;
  gap: .65rem;
  max-width: calc(63% - 2rem);
  padding: 0 1.25rem 1.25rem;
}

.stay-map-real::before {
  content: "";
  position: absolute;
  inset: 1rem;
  border: 1px solid rgba(255,255,255,.1);
  border-radius: 28px;
  pointer-events: none;
  z-index: 2;
}

.stay-map-real::after {
  content: none;
}


.map-compass {
  position: absolute;
  left: 1.55rem;
  top: 1.55rem;
  z-index: 6;
  width: 48px;
  height: 48px;
  display: grid;
  place-items: center;
  border: 1px solid rgba(255,255,255,.18);
  border-radius: 999px;
  background: rgba(2,6,23,.48);
  color: rgba(255,255,255,.88);
  font-size: .72rem;
  font-weight: 900;
  letter-spacing: .12em;
  box-shadow: inset 0 0 0 1px rgba(255,255,255,.05), 0 14px 36px rgba(2,6,23,.26);
  backdrop-filter: blur(14px);
  -webkit-backdrop-filter: blur(14px);
}

.map-compass span {
  transform: translateY(8px);
}

.map-compass::before {
  content: "";
  position: absolute;
  top: 6px;
  width: 0;
  height: 0;
  border-left: 5px solid transparent;
  border-right: 5px solid transparent;
  border-bottom: 11px solid #fbbf24;
}

.map-route-caption {
  position: absolute;
  left: 1.55rem;
  bottom: 1.55rem;
  z-index: 6;
  display: grid;
  gap: .18rem;
  padding: .75rem .9rem;
  border: 1px solid rgba(255,255,255,.16);
  border-radius: 18px;
  background: rgba(2,6,23,.58);
  color: #fff;
  box-shadow: 0 16px 42px rgba(2,6,23,.26);
  backdrop-filter: blur(16px);
  -webkit-backdrop-filter: blur(16px);
}

.map-route-caption span {
  color: #93c5fd;
  font-size: .68rem;
  font-weight: 900;
  letter-spacing: .14em;
  text-transform: uppercase;
}

.map-route-caption strong {
  font-size: .9rem;
}

.stay-map-svg {
  position: relative;
  z-index: 3;
  display: block;
  width: 100%;
  height: 600px;
}

.map-bg-arc {
  fill: none;
  stroke: rgba(255,255,255,.09);
  stroke-width: 2;
  stroke-linecap: round;
  stroke-dasharray: 10 16;
}

.map-bg-arc-two {
  opacity: .7;
}

.map-bg-label {
  fill: rgba(255,255,255,.15);
  font-size: 18px;
  font-weight: 950;
  letter-spacing: .2em;
}

.map-bg-label-campus {
  fill: rgba(251,191,36,.22);
}

.map-bg-label-campus-small {
  fill: rgba(251,191,36,.18);
  font-size: 13px;
  letter-spacing: .24em;
}


.map-bg-label-city {
  fill: rgba(56,189,248,.2);
}



.map-bg-label-garden {
  fill: rgba(134,239,172,.22);
  letter-spacing: .12em;
}





.map-english-garden path:first-child {
  fill: rgba(34,197,94,.12);
  stroke: rgba(134,239,172,.18);
  stroke-width: 2;
}

.map-english-garden path:last-child {
  fill: rgba(34,197,94,.08);
  stroke: rgba(134,239,172,.16);
  stroke-width: 2;
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


.map-u6-line,
.map-u6-line-soft,
.map-u6-highlight {
  fill: none;
  stroke-linecap: round;
}

.map-u6-line {
  stroke: url(#u6Gradient);
  stroke-width: 14;
  filter: url(#routeGlow);
}

.map-u6-highlight {
  stroke: rgba(255,255,255,.36);
  stroke-width: 3;
  stroke-dasharray: 1 28;
  stroke-linecap: round;
}

.map-u6-line-soft {
  stroke: rgba(56,189,248,.22);
  stroke-width: 44;
  filter: none;
}

.map-u6-logo rect {
  fill: #0065bd;
  stroke: rgba(255,255,255,.78);
  stroke-width: 2;
  filter: url(#pinShadow);
}


.map-u6-logo text {
  fill: #fff;
  font-size: 20px;
  font-weight: 900;
  text-anchor: middle;
}


.map-stop circle:not(.map-stop-halo) {
  fill: #fff;
  stroke: #38bdf8;
  stroke-width: 6;
  filter: url(#pinShadow);
}

.map-stop-warning circle:not(.map-stop-halo) {
  stroke: #f59e0b;
}

.map-stop-halo {
  fill: rgba(251,191,36,.15);
  stroke: rgba(251,191,36,.22);
  stroke-width: 1;
  filter: none;
}

.map-stop-halo-warning {
  fill: rgba(245,158,11,.12);
  stroke: rgba(245,158,11,.2);
}

.map-star {
  fill: #111827;
  pointer-events: none;
}

.map-warning-mark {
  fill: #111827;
  font-size: 18px;
  font-weight: 950;
  text-anchor: middle;
  pointer-events: none;
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
  display: block;
  fill: rgba(255,255,255,.78);
  font-size: 15px;
  font-weight: 900;
  text-anchor: end;
  transform: translateX(-12px);
}

.map-stop-venue .map-mobile-label {
  transform: translateX(-26px);
}

.map-stop-warning .map-mobile-label {
  transform: translateX(-16px);
}
.map-stop.is-map-selected circle:not(.map-stop-halo) {
  fill: #fbbf24;
  stroke: rgba(255,255,255,.9);
}

.map-stop.is-map-selected .map-mobile-label {
  fill: #fbbf24;
}

.map-area-bubble {
  position: relative;
  z-index: 7;
  display: inline-flex;
  align-items: center;
  justify-content: center;
  gap: .35rem;
  min-height: 42px;
  width: auto;
  min-width: 175px;
  padding: .58rem .9rem;
  border: 1px solid rgba(255,255,255,.2);
  border-radius: 999px;
  background: rgba(15,23,42,.72);
  color: #fff;
  font-size: .78rem;
  font-weight: 950;
  letter-spacing: .02em;
  white-space: normal;
  cursor: pointer;
  box-shadow: 0 16px 38px rgba(2,6,23,.3);
  backdrop-filter: blur(16px);
  -webkit-backdrop-filter: blur(16px);
  transition: transform .18s ease, background .18s ease, border-color .18s ease, box-shadow .18s ease;
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
  transform: translateY(-2px);
  border-color: rgba(251,191,36,.9);
  background: rgba(2,6,23,.96);
  box-shadow: 0 22px 54px rgba(2,6,23,.42), inset 0 0 0 1px rgba(255,255,255,.08);
}

.map-area-bubble:focus-visible {
  outline: 3px solid #f59e0b;
  outline-offset: 3px;
}



.stay-map-panel {
  position: absolute;
  top: 1.25rem;
  right: 1.25rem;
  bottom: 1.25rem;
  z-index: 8;
  width: min(390px, 37%);
  overflow: hidden;
  border: 1px solid rgba(255,255,255,.2);
  border-radius: 28px;
  background: rgba(255,255,255,.95);
  color: #111827;
  box-shadow: 0 34px 84px rgba(2,6,23,.36);
  backdrop-filter: blur(22px);
  -webkit-backdrop-filter: blur(22px);
}

.stay-map-panel-photo {
  min-height: 150px;
  background-image:
    linear-gradient(180deg, rgba(15,23,42,.04), rgba(15,23,42,.68)),
    url("https://images.unsplash.com/photo-1562774053-701939374585?auto=format&fit=crop&w=1200&q=80");
  background-size: cover;
  background-position: center;
  border-radius: 28px 28px 0 0;
}

.stay-map-panel-content {
  padding: 1rem;
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
  margin: 0 0 .55rem;
  font-size: 1.22rem;
  letter-spacing: -.04em;
}

.stay-map-panel p {
  margin: 0;
  color: #374151;
  font-size: .92rem;
  line-height: 1.52;
}

.stay-map-panel dl {
  display: grid;
  gap: .38rem;
  margin: .65rem 0 0;
}

.stay-map-panel dl div {
  display: grid;
  gap: .1rem;
  padding: .58rem .65rem;
  border-radius: 16px;
  background: linear-gradient(180deg,#f8fafc,#fff);
  border: 1px solid #e5e7eb;
  box-shadow: 0 8px 22px rgba(15,23,42,.05);
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
  border-radius: 26px;
  border: 1px solid #e5e7eb;
  background: linear-gradient(180deg,#fff,#f8fafc);
  box-shadow: 0 18px 42px rgba(15,23,42,.08);
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

.hotel-photo-ibis-garching {
  background-image:
    linear-gradient(180deg, rgba(15,23,42,.08), rgba(15,23,42,.72)),
    url("{{ '/assets/img/attractions/3679_ho_01_p_1024x768.jpg' | relative_url }}");
  background-size: cover;
  background-position: center;
}

.hotel-photo-motel-one-garching {
  background-image:
    linear-gradient(180deg, rgba(15,23,42,.08), rgba(15,23,42,.72)),
    url("{{ '/assets/img/attractions/MO-Hotel-Muenchen-Garching-Outdoor-3.jpg' | relative_url }}");
  background-size: cover;
  background-position: center;
}

.hotel-photo-bb-garching {

  background-image:

    linear-gradient(180deg, rgba(15,23,42,.08), rgba(15,23,42,.72)),

    url("{{ '/assets/img/attractions/0498f661-e1cc-45e7-9aca-0cc9701eafb4.jpeg' | relative_url }}");

  background-size: cover;

  background-position: center;

}

.hotel-photo-budget {
  background-image:
    linear-gradient(180deg, rgba(15,23,42,.08), rgba(15,23,42,.72)),
    url("https://images.unsplathe sh.com/photo-1564501049412-61c2a3083791?auto=format&fit=crop&w=1200&q=80");
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
    border-radius: 28px;
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
    height: 460px;
    border-radius: 22px;
    background: transparent;
  }

  .map-compass {
    left: 1.25rem;
    top: 1.25rem;
    width: 42px;
    height: 42px;
  }

  .map-route-caption {
    position: relative;
    left: auto;
    bottom: auto;
    margin-top: .85rem;
  }

  .map-mobile-label {
    fill: rgba(255,255,255,.9);
    font-size: 24px;
    transform: translateX(-18px);
  }

  .map-stop-venue .map-mobile-label {
    transform: translateX(-34px);
  }

  .map-stop-warning .map-mobile-label {
    transform: translateX(-24px);
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

  .map-area-buttons {
    display: flex;
    flex-wrap: wrap;
    justify-content: flex-start;
    gap: .55rem;
    max-width: none;
    padding: 0 .35rem 0;
  }

  .map-area-bubble {
    flex: 0 1 calc(50% - .3rem);
    min-width: 0;
    min-height: 42px;
    margin: .45rem 0 0;
    justify-content: flex-start;
    font-size: .78rem;
  }

  .stay-map-panel {
    position: relative;
    top: auto;
    right: auto;
    bottom: auto;
    width: 100%;
    min-width: 0;
    margin: 1.25rem 0 0;
    max-height: none;
    overflow: hidden;
  }

  .stay-map-panel-photo {
    min-height: 150px;
  }

  .map-bg-label {
    font-size: 15px;
  }

  .map-bg-label-garden,
  .map-bg-label-city,
 

  .map-bg-label-garden {
    transform: none;
  }

  .map-bg-label-city {
    transform: translateY(-54px);
  }

  .map-bg-arc {
    stroke-width: 2.6;
  }
}

@media (min-width:761px) and (max-width:1080px) {
  .map-area-buttons {
    max-width: calc(58% - 2rem);
  }

  .map-area-bubble {
    min-width: 155px;
    font-size: .74rem;
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
      mapSvg.setAttribute('viewBox', '-45 0 650 600');
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
      text: 'The summer school venue and the closest hotels are located directly on the research campus. Choose this area for the most effortless stay.',
      photo: 'stay-map-panel-photo-venue',
      link: '#tum-campus-hotels',
      facts: [['Best for', 'Shortest commute'], ['Hotel focus', 'Courtyard + Stellaris']]
    },
    garching: {
      title: 'Garching',
      text: 'A convenient town option close to the research campus, with quick U6 access to the venue and a quieter local setting than central Munich.',
      photo: 'stay-map-panel-photo-garching',
      link: '#garching-area',
      facts: [['Best for', 'Close to campus'], ['Hotel focus', 'ibis + Motel One + B&B']]
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

  // 8. Add stops NodeList after buttons
  var stops = document.querySelectorAll('.map-stop[data-area]');

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
      // 9. Replace block with new logic for stops and area selection
      var selectedArea = button.getAttribute('data-area');
      button.classList.add('is-active');
      button.setAttribute('aria-pressed', 'true');
      stops.forEach(function (stop) {
        stop.classList.toggle('is-map-selected', stop.getAttribute('data-area') === selectedArea);
      });
      render(selectedArea);
    });
  });
});
</script>
