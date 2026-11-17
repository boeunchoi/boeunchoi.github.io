---
layout: research
title: Radiative Transfer through Neutral Hydrogen
# description: Rayleigh and Raman Scattering in H I Medium
img: assets/img/raman/raman_heii.png
img_fit: contain # show the whole (wide) image in the thumbnail
img_bg: light # light panel behind the thumbnail in dark mode (transparent image)
importance: 2
category: research
related_publications: true
permalink: /research/raman-scattering/
published: true
---

During my master's program at Sejong University, I worked with Prof. Hee-Won Lee and Dr. Seok-Jun Chang on radiative transfer simulations of UV emission lines in neutral hydrogen (H I) regions. Some UV lines from ions, such as O VI λλ1032, 1038 and He II λ1025, 972, and 949, lie close to the hydrogen Lyman series lines. In an optically thick H I region, these photons scatter multiple times, and some of them turn into optical photons through Raman scattering. These optical photons escape the H I region right away. Such Raman-scattered features offer a unique probe of the scattering medium, including its kinematics, geometry, and H I column density.

I particularly studied Raman scattering of He II lines, whose Raman-scattered features appear in a few planetary nebulae and symbiotic stars. These lines lie slightly blueward of the hydrogen Lyman series lines, so when they scatter with H I, they excite the ground-state electron to a level slightly higher than the corresponding hydrogen level (see the figure below). When the electron then de-excites to the n = 2 level instead of the ground state, the photon is Raman-scattered into the optical, slightly blueward of the hydrogen Balmer series lines. To understand how these features form in planetary nebulae, we investigated Raman-scattered line formation in an expanding shell using a Monte Carlo radiative transfer code {% cite choi20a %} and showed that the scattered feature develops a long red tail due to the expansion. This suggests that Raman-scattered features can serve as a probe of the expansion in planetary nebulae, which may reflect the stellar wind during the AGB phase.

<figure style="text-align: center; margin: 2rem 0;">
{% include figure.liquid path="assets/img/raman/raman_schematic.png" title="Raman He II scattering in planetary nebulae" class="img-fluid on-light" width="650" %}
<figcaption class="small-caption" style="text-align: left;">Schematic of Raman scattering of He II in a planetary nebula. An AGB star loses its mass through a stellar wind and becomes a planetary nebula with a white dwarf (WD) at its center. Near the hot WD, the strong UV radiation fully ionizes helium, and this He II region produces UV emission lines (λ1025, 972, and 949) close to the H I Lyman series. In the surrounding H I region, these photons can be Rayleigh-scattered, staying at the same UV wavelength and scattering multiple times, or Raman-scattered into optical lines (λ6545, 4851, and 4332) close to the H I Balmer series, which escape the H I region right away.</figcaption>
</figure>

I also led a spectroscopic survey searching for Raman-scattered features in planetary nebulae using BOES on the [BOAO 1.8 m telescope](https://www.kasi.re.kr/eng/pageView/65) in Korea. We discovered Raman-scattered He II features in four planetary nebulae {% cite choi20b lim25 %}, which doubled the number of known planetary nebulae with these features. These nebulae also show strong carbon emission, which may point to a connection between the progenitor mass and the dredge-up process during the AGB phase {% cite choi20b %}.
