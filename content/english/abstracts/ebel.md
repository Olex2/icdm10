---
title: "Implementation of density matrix tight-binding (PTB) for quantum crystallographic refinement in NoSpherA2"
author: "Ben Ebel"
affiliation: "RWTH Aachen"
meta_title: ""
description: ""
summary: The computational cost associated with simulations of large ... presents a significant challenge to the adoption of quantum crystallographic refinement as a standard refinement tool. A possibility to improve computational time, without sacrificing much accuracy is the use of semiempirical methods, which use empirical parameters..
date: 2025-05-16  
categories: ["Talk"]
image: "/images/authors/BEebel.png"
tags: ["NOSPHERA2", "HAR", "PTB"]
draft: false
params:
  math: true
---
#### Ben Ebel, Daniel Brüx, Florian Kleemiss

##### Institute of Inorganic Chemistry, RWTH Aachen University, Landoltweg 1, 52074 Aachen, Germany

##### e-mail: ben.ebel@ac.rwth-aachen.de

The computational cost associated with simulations of large or electron-rich systems, coupled with the potential for an unlimited number of combinations for the chosen level of theory, presents a significant challenge to the adoption of quantum crystallographic refinement as a standard refinement tool. A possibility to improve computational time, without sacrificing much accuracy is the use of semiempirical methods, which use empirical parameters to approximate the ab-initio approach. One method is the tight-binding (TB) approach[1], which assumes that electrons are tightly bound to the core instead of acting as a free electron gas, an assumption quite suitable for molecular crystals. Energetic contributions of a given chemical system are split into approximate contributions leading to a large decrease in computational steps. Errors from this are then accounted for through empirical parameters introduced in the method.

{{< absfig src="/images/abstracts/ebel.png" alt="Comparison of the different methods for Co110[8] (Level: 0.330 eÅ^-3)." width="100%">}}

PTB[2] is a method developed by Grimme et al. to reproduce the density matrix P of the high-level range-separated hybrid density functional with an integrated double ξ basis set ωB97X-3c[3]. This matrix can then be partitioned into atomic contributions e.g. using Hirshfeld’s stockholder partition scheme to yield more accurate non-spherical atomic form factors[4–6]. We herein present the implementation of the method into NoSpherA2[7], the non-spherical refinement suite within Olex2[8] and present first results.



### References:

[1] Jelsch, Miteva, Guillot (2023) European Patent EP004195210A1.

[2] Williams … Jhoti. 2003, *Nature*,  **424**, 464-468.

[3] Domagala, … Guillot, Jelsch. 2012. *Acta Cryst*. **A68**,337-351.

[4] Vukovic, … Guillot, Jelsch. 2021. *Acta Cryst*. **D77**, 1292-1304.

[5] Sparrow … DiStasio. 2021. *J. Chemical Physics*, **155(18)**, 184303.