---
layout: project
title: Functional Prototype – Lanternfly Trap
description: First functional prototype of a lanternfly trapping mechanism using a rotating disk and ridge system
image: /assets/images/exploded_view.png
technologies: [Mechanical Design, Prototyping, 3D Printing, Testing, CAD]
---

<style>
.fp-hero,.fp-card,.fp-test,.fp-figure,.fp-table-wrap {
  border: 1px solid #e7e7e2;
  border-radius: 16px;
  background: #fff;
}
.fp-hero,.fp-card,.fp-test { padding:1.2rem; margin:1rem 0;}
.fp-hero {background:linear-gradient(135deg,#f7f8f2 0%,#ffffff 55%,#f3f7f5 100%);}

.fp-nav {display:grid;grid-template-columns:repeat(2,1fr);gap:1rem;}
.fp-nav-item {padding:1rem;border-radius:12px;border:1px solid #ddd;}

.fp-gallery {
  display:grid;
  grid-template-columns:repeat(2,1fr);
  gap:1rem;
  margin:1rem 0;
}

.fp-figure {
  overflow:hidden;
}

.fp-figure img {
  width:100%;
  border-radius:12px;
}

.fp-figcap {
  font-size:.9rem;
  padding:.4rem;
  color:#444;
}

.fp-table {width:100%;border-collapse:collapse;}
.fp-table th,.fp-table td {padding:.6rem;border-bottom:1px solid #eee;}

.fp-note {background:#f8fbf3;padding:.8rem;border-left:4px solid #799d4b;}
</style>

<div class="fp-hero">
<h2>Functional Prototype – Lanternfly Trap</h2>

<p>
This prototype was designed to test a mechanical system for capturing and eliminating spotted lanternflies using a rotating disk with ridges.
</p>

<div class="fp-nav">
  <div class="fp-nav-item">
    <a href="#overview"><b>Overview</b></a><br>
    <span>Purpose and design</span>
  </div>

  <div class="fp-nav-item">
    <a href="#testing"><b>Testing</b></a><br>
    <span>Experiments and results</span>
  </div>
</div>

</div>


---

<h2 id="overview">Prototype Overview</h2>

The system uses rotation and geometry to either force bugs into a tube or squash them.

### Key Components
- Rotating acrylic plate  
- Ridges  
- Roof  
- Tube  
- Fastening + string system  

---

## Prototype Gallery

<div class="fp-gallery">

<div class="fp-figure">
<img src="{{ '/assets/images/exploded_view.png' | relative_url }}">
<div class="fp-figcap"><b>Exploded CAD View.</b> Shows all major components and assembly layout.</div>
</div>

<div class="fp-figure">
<img src="{{ '/assets/images/prototype_full.jpg' | relative_url }}">
<div class="fp-figcap"><b>Full Prototype.</b> Assembled device with rotating disk and ridge system.</div>
</div>

<div class="fp-figure">
<img src="{{ '/assets/images/ridges.png' | relative_url }}">
<div class="fp-figcap"><b>Ridges Detail.</b> Direct bugs inward or squash them.</div>
</div>

<div class="fp-figure">
<img src="{{ '/assets/images/tube.png' | relative_url }}">
<div class="fp-figcap"><b>Tube + Containment.</b> Guides bugs into collection area.</div>
</div>
</div>



---

## Design Components

| Component | Purpose |
|----------|--------|
| Acrylic Plate: | Rotates and drives motion |
| Ridges: | Move or squash bugs |
| Roof: | Prevents escape |
| Tube: | Transfers bugs |
| Fasteners: | Enable rotation |

---

<h2 id="testing">Testing</h2>

<div class="fp-note">
Testing focused on evaluating the performance, durability, and effectiveness of the lanternfly trapping mechanism under realistic operating conditions.
</div>

---

### Test 1: Light Transmission
**Purpose:**  
To determine whether sufficient light passes through the acrylic plate to effectively attract lanternflies. Light attraction is critical to the success of the trap.

**Procedure:**  
The test was conducted in a dark room using a phone flashlight and a second phone equipped with a light intensity (lux) measurement app. Measurements were taken at a fixed distance of 5 inches:
- First without the acrylic plate  
- Then with the acrylic plate placed between the light source and sensor  

**Results:**  
- Without acrylic: 740 lux  
- With acrylic: 610 lux  
- Light transmission: ~83%

**Outcome:**  
<span class="fp-status">Successful</span> — The system exceeded the required threshold of 50% light transmission.

**Implications:**  
No changes are needed to the acrylic material. The current thickness and transparency are sufficient for attracting lanternflies without causing overheating.

---

### Test 2: Shake Test (Stability)

**Purpose:**  
To evaluate whether the device maintains structural integrity under conditions similar to wind or environmental vibrations.

**Procedure:**  
The prototype was shaken for 10 seconds at approximately 5 Hz (5 shakes per second). Observations were made during and after the test to identify any loosening or structural failures.

**Results:**  
- The structure remained intact  
- No major components failed  
- Nuts at the corners loosened slightly  

**Outcome:**  
<span class="fp-status warn">Partially Successful</span>

**Implications:**  
While the overall structure is durable, fastening reliability needs improvement. Future iterations should use locking mechanisms such as nylon insert nuts to prevent loosening under repeated vibrations.

---

### Test 3: Speed Test (Rotational Performance)

**Purpose:**  
To determine whether the rotating mechanism can operate at high speeds without failure or performance degradation.

**Procedure:**  
The disk was spun manually using the string mechanism as fast as possible. Rotational speed was estimated by measuring time per revolution.

**Results:**  
- Achieved approximately 7.25 rad/s  
- No structural damage occurred  
- Minor friction observed between ridges and roof  

**Outcome:**  
<span class="fp-status warn">Functional with Minor Issues</span>

**Implications:**  
The system is capable of high-speed operation, but consistency is limited by the manual actuation method. Future improvements should include a motorized system and better alignment of ridges to reduce friction.

---

### Test 4: Throw Test (Impact and Capture)

**Purpose:**  
To simulate lanternflies landing on the device at realistic speeds and evaluate capture effectiveness.

**Procedure:**  
Small bug-shaped objects (0.5–1 inch) were thrown at the rotating device at approximately 3 m/s. The behavior of the objects upon impact was observed.

**Results:**  
- All objects were successfully captured  
- No structural damage occurred  
- The roof remained stable under impact  

**Outcome:**  
<span class="fp-status">Highly Successful</span>

**Implications:**  
The design is highly effective at capturing incoming targets. The ridge system performs well under dynamic conditions and does not require modification.

---

### Test 5: High Volume Test (Throughput)

**Purpose:**  
To determine whether the system can handle multiple bugs entering the trap simultaneously.

**Procedure:**  
Multiple bug-sized objects were placed into the system at the same time to simulate real-world conditions.

**Results:**  
- Up to 6 smaller objects (0.5 inch) passed through successfully  
- Larger objects (1 inch) became stuck at the tube entrance  

**Outcome:**  
<span class="fp-status warn">Partially Successful</span>

**Implications:**  
The tube opening is slightly too small for larger targets. Increasing the opening size by approximately 0.25 inches will improve performance and prevent clogging.

---

### Test 6: Tolerance Test (Assembly Fit)

**Purpose:**  
To evaluate how well the manufactured components fit together and whether tolerances are appropriate.

**Procedure:**  
The prototype was assembled and inspected for fit, stability, and need for additional fastening methods.

**Results:**  
- All parts fit together successfully  
- Excess glue was required to secure ridges  

**Outcome:**  
<span class="fp-status warn">Needs Improvement</span>

**Implications:**  
The tolerances are slightly too loose. Future designs should tighten tolerances by approximately 0.01 inches to reduce reliance on adhesives and improve assembly quality.

---

## Summary of Testing Insights

- The trapping mechanism is **functionally effective** and performs well in dynamic conditions  
- The structure is **durable**, but fastening methods need improvement  
- **Geometry and sizing** (tube opening, tolerances) are the main areas for refinement  
- The system is ready for **next iteration improvements**, not a redesign  

<div class="fp-note">
Overall, testing validated the core concept while providing clear, measurable directions for improving reliability, consistency, and manufacturability in the next prototype.
</div>

## Success Criteria

| Criterion | Status |
|----------|--------|
| Light transmission | ✅ Met |
| Multi-bug transport | ⚠️ Partial |
| Structural durability | ✅ Met |
| Squish ability | ✅ Met |

---

## Reflection

This prototype validated that a mechanical trapping system can effectively manipulate and capture lanternflies. The rotating ridge mechanism proved highly effective, especially under impact conditions.

However, improvements are needed in tolerance precision, fastening reliability, and handling of larger objects. These insights directly guide the next design iteration.