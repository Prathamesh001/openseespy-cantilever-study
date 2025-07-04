# openseespy-cantilever-study
Comparative study of cantilever beam modeling in OpenSeesPy using ElasticBeamColumn and Quadrilateral Plane Stress elements.
# OpenSeesPy Cantilever Study

This repository contains the code and data for the paper:

**“Investigating Meshing Effects and Element Type Selection in Cantilever Beam Simulations with OpenSeesPy”**

It provides a comparative study of cantilever beam analysis using:
- 1D line elements (ElasticBeamColumn)
- 2D continuum elements (Quadrilateral Plane Stress)

---

## 📌 Project Overview

The project analyzes how mesh density and element type affect:
- Tip deflection
- Maximum bending moment at the fixed end
- Maximum stress at the support section

Key findings show that while ElasticBeamColumn elements match theoretical predictions with minimal meshing, Quadrilateral Plane Stress elements require very fine meshes for comparable accuracy.

---

## 🛠️ Contents

- `ElasticBeamColumn/`
  - Example OpenSeesPy script for 1D beam element analysis.
- `QuadrilateralPlaneStress/`
  - Scripts for 2D plane stress meshing, loading, analysis.
- `Results/`
  - Plots of deformation, stress distribution, bending moment diagrams.
- `Paper/`
  - PDF of the paper.

---

## 📈 Example Figures

| ElasticBeamColumn Model                   | Quadrilateral Plane Stress Model              |
|-------------------------------------------|-----------------------------------------------|
| ![ElasticBeamColumn Example](ElasticBeamColumn/sample_plot.png) | ![Quad Example](QuadrilateralPlaneStress/sample_plot.png) |

---

## 💻 Requirements

- Python 3.x
- [OpenSeesPy](https://openseespydoc.readthedocs.io/en/latest/)
- matplotlib
- numpy
- opsvis

Install dependencies:

<pre>
pip install openseespy matplotlib numpy opsvis
</pre>

## 📜 Citation

If you use this code or refer to this study, please cite:

> Varma, P. (2025). Investigating Meshing Effects and Element Type Selection in Cantilever Beam Simulations with OpenSeesPy.  

## 📬 Contact
For questions, feel free to open an issue or contact:

Prathamesh Varma  
Website: www.PrathameshVarma.wordpress.com  
E-mail📧: prathamesh66523@gmail.com  
LinkedIn: https://www.linkedin.com/in/prathamesh-varma-45bbb0333/
