---
layout: project
title: Client Report
description: Final Lantern Lure client report for MAE 2250
image: /assets/images/intake-final-assembly.png
technologies: [Client Report, Mechanical Design, Prototyping, Testing, CAD]
hide_from_gallery: true
---

<style>
.cr-hero,
.cr-panel,
.cr-figure,
.cr-table-wrap {
  border: 1px solid #e1e4dc;
  border-radius: 8px;
  background: #fff;
}

.cr-hero,
.cr-panel {
  padding: 1.1rem;
  margin: 1rem 0;
}

.cr-hero {
  background: #f8faf4;
}

.cr-actions {
  display: flex;
  flex-wrap: wrap;
  gap: .7rem;
  margin-top: .8rem;
}

.cr-actions a {
  display: inline-block;
  padding: .55rem .8rem;
  border: 1px solid #6f8f52;
  border-radius: 6px;
  color: #34481f;
  text-decoration: none;
  font-weight: 700;
}

.cr-gallery {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: .9rem;
  margin: 1rem 0;
}

.cr-figure {
  overflow: hidden;
}

.cr-figure img {
  width: 100%;
  display: block;
}

.cr-caption {
  padding: .55rem .65rem;
  font-size: .9rem;
  color: #444;
}

.cr-table-wrap {
  overflow-x: auto;
  margin: 1rem 0;
}

.cr-table {
  width: 100%;
  border-collapse: collapse;
}

.cr-table th,
.cr-table td {
  padding: .6rem;
  border-bottom: 1px solid #eceee8;
  text-align: left;
  vertical-align: top;
}

.cr-note {
  margin: 1rem 0;
  padding: .85rem 1rem;
  border-left: 4px solid #6f8f52;
  background: #f7fbf1;
}

@media (max-width: 760px) {
  .cr-gallery {
    grid-template-columns: 1fr;
  }
}
</style>

<div class="cr-hero">
<p><b>Team:</b> The Grape Guardians</p>
<p><b>Team members:</b> Ashlyn Roeder, Asher Ciardiello, Ira Geller, Nicholas Letendre, and Mamadou Barry</p>

<p>
This client report summarizes the final Lantern Lure prototype, the test results that guided our recommendation, and the next steps needed before vineyard field testing.
</p>

<div class="cr-actions">
  <a href="{{ site.baseurl }}{% link _projects/2026_Lantern_Lure.md %}">Project Hub</a>
  <a href="{{ site.baseurl }}{% link _projects/2026_Problem_proposal.md %}">Client Pitch</a>
  <a href="{{ site.baseurl }}{% link _projects/2026_Functional Prototype – Lanternfly Trap.md %}">Functional Prototype</a>
  <a href="{{ '/assets/pdfs/O6_Client_Report.pdf' | relative_url }}">Report PDF</a>
</div>
</div>

## Context and Problem

Spotted lanternflies create a major vineyard problem because they land on grapevines, feed on the plants, and can infest grapes before harvest. Once grapes are already contaminated, there is not a reliable way to separate SLF from the crop. Our team therefore focused on prevention: stop the insects before they reach the vines.

Lantern Lure uses light to attract SLF away from grape rows at night. This direction avoids pesticides near the crop and gives vineyard operators a physical trap that can be placed around the field perimeter or in areas where SLF commonly land.

## Final Prototype and Use

<div class="cr-panel">
The final prototype is a light trap with a clear rotating top plate, raised ridges, a roof, a center tube, a crank-driven gear system, and a lower containment drawer. SLF are attracted to the light, land on the rotating plate, and are forced either toward the center tube or into the interlocking ridges. Insects that enter the center tube fall into the bottom container, which can be emptied and cleaned by the user.
</div>

For a vineyard version, we recommend replacing the hand crank with a motor, pairing the light and motor with a small power source, and exploring solar power because the device would be outdoors and mostly active at night. The trap should also be placed where SLF are most likely to land so it pulls insects away from grapevines before harvest.

## Conclusion and Recommendation

<div class="cr-note">
Lantern Lure is promising and worth further development before field testing. The core mechanism does not need a full redesign, but it should be motorized, tested with real SLF, and updated with more durable purchased or manufactured gears.
</div>

The recommendation is based on testing: the prototype transmitted enough light, handled multiple mock insects, prevented escape through the ridge geometry, and stayed intact during basic structural tests. The main risks are practical rather than conceptual. The current 3D-printed crown gear may wear down under motorized use, and more testing is needed to identify which light type best attracts SLF at night.

## Testing and Results

<div class="cr-table-wrap">
<table class="cr-table">
  <tr>
    <th>Success Criteria</th>
    <th>Test and Result</th>
    <th>Decision</th>
  </tr>
  <tr>
    <td>Hold a large number of SLF</td>
    <td>The target was 1000 SLF, estimated to require at least 4 L of storage. CAD volume and drawer checks showed the containment area could meet the target.</td>
    <td>The trap should not need frequent service during normal vineyard use.</td>
  </tr>
  <tr>
    <td>Transmit light effectively</td>
    <td>Measured light dropped from 14400 lux to 14200 lux through the trap top, meaning about 98.6% of the light passed through.</td>
    <td>The transparent top is suitable for attracting SLF without wasting major power.</td>
  </tr>
  <tr>
    <td>Handle multiple SLF at once</td>
    <td>The first prototype fit 6 mock SLF through the central tube. The final prototype moved 3 mock SLF into the bottom container during shake testing.</td>
    <td>The mechanism can handle multiple insects landing in the trap at the same time.</td>
  </tr>
  <tr>
    <td>Prevent escape</td>
    <td>Mock SLF placed between the ridge sets could not find gaps to crawl through as the top rotated.</td>
    <td>The ridge system creates a credible path toward containment or crushing.</td>
  </tr>
  <tr>
    <td>Survive basic use conditions</td>
    <td>The prototype survived a 5 Hz shake test, a 7.25 rad/s spin test, and thrown mock-SLF impacts.</td>
    <td>The structure is durable enough for continued development and more realistic tests.</td>
  </tr>
</table>
</div>

## Prototype Evidence

<div class="cr-gallery">
  <div class="cr-figure">
    <img src="{{ '/assets/images/intake-cardboard-prototype.png' | relative_url }}" alt="Early cardboard Lantern Lure prototype">
    <div class="cr-caption"><b>Early Prototype.</b> Physical model used to check the trap form and the basic layout before final fabrication.</div>
  </div>

  <div class="cr-figure">
    <img src="{{ '/assets/images/intake-exploded-cad.png' | relative_url }}" alt="Exploded CAD view of Lantern Lure">
    <div class="cr-caption"><b>Exploded CAD View.</b> Shows how the acrylic plate, ridge sets, roof, central tube, and fasteners relate to each other.</div>
  </div>

  <div class="cr-figure">
    <img src="{{ '/assets/images/intake-light-mechanism-dark.png' | relative_url }}" alt="Lantern Lure light mechanism in a dark room">
    <div class="cr-caption"><b>Light Mechanism.</b> Demonstrates the light source that attracts SLF toward the trap top.</div>
  </div>

  <div class="cr-figure">
    <img src="{{ '/assets/images/intake-final-assembly.png' | relative_url }}" alt="Final assembled Lantern Lure prototype">
    <div class="cr-caption"><b>Final Assembly.</b> The completed prototype combines the rotating top, containment path, body, and crank system.</div>
  </div>
</div>

## Assembly Process

The prototype assembly is organized into two main batches. First, the crank and gear assembly is put together so the user can rotate the trap top. Second, the top assembly is built from the clear plate, ridges, roof, and center tube. Once those two assemblies are complete, they are joined with the trap body and lower containment drawer.

## Component List

<div class="cr-table-wrap">
<table class="cr-table">
  <tr>
    <th>Part</th>
    <th>Key Specs</th>
  </tr>
  <tr>
    <td>Ridges #1-9</td>
    <td>0.875 in tall; widths vary from 0.25 in to 1.25 in.</td>
  </tr>
  <tr>
    <td>Roof and wall</td>
    <td>4.5 in radius, matched to the ridge geometry and 3D printed as one piece.</td>
  </tr>
  <tr>
    <td>Crown and evoloid gears</td>
    <td>96-tooth crown gear and 8-tooth pinion gear.</td>
  </tr>
  <tr>
    <td>Crank</td>
    <td>4 in long hand crank for the prototype mechanism.</td>
  </tr>
  <tr>
    <td>Trap body</td>
    <td>9 in diameter and 9.5 in height.</td>
  </tr>
  <tr>
    <td>Containment tub</td>
    <td>295.3 in3 volume for trapped insects.</td>
  </tr>
  <tr>
    <td>Acrylic sheet</td>
    <td>12 in x 12 in x 1/16 in clear scratch- and UV-resistant cast acrylic.</td>
  </tr>
  <tr>
    <td>Fasteners</td>
    <td>M3 bolts and nuts from the TDS bill of materials.</td>
  </tr>
</table>
</div>

## Budget

<div class="cr-table-wrap">
<table class="cr-table">
  <tr>
    <th>Item</th>
    <th>Cost</th>
    <th>Note</th>
  </tr>
  <tr>
    <td>Light</td>
    <td>$19.99</td>
    <td>Light source for SLF attraction.</td>
  </tr>
  <tr>
    <td>3D prints</td>
    <td>$70.62</td>
    <td>PLA parts printed through the RPL.</td>
  </tr>
  <tr>
    <td>Acrylic</td>
    <td>$13.24</td>
    <td>Clear top plate material.</td>
  </tr>
  <tr>
    <td>Wood</td>
    <td>$1.75</td>
    <td>Prototype body/support material.</td>
  </tr>
  <tr>
    <td>Material subtotal</td>
    <td>$105.60</td>
    <td>Approximate raw-material cost for the prototype.</td>
  </tr>
  <tr>
    <td>Laser cutting service</td>
    <td>$31.41</td>
    <td>Service cost for acrylic fabrication.</td>
  </tr>
</table>
</div>

## Next Steps

The next version should replace the hand crank with a motor, investigate solar power, and use a purchased or manufactured gear pair that can survive extended powered operation. Before full vineyard deployment, the design should also be tested with real SLF and with different light types, since there is limited published guidance on which light best attracts SLF at night.
