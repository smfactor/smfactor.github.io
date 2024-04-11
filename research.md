---
layout: page
title: Research
subtitle: Exoplanets and Planet Formation
mathjax: true
cover-img:
  - "/assets/img/big-imgs/heic0917aasc.jpg" : "The Orion ''Proplyds'', Credit: NASA/ESO"
  - "/assets/img/big-imgs/heic0917absc.jpg" : "Orion, Credit: NASA/ESO"
  - "/assets/img/big-imgs/alma-starry-night.jpg" : "ALMA, Credit: ESO"
  - "/assets/img/big-imgs/hltau.jpg" : "HL Tau, Credit: ALMA"
  - "/assets/img/big-imgs/SMA.jpg" : "SMA, Credit: CfA"
  - "/assets/img/big-imgs/JWSTDI.jpg" : "JWST image of HIP 65426 b, Credit: NASA/ESA/CSA, A. Carter (UCSC), the ERS 1386 team, and A. Pagan (STScI)"
---

# Current Postoctoral Work at UT Austin:

I am currently working to assess the detection limits of and best practices for applying Kernel Phase Interferometry to JSWT imaging. I applied this technique to multiple datasets in my dissertation work (see below) and am excited to explore it further on a new telescope. I am PI of cycle 1 JWST program AR-2509 which supports my current postdoctoral research.

# Dissertation Work at UT Austin:

My dissertation research was with Dr. Adam Kraus at the University of Texas at Austin applying interferometric analysis techniques to archival data to detect close in companions, binary stars or exoplanets. This technique models the full aperture of the telescope as an array of sub-apertures. This model is then used to analyze images in the Fourier domain by simulating a redundant interferometer. 

### Kernel-phase interferometry for imaging beyond the diffraction limit ([Factor & Kraus 2022](https://ui.adsabs.harvard.edu/abs/2022AJ....164..244F))

The first project in this series was an archival binary search around old field brown dwarfs. The figures below show our aperture model, and the progression from  images, to Fourier amplitude and phase, to kernel-phase, and finally to fitted astrometry and photometry. This target demonstrates the power of kernel-phase analysis by detecting a binary at $$ \sim90 $$ miliarcseconds, just over $$ 0.5\,\lambda/D $$ for *HST*, at a contrast of $$ \sim8\!:\!1\! $$. This project has two accepted publications, one detailing the binary search and another analyzing the population demographics of the catalogue. My kernel-phase interferometry pipeline, named Argus, can be found here: [https://github.com/smfactor/argus](https://github.com/smfactor/argus) (tutorials are under construction). 

| [![HST model](../assets/img/mask.png){: class="image-100" }](../assets/img/mask.pdf) | [![Baselines](../assets/img/baselines.png){: class="image-100" }](../assets/img/baselines.pdf) |
|:---:|:---:|
| HST aperture model | Baselines from the model colored by redundancy |

| [![HST Image Analysis](../assets/img/4plt.png){: class="image-100"}](../assets/img/4plt.pdf) | [![Corner Plot](../assets/img/cornerCor.png){: class="image-100"}](../assets/img/cornerCor.pdf) |
|:---:|:---:|
|HST Image of a binary star system (top left), Fourier amplitude and phase with baselines overlayed in gray (bottom row), and histogram of the kernel-phases (top right) | 1 and 2D posteriors from fitting a binary model (separation, position, and contrast in each filter) to the Kernel-phases (lower left) and correlation plots showing the goodnes of fit in the two filters (upper right) to the immage in the far upper right. |

### Binary Demographics of Nearby Field-Age Brown Dwarfs ([Factor & Kraus 2023](https://ui.adsabs.harvard.edu/abs/2023AJ....165..130F))

I then conducted a demographic analysis of this catalogue to infer the underlying binary brown dwarf population. The results of this 4 parameter fit (companion frequency $$ F $$, mass-ratio power-law index $$ \gamma $$, and log-normal separation mean $$ \overline{\log(\rho)} $$ and standard deviation $$ \sigma_{\overline{\log(\rho)}} $$) are shown below in the context of previous surveys of similar objects and literature values as a funciton of primary mass. We find a strong preference for tight and equal mass systems. I am PI of cycle 24 Hubble Space Telescope program AR-14561 which supported these two projects.

| [![Demographic Parameters](../assets/img/paramsFnMassMalm.png){: class="image-100" }](../assets/img/paramsFnMassMalm.pdf) | [![Detections, Sensitivity, and Underlying Population](../assets/img/2DpopMalm1p9.png){: class="image-100" }](../assets/img/2DpopMalm1p9.pdf) |
|:---:|:---:|
| Binary demographic parameters as a function of stellar mass, putting the results from this work in the context of literature values. Fits from this work are shown on a color scale from purple to yellow for different assumed field ages. |  The progression from underlying population and survey sensitivity to observed population. Blue points indicate detected companions. Top left: Underlying companion population produced from the median values of our informed prior fit. Top right: Survey sensitivity in units of number of targets. Bottom center: Observed population (i.e., the inferred probability that we should detect a companion in a given bin), calculated by correcting the underlying population for Malmquist bias (as a function of mass ratio) and applying our survey sensitivity.|

### Young Low Mass Binaries in Taurus and Upper Scorpius (Factor & Kraus in prep.)

The final project in my dissertation was to apply a modified version of the same kernel-phase interferometry pipeline to ACS/HRC imaging of young very low mass objects in Taurus and Upper Scorpius to search for newly formed planets. This is the first time that KPI has been applied to observations at visible wavelengths. We have detected a few (preliminary) new candidate companions and performed the same demographic analysis as above to this young population. We then compared the young population to the field and find an excess of young wide separation companions, indicating dynamical evolution significantly sculpts the population. A publication on this work is in prep and was supported by cycle 29 HST program AR-16612 which I am PI of. 

# Master's thesis at Wesleyan:

### Analysis of ALMA observations of a protoplanetary disk ([Factor et al. 2017](http://adsabs.harvard.edu/abs/2017AJ....153..233F))

My Master's research, at Wesleyan University with Professor A. Meredith Hughes, looked at the initial conditions of planet formation inside disks of gas and dust around young stars. Specifically, I analyzed radio interferometric observations of gas line emission from a protoplanetary disk in the Orion Nebula Cluster. These observations were part of an Atacama Large Millimeter/submillimeter Array (ALMA) cycle 0 program ([P.I. Rita Mann](http://adsabs.harvard.edu/abs/2014ApJ...784...82M)). 

| [![ALMApv](../assets/img/f4.png  "Position-velocity diagram"){:class="image-100"}](../assets/img/f4.pdf) | [![HR Diagram](../assets/img/f12.png){:class="image-100"}](../assets/img/f12.pdf) |
|:---:|:---:|
|Position-velocity diagram showing the asymmetric feature | HR diagram showing pre-main sequence evolutionary tracks for different masses. The green track is for our best fit mass while the blue dot and bar indicate the absolute magnitude and temperature from the literature. |


I used a simple model of the gas emission to fit the density and temperature structure of the disk. Using this information, we can compare this disk to the theoretical disk which our own solar system formed from and investigate the likelihood of planet formation. We can also compare this disk, located in a high mass star forming region (SFR), to previously studied disks in nearby low mass SFR's, to investigate the effect of the surrounding environment. I wrote my Master’s thesis on this work and it was published in the Astronomical Journal. 

A few of the interesting results are as follows. We serendipitously discovered high-velocity asymmetric emission consistent with a 1.8-8 M$$ _\mathrm{Jupiter} $$ clump of gas orbiting at $$ 60 \pm 20 $$au. This clump is indicated by the arrow in the position-velocity diagram above, showing the velocity of gas as a function of position offset from the central star along disk major axis. Since we can resolve both the position and velocity of the gas, we were able to fit Keplerian orbits to measure the mass of the central star. We measured it to be $$ 2.17 \pm 0.07 \mathrm{M}_\odot $$, inconsistent with the previously determined spectral type of K5.  

# Undergraduate physics work at Wesleyan:

### Parity-Time symmetric systems

As an undergraduate at Wesleyan University, I worked with Professor Fred Ellis on modeling novel optical systems using simple electronics. I focused specifically on systems exhibiting parity time (PT) symmetry. PT-symmetric systems are not symmetric under parity $$ (x \rightarrow -x) $$ or time $$ (t \rightarrow -t) $$ reflection individually but are symmetric under a combined parity and time reflection. A simple example of this is a coupled oscillator system with balanced gain and loss. Under time reversal gain turns into loss and visa versa. Thus a combined parity and time reflection returns the system to its original state. We demonstrated a wide variety of interesting applications of these systems including asymmetric transport and unidirectional lasing. For more information on this work see my three second author papers from 2013 and 2014 on my [publications](/publications) page.
