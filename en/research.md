---
layout: page
title: Research
lang: en
lang-ref: research
permalink: /en/research/
---

Most of my current research is on the [active particles](#active-particles) and [motility induced phase separation](#motility-induced-phase-separation). I'm also interested in systems biology, nonlinear dynamical systems, and using machine learning methods in studying such complex systems.

## Active paticles

**Active particles** are particles that can propel the motion of itself. It is an useful concept to describe the macroscopic motion of bacteria, mammalian cells, birds, fishes, and even human beings. Systems of active particles are very common in the nature.

{:refdef: style="text-align: center;"}
![Motion of E. Coli]({{site.url}}/assets/ecoli_RTP.png)
{: refdef}

*The trajectory of an E. Coli cell, modified from H. C. Berg and D. A. Brown, Nature, 1972*

A group of active particles is a typical far-from-equilibrium system. Each particle consume "fuel" (e.g. ATP) to generate a driving force, and the energy is dissipated by the friction from the surronding fluids or substrates. Usually because of thermal fluctuations of the solvent, or interal dynamics of motors of particles, the orientations of particles cannot persist at large enough time. Thus the conservations of energy and momentum of particles are broken at the very microscopic level.

That's why active particles can have many complex behaviors compared to the passive systems. A group of aligning particles can form clusters and move collectively. Chiral active particles can form rotating vortex. Even the simplest active particles with force interactions can have liquid-gas-like phase separation and even form patterns. Due to their far-from-equilibrium nature, the world of active particles is very vast!

### selected publications
*Authors contribute equally
<ol>

<li>Ruben Zakine*, <strong>Yongfeng Zhao</strong>*, Miloš Knežević, Adrian Daerr, Yariv Kafri, Julien Tailleur, Frédéric van Wijland, "<em>Surface Tensions between Active Fluids and Solid Interfaces: bare vs dressed</em>". </li> 

<a href="https://arxiv.org/pdf/1907.07738">Preprint</a> 

<li>Eric Woillez, <strong>Yongfeng Zhao</strong>, Yariv Kafri, Vivien Lecomte, Julien Tailleur, “<em>Activated escape of a self-propelled particle from a metastable state</em>”, Phys. Rev. Lett. 122, 258001 (2019). </li> 

<a href="https://arxiv.org/pdf/1904.00599">Preprint</a>, <a href="https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.122.258001">Phys. Rev. Lett.</a> 

<li>Thibault Bertrand, <strong>Yongfeng Zhao</strong>, Olivier Bénichou, Julien Tailleur, Raphaël Voituriez, “<em>Optimized Diffusion of Run-and-Tumble Particles in Crowded Environments</em>”, Phys. Rev. Lett. 120, 198103 (2018). </li> 

<a href="https://arxiv.org/pdf/1711.05209">Preprint</a>, <a href="https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.120.198103">Phys. Rev. Lett.</a>

</ol>

## Motility induced phase separation

It has been known that if some interactions can reduce the speed of active particles at high density region, we could find liquid-gas-like phase separation, which is often referred to as **motility induced phase separation (MIPS)**. Typical interactions include quorum sensing interactions, and pairwise force interactions.

Quorum sensing is a mechanism of cells sensing the local cell density. Typically this kind of interaction is via a short lifetime small molecules. Using method developed in synthetic biology, we can engineer the gene of E. coli cells to express constantly and sense AHL molecules. The local concentration of AHL molecules will be positive related to the local cell density. Thus it is a good model of quorum sensing active particles. If we further let the cells decrease their mobility at high density region, we indeed found clustering of cells, and even pattern formation if we consider population dynamics of cells (C. Liu, et al, Science, 2011).

{:refdef: style="text-align: center;"}
![MIPS of quorum sensing active particles]({{site.url}}/assets/3Species_MI.png)
{: refdef}
*Motility induced liquid-gas phase separation of quorum sensing active particles, though a mutual inibition of motility among three species of active particles*

Pairwise forces interactions are just the mechanical forces. It is found, quite surprisingly, that even the purely repulsive short-range forces (collision) can also make active particles cluster and form liquid-gas phase separation. The picture is more or less similar to the traffic jamming in 2D or 3D space.

{:refdef: style="text-align: center;"}
![MIPS of pairwise forces active particles]({{site.url}}/assets/PFAP_MIPS.png)
{: refdef}
*Motility induced liquid-gas phase separation of pairwise forces active particles*

Because of the non-equilibrium nature of the active systems, the usual thermodynamics of equilibrium systems does not apply to these active fluids: there's typically no free energy formalism in such systems. Finding a generalized thermodynamics of these non-equilibrium steady states is still an open question.

### selected publications
*Authors contribute equally
<ol>

<li>Agnese I. Curatolo*, Nan Zhou*, <strong>Yongfeng Zhao</strong>*, Chenli Liu, Adrian Daerr, Julien Tailleur, Jian-Dong Huang, "<em>Cooperative pattern formation in multi-component bacterial systems through reciprocal motility regulation</em>", Nat. Phys., (2020). </li> 

<a href="https://www.biorxiv.org/content/10.1101/798827v1.full.pdf">Preprint</a>, <a href="https://doi.org/10.1038/s41567-020-0964-z">Nat. Phys.</a> 

</ol>