---
layout: project
title: Lantern Lure
description: Client-focused engineering design project for a light-based spotted lanternfly trapping system
image: /assets/images/fly.png
technologies: [Mechanical Design, Client Report, Functional Prototyping, CAD, Testing]
---

<style>
.ll-hero,.ll-section,.ll-callout,.ll-media,.ll-table-wrap {
  border: 1px solid #e4e6df;
  border-radius: 8px;
  background: #fff;
}

.ll-hero,.ll-section,.ll-callout {
  padding: 1rem;
  margin: 1rem 0;
}

.ll-hero {
  background: #f7f8f2;
}

.ll-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 1rem;
  margin: 1rem 0;
}

.ll-media {
  overflow: hidden;
}

.ll-placeholder {
  min-height: 190px;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  padding: 1rem;
  background: #eef4e8;
  color: #2f3a2f;
  font-size: .92rem;
}

.ll-media img {
  width: 100%;
  display: block;
}

.ll-media img + .ll-placeholder {
  display: none;
}

.ll-caption {
  padding: .65rem;
  font-size: .9rem;
  color: #444;
}

.ll-callout {
  border-left: 4px solid #6f8f45;
  background: #f8fbf3;
}

.ll-table {
  width: 100%;
  border-collapse: collapse;
}

.ll-table th,.ll-table td {
  padding: .6rem;
  border-bottom: 1px solid #eceee8;
  text-align: left;
  vertical-align: top;
}

@media (max-width: 700px) {
  .ll-grid {
    grid-template-columns: 1fr;
  }
}
</style>

<div class="ll-hero">
<h2>Lantern Lure</h2>

<p>
Lantern Lure is a client-focused engineering design project developed to reduce spotted lanternfly damage in vineyards. The design uses light attraction, a protective housing, and a rotating ridge mechanism to draw insects away from grapevines and move them into a containment path before they can damage crops.
</p>

<p>
The final portfolio combines the original client proposal with the functional prototype work: identifying the client need, defining measurable design requirements, building a testable mechanism, and using prototype data to guide the next design iteration.
</p>
</div>

## Project Need

Spotted lanternflies are an invasive pest that feed on grapevines and threaten vineyard yield and fruit quality. For a vineyard client, the most useful solution is not only a trap that kills insects, but a system that can be placed around vulnerable growing areas, attract lanternflies away from crops, and operate with limited chemical intervention.

The design challenge was to create a perimeter-based trapping concept that could attract lanternflies using light, physically prevent escape, and remain simple enough to prototype and improve through testing.

<div class="ll-callout">
<b>Client goal:</b> protect grape production by intercepting spotted lanternflies before they reach the vines, while keeping the design practical, low-cost, and safer than broad chemical treatment.
</div>

## Design Approach

The proposed system combines three main functions:

- <b>Attraction:</b> a light source draws lanternflies toward the trap, especially in low-light conditions.
- <b>Capture:</b> the roof and tube geometry guide insects into the device and reduce the chance of escape.
- <b>Removal:</b> a rotating acrylic plate with ridges moves insects toward the tube and can crush or force them into containment.

Early work focused on the overall client proposal and problem definition. The functional prototype then narrowed the scope to the mechanical capture mechanism so the team could test whether the moving plate, ridges, roof, and tube could work together.

## Prototype Gallery

Add the following images to `assets/images/` using these exact filenames. I placed each one where it best supports the story of the project.

<div class="ll-grid">
  <div class="ll-media">
    <img src="{{ '/assets/images/intake-exploded-cad.png' | relative_url }}" alt="Exploded CAD assembly of the Lantern Lure prototype" onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';">
    <div class="ll-placeholder"><b>intake-exploded-cad.png</b><br>Place the exploded CAD assembly here.</div>
    <div class="ll-caption"><b>Exploded CAD Assembly.</b> Shows the full component layout, including the acrylic plate, roof, ridges, tube, and fasteners.</div>
  </div>

  <div class="ll-media">
    <img src="{{ '/assets/images/intake-final-assembly.png' | relative_url }}" alt="Full assembled Lantern Lure functional prototype" onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';">
    <div class="ll-placeholder"><b>intake-final-assembly.png</b><br>Place the full assembled prototype here.</div>
    <div class="ll-caption"><b>Final Assembly.</b> Shows the complete functional prototype as built for testing.</div>
  </div>

  <div class="ll-media">
    <img src="{{ '/assets/images/intake-light-mechanism-dark.png' | relative_url }}" alt="Lantern Lure light mechanism glowing in a dark room" onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';">
    <div class="ll-placeholder"><b>intake-light-mechanism-dark.png</b><br>Place the dark-room light mechanism image here.</div>
    <div class="ll-caption"><b>Light Attraction Mechanism.</b> Demonstrates how the trap uses light to lure spotted lanternflies toward the capture system.</div>
  </div>

  <div class="ll-media">
    <img src="{{ '/assets/images/intake-cardboard-prototype.png' | relative_url }}" alt="Cardboard prototype for the Lantern Lure trap" onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';">
    <div class="ll-placeholder"><b>intake-cardboard-prototype.png</b><br>Place the cardboard prototype image here.</div>
    <div class="ll-caption"><b>Cardboard Prototype.</b> Documents the early physical model used to think through scale, geometry, and user-facing form before the functional build.</div>
  </div>
</div>

## Functional Prototype

The prototype tested whether the rotating mechanism could move bug-sized objects through the trap while staying structurally stable. The main components were:

- Rotating acrylic plate
- Ridge system
- Roof structure
- Tube and containment path
- Fasteners and string-based actuation

The acrylic plate provided a transparent surface for light transmission while also acting as the moving part of the trap. Ridges on the plate created the mechanical interaction needed to push lanternflies inward or crush them. The roof helped keep targets in the device, and the tube created a path into containment.

## Testing Summary

<div class="ll-table-wrap">
<table class="ll-table">
  <tr>
    <th>Test</th>
    <th>What It Checked</th>
    <th>Result</th>
  </tr>
  <tr>
    <td>Light Transmission</td>
    <td>Whether enough light passed through the acrylic to attract lanternflies.</td>
    <td>The acrylic transmitted about 83% of the light, exceeding the 50% goal.</td>
  </tr>
  <tr>
    <td>Shake Test</td>
    <td>Whether the structure could withstand vibration similar to wind or outdoor disturbance.</td>
    <td>The structure stayed intact, but some nuts loosened.</td>
  </tr>
  <tr>
    <td>Speed Test</td>
    <td>Whether the rotating plate could spin quickly without failing.</td>
    <td>The mechanism reached about 7.25 rad/s with minor friction between the ridges and roof.</td>
  </tr>
  <tr>
    <td>Throw Test</td>
    <td>Whether bug-sized objects could be captured during impact.</td>
    <td>All test objects were captured and the roof stayed stable.</td>
  </tr>
  <tr>
    <td>High Volume Test</td>
    <td>Whether multiple objects could pass through the system at once.</td>
    <td>Six smaller objects passed through, but larger objects could get stuck at the tube opening.</td>
  </tr>
  <tr>
    <td>Tolerance Test</td>
    <td>Whether manufactured parts fit together cleanly.</td>
    <td>The parts assembled, but tighter tolerances would reduce the need for glue.</td>
  </tr>
</table>
</div>

## Results and Improvements

Testing showed that the Lantern Lure concept is mechanically promising. The light transmission test supported the acrylic material choice, and the throw test showed that the ridge mechanism can capture incoming targets. The prototype also revealed practical next steps: use locking fasteners, enlarge the tube opening by about 0.25 inches, tighten part tolerances by about 0.01 inches, and consider motorized rotation for more consistent operation.

The strongest result was that the project moved from a client proposal into a working mechanism with measurable performance data. Instead of requiring a full redesign, the prototype identified specific improvements for reliability, manufacturing, and outdoor use.

## Reflection

This project strengthened my ability to connect client needs with engineering decisions. The proposal stage required research into spotted lanternfly behavior and vineyard impact, while the prototype stage required hands-on iteration, CAD planning, fabrication, and testing. Lantern Lure demonstrates how an early design concept can become a functional prototype when the problem is translated into clear requirements and each test is tied back to the client.
