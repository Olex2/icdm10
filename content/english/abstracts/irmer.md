---
title: Correlations in Multipole Refinements
author: "Regine Herbst-Irmer"
affiliation: "Georg-August-Universität Göttingen"
meta_title: ""
description: ""
summary: The Hansen-Coppens Multipole Model partitions the electron density into three components -- core density, spherical valence density and aspherical valence density.
date: 2025-05-16
image: "/images/blank.png"
categories: ["Talk", "Data Quality"]
tags: ["multipolar refinement", "anharmonic motion", "correlations"]
draft: false

params:
  math: true
  tt: 2025-07-14T13:18:50Z

---

#### Regine Herbst-Irmer

##### Institut für Anorganische Chemie, Georg-August-Universität Göttingen, Tammannstraße 4, D-37077 Göttingen, Germany

##### e-mail: rherbst@chemie.uni-goettingen.de

The Hansen-Coppens Multipole Model partitions the electron density into three components: core density, spherical valence density and aspherical valence density.[1]

The aspherical component is modelled using spherical harmonics and *κ* and *κ*’ parameters accounting for contraction and expansion of the valence shell. Including harmonics up to the hexadecapole level requires up to 25 additional parameters per atom for monopole and multipole populations, and the *κ* and *κ*′ parameters. While high-resolution data should support such refinements, many of the valence density parameters are predominantly determined from the low-order data and some of the parameters are highly correlated, like the monopole population and the *κ* parameter of one particular atom.[2] Stevens & Coppens also highlighted the strong influence of the correct determination of the scale factor *k* on residual densities, particularly at nuclear positions, which also impacts monopole populations.[3]

Anharmonic motions of atoms can be modelled via Gram-Charlier coefficients but then additional 10 parameter for third and further 15 for fourth order coefficients are added to the refinement. Literature reports on high correlations between these coefficients and the multipole populations of the same atom.[4] Nonetheless, successful refinements of Gram-Charlier coefficients without these correlations are known, showing instead correlations of third order Gram-Charlier coefficients with the positional parameters *x*, *y*, *z* and of fourth order coefficients with *U*ij values.[5] Both, *Uij* and Gram-Charlier coefficients can inherently absorb residual density caused by various effects, such as disorder. It is therefore important to validate their physical plausibility during refinement.

Disorder should be avoided, however, often the most interesting structures cannot be crystallized without any disorder. In such cases, a TAAM (transferable aspherical atom model) approach, using databases like the INVARIOM database [6] for multipole parameters, proves to be effective. If the resolution of a data set is still high enough for a multipole refinement, a combination of TAAM for the disordered parts and experimentally refined multipoles for the main part of the structures can be used.[7]

This talk will illustrate these considerations with relevant structural examples.


### References:

[1] Hansen, N. K. & Coppens, P. (1978). *Acta Cryst.* A**34**, 909–921.

[2] Volkov, A., Abramov, Y. A. & Coppens, P. (2001). *Acta Cryst*. A**57**, 272–282.

[3] Stevens, E. D. & Coppens, P. (1975). *Acta Cryst*. A**31**, 612–619.

[4] Mallinson, P. R., Koritsanszky, T., Elkaim, E., Li, N. & Coppens, P. (1988*). Acta Cryst.* A**44**, 336–343.

[5] Herbst-Irmer, R., Henn, J., Holstein, J. J., Hübschle, C. B., Dittrich, B., Stern, D., Kratzert, D. & Stalke, D. (2013*). J. Phys. Chem. A*, **117**, 633–641.

[6] Dittrich, B., Hübschle, C. B., Pröpper, K., Dietrich, F., Stolper, T. & Holstein, J. J. (2013). *Acta Cryst*. B**69**, 91–104.

[7] Kratzert, D., Leusser, D., Holstein, J. J., Dittrich, B., Abersfelder, K., Scheschkewitz, D. & Stalke, D. (2013). *Angew. Chem. Int. Ed*., **52**, 4478-4482.