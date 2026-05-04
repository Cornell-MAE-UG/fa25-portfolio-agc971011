---
layout: project
title: Lantern Lure
description: MAE 2250 project hub linking the client pitch, functional prototype, and final client report
image: /assets/images/fly.png
technologies: [Research, Client Report, Mechanical Design, Prototyping, Testing, CAD]
---

<style>
.fp-hero,.fp-card,.fp-figure,.fp-table-wrap {
  border: 1px solid #e7e7e2;
  border-radius: 16px;
  background: #fff;
}

.fp-hero,.fp-card {
  padding: 1.2rem;
  margin: 1rem 0;
}

.fp-hero {
  background: linear-gradient(135deg,#f7f8f2 0%,#ffffff 55%,#f3f7f5 100%);
}

.fp-nav {
  display: grid;
  grid-template-columns: repeat(3,1fr);
  gap: 1rem;
  margin-top: 1rem;
}

.fp-nav-item {
  padding: 1rem;
  border-radius: 12px;
  border: 1px solid #ddd;
}

.fp-nav-item a {
  text-decoration: none;
}

.fp-gallery {
  display: grid;
  grid-template-columns: repeat(2,1fr);
  gap: 1rem;
  margin: 1rem 0;
}

.fp-figure {
  overflow: hidden;
}

.fp-figure img {
  width: 100%;
  display: block;
  border-radius: 12px;
}

.fp-figure img + .fp-placeholder {
  display: none;
}

.fp-placeholder {
  min-height: 210px;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  padding: 1rem;
  background: #eef4e8;
  color: #304030;
  font-size: .92rem;
}

.fp-figcap {
  font-size: .9rem;
  padding: .5rem;
  color: #444;
}

.fp-table {
  width: 100%;
  border-collapse: collapse;
}

.fp-table th,.fp-table td {
  padding: .6rem;
  border-bottom: 1px solid #eee;
  text-align: left;
  vertical-align: top;
}

.fp-note {
  background: #f8fbf3;
  padding: .8rem;
  border-left: 4px solid #799d4b;
}

@media (max-width: 700px) {
  .fp-nav,
  .fp-gallery {
    grid-template-columns: 1fr;
  }
}
</style>

<div class="fp-hero">
<h2>Lantern Lure</h2>

<p>
Lantern Lure is the overall MAE 2250 project focused on reducing spotted lanternfly damage in vineyards. The project progressed through three main milestones: the original client pitch, the functional prototype, and the final client report.
</p>

<div class="fp-nav">
  <div class="fp-nav-item">
    <a href="{% link _projects/2026_Problem_proposal.md %}"><b>Client Pitch</b></a><br>
    <span>O3: Grape Guardians – SLF Light Trap</span>
  </div>

  <div class="fp-nav-item">
    <a href="{% link _projects/2026_Functional Prototype – Lanternfly Trap.md %}"><b>Functional Prototype</b></a><br>
    <span>O5: Rotating trap mechanism and test results</span>
  </div>

  <div class="fp-nav-item">
    <a href="#client-report"><b>Client Report</b></a><br>
    <span>O6: Final project summary and supporting evidence</span>
  </div>
</div>

</div>

---

## Milestone Overview

<div class="fp-card">
<p>
<b>Client Pitch:</b> The <i>Grape Guardians – SLF Light Trap</i> page presents the original problem framing and concept proposal for attracting spotted lanternflies away from grapevines with a perimeter light trap.
</p>

<p>
<a href="{% link _projects/2026_Problem_proposal.md %}">Open Client Pitch page</a>
</p>
</div>

<div class="fp-card">
<p>
<b>Functional Prototype:</b> The prototype page documents the mechanical design, fabrication choices, and full testing process for the rotating ridge mechanism.
</p>

<p>
<a href="{% link _projects/2026_Functional Prototype – Lanternfly Trap.md %}">Open Functional Prototype page</a>
</p>
</div>

<div class="fp-card">
<p>
<b>Client Report:</b> The section below serves as the final project report on this overall project page. It summarizes the problem, the design solution, the supporting figures, and the prototype evidence that guided the final recommendations.
</p>
</div>

---

<h2 id="client-report">Client Report</h2>

<div class="fp-card">
<p>
Spotted lanternflies are an invasive pest that threaten grape production by feeding on vines and reducing crop quality. The client need behind Lantern Lure was to develop a practical vineyard solution that could attract lanternflies away from grapevines, capture them before harvest, and reduce reliance on chemical treatment.
</p>

<p>
The final concept focused on a perimeter-based light trap that uses light attraction, one-way containment, and a mechanical capture system. The project moved from early research and concept development into a functional prototype that could be tested and improved using measurable results.
</p>
</div>

## Problem and Design Requirements

<div class="fp-table-wrap">
<table class="fp-table">
  <tr>
    <th>Requirement</th>
    <th>Response</th>
  </tr>
  <tr>
    <td>Protect grapevines from SLF damage</td>
    <td>Use a perimeter trap to intercept insects before they reach the crop.</td>
  </tr>
  <tr>
    <td>Attract insects effectively</td>
    <td>Use a light-based lure that remains visible through the acrylic plate.</td>
  </tr>
  <tr>
    <td>Capture and contain insects</td>
    <td>Use roof and tube geometry together with a rotating ridge mechanism.</td>
  </tr>
  <tr>
    <td>Reduce chemical dependence</td>
    <td>Favor a mechanical trapping approach instead of broad chemical treatment.</td>
  </tr>
  <tr>
    <td>Support iteration with evidence</td>
    <td>Test light transmission, durability, speed, impact capture, throughput, and fit.</td>
  </tr>
</table>
</div>

<div class="fp-note">
The client pitch established the overall vineyard problem and concept direction, while the prototype provided the performance evidence summarized in this report.
</div>

## Client Report Figures

Add these images to `assets/images/` with these exact filenames:

- `intake-cardboard-prototype.png`
- `intake-exploded-cad.png`
- `intake-light-mechanism-dark.png`
- `intake-final-assembly.png`

<div class="fp-gallery">

<div class="fp-figure">
<img src="{{ '/assets/images/intake-cardboard-prototype.png' | relative_url }}" alt="Cardboard prototype for Lantern Lure" onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';">
<div class="fp-placeholder"><b>intake-cardboard-prototype.png</b><br>Put the cardboard prototype image here.</div>
<div class="fp-figcap"><b>Cardboard Prototype.</b> Early physical model used to study form, layout, and general system structure.</div>
</div>

<div class="fp-figure">
<img src="{{ '/assets/images/intake-exploded-cad.png' | relative_url }}" alt="Exploded CAD view of Lantern Lure" onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';">
<div class="fp-placeholder"><b>intake-exploded-cad.png</b><br>Put the exploded CAD image here.</div>
<div class="fp-figcap"><b>Exploded CAD View.</b> Shows the relationship between the acrylic plate, ridges, roof, tube, and fasteners.</div>
</div>

<div class="fp-figure">
<img src="{{ '/assets/images/intake-light-mechanism-dark.png' | relative_url }}" alt="Lantern Lure light mechanism shown in the dark" onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';">
<div class="fp-placeholder"><b>intake-light-mechanism-dark.png</b><br>Put the dark-room light mechanism image here.</div>
<div class="fp-figcap"><b>Light Mechanism in the Dark.</b> Demonstrates the light-based attraction feature central to the design.</div>
</div>

<div class="fp-figure">
<img src="{{ '/assets/images/intake-final-assembly.png' | relative_url }}" alt="Final assembled Lantern Lure prototype" onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';">
<div class="fp-placeholder"><b>intake-final-assembly.png</b><br>Put the final assembled prototype image here.</div>
<div class="fp-figcap"><b>Final Assembly.</b> Shows the completed prototype after moving from concept to functional build.</div>
</div>

</div>

## Prototype Evidence

<div class="fp-table-wrap">
<table class="fp-table">
  <tr>
    <th>Test</th>
    <th>Main Result</th>
    <th>Implication</th>
  </tr>
  <tr>
    <td>Light Transmission</td>
    <td>About 83% of light passed through the acrylic.</td>
    <td>The material remained suitable for light-based attraction.</td>
  </tr>
  <tr>
    <td>Shake Test</td>
    <td>The structure stayed intact, but nuts loosened slightly.</td>
    <td>Locking fasteners should be added in the next iteration.</td>
  </tr>
  <tr>
    <td>Speed Test</td>
    <td>The mechanism reached about 7.25 rad/s with minor friction.</td>
    <td>Motorized actuation and improved alignment would increase consistency.</td>
  </tr>
  <tr>
    <td>Throw Test</td>
    <td>All test objects were captured successfully.</td>
    <td>The ridge concept works well under dynamic impact.</td>
  </tr>
  <tr>
    <td>High Volume Test</td>
    <td>Smaller objects passed through, larger ones could jam at the tube opening.</td>
    <td>The opening should be enlarged by about 0.25 inches.</td>
  </tr>
  <tr>
    <td>Tolerance Test</td>
    <td>Parts assembled successfully, but glue was still needed.</td>
    <td>Tighter tolerances would improve assembly quality.</td>
  </tr>
</table>
</div>

<div class="fp-note">
The full test procedures and detailed prototype discussion remain on the Functional Prototype page, while this report keeps the key evidence in one place for the final milestone.
</div>

## Final Assessment

<div class="fp-card">
<p>
Lantern Lure successfully developed from a research-based client pitch into a tested mechanical prototype. The project showed that a light-guided trapping system can be combined with a rotating ridge mechanism to capture incoming targets and move them into containment.
</p>

<p>
The strongest outcomes were the successful light transmission, impact capture, and overall functional performance of the mechanism. The most important next steps are improving fastening reliability, increasing the tube opening, tightening assembly tolerances, and replacing manual actuation with a more consistent drive system.
</p>
</div>

## Reflection

This project connected research, client-centered design, and prototype testing in one workflow. The Client Pitch defined the vineyard problem, the Functional Prototype tested the mechanism in practice, and this Client Report brings those milestones together into one overall project page.
