---
title: Lecture Preparation
layout: default
permalink: /lecture-preparation/
sitemap: false
---

<section class="prep-hero" aria-labelledby="prep-title">
  <div>
    <p class="prep-eyebrow">TAROT 2026 Attendee Guide</p>
    <h1 id="prep-title">Lecture Preparation</h1>
    <p class="prep-hero-text">
      Some lecturers have suggested optional reading or software setup before their sessions.
      Most lectures require no preparation. Please review the relevant instructions below and
      bring a laptop where indicated.
    </p>
  </div>
</section>

<section class="prep-summary" aria-label="Preparation overview">
  <div class="prep-summary-card">
    <strong>Required or recommended setup</strong>
    <span>K. Friedl &amp; L. Sorokin · F. Pastore</span>
  </div>
  <div class="prep-summary-card">
    <strong>Suggested reading or exploration</strong>
    <span>W. Mallouli · D. Nickovic</span>
  </div>
  <div class="prep-summary-card">
    <strong>No preparation needed</strong>
    <span>S. Tong · E. Bartocci · N. Franco · S. Elbaum · S. Eldth · G. Calikli</span>
  </div>
</section>

<section class="prep-section" aria-labelledby="prep-instructions-title">
  <div class="prep-section-heading">
    <p class="prep-eyebrow">By lecturer</p>
    <h2 id="prep-instructions-title">Preparation Instructions</h2>
  </div>

  <article class="prep-card">
    <div class="prep-card-heading">
      <div>
        <p class="prep-status prep-status-optional">Optional</p>
        <h3>W. Mallouli</h3>
      </div>
    </div>
    <p>Students are welcome to explore Montimage’s Smart Fuzzer before the session.</p>
    <div class="prep-actions">
      <a class="prep-button prep-button-primary" href="https://strongcourage.notion.site/Hands-On-Tutorials-for-NetworkFuzzer-1fd1f0954df8801fbdb5d3c68c9a9daf" target="_blank" rel="noopener noreferrer">Smart Fuzzer tutorials</a>
    </div>
  </article>

  <article class="prep-card prep-card-compact">
    <div class="prep-card-heading">
      <div>
        <p class="prep-status prep-status-none">No preparation</p>
        <h3>S. Tong</h3>
      </div>
    </div>
    <p>No specific preparation is required.</p>
  </article>

  <article class="prep-card">
    <div class="prep-card-heading">
      <div>
        <p class="prep-status prep-status-reading">Recommended reading</p>
        <h3>D. Nickovic</h3>
      </div>
    </div>
    <p>
      Please read: Anagha Athavale, Ezio Bartocci, Maria Christakis, Matteo Maffei,
      Dejan Nickovic, and Georg Weissenbacher, “Verifying Global Two-Safety Properties
      in Neural Networks with Confidence,” CAV (2), 2024, pp. 329–351.
    </p>
    <div class="prep-actions">
      <a class="prep-button prep-button-primary" href="https://link.springer.com/chapter/10.1007/978-3-031-65630-9_17" target="_blank" rel="noopener noreferrer">Open paper</a>
    </div>
  </article>

  <article class="prep-card prep-card-highlight">
    <div class="prep-card-heading">
      <div>
        <p class="prep-status prep-status-required">Prepare in advance</p>
        <h3>K. Friedl &amp; L. Sorokin</h3>
      </div>
    </div>

    <p>
      The hands-on session will focus on testing the natural-language understanding of a
      task-oriented in-car chatbot. Participants will use STELLAR, a guided testing framework,
      to generate natural-language test inputs automatically and expose failures in the
      assistant’s intent recognition.
    </p>

    <div class="prep-checklist">
      <label><input type="checkbox"> Install STELLAR locally before the session.</label>
      <label><input type="checkbox"> Optional: read the STELLAR paper.</label>
      <label><input type="checkbox"> Bring a laptop to the session.</label>
    </div>

    <p class="prep-note">The code used during the live session will be shared shortly before the session starts.</p>

    <div class="prep-actions">
      <a class="prep-button prep-button-secondary" href="https://arxiv.org/abs/2601.00497" target="_blank" rel="noopener noreferrer">Paper</a>
      <a class="prep-button prep-button-primary" href="https://github.com/ast-fortiss-tum/STELLAR" target="_blank" rel="noopener noreferrer">Repository</a>
      <a class="prep-button prep-button-secondary" href="https://github.com/ast-fortiss-tum/STELLAR/tree/master/jupyter" target="_blank" rel="noopener noreferrer">Jupyter notebooks</a>
    </div>
  </article>

  <article class="prep-card prep-card-compact">
    <div class="prep-card-heading">
      <div>
        <p class="prep-status prep-status-none">No preparation</p>
        <h3>E. Bartocci</h3>
      </div>
    </div>
    <p>No preparation is required.</p>
  </article>

  <article class="prep-card prep-card-compact">
    <div class="prep-card-heading">
      <div>
        <p class="prep-status prep-status-none">No preparation</p>
        <h3>N. Franco</h3>
      </div>
    </div>
    <p>No preparation is required.</p>
  </article>

  <article class="prep-card prep-card-compact">
    <div class="prep-card-heading">
      <div>
        <p class="prep-status prep-status-none">No preparation</p>
        <h3>S. Elbaum</h3>
      </div>
    </div>
    <p>No preparation is required.</p>
  </article>

  <article class="prep-card prep-card-highlight">
    <div class="prep-card-heading">
      <div>
        <p class="prep-status prep-status-required">Software setup</p>
        <h3>F. Pastore</h3>
      </div>
    </div>

    <p>Please complete the relevant software setup before the session.</p>

    <details class="prep-details" open>
      <summary>ClusterXplain setup</summary>
      <div class="prep-details-body">
        <ol>
          <li>Install Python 3.13.</li>
          <li>
            Download <a href="https://zenodo.org/records/21249809/files/clusterxplain.zip?download=1" target="_blank" rel="noopener noreferrer">clusterxplain.zip</a>.
          </li>
          <li>Unzip the archive and open the project directory in a terminal.</li>
        </ol>

<pre><code>cd clusterxplain/clusterxplain/</code></pre>

        <p>Create and activate a virtual environment:</p>
<pre><code>python3.13 -m venv env

# macOS / Linux
source env/bin/activate

# Windows
env\Scripts\activate</code></pre>

        <p>Install the required packages:</p>
<pre><code>pip install -r requirements.txt</code></pre>
      </div>
    </details>

    <details class="prep-details">
      <summary>MarsSim setup — Windows only</summary>
      <div class="prep-details-body">
        <p class="prep-warning">
          MarsSim requires Windows. It may also be run inside a Windows virtual machine.
        </p>
        <ol>
          <li>Install Python 3.10.</li>
          <li>Download and unzip <strong>AirSim.zip</strong>. The download link will be provided separately.</li>
          <li>
            Download <strong>Simulator_GUI.zip</strong> from
            <a href="https://zenodo.org/records/17449849" target="_blank" rel="noopener noreferrer">Zenodo</a>, then unzip it.
          </li>
          <li>Open the Simulator GUI directory in a terminal.</li>
        </ol>

<pre><code>cd Simulator_GUI\Simulator_GUI
python3.10 -m venv env

# macOS / Linux, when using a Windows VM shell that supports it
source env/bin/activate

# Windows
env\Scripts\activate

python -m pip install --upgrade pip</code></pre>

        <p><strong>Without a GPU:</strong> remove both occurrences of <code>+cu113</code> from <code>requirements.txt</code>, then run:</p>
<pre><code>pip install -r requirements.txt</code></pre>

        <p><strong>With a GPU:</strong></p>
<pre><code>python -m pip install -r requirements.txt --extra-index-url https://download.pytorch.org/whl/cu113</code></pre>

        <p>Install the remaining dependency and AirSim Python client:</p>
<pre><code>pip install msgpack-rpc-python

cd ..\..\AirSim\AirSim\PythonClient
python.exe setup.py install</code></pre>

        <p>Return to the Simulator GUI and start it:</p>
<pre><code>cd ..\..\Simulator_GUI\Simulator_GUI
python.exe sim_gui.py</code></pre>

        <p>Continue from Step 3 in <code>Simulator_GUI\Simulator_GUI\README.md</code>.</p>
      </div>
    </details>
  </article>

  <article class="prep-card prep-card-compact">
    <div class="prep-card-heading">
      <div>
        <p class="prep-status prep-status-none">No preparation</p>
        <h3>S. Eldth</h3>
      </div>
    </div>
    <p>No preparation is required.</p>
  </article>

  <article class="prep-card prep-card-compact">
    <div class="prep-card-heading">
      <div>
        <p class="prep-status prep-status-none">No preparation</p>
        <h3>G. Calikli</h3>
      </div>
    </div>
    <p>No preparation is required.</p>
  </article>
</section>

<section class="prep-footer-note" aria-label="Updates">
  <p>This page is not included in the main navigation. Please keep the link available and check it again before the summer school for updates.</p>
</section>

<style>
.prep-hero {
  position: relative;
  margin: 0 0 2rem;
  padding: clamp(1.6rem, 4vw, 2.6rem);
  overflow: hidden;
  border: 1px solid #e5e7eb;
  border-radius: 30px;
  background:
    radial-gradient(circle at 12% 8%, rgba(245, 158, 11, 0.18), transparent 30%),
    radial-gradient(circle at 88% 12%, rgba(14, 165, 233, 0.16), transparent 28%),
    linear-gradient(135deg, #eff6ff, #f8fafc 52%, #ecfeff);
  box-shadow: 0 24px 60px rgba(15, 23, 42, 0.13);
}

.prep-eyebrow {
  margin: 0 0 0.65rem;
  color: #0369a1;
  font-size: 0.76rem;
  font-weight: 900;
  letter-spacing: 0.12em;
  text-transform: uppercase;
}

.prep-hero h1 {
  max-width: 760px;
  margin: 0;
  color: #0f172a;
  font-size: clamp(2.3rem, 6vw, 4.8rem);
  line-height: 0.96;
  letter-spacing: -0.065em;
}

.prep-hero-text {
  max-width: 760px;
  margin: 1.2rem 0 0;
  color: #374151;
  font-size: clamp(1rem, 2vw, 1.15rem);
  line-height: 1.7;
}

.prep-summary {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 0.9rem;
  margin: 0 0 2.4rem;
}

.prep-summary-card {
  display: grid;
  gap: 0.35rem;
  padding: 1rem;
  border: 1px solid #e5e7eb;
  border-radius: 18px;
  background: #fff;
  box-shadow: 0 10px 24px rgba(15, 23, 42, 0.06);
}

.prep-summary-card strong {
  color: #111827;
}

.prep-summary-card span {
  color: #4b5563;
  font-size: 0.9rem;
  line-height: 1.45;
}

.prep-section {
  display: grid;
  gap: 1rem;
  margin: 2rem 0;
}

.prep-section-heading {
  margin-bottom: 0.35rem;
}

.prep-section-heading h2 {
  margin: 0;
  color: #111827;
  font-size: clamp(1.8rem, 4vw, 2.6rem);
  letter-spacing: -0.05em;
}

.prep-card {
  padding: clamp(1.1rem, 3vw, 1.5rem);
  border: 1px solid #e5e7eb;
  border-radius: 24px;
  background:
    radial-gradient(circle at top right, rgba(14, 165, 233, 0.07), transparent 30%),
    linear-gradient(180deg, #fff, #f8fafc);
  box-shadow: 0 14px 34px rgba(15, 23, 42, 0.07);
}

.prep-card-highlight {
  border-left: 5px solid #f59e0b;
  background:
    radial-gradient(circle at top right, rgba(245, 158, 11, 0.1), transparent 28%),
    linear-gradient(180deg, #fff, #fffbeb);
}

.prep-card-pending {
  border-style: dashed;
}

.prep-card-compact {
  padding-block: 1rem;
}

.prep-card-heading {
  display: flex;
  align-items: start;
  justify-content: space-between;
  gap: 1rem;
}

.prep-card h3 {
  margin: 0;
  color: #111827;
  font-size: clamp(1.3rem, 3vw, 1.8rem);
  letter-spacing: -0.04em;
}

.prep-card > p,
.prep-details-body p,
.prep-details-body li {
  color: #374151;
  line-height: 1.65;
}

.prep-status {
  display: inline-flex;
  margin: 0 0 0.45rem;
  padding: 0.3rem 0.58rem;
  border-radius: 999px;
  font-size: 0.68rem;
  font-weight: 900;
  letter-spacing: 0.08em;
  text-transform: uppercase;
}

.prep-status-none {
  background: #ecfdf5;
  color: #047857;
}

.prep-status-optional,
.prep-status-reading {
  background: #eff6ff;
  color: #0369a1;
}

.prep-status-required {
  background: #fff7ed;
  color: #9a3412;
}

.prep-status-pending {
  background: #f3f4f6;
  color: #4b5563;
}

.prep-actions {
  display: flex;
  flex-wrap: wrap;
  gap: 0.6rem;
  margin-top: 1rem;
}

.prep-button {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  min-height: 40px;
  padding: 0.55rem 0.85rem;
  border-radius: 999px;
  font-size: 0.78rem;
  font-weight: 900;
  text-decoration: none;
}

.prep-button-primary {
  background: #111827;
  color: #fff;
}

.prep-button-secondary {
  border: 1px solid #dbeafe;
  background: #fff;
  color: #075985;
}

.prep-checklist {
  display: grid;
  gap: 0.55rem;
  margin-top: 1rem;
}

.prep-checklist label {
  display: flex;
  gap: 0.65rem;
  align-items: start;
  color: #374151;
  line-height: 1.45;
}

.prep-checklist input {
  margin-top: 0.18rem;
}

.prep-note,
.prep-warning {
  padding: 0.85rem 1rem;
  border-radius: 16px;
  background: #ecfeff;
  color: #075985 !important;
}

.prep-warning {
  background: #fff7ed;
  color: #9a3412 !important;
}

.prep-resource-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 0.65rem;
  margin-top: 1rem;
}

.prep-resource-grid span {
  padding: 0.7rem;
  border-radius: 14px;
  background: #f3f4f6;
  color: #4b5563;
  font-size: 0.85rem;
  font-weight: 700;
}

.prep-details {
  margin-top: 1rem;
  overflow: hidden;
  border: 1px solid #e5e7eb;
  border-radius: 18px;
  background: rgba(255, 255, 255, 0.85);
}

.prep-details summary {
  cursor: pointer;
  padding: 1rem;
  color: #075985;
  font-weight: 900;
}

.prep-details[open] summary {
  border-bottom: 1px solid #e5e7eb;
  color: #111827;
}

.prep-details-body {
  padding: 0.25rem 1rem 1rem;
}

.prep-details-body pre {
  overflow-x: auto;
  margin: 0.8rem 0;
  padding: 0.9rem;
  border-radius: 14px;
  background: #111827;
  color: #f9fafb;
  font-size: 0.82rem;
  line-height: 1.55;
}

.prep-details-body code {
  font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
}

.prep-footer-note {
  margin: 2rem 0 0;
  padding: 1rem 1.2rem;
  border-left: 5px solid #38bdf8;
  border-radius: 18px;
  background: #eff6ff;
}

.prep-footer-note p {
  margin: 0;
  color: #374151;
  line-height: 1.6;
}

@media (max-width: 760px) {
  .prep-summary,
  .prep-resource-grid {
    grid-template-columns: 1fr;
  }

  .prep-hero {
    border-radius: 22px;
  }

  .prep-actions {
    align-items: stretch;
  }

  .prep-button {
    width: 100%;
  }
}
</style>
