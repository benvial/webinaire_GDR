


My presentation slides for the [GDR Ondes](https://gdr-ondes.cnrs.fr/) seminar series on open-source software.


## Abstract

### Optimization of Photonic Devices: Implementation of Auto-Differentiable Numerical Methods in Open-Source Software

I will present the development of software libraries with automatic differentiation capabilities, including a Finite Element Method (FEM) code for 2D scattering problems, an implementation of the Fourier Modal Method (FMM) for stacked bi-periodic structures, and a Plane Wave Expansion Method (PWEM) for computing the eigenmodes of 2D photonic crystals. After introducing these numerical methods and the tools for automatic differentiation and topology optimization, I will illustrate their applications: designing superscattering structures using FEM, optimizing a metasurface for maximal transmission in a specific diffraction order with FMM, and enhancing bandgap and dispersion properties in dielectric photonic crystals with PWEM.  

The availability of open-source software for solving Maxwell’s equations is crucial for advancing metamaterials and photonics research. Our implementations of these three widely used numerical methods are freely accessible as Python packages: [Gyptis (FEM)](https://gyptis.gitlab.io), [Nannos (FMM)](https://nannos.gitlab.io), and [Protis (PWEM)](https://protis.gitlab.io).
I will also discuss the various aspects of development associated with it (documentation, testing, distribution...). 
The presentation will be in English.


### Optimisation de dispositifs photoniques : implémentation de méthodes numériques auto-différentiables en logiciel libre


Dans ce talk, je présenterai le développement de bibliothèques logicielles intégrant la différentiation automatique pour la simulation en photonique. J’aborderai trois méthodes numériques : la Méthode des Éléments Finis (FEM) pour les problèmes de diffraction, la Méthode Modale de Fourier (FMM) pour les structures bi-périodiques empilées et la Méthode d’Expansion en Ondes Planes (PWEM) pour le calcul des modes propres des cristaux photoniques 2D. Après avoir décrit ces méthodes et les outils d’optimisation topologique associés, je montrerai des applications concrètes, notamment la conception de diffuseurs (FEM), l’optimisation d’une métasurface pour la transmission dans un ordre de diffraction donné (FMM) et l’ingénierie de dispersion des cristaux photoniques (PWEM).

L’accessibilité des codes open-source pour la résolution des équations de Maxwell est essentielle au développement des métamatériaux et de la photonique. Nos implémentations des trois méthodes sont disponibles en tant que packages Python : [Gyptis (FEM)](https://gyptis.gitlab.io), [Nannos (FMM)](https://nannos.gitlab.io), and [Protis (PWEM)](https://protis.gitlab.io). 
Je discuterais aussi les différents aspects de développement associés (documentation, tests, distribution...).
L'exposé sera en anglais.

