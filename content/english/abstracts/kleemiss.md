---
title: "Modern Diffractometers & Modern Models"
author: "Florian Kleemiss"
affiliation: "RWTH Aachen"
meta_title: ""
description: ""
image: "/images/abstracts/kleemiss.jpg"
date: 2025-05-21
categories: ["Talk", "Data Quality"]
tags: ["data quality", "automation"]
draft: false
summary: In-house diffractometers and synchrotron beamlines provide extremely high-intensity primary beams, with detectors becoming faster, larger, and more widely available. The question arises as to whether automation will lead to a situation where datasets are directly forwarded to repositories, carrying the associated risk of creating “damaged” database entries.

params:
  math: true
  tt: 2025-07-14T13:18:50Z

---

#### Florian Kleemiss

##### Institute of Inorganic Chemistry, RWTH Aachen University, Landoltweg 1a, 52074 Aachen, Germany

e-mail: florian.kleemiss@ac.rwth-aachen.de

In-house diffractometers and synchrotron beamlines provide extremely high-intensity primary beams, with detectors becoming faster, larger, and more widely available.[1–4] This enhanced measurement capacity facilitates access to diffraction data from smaller or less diffracting crystals in increasingly shorter timeframes. Meanwhile, various advanced modeling techniques and automation enable the analysis of acquired data in quicker timeframes with reduced human involvement.[5–7]

The question arises as to whether automation will lead to a situation where datasets are directly forwarded to repositories, carrying the associated risk of creating “damaged” database entries. Alternatively, the interplay between rapid data collection, automated analysis, and data quality assessment automation may provide a feedback loop to enhance data collection strategies and model building. This interplay might even be feasible for appending data collection while the specimen is still on the diffractometer, provided that the analysis is performed on the fly. However, the model quality for these automations may be crucial in determining whether the discrepancy lies within the experimental data or is due to the insufficiency of the model.

{{< absfig src="/images/abstracts/kleemiss.jpg" alt="A collage of different statistical measures of the collected data, model performance, detector response curves (taken from [1]) and an in-house diffractometer." width="100%">}}

This talk aims to spark a discussion about the possibility of detecting flaws in the collected data in-operando, metrics that may be interesting for this endeavor, and potential remedies from a data collection perspective.


### References:

[1] A. Casanas, R. Warshamanage, A. D. Finke, E. Panepucci, V. Olieric, A. Nöll, R. Tampé, S. Brandstetter, A. Förster, M. Mueller, C. Schulze-Briese, O. Bunk, M. Wang, *Acta. Cryst.* **2016**, *D72*, 1036–1048.

[2] B. L. Becker, J. Kaercher, M. Krug, T. Stuerzer, B. Weinhausen, R. Durst, in *Hard X-Ray, Gamma-Ray, and Neutron Detector Physics XXIII* (Eds.: N.J. Cherepy, M. Fiederle, R.B. James), SPIE, San Diego, United States, **2021**, p. 23.

[3] P. N. Ruth, N. Graw, T. Ernemann, R. Herbst-Irmer, D. Stalke, *J. Appl. Cryst.* **2023**, *56*, 1322–1329.

[4] W. Clegg, *Phil. Trans. R. Soc. A.* **2019**, *377*, 20180239.

[5] S. Grabowsky, A. Genoni, H.-B. Bürgi, *Chem. Sci.* **2017**, *8*, 4159–4176.

[6] A. Genoni, P. Macchi, *Crystals* **2020**, *10*, 473.

[7] A. Genoni, L. Bucinský, N. Claiser, J. Contreras-García, B. Dittrich, P. M. Dominiak, E. Espinosa, C. Gatti, P. Giannozzi, J.-M. Gillet, D. Jayatilaka, P. Macchi, A. O. Madsen, L. Massa, C. F. Matta, K. M. Merz, P. N. H. Nakashima, H. Ott, U. Ryde, K. Schwarz, M. Sierka, S. Grabowsky, *Chem.–Eur. J.* **2018**, *24*, 10881–10905.