---
layout: project
title: Lantern Lure
description: MAE 2250 project hub for the client pitch, functional prototype, and final client report
image: /assets/images/fly.png
technologies: [Research, Mechanical Design, Prototyping, Testing, CAD]
---

<style>
.ll-hero,
.ll-card {
  border: 1px solid #e1e4dc;
  border-radius: 8px;
  background: #fff;
}

.ll-hero {
  padding: 1.2rem;
  margin: 1rem 0 1.4rem;
  background: #f8faf4;
}

.ll-nav {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: .85rem;
  margin-top: 1rem;
}

.ll-card {
  padding: 1rem;
}

.ll-card a {
  display: block;
  font-weight: 700;
  text-decoration: none;
}

.ll-card span {
  display: block;
  margin-top: .35rem;
  color: #4b4f46;
  font-size: .92rem;
}

@media (max-width: 760px) {
  .ll-nav {
    grid-template-columns: 1fr;
  }
}
</style>

<div class="ll-hero">
<h2>MAE 2250 Overall Project</h2>

<p>
Lantern Lure is a vineyard pest-control concept designed to attract spotted lanternflies away from grapevines, trap them mechanically, and reduce the need for chemical treatment. The project developed through three connected milestones: the client pitch, functional prototype, and client report.
</p>

<div class="ll-nav" aria-label="Lantern Lure milestones">
  <div class="ll-card">
    <a href="{{ site.baseurl }}{% link _projects/2026_Problem_proposal.md %}">Client Pitch</a>
    <span>Original problem framing and proposed light-trap concept.</span>
  </div>

  <div class="ll-card">
    <a href="{{ site.baseurl }}{% link _projects/2026_Functional Prototype – Lanternfly Trap.md %}">Functional Prototype</a>
    <span>Prototype mechanism, fabrication choices, and test evidence.</span>
  </div>

  <div class="ll-card">
    <a href="{{ site.baseurl }}{% link _projects/2026_Client_Report.md %}">Client Report</a>
    <span>Final recommendation, testing summary, assembly, parts, and budget.</span>
  </div>
</div>
</div>

## Project Context

Spotted lanternflies damage grape production by feeding on vines and contaminating harvests. Because separating insects from harvested grapes is not an effective solution, our team focused on prevention: lure the insects away from the vines before they reach the crop.

The final design direction uses light attraction, a rotating clear plate, interlocking ridges, and a central containment path. Testing showed the concept is promising, while also identifying next-step improvements such as motorizing the crank, selecting a durable purchased gear set, and field-testing with real spotted lanternflies.
