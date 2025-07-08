---
title: "QCrBox: A Containerised Platform for Quantum Crystallographic Workflows"
author: "Niklas Ruth"
affiliation: "Durham University"
summary: "We will report on our progress to build a similarly user-friendly platform, that focusses on reducing practical barriers such as complex  multi-software workflows, interoperability challenges, and installation difficulties across diverse operating systems and software dependencies."
date: 2025-07-07
categories: ["Session 12", "Thursday pm"]
image: "/images/blank.png"
tags: ["QCrBox", "Quantum Crystallography", "Containerisation", "docker", "workflows"]
draft: false
weight: 52
params:
  math: true
  tt: 2025-07-17T13:30:50Z
---

#### Paul Niklas Ruth<sup>a</sup>, Horst Puschmann<sup>b</sup> and Simon Coles<sup>c</sup>

##### <sup>a</sup>Advanced Research Computing, Durham University, UK; <sup>b</sup>Department of Mathematicl Sciences, Durham University, UK; <sup>c</sup>University of Southampton, School of Chemistry, Highfield Campus, Southampton, SO17 1BJ, UK


##### e-mail: paul.n.ruth@durham.ac.uk

The crystallographic community has seen increasing interest
in quantum crystallographic methods that move beyond the independent atom model
to describe aspherical electron density. The slow but consistent adoption of
Hirshfeld atom refinement implemented in Olex2 [1] in the form of NoSpherA2 [2]
has shown that if the experience of using more sophisticated models is
sufficiently streamlined, adoption is possible. We will report on our progress
to build a similarly user-friendly platform, that focusses on reducing
practical barriers such as complex multi-software workflows, interoperability
challenges, and installation difficulties across diverse operating systems and
software dependencies.

QCrBox addresses these obstacles through a containerized
platform that encapsulates crystallographic applications within Docker
containers, accessible via a unified web interface. Each application is
configured to exchange data using standardized CIF formats, with clearly
defined prerequisites and input specifications. This approach eliminates manual
software installation while maintaining the full functionality of existing
crystallographic tools.

Data exchange occurs through identified datasets that are
properly attributed to users and research groups, ensuring appropriate
provenance tracking. Intermediate results at each processing stage can be
visualized directly within the interface, allowing researchers to monitor data
quality and make informed decisions about subsequent processing steps. In
future, workflows will be automatically recorded with complete parameter sets,
enabling straightforward reproduction and systematic exploration of processing
options.


The containerization strategy accommodates both established
packages like Olex2 and MoPro, as well as specialized research scripts that
typically suffer from installation and interoperability issues. By providing a
common framework for software integration, QCrBox lowers barriers to entry for
quantum crystallographic methods.


This platform represents a practical solution to workflow
management challenges that have historically limited the broader adoption of
sophisticated crystallographic methods. We invite community contributions to
expand the ecosystem of available containerized applications.


[1] Dolomanov, O. V.; Bourhis, L. J.; Gildea, R. J.; Howard, J. A. K.;
Puschmann, H. (2009). J. Appl. Cryst., 42,
339.

[2] Kleemiss, F., Dolomanov, O. V., Bodensteiner, M., Peyerimhoff, N.,
Midgley, L., Bourhis, L. J., Genoni, A., Malaspina, L. A., Jayatilaka, D., Spencer,
J. L., White, F., Grundkötter-Stock, B., Steinhauer, S., Lentz, D., Puschmann,
H., Grabowsky S. (2021). Chem. Sci. 12,
1675.