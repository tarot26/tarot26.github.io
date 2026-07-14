---
title: Pictures
layout: default
permalink: /event-pictures/
---

<section class="pictures-hero" aria-labelledby="pictures-title">
  <p class="pictures-eyebrow">TAROT 2026</p>

  <h1 id="pictures-title">Pictures</h1>

  <p class="pictures-lede">
    A selection of pictures from the lectures and social events
    of TAROT 2026.
  </p>
</section>

<style>
.pictures-hero {
  position: relative;
  overflow: hidden;
  margin-bottom: 2.5rem;
  padding: clamp(2rem, 5vw, 4rem);
  border: 1px solid #e5e7eb;
  border-radius: 30px;
  background:
    radial-gradient(
      circle at 12% 6%,
      rgba(245, 158, 11, 0.22),
      transparent 30%
    ),
    radial-gradient(
      circle at 88% 12%,
      rgba(14, 165, 233, 0.14),
      transparent 28%
    ),
    linear-gradient(135deg, #111827, #1f2937 58%, #374151);
  color: #ffffff;
  box-shadow: 0 24px 60px rgba(15, 23, 42, 0.18);
}

.pictures-hero::after {
  content: "";
  position: absolute;
  right: -7rem;
  bottom: -8rem;
  width: 18rem;
  height: 18rem;
  border-radius: 999px;
  background: rgba(255, 255, 255, 0.08);
  pointer-events: none;
}

.pictures-eyebrow {
  margin: 0 0 0.7rem;
  color: #fbbf24;
  font-size: 0.78rem;
  font-weight: 900;
  letter-spacing: 0.14em;
  text-transform: uppercase;
}

.pictures-hero h1 {
  margin: 0;
  color: #ffffff;
  font-size: clamp(2.6rem, 8vw, 5.2rem);
  line-height: 0.95;
  letter-spacing: -0.07em;
}

.pictures-lede {
  max-width: 760px;
  margin: 1.1rem 0 0;
  color: #e5e7eb;
  font-size: clamp(1.05rem, 2vw, 1.25rem);
  line-height: 1.65;
}

.pictures-section {
  margin: 2.5rem 0;
  padding: clamp(1.2rem, 3vw, 1.8rem);
  border: 1px solid #e5e7eb;
  border-radius: 26px;
  background: #ffffff;
  box-shadow: 0 16px 40px rgba(15, 23, 42, 0.07);
}

.pictures-section-header {
  margin-bottom: 1.25rem;
}

.pictures-section-header h2 {
  margin: 0;
  color: #111827;
  font-size: clamp(1.8rem, 4vw, 2.5rem);
  line-height: 1.05;
  letter-spacing: -0.05em;
}

.pictures-section-header p {
  max-width: 700px;
  margin: 0.6rem 0 0;
  color: #4b5563;
  line-height: 1.6;
}

.pictures-grid {
  display: grid;
  grid-template-columns: repeat(5, minmax(0, 1fr));
  gap: 0.75rem;
}

.picture-item {
  position: relative;
  display: block;
  overflow: hidden;
  aspect-ratio: 4 / 3;
  border-radius: 14px;
  background: #e5e7eb;
}

.picture-item img {
  display: block;
  width: 100%;
  height: 100%;
  object-fit: cover;
  transition: transform 0.25s ease;
}

.picture-item:hover img {
  transform: scale(1.04);
}

.picture-item:focus-visible {
  outline: 3px solid #f59e0b;
  outline-offset: 3px;
}

.album-area {
  margin: 3rem 0;
  text-align: center;
}

.album-area p {
  margin: 0 0 1rem;
  color: #4b5563;
  line-height: 1.6;
}

.album-button {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  padding: 0.85rem 1.25rem;
  border-radius: 999px;
  background: #111827;
  color: #ffffff;
  font-weight: 900;
  text-decoration: none;
  transition:
    transform 0.18s ease,
    box-shadow 0.18s ease,
    background 0.18s ease;
}

.album-button:hover {
  transform: translateY(-1px);
  background: #1f2937;
  box-shadow: 0 10px 24px rgba(15, 23, 42, 0.2);
}

.album-button:focus-visible {
  outline: 3px solid #f59e0b;
  outline-offset: 3px;
}

@media (max-width: 1000px) {
  .pictures-grid {
    grid-template-columns: repeat(4, minmax(0, 1fr));
  }
}

@media (max-width: 760px) {
  .pictures-grid {
    grid-template-columns: repeat(3, minmax(0, 1fr));
  }
}

@media (max-width: 520px) {
  .pictures-hero,
  .pictures-section {
    border-radius: 20px;
  }

  .pictures-grid {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }
}

@media (prefers-reduced-motion: reduce) {
  .picture-item img,
  .album-button {
    transition: none;
  }
}
</style>

<section
  class="pictures-section"
  aria-labelledby="speakers-pictures-title"
>
  <div class="pictures-section-header">
    <h2 id="speakers-pictures-title">Speakers and sessions</h2>

    <p>
      Pictures from lectures and presentations.
    </p>
  </div>

  <div class="pictures-grid">
    <a
      class="picture-item"
      href="{{ 'assets/images/events/pics-coming.jpeg' | relative_url }}"
      target="_blank"
      aria-label="Open speaker picture 1"
    >
      <img
        src="{{ 'assets/images/events/pics-coming.jpeg' | relative_url }}"
        alt="Lecture"
        loading="lazy"
      >
    </a>

    <!-- <a
      class="picture-item"
      href="{{ '/assets/images/events/speakers/speaker-02.jpg' | relative_url }}"
      target="_blank"
      aria-label="Open speaker picture 2"
    >
      <img
        src="{{ '/assets/images/events/speakers/speaker-02.jpg' | relative_url }}"
        alt="Lecture"
        loading="lazy"
      >
    </a>

    <a
      class="picture-item"
      href="{{ '/assets/images/events/speakers/speaker-03.jpg' | relative_url }}"
      target="_blank"
      aria-label="Open speaker picture 3"
    >
      <img
        src="{{ '/assets/images/events/speakers/speaker-03.jpg' | relative_url }}"
        alt="Lecture"
        loading="lazy"
      >
    </a>

    <a
      class="picture-item"
      href="{{ '/assets/images/events/speakers/speaker-04.jpg' | relative_url }}"
      target="_blank"
      aria-label="Open speaker picture 4"
    >
      <img
        src="{{ '/assets/images/events/speakers/speaker-04.jpg' | relative_url }}"
        alt="Lecture"
        loading="lazy"
      >
    </a>

    <a
      class="picture-item"
      href="{{ '/assets/images/events/speakers/speaker-05.jpg' | relative_url }}"
      target="_blank"
      aria-label="Open speaker picture 5"
    >
      <img
        src="{{ '/assets/images/events/speakers/speaker-05.jpg' | relative_url }}"
        alt="Lecture"
        loading="lazy"
      >
    </a>

    <a
      class="picture-item"
      href="{{ '/assets/images/events/speakers/speaker-06.jpg' | relative_url }}"
      target="_blank"
      aria-label="Open speaker picture 6"
    >
      <img
        src="{{ '/assets/images/events/speakers/speaker-06.jpg' | relative_url }}"
        alt="Lecture"
        loading="lazy"
      >
    </a>

    <a
      class="picture-item"
      href="{{ '/assets/images/events/speakers/speaker-07.jpg' | relative_url }}"
      target="_blank"
      aria-label="Open speaker picture 7"
    >
      <img
        src="{{ '/assets/images/events/speakers/speaker-07.jpg' | relative_url }}"
        alt="Lecture"
        loading="lazy"
      >
    </a>

    <a
      class="picture-item"
      href="{{ '/assets/images/events/speakers/speaker-08.jpg' | relative_url }}"
      target="_blank"
      aria-label="Open speaker picture 8"
    >
      <img
        src="{{ '/assets/images/events/speakers/speaker-08.jpg' | relative_url }}"
        alt="Lecture"
        loading="lazy"
      >
    </a>

    <a
      class="picture-item"
      href="{{ '/assets/images/events/speakers/speaker-09.jpg' | relative_url }}"
      target="_blank"
      aria-label="Open speaker picture 9"
    >
      <img
        src="{{ '/assets/images/events/speakers/speaker-09.jpg' | relative_url }}"
        alt="Lecture"
        loading="lazy"
      >
    </a>

    <a
      class="picture-item"
      href="{{ '/assets/images/events/speakers/speaker-10.jpg' | relative_url }}"
      target="_blank"
      aria-label="Open speaker picture 10"
    >
      <img
        src="{{ '/assets/images/events/speakers/speaker-10.jpg' | relative_url }}"
        alt="Lecture"
        loading="lazy"
      >
    </a>

    <a
      class="picture-item"
      href="{{ '/assets/images/events/speakers/speaker-11.jpg' | relative_url }}"
      target="_blank"
      aria-label="Open speaker picture 11"
    >
      <img
        src="{{ '/assets/images/events/speakers/speaker-11.jpg' | relative_url }}"
        alt="Lecture"
        loading="lazy"
      >
    </a>

    <a
      class="picture-item"
      href="{{ '/assets/images/events/speakers/speaker-12.jpg' | relative_url }}"
      target="_blank"
      aria-label="Open speaker picture 12"
    >
      <img
        src="{{ '/assets/images/events/speakers/speaker-12.jpg' | relative_url }}"
        alt="Lecture"
        loading="lazy"
      >
    </a>

    <a
      class="picture-item"
      href="{{ '/assets/images/events/speakers/speaker-13.jpg' | relative_url }}"
      target="_blank"
      aria-label="Open speaker picture 13"
    >
      <img
        src="{{ '/assets/images/events/speakers/speaker-13.jpg' | relative_url }}"
        alt="Lecture"
        loading="lazy"
      >
    </a>

    <a
      class="picture-item"
      href="{{ '/assets/images/events/speakers/speaker-14.jpg' | relative_url }}"
      target="_blank"
      aria-label="Open speaker picture 14"
    >
      <img
        src="{{ '/assets/images/events/speakers/speaker-14.jpg' | relative_url }}"
        alt="Lecture"
        loading="lazy"
      >
    </a>

    <a
      class="picture-item"
      href="{{ '/assets/images/events/speakers/speaker-15.jpg' | relative_url }}"
      target="_blank"
      aria-label="Open speaker picture 15"
    >
      <img
        src="{{ '/assets/images/events/speakers/speaker-15.jpg' | relative_url }}"
        alt="Lecture"
        loading="lazy"
      >
    </a>

    <a
      class="picture-item"
      href="{{ '/assets/images/events/speakers/speaker-16.jpg' | relative_url }}"
      target="_blank"
      aria-label="Open speaker picture 16"
    >
      <img
        src="{{ '/assets/images/events/speakers/speaker-16.jpg' | relative_url }}"
        alt="Lecture"
        loading="lazy"
      >
    </a>

    <a
      class="picture-item"
      href="{{ '/assets/images/events/speakers/speaker-17.jpg' | relative_url }}"
      target="_blank"
      aria-label="Open speaker picture 17"
    >
      <img
        src="{{ '/assets/images/events/speakers/speaker-17.jpg' | relative_url }}"
        alt="Lecture"
        loading="lazy"
      >
    </a>

    <a
      class="picture-item"
      href="{{ '/assets/images/events/speakers/speaker-18.jpg' | relative_url }}"
      target="_blank"
      aria-label="Open speaker picture 18"
    >
      <img
        src="{{ '/assets/images/events/speakers/speaker-18.jpg' | relative_url }}"
        alt="Lecture"
        loading="lazy"
      >
    </a>

    <a
      class="picture-item"
      href="{{ '/assets/images/events/speakers/speaker-19.jpg' | relative_url }}"
      target="_blank"
      aria-label="Open speaker picture 19"
    >
      <img
        src="{{ '/assets/images/events/speakers/speaker-19.jpg' | relative_url }}"
        alt="Lecture"
        loading="lazy"
      >
    </a>

    <a
      class="picture-item"
      href="{{ '/assets/images/events/speakers/speaker-20.jpg' | relative_url }}"
      target="_blank"
      aria-label="Open speaker picture 20"
    >
      <img
        src="{{ '/assets/images/events/speakers/speaker-20.jpg' | relative_url }}"
        alt="Lecture"
        loading="lazy"
      >
    </a> -->
  </div>
</section>

<section
  class="pictures-section"
  aria-labelledby="social-pictures-title"
>
  <div class="pictures-section-header">
    <h2 id="social-pictures-title">Social events</h2>

    <p>
      Pictures from BMW Welt, Tollwood Olympiapark, dinners,
      informal gatherings, and other moments around Munich.
    </p>
  </div>

  <div class="pictures-grid">
    <a
      class="picture-item"
      href="{{ 'assets/images/events/pics-coming.jpeg' | relative_url }}"
      target="_blank"
      aria-label="Open social event picture 1"
    >
      <img
        src="{{ 'assets/images/events/pics-coming.jpeg' | relative_url }}"
        alt="TAROT 2026 social event"
        loading="lazy"
      >
    </a>

  </div>
</section>

<!-- <div class="album-area">
  <p>
    Browse all available pictures in the complete shared Google Photos album.
  </p>

  <a
    class="album-button"
    href="GOOGLE_PHOTOS_FULL_ALBUM_URL"
    target="_blank"
    rel="noopener noreferrer"
  >
    Open complete Google Photos album
  </a>
</div> -->