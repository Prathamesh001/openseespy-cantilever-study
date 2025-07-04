
# ElasticBeamColumn Cantilever Example

This folder contains OpenSeesPy code for simulating a cantilever beam using **ElasticBeamColumn** elements.

It is part of the study:

> **Investigating Meshing Effects and Element Type Selection in Cantilever Beam Simulations with OpenSeesPy**

---

## 📌 Description

This example models a 3 m long cantilever beam fixed at one end and subjected to a 100 N vertical point load at its free end.  

Key aspects:
- Uses **ElasticBeamColumn** element in OpenSeesPy.
- Varies the number of elements from 1 to 10 (mesh refinement study).
- Reports nodal displacements and support reactions.
- Generates and saves plots of the undeformed and deformed shapes.

---

## 🛠️ Requirements

Install required packages using pip:

<pre>
pip install openseespy matplotlib numpy opsvis
</pre>

## 📂 Contents
- cantilever_beamcolumn.py – Main OpenSeesPy script for running the cantilever simulation.
- Generated plots (saved during runs).

## 📈 Expected Results
- Deflection at the free end converges to theoretical value with increasing elements.
- Reaction forces: ~100 N vertical force and ~300 Nm moment at the fixed end.
