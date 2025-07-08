---
title: "From Frames to Intensity Data"
author: "Loes Kroon-Batenburg"
affiliation: "Utrecht University"
meta_title: ""
description: ""
image: "/images/blank.png"
date: 2025-05-02
categories: ["Session 1", "Data Quality"]
tags: ["data reduction", "intensity data", "raw diffraction data", "imgCIF", "metadata"]
draft: false
weight: 23
summary: Data collection on single crystals starts with recording raw diffraction images (data frames). These 'raw' data frames have usually already been corrected for spatial distortions and non-uniformities of the detector response.
params:
  math: true
  tt: 2025-07-14T09:40:50Z
---

#### Loes Kroon-Batenburg

##### Structural Biochemistry, Bijvoet Centre for Biomolecular Research Utrecht University Universiteitsweg 99, 3584 CG Utrecht The Netherlands

e-mail: l.m.j.kroon-batenburg@uu.nl

Data collection on single crystals starts with recording raw diffraction images (data frames). These 'raw' data frames have usually already been corrected for spatial distortions and non-uniformities of the detector response.

Diffraction occurs in the form of Bragg reflections, that are seen as bright spots on the detector. Ideally, we can index these, find the crystal lattice, and integrate their intensities by box summation or profile fitting at predicted positions, while subtraction (incoherent) background scattering [1]. However, reflections can also have low intensities (weak), especially at high resolutions, and we have to find the best way of recording their intensities accurately.

Data collection strategies usually consist of different scans made possible by use of the goniometer of the diffraction equipment. The aim is to achieve large redundancy of the data by letting reflections traverse in different ways through the Ewald sphere. This reduces systematic errors in the processed Bragg intensities. However, it requires that geometrical corrections such as the Lorentz and polarization and absorption corrections are applied. Particular attention will be given to scaling the reflection data and the estimation of standard deviations.

In every day's practice crystals are not strictly regular, ordered arrays of unit cells, but show dynamic or static disorder of the lattice or its contents. This gives rise to Thermal Diffuse Scattering (TDS), diffuse scattering in the shape of streaks, circles/triangles or clouds. This can be a research subject on itself, but we have to realize that these effects influence the results we obtain from our data processing method for obtaining Bragg reflections [2].

The workflow in chemical crystallography is well established and procedures such as checkCIF [3] are in place, which provides maximum trust in crystallographic results. However, in the more complicated cases, such as twinned crystals, crystals that produce diffuse scattering, incommensurately modulated crystals or high-resolution charge density studies different approaches may still be used. The community would be served by the open availability of the raw diffraction data. Currently, ample possibilities are available to archive raw diffraction data [4]. In doing so it is very important that the archiving follows the FAIR data principles [5] that the data are Findable, Accessible, Interoperable and Reusable. To ensure reusability,

metadata should be provided that are accurate and complete and at least sufficient. One way to do that is to capture metadata in imgCIF format [6,7,8] which includes the appropriate data names for the required set of metadata list. A researcher may want to publish his raw diffraction data in a permanent archive and is strongly encouraged to do so. Zenodo is an easy and sustainable solution to archiving data in chemical crystallography.

### References:

[1] Schreurs, A. M. M., Xian, X. & Kroon-Batenburg, L. M. J. (2010). *J. Appl. Cryst*. **43**, 70–82.

[2] Niepotter, B., Herbst-Irmer, R. & Stalke, D. (2015). *J. Appl. Cryst*. **48**, 1485-1497

[3] IUCr checkCIF, <https://checkcif.iucr.org>

[4] Helliwell, J. R., Hester, J. R., Kroon-Batenburg, L. M. J., McMahon, B. & Storm, S. L. S. (2024). *IUCrJ*, **11**, 464-47

[5] Wilkinson et al. (2016). *Sci. Data*, **3**, 160018.

[6] Bernstein, H. J. & Hammersley, A. P. (2005). *International Tables For Crystallography*, **Vol. G**, edited by S. R. Hall & B. McMahon, pp. 37–43. Chester: International Union of Crystallography

[7] Hammersley, A. P., Bernstein, H. J. & Westbrook, J. D. (2005). *International Tables For Crystallography*,** Vol. G**, edited by S. R. Hall & B. McMahon, pp. 444–458. Chester: International Union of Crystallography

[8] Kroon-Batenburg, L. M. J., Helliwell, J. R. & Hester, J. R. (2022).* IUCrData*, **7**