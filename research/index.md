---
layout: page
title: Research
subtitle: Exoplanets and Planet Formation
bigimg:
  - "/img/big-imgs/heic0917aasc.jpg" : "The Orion ''Proplyds'', Credit: NASA/ESO"
  - "/img/big-imgs/heic0917absc.jpg" : "Orion, Credit: NASA/ESO"
  - "/img/big-imgs/alma-starry-night.jpg" : "ALMA, Credit: ESO"
  - "/img/big-imgs/hltau.jpg" : "HL Tau, Credit: ALMA"
  - "/img/big-imgs/SMA.jpg" : "SMA, Credit: CfA"
---
{% include mathjs %}

# Current Work at UT Austin:

### Kernel-phase interferometry for imaging beyond the diffraction limit

I currently work with Adam Kraus at the University of Texas at Austin applying interferometric analysis techniques to archival data to detect close in companions, binary stars or exoplanets. This technique models the full aperture of the telescope as an array of sub-apertures. This model is then used to analyze images in the Fourier domain by simulating a redundant interferometer. The figures below show the progression from aperture model, to images, to Fourier amplitude and phase, to kernel-phase, to fitted astrometry and photometry. 
This target demonstrates the power of kernel-phase analysis by detecting a binary at $$ \sim90 $$ miliarcseconds, just over $$ 0.5\,\lambda/D $$ for *HST*, at a contrast of $$ \sim8\!:\!1\! $$. I am PI of cycle 24 Hubble Space Telescope Archival Research Grant number 14561 to support this work. 


| ![HST model](../img/mask.pdf) | ![Baselines](../img/baselines.pdf) |
|:---:|:---:|
| HST aperture model | Baselines from the model colored by redundancy |

| ![HST Image Analysis](../img/4plt.pdf) | ![Corner Plot](../img/GJ164F190Ncorner.pdf) |
|:---:|:---:|
|"HST Image of GJ164 (top left), Fourier amplitude and phase with baselines overlayed in gray (bottom row), and kernel-phase (top right) | 1 and 2D posteriors from fitting the Kernel-phases (lower left) and correlation plot showing the goodnes of fit (upper right). |

# Master's thesis at Wesleyan:

### Analysis of ALMA observations of a protoplanetary disk

My Master's research, at Wesleyan University with Professor A. Meredith Hughes, looked at the initial conditions of planet formation inside disks of gas and dust around young stars. Specifically, I analyzed radio interferometric observations of gas line emission from a protoplanetary disk in the Orion Nebula Cluster. These observations were part of an Atacama Large Millimeter/submillimeter Array (ALMA) cycle 0 program ([P.I. Rita Mann](http://adsabs.harvard.edu/abs/2014ApJ...784...82M)). 

| ![ALMApv](../img/f4.png  "Position-velocity diagram") | ![HR Diagram](../img/f12.pdf) |
|:---:|:---:|
|Position-velocity diagram showing the asymmetric feature | HR diagram showing pre-main sequence evolutionary tracks for different masses. The green track is for our best fit mass while the blue dot and bar indicate the absolute magnitude and temperature from the literature. |


I used a simple model of the gas emission to fit the density and temperature structure of the disk. Using this information, we can compare this disk to the theoretical disk which our own solar system formed from and investigate the likelihood of planet formation. We can also compare this disk, located in a high mass star forming region (SFR), to previously studied disks in nearby low mass SFR's, to investigate the effect of the surrounding environment. I wrote my Master’s thesis on this work and it was published in the Astronomical Journal ([Factor et al. 2017](http://adsabs.harvard.edu/abs/2017AJ....153..233F)). 

A few of the interesting results are as follows. We serendipitously discovered high-velocity asymmetric emission consistent with a 1.8-8 M$$ _\mathrm{Jupiter} $$ clump of gas orbiting at $$ 60 \pm 20 $$au. This clump is indicated by the arrow in the position-velocity diagram below, showing the velocity of gas as a function of position offset from the central star along disk major axis. Since we can resolve both the position and velocity of the gas, we were able to fit Keplerian orbits to measure the mass of the central star. We measured it to be $$ 2.17 \pm 0.07 \mathrm{M}_\odot $$, inconsistent with the previously determined spectral type of K5.  

# Undergraduate physics work at Wesleyan:

### Parity-Time symmetric systems

As an undergraduate at Wesleyan University, I worked with Professor Fred Ellis on modeling novel optical systems using simple electronics. I focused specifically on systems exhibiting parity time (PT) symmetry. PT-symmetric systems are not symmetric under parity $$ (x \rightarrow -x) $$ or time $$ (t \rightarrow -t) $$ reflection individually but are symmetric under a combined parity and time reflection. A simple example of this is a coupled oscillator system with balanced gain and loss. Under time reversal gain turns into loss and visa versa. Thus a combined parity and time reflection returns the system to its original state. We demonstrated a wide variety of interesting applications of these systems including asymmetric transport and unidirectional lasing. For more information on this work see my three second author papers on my [publications](/publications) page.
