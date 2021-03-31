---
layout: post
title: Imaged Companion Drives Spiral Arms in Disk
subtitle: reposted from astrobites.org
author: Sam Factor
tags: [astrometry, binary-stars, computer-simulations, numerical-simulations, observations, planet-formation, protoplanetary-disks, radio-astronomy, simulations, star-formation]
image: /assets/img/blog/HD100453_thumb.jpg
---

<strong>Title:</strong> <a href="https://arxiv.org/abs/1801.03900">The Orbit of the Companion to HD 100453A: Binary-Driven Spiral Arms in a Protoplanetary Disk</a>

<strong>Authors:</strong> Kevin Wagner, Ruobing Dong, Patrick Sheehan, Daniel Apai, Markus Kasper, Melissa McClure, Katie M. Morzinski, Laird Close, Jared Males, Phil Hinz, Sascha P. Quanz, Jeffrey Fung

<strong>First Author’s Institution:</strong> Steward Observatory, University of Arizona

<strong>Status:</strong> Published in The Astrophysical Journal, <span style="font-weight: 400; color: #339966;">open access</span>

&nbsp;

Today’s paper combines a wide range of data sets---spanning the radio to near-infrared---and analysis techniques---orbit fitting and hydrodynamic simulations---to connect a binary companion to intriguing features seen in the protoplanetary disk around the primary star.

Using the Spectro-Polarimetric High Contrast Exoplanet Research instrument (<a href="https://www.eso.org/sci/facilities/paranal/instruments/sphere.html">SPHERE</a>) in 2015, astronomers discovered a two-armed spiral structure in the disk around HD 100453 A (see Figure 1). This structure is very different from the gaps seen in images of protoplanetary disks from the Atacama Large Millimeter/submillimeter Array (<a href="http://www.almaobservatory.org/en/home/">ALMA</a>) such as <a href="https://astrobites.org/2016/06/26/new-rings-detected-for-old-protoplanetary-disk/">HL Tau and TW Hya</a>. The spiral arms seen in the disk around HD 100453 A and two other disks (<a href="https://science.nasa.gov/science-news/science-at-nasa/2011/31oct_spiralarms">SAO 206462</a> and <a href="http://www.sci-news.com/astronomy/science-spirals-arms-young-stars-giant-planets-03397.html">MWC 758</a>) could be caused by a massive companion (planet or star) orbiting outside the disk or processes within the disk such as self-gravity or dead zones. The HD 100453 system is unique in that it has a known M-dwarf companion of about 0.2 solar masses (HD 100453 B). The authors of this paper show that this companion is the cause of the spiral arms seen in the disk, without invoking other driving mechanisms.

<div class="image">
<img src="/assets/img/blog/HD100453.jpg" alt="Image of HD100453">
<div class="caption"><strong>Figure 1:</strong> Image of the HD 100453 system showing the primary star (behind the coronagraph), the disk and spiral arms, and the M-dwarf companion. Red, green, and blue colors are Y-, J-, and H-band filters, respectively. <em>Figure 1 in the paper.</em></div>
</div>

The first step in connecting the companion star to the spiral arms of the disk was to determine the companion's orbit. The authors used six observations with SPHERE and the Nasmyth Adaptive Optics System and Near-Infrared Imager (<a href="https://www.eso.org/sci/facilities/paranal/instruments/naco.html">NACO</a>) cameras on the <a href="http://www.eso.org/public/usa/teles-instr/paranal-observatory/vlt/">Very Large Telescope</a> and the <a href="https://en.wikipedia.org/wiki/Magellan_Telescopes#MagAO_Adaptive_Optics_System">Magellan Adaptive Optics</a> system taken over a span of 14 years. The authors took care to minimize systematic errors in the <a href="https://en.wikipedia.org/wiki/Astrometry">astrometry</a> which could be introduced by errors in the <a href="http://mingus.as.arizona.edu/~bjw/spectrographs/node3.html">plate scale</a>, orientation of the telescope (which direction is north on the camera) and using a coronagraph. With six pairs of separations and position angles, the authors were able to fit the orbital parameters of the companion M-dwarf. Most important for determining the origin of the spiral arms are the semi-major axis (109±9 au), eccentricity (0.17±0.07), and inclination (32.5±6.5 degrees). This semi-major axis and eccentricity are consistent with the companion truncating the disk at 40 au, much smaller than a typical disk around a single star.

Since the mutual inclination between the companion and disk has a significant effect on the evolution of the system, the authors needed to determine the inclination of the protoplanetary disk. They used publicly available ALMA observations of carbon monoxide in the disk. Fitting a simple smooth disk profile to the keplerian orbits of the gas gave a disk inclination of 28 degrees, consistent within 1σ with the inclination of the companion.

<div class="image">
<img src="/assets/img/blog/HD100453_models.jpg" alt="Model comparison of HD100453">
<div class="caption"><strong>Figure 2:</strong> Image of the HD 100453 system (<em>top</em>) compared with hydrodynamic and radiative transfer simulation viewed from an inclination of 30 degrees (<em>bottom</em>). <em>Figure 7 in the paper.</em></div>
</div>

The final step was to run a <a href="https://astrobites.org/2014/12/03/orderly-disorder-simulations-of-planet-disk-dynamics-with-arepo/">hydrodynamic simulation</a> of the entire system including the effects of the companion. They evolved an initially smooth disk for 100 orbits of the companion and produced synthetic observations using a radiative transfer code. A sample of simulation results is shown in Figure 2. The separation of the spiral arms, their <a href="https://ned.ipac.caltech.edu/level5/STRUCTURE/spst.html">pitch angle</a>, and the locations where they sprout from the central ring are all well reproduced by the model. The authors note that the disks in their simulations are ~30% larger than the observed disk though they suspect this is likely due to the short amount of time that the simulations were run for (100 companion orbits) compared to the age of the system (~12,000 companion orbits). If the computer time were available to run the simulation longer, the authors speculate that the companion would truncate the disk further. The amount of truncation also depends on the scale height and viscosity of the disk which are likely not exactly correct in their models.

The agreement between the inclination of the M-dwarf companion and the disk suggest that the entire system formed from a single cloud rather than the companion later becoming bound to the primary star (and its disk). The likely inclination of HD 100453 A (determined by comparing the observed rotational velocity of the star with stars of similar mass) is also consistent with the disk and companion star. This rules out a possible scenario where the companion formed separately, but torqued the disk to share its inclination while leaving the star untouched.

While the spiral arms in the HD 100453 A disk are clearly driven by HD 100453 B, it is hard to make the same conclusion for the other two disks hosting "grand design" spiral arms. This and other studies suggest where a companion could be located with respect to the spiral arms in those systems, but previous searches for such a companion have found nothing, setting strict limits on its mass (or brightness). As always, more work is needed to determine the origin of the spiral arms in SAO 206462 and MWC 758.

Read the origional post at [astrobites.org](https://astrobites.org/2018/02/27/spiral_arms_driven_by_companion/).
