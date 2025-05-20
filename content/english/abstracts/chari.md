---
title: "High-precision, high-accuracy macromolecular crystallography"
author: "Ashwin Chari"
affiliation: "Max Planck Institute for Multidisciplinary Sciences"
meta_title: ""
description: ""
image: "/images/authors/CA.jpg"
date: 2025-03-21
categories: ["Talk"]
tags: ["macromolecular", "high-accuracy"]
summary: I introduce a novel concept of high-energy data acquisition with a highly optimized setup and workflow for protein crystallography. I will present how the implementation of these procedures allows us to routinely collect single-crystal datasets at atomic and sub-Å resolution.
draft: false
params:
  math: true
---

#### Ashwin Chari<sup>a</sup> ,\*, Elham Paknia<sup>a</sup>, Alexander Mehr<sup>a</sup>, Emma Newby<sup>a</sup>, Uma L. Dakshinamoorthy<sup>a</sup>, Claus Flensburg<sup>b</sup>, Clemens Vonrhein<sup>b</sup>, Rasmus Fogh<sup>b</sup>, Peter Keller<sup>b</sup>, Thomas R. Schneider<sup>c</sup>, Clemens Schulze-Briese<sup>d</sup>, Gleb Bourenkov<sup>c</sup>, Gérard Bricogne<sup>b</sup>;

##### {{< sub "a" >}}Research Group for Structural Biochemistry and Mechanisms, Max Planck Institute for Biophysical Chemistry, Am Fassberg 11, D-37077 Göttingen, Germany; {{< sub "b" >}}Global Phasing Limited, Sheraton House, Castle Park, Cambridge CB3 0AX, UK; {{< sub "c" >}}EMBL Hamburg Outstation c/o DESY, European Molecular Biology Laboratory, Notkestrasse 85, 22607 Hamburg, Germany; {{< sub "d" >}}DECTRIS Ltd. Täfernweg 1, 5405 Baden-Dättwil, Switzerland

##### e-mail: ashwin.chari@mpinat.mpg.de

This presentation consists of two parts. First, I introduce a novel concept of high-energy data acquisition with a highly optimized setup and workflow for protein crystallography. The setup is implemented at the undulator beamline P14 at the PETRA III storage ring at DESY (Hamburg, Germany). It allows for variable-size top-hat beams, which are particularly important in structural studies of large macromolecular complexes [1,2] and ultra-high-resolution studies of enzymatic mechanisms under precise dose control. The combination of a high-flux collimated mode, with a detector of high quantum efficiency at 26.687 keV increases data quality by reducing radiation damage and enhancing the Signal-to-Noise ratio [3]. To further improve data quality, Global Phasing Ltd.’s workflow has been deployed on P14 through its interface to MXCuBE2 ([4], § 4.4.7). Crystal symmetry and orientation are first determined, then used together with knowledge of the MD3-goniostat’s reorientation capabilities to design a multi-orientation strategy aiming at achieving completeness (no cusps) and uniformity of redundancy, within a “dose budget” adapted to the target resolution. The workflow then directly drives the execution of that strategy via MXCuBE2.

In the second part, I will present how the implementation of these procedures allows us to routinely collect single-crystal datasets at atomic and sub-Å resolution. The precision of these datasets and accuracy in the models derived from them effectively allow us to achieve single-electron accuracy in protein X-ray crystallography. For instance, we can now directly visualize the active site and reaction mechanisms of enzymes by cryo-trapped snapshots. On the basis of these new insights, we are forced to redefine the chemical structure of some enzyme active sites and revise some enzymatic reaction mechanisms. I will discuss how the accurate, detailed visualization of a wide variety of enzyme reaction mechanisms based on these data might benefit from the routine deployment of aspherical atom models in protein crystallography.

### References:

1] Schrader *et al.* (2016) *Science* **353**, 594-598.

[2] Singh *et al.* (2020) *Cell* **180**, 1130-1143.

[3] Storm *et al.* (2021) *IUCrJ* **8(6)**

[4] Oscarsson *et al.* (2019) *Journal of Synchrotron Radiation* **26**, 393-405.