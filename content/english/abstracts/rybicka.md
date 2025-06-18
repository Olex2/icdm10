---
title: "Advancements in the Aspherical Electron Density Modeling for Small Molecules and Macromolecules with the MATTS Data Bank"
author: "Paulina Rybicka"
affiliation: "University of Warsaw"
meta_title: ""
description: ""
summary: Recent efforts have focused on extending the MATTS data bank to cover unusual chemical topologies in small molecules. A key component involved machine learning-driven tools...
date: 2025-05-13  
categories: ["Session 8",  "Methods"]
image: "/images/blank.png"
tags: ["electron density", "aspherical", "TAAM", "Multipole Model", "MATTS databank", "machine learning", "macromolecules", "protein dictionary"]
draft: false
weight: 32
params:
  math: true
  tt: 2025-07-16T09:00:50Z
---

#### Paulina Maria Rybicka<sup>a</sup>, Vladislav Ignat’ev<sup>a</sup>, Clement Grandgirard<sup>b</sup>, Michał Leszek Chodkiewicz<sup>a</sup>, Marta Kulik<sup>a</sup>, Paulina Maria Dominiak<sup>a</a>

##### <sup>a</sup>University of Warsaw, Faculty of Chemistry, Biological and Chemical Research Centre, ul. Żwirki I Wigury 101, 02-089 Warsaw, Poland.; <sup>b</sup>CESI Graduate School of Engineering, 6 Rue Bois du Chêne le Loup, 54500, Vandœuvre-lès-Nancy, France

##### e-mail: p.rybicka@uw.edu.pl
Accurate electron density modelling is essential for obtaining the three-dimensional structure of molecules, understanding chemical bonding and interactions, and calculating electron density properties. The electron density description is greatly enhanced by the use of models that implement the aspherical scattering factors and data banks of transferable electron density parameters, which in our work are the Multipole Model [1] and the MATTS data bank [2,3].

Recent efforts have focused on extending the MATTS data bank to cover unusual chemical topologies (rare functional groups, complex ring systems) in small molecules. A key component involved machine learning-driven tools to identify topology- and density-based similarities, define new atom types, and explore factors influencing description of the apparent pseudosymmetry of atomic electron density, such as local coordinate systems and symmetry constraints. The resulting updated and restructured MATTS2025 data bank includes an expanded model molecules set, new atom types, enhanced refinement accuracy [4], and improved treatment of local symmetry.

Although multipole modeling is usually applied to small molecules, growing interest in macromolecular applications faces challenges in the atomic model such as disorder, clashes, distorted geometry, missing atoms, and time-consuming atom type assignment with atomic coordinates. To address this, we analyzed high-quality structures from the RCSB Protein Data Bank and developed a dictionary of residues in proteins, RNA, DNA, and common ligands with reliable atom type assignments including different protonation states. The use of the dictionary will reduce the computational cost of the atom type assignment process and allow for the reconstruction of electron density in macromolecules with lower resolution and structural imperfections.

Collectively, these developments contribute to a unified framework for multipole-based electron density modelling for small and large molecules, integrating data bank development, machine learning, and advanced density analysis.

This research was funded by National Science Centre, Poland UMO-2020/39/I/ST4/02904 and UMO-2023/49/N/ST4/02967.

### References:

[1] Hansen, N.K. et al. (1978). *Acta Cryst*. **A34**, 909-921.

[2] Jha, K.K. et al. (2022). *J. Chem. Inf. Model*. **62**, 3752-3765.

[3] Rybicka, P.M. et al. (2022). *J. Chem. Inf. Model. **62**, 3766-3783.

[4] Ignat’ev, V.M. et al. (2024). *J. Appl. Cryst*. **57**, 1884-1895.