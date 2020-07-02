---
layout: post
title: Directly measuring the mass of an imaged planet
subtitle: reposted from astrobites.org
author: Sam Factor
tags: astrometry Beta-Pictoris direct-imaging exoplanets Gaia Jupiter-like-exoplanets
image: /assets/img/blog/Beta_Pictoris_system_annotated.jpg
---

<strong>Title:</strong> <a href="https://arxiv.org/abs/1808.06257">The mass of the young planet Beta Pictoris b through the astrometric motion of its host star</a>

<strong>Authors:</strong> I. A. G. Snellen &amp; A. G. A. Brown

<strong>First Author’s Institution:</strong> Leiden Observatory, Leiden University, Leiden, Netherlands

<strong>Status:</strong> Published in Nature Astronomy, <span style="font-weight: 400; color: #ff0000;">closed access</span>

The mass of a directly imaged planet is a tricky quantity to measure. Normally all you have is the brightness of the planet in comparison to its host star. Since giant planets do not produce their own energy (e.g. through fusion like a star) they simply cool with time. Their initial brightness depends on their mass: the gravitational potential energy of all the material collapsing down to form the planet. Therefore, the brightness of the planet, combined with the age of the system and models of planet formation, can be used to back out the mass of the planet. A prominent question in the field of planet formation is the initial conditions for these models: how much of the gravitational potential energy goes into the planet (heating it up) and how much is dissipated before the planet forms? This uncertainty leads to a spectrum of different initial conditions ranging from <a href="http://beyondearthlyskies.blogspot.com/2014/08/giant-planet-formation-cold-start-vs.html">"hot" to "cold" start</a> models.

<div class="img">
<img src="/assets/img/blog/Beta_Pictoris_system_annotated.jpg"> <img src="/assets/img/blog/betapic_orbit.gif"> <br/><br/> 
<div class="caption"><strong>Figure 1:</strong> <em>Top:</em> Discovery image of β Pictoris b orbiting its host star inside a disk of gas and dust. <em>Bottom:</em> Animation of more recent data showing orbital motion of the planet. <br/><em>Credit: (left) ESO/A.-M. Lagrange et al. (2009), (right) <a href="https://jasonwang.space/orbits.html">Jason Wang</a>.</em></div>
</div>

<a href="https://en.wikipedia.org/wiki/Beta_Pictoris_b">β Pictoris b</a> is one of the first directly imaged planets. It is a gas giant (4-17 times the mass of Jupiter, though likely closer to 13) orbiting a nearby (19 pc) star in the young (~10-20 Myr) β Pictoris moving group. It has been <a href="https://astrobites.org/2014/05/09/an-exoplanets-fast-spin/">well studied</a> in the last decade since its discovery, including determining that its orbit is nearly edge on, though non-transiting. Figure 1 shows the first image of the planet and some more recent observations showing its orbital motion. Today's paper presents the measurement of the mass of β Pic b using astrometry. Since the measurement is model independent, it can be used to calibrate the initial conditions of the models.

<div class="img">
<img src="/assets/img/blog/41550_2018_561_Fig1_HTML.png">
<div class="caption"><strong>Figure 2:</strong> Hipparcos data from 1990-1993 showing the astrometric motion of β Pic. The black curve is the best-fit model to the parallax (shown by the gray circle) and the star’s proper motion (gray line). The light blue line shows the proper motion measured using the 24 yr Hipparcos–Gaia baseline, and the red arrow indicates the difference from the proper motion calculated using only the Hipparcos data. This difference, caused by the planet, is amplified by a factor of ten to make the effect visible. <em>Figure 1 in the paper.</em></div>
</div>

Astrometry is the precise measurement of the positions of stars and their motion. The dominant contribution to the apparent motion of stars is <a href="https://lco.global/spacebook/parallax-and-distance-measurement/">parallax</a> (caused by the Earth’s yearly motion around the Sun) and the star's <a href="https://en.wikipedia.org/wiki/Proper_motion">proper motion</a> (its 3D space velocity projected onto the plane of the sky). If the measurements are precise enough, it is possible to detect the much smaller reflex motion of the star orbiting the center of mass of the star and planet(S) (i.e. <a href="https://en.wikipedia.org/wiki/Barycenter">barycenter</a>). The two most prolific space telescopes dedicated to astrometry are <em><a href="http://sci.esa.int/hipparcos/">Hipparcos</a></em> and <em><a href="http://sci.esa.int/gaia/">Gaia</a></em>, both run by the European Space Agency.

The authors of this paper leveraged the 24.25 years between the Hipparcos and Gaia measurements to precisely measure the proper motion of the host star, β Pic. The proper motion is simply the difference in the two position measurements divided by the time between them (with some small perturbation by the planet which is incorporated in the modeling). They then subtracted this motion from the 3 years of Hipparcos data to reveal the effects of the planet. Figure 2 shows this process. The amplitude of the star's motion (Δθ) is the distance from the star to the center of mass of the system divided by the distance to the star (to convert to the angle on the sky). The equation is thus <em>Δθ = (m<sub>p</sub>/M)*(a<sub>pl</sub>/D)</em>, where <em>m<sub>p</sub></em> is the planet's mass, <em>M</em> is the mass of the star, <em>a<sub>pl</sub></em> is the size of the planet's orbit, and <em>D</em> is the distance to the star. Fitting the specific data points is somewhat more complicated but uses a combination of Kepler's laws and the center of mass equation to measure the planet's mass.

While the inclination and position angle of the orbit of β Pic b are well constrained by the imaging data, the period is not (previously constrained to about 20-26 years). This is because all but one observation were taken when the planet was southwest of the star meaning that only about half the orbit has been observed. Luckily, astrometry can be used to constrain not only the mass of the planet but the period as well. Changing the period would shift the orbital phase at which Hipparcos observed β Pic, causing an acceleration or deceleration in the observed motion. Since the proper motion observed by Hipparcos was approximately constant over its 3 years of data the period of β Pic b must be 22-30 years. Combining this limit with constraints from fitting the orbit using imaging data, β Pic b has a mass of 11±2 Jupiter masses and a period of 24-26 years.

This mass measurement is consistent with the "hot start" models of planet formation, suggesting that much of the gravitational potential energy of the material which formed the planet was retained and not dissipated during accretion. This points towards gravitational collapse within the disk rather than core accretion being the formation mechanism of β Pic b. In the future, as Gaia builds up more data, measurements like this will be commonplace and up to an order of magnitude more precise. We are on the verge of moving from the era of lower limits on exoplanet masses (provided by the<a href="http://www.planetary.org/explore/space-topics/exoplanets/radial-velocity.html"> radial velocity technique</a>) to absolutely measured exoplanet masses.
