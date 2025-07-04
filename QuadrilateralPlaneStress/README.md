# Quadrilateral Plane Stress Cantilever Example

This folder contains OpenSeesPy code for simulating a cantilever beam using **2D Quadrilateral Plane Stress** elements.

It is part of the study:

> **Investigating Meshing Effects and Element Type Selection in Cantilever Beam Simulations with OpenSeesPy**

---

## 📌 Description

This example models a 3 m long cantilever beam with a 0.1 m height cross-section, fixed at one end and subjected to a 100 N vertical point load at its free end.  

Key aspects:
- Uses **Quadrilateral Plane Stress** elements in OpenSeesPy.
- Performs a mesh refinement study across 10 iterations, increasing elements along length and height.
- Computes and records:
  - Tip deflection
  - Bending moment at the support section
  - Maximum stress at the support section
- Generates and saves plots of undeformed and deformed shapes, stress distributions, and bending moment diagrams.

---

## 🛠️ Requirements

Install required packages using pip:

<pre>
pip install openseespy matplotlib numpy opsvis
</pre>

## 📂 Contents
- cantilever_quad_element.py – Main OpenSeesPy script performing the mesh refinement study.
- Generated plots:
- Node numbers
- Element connectivity
- Deformed shapes
- Stress diagrams
- Bending moment diagrams
- Text output with iteration summaries.

## 📈 Expected Results
- Tip deflection decreases slightly and converges as mesh density increases.
- Bending moment at the fixed end approaches theoretical ~300 Nm with finer meshes.
- Maximum stress at the support section becomes more consistent with mesh refinement.
