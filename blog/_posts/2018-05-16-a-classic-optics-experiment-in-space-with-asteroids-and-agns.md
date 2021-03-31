---
layout: post
title: A classic optics experiment, in space with asteroids and AGNs!
subtitle: reposted from astrobites.org
author: Sam Factor
tags: [asteroids, diffraction, Interferometry, occultations, radio-astrometry]
image: /assets/img/blog/palma_fg12cropped.jpg
---

<strong>Title:</strong> <a href="https://arxiv.org/abs/1804.05640">Radio interferometric observation of an asteroid occultation</a>

<strong>Authors:</strong> Jorma Harju, Kimmo Lehtinen, Jonathan Romney et al.

<strong>First Author’s Institution:</strong> Department of Physics, University of Helsinki, Finland; <em>Max-Planck-Institut für extraterrestrische Physik</em>, Garching, Germany

<strong>Status:</strong> Submitted to the Astronomical Journal, <span style="font-weight: 400; color: #339966;">open access on arXiv</span>

For decades astronomers have used occultations to study celestial bodies such as the moon, asteroids and even quasars. An <a href="https://occultations.org/occultations/what-is-an-occultation/">occultation</a> occurs when some foreground object—the moon, a planet, or an asteroid—crosses in front of a background object—the sun (in the case of an eclipse), a planet, a star or a quasar. While rare, these occurrences can tell us a lot about the foreground and/or background objects. For example they have been used to determine the positions of quasars (before radio interferometers were available), <a href="https://astrobites.org/2011/05/30/using-the-moon-as-a-scientific-instrument/">detect binary stars</a>, study surface topography of the moon, the <a href="https://www.nasa.gov/feature/first-stellar-occultations-shed-additional-light-on-pluto-s-atmosphere">atmosphere</a> <a href="http://sci.esa.int/gaia/58284-pluto-occultation/">of the</a> <a href="https://astrobites.org/2013/01/14/touring-sofia/">outer planets</a>, and the shapes and sizes of asteroids (including <a href="https://www.nasa.gov/mission_pages/newhorizons/main/index.html">New Horizons</a>'s <a href="https://www.nasa.gov/feature/does-new-horizons-next-target-have-a-moon">next target</a>). Today's paper uses an intriguing technique to analyze an occultation of an active galactic nucleus (AGN) by an asteroid observed with the Very Long Baseline Array (<a href="https://science.nrao.edu/facilities/vlba">VLBA</a>).

On May 15, 2017 at UT 14:31:23 an asteroid named Palma crossed in-between AGN 0141+268 and the Brewster VLBA station. Figure 1 shows the path of the shadow across the North Western United States. Normally when observing an occultation you would expect to simply see the background source disappear for some period of time and then reappear from behind the occulter. This was not quite the case for this observation. This observation was special because of the relative size of the asteroid, the distance to the asteroid, and the wavelength of the observation. In this case they observed not just the shadow of the asteroid as it occulted the AGN but also the diffraction pattern.

<div class="img">
<img src="/assets/img/blog/palma_fg2.jpg"/>
<div class="caption"><strong>Figure 1:</strong> Path of the shadow cast by Palma across the Brewster VLBA station. Grey eclipses indicate the geometric shadow at intervals of one second. Orange eclipses indicate the location of the first maxima of the diffraction pattern four seconds before and after the closest approach. <em>Figure 2 in the paper.</em></div>
</div>

This is essentially the classic diffraction experiment of shining a laser on a small ball bearing but on a much larger scale and under less than ideal conditions. It is actually these less than ideal conditions which allow us to learn about the asteroid. Since the asteroid is not a perfect sphere it's diffraction pattern is asymmetric. This asymmetry can then be used to infer the shape of the asteroid. This asymmetry can clearly be seen in the bottom center panel of Figure 2.

Since the occultation was observed with a radio interferometer they not only observed how the intensity of light changed but also the phase. This was the first time a measurement of the phase of astronomical diffraction has been measured. This phase information, combined with the amplitude in an amplitude-phase diagram, plays a crucial role in determining the size and shape of the asteroid. This diagram is shown in the bottom left panel of Figure 2. The authors fit a number of models (circle, ellipse, two overlapping circles they call potato-shaped, a random continuous shape, and a model derived from visible light occultations) to the combined amplitude and phase observations. With the given data it is difficult to discern the exact shape of the asteroid though they did find a diameter of 192 km (consistent with previous observations) and that it deviates 10–20% from a circle.

<div class="image">
<img src="/assets/img/blog/palma_fg12.jpg"> 
<div class="caption"><strong>Figure 2:</strong> Top: model of the shape of the asteroid Palma (a), and the amplitude (b) and phase (c) of the resulting diffraction pattern. Bottom: amplitude phase diagram (d) showing the data points and modeled curves (blue and red correspond to ingress and egress, respectively), and amplitude (e) and phase (f) cuts along the path of the Brewster VLBA station. Data are shown in thick lines, models in thin lines and residuals at the bottom. <em>Figure 12 in the paper.</em></div>
</div>

An interesting effect of diffraction around a circular occulter, in this case an asteroid, is that there is a bright spot at the center of the shadow. Since the center of the shadow is equidistant from all points on the edge of the sphere, light constructively interferes and creates a light spot in the middle of the dark shadow. This spot can be seen in the center of the two center panels (b and e) in Figure 2. This spot, called the <a href="https://www.youtube.com/watch?v=y9c8oZ49pFc">Arago-Poisson spot</a>, was an early point of contention when the wave theory of light was first being developed. The measurement of this spot tells you how far you are from the center of the shadow, or in other words how close the center of the occulter is to lining up with the light source. In this case this corresponds to the exact position of the asteroid relative to the background AGN during the occultation. This extremely precise position measurement can be used to refine the orbit of the asteroid, reducing the long term uncertainty in its position by an order of magnitude.

While the concept of diffraction and the odd effects of the wave nature of light can be difficult to get your head around, they are important and powerful tools which can be leveraged to perform amazing science from spectroscopy (diffraction gratings) to high resolution imaging by combining light from multiple telescopes (interferometry). 

Read the origional post at [astrobites.org](https://astrobites.org/2018/05/16/a-classic-optics-experiment-in-space-with-asteroids-and-agns/).
