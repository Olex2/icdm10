---
title: "Exploring bonding and the impact of non-covalent interactions on
solid-state photoswitching by non-spherical structure refinements"
author: "Lauren Hatcher"
affiliation: "Cardiff University"
meta_title: ""
description: ""
summary: TBC
date: 2025-06-11  
categories: ["Session 10",  "Methods"]
image: "/images/abstracts/hatcher.png"
tags: []
draft: false
weight: 44
params:
  math: true
  tt: 2025-07-17T10:00:50Z

---
#### Lauren E. Hatcher

##### School of Chemistry, Cardiff University, Park Place, Cardiff, CF103AT, UK

##### e-mail: HatcherL1@cardiff.ac.uk

Solid-state photo-switches have a variety of applications including
data-storage, solar energy and photocatalysis.<sup>1-3</sup> Even in
systems that can accommodate movement of whole atoms or molecules,
non-covalent interactions can control various aspects of switching,
including likely reaction pathways, the photo-products obtained or the
excited-state population achieved. This is particularly true of
intermolecular interactions, e.g. hydrogen bonds, that must be broken
throughout the solid to facilitate photo-switching in the
bulk.<sup>4</sup> Thus, non-covalent interactions are often key to
explaining important structure-property correlations.

While single-crystal X-ray diffraction (SCXRD) refinements using the
traditional Independent Atom Model provide atomic-scale information
before, after and even during photo-switching, often information on
non-covalent interactions is unavailable or, at best, can only be
inferred from refined parameters (e.g. bond lengths/angles).
Experimental charge density refinements can directly refine the electron
density based on more accurate, non-spherical models e.g. multipolar
refinements, providing unique understanding of the fine electron
density.<sup>5-7</sup> However, such experiments typically require very
high resolution data (&lt;0.5 Å). As many issues typical for
photocrystallographic studies can significantly limit the diffraction
data quality e.g. light damage, phase transitions or disorder due to
partial excitation, these studies present a significant challenge for
traditional charge density analysis.

More recently, a semi-empirical approaches have emerged that sit between
experimental charge density refinements and ab-initio charge density
calculations.<sup>8</sup> NoSpherA2 (Non-Spherical Atoms in Olex2) is
one such approach that has already been applied to several interesting
crystallographic problems.<sup>9-11</sup> The software utilises
Hirshfeld atom refinement (HAR) to calculate non-spherical atomic form
factors, then refines these non-spherical atom shapes against the
experimental electron density obtained by SCXRD.<sup>8</sup> Through
this combination of quantum chemical calculations and experimental
electron density refinement a greatly improved crystallographic model is
obtained, providing new insight into intra- and intermolecular bonding.
NoSpherA2 has advantages over experimental charge density analysis as it
can be applied to materials that do not diffract to such high resolution
as needed for multipolar refinements, and materials containing disorder.

We here-in present an application of NoSpherA2 to photo-switchable
linkage isomer crystals. Using non-spherical structure refinements, we
uncover the non-covalent interactions present in ground-state and
excited-state isomers and explore the nature of the bonding between the
isomerisable ligand and the metal. This insight can be used to
rationalise key properties, e.g. stability/lifetime of the
photoexcited-state, knowledge that can iteratively be applied to design
new materials tailored for particular applications. The results show the
applicability of NoSpherA2 for photocrystallographic refinements and
recommend its application to other photoswitchable and photocatalytic
materials.

### References:

[1]  Zeng et al., *ACS Catalysis*, 2016, **6**, 7935-7947.

[2]  Tsai et al., *Science*, 2018, 360, **67**.

[3]  Sato, *Nat. Chem.*, 2016, **8**, 644-656.

[4]  Hatcher and Raithby, *CrystEngComm*, 2017, **19**, 6297-6304.

[5]  Stevens and Coppens, *Acta Cryst. A*, 1979, **35**, 536-539.

[6]  Coppens et al., *Acta Cryst. A*, 1979, **35**, 63-72.

[7]  Hansen and Coppens, *Acta Cryst. A*, 1978, **34**, 909-921.

[8]  Kleemiss et al., *Chem. Sci.*, 2021, **12**, 1675-1692.

[9]  Saunders et al., *CrystEngComm*, 2021, **23**, 6180-6190.

[10] Chocolatl Torres et al., *Acta Cryst. E*, 2021, **77**, 681-685.

[11] Novelli et al., *Acta Cryst. B*, 2021, **77**, 785-800.

