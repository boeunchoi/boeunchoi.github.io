---
layout: page
title: Milky Way CGM
description: Probing the gaseous halo of the Milky Way
img: assets/img/cgm/plank_mw.png
importance: 1
category: research
related_publications: false
---

<!-- match the figure height -->
<style>
.match-height {
height: 450px;
width: auto;
object-fit: contain;
}

@media (max-width: 768px) {
.match-height {
height: 200px; /* Adjust for smaller screens */
width: auto;
object-fit: contain;
}
}
</style>

<!-- Figure original ratio-->
<style>
.original-ratio {
  max-width: 100%; /* Ensure the image fits within its container */
  height: auto; /* Maintain the original aspect ratio */
  display: block; /* Remove any inline spacing issues */
}
</style>

<!-- small caption -->
<style>
.small-caption {
  font-size: 0.88rem; /* Adjust as needed */
  color: #424E58; /* Optional: a lighter text color */
}
</style>

In Seattle, a city famous for its cloudy and rainy days during much of the year, and where I am doing my PhD, I often reflect on the impact of the atmosphere on the environment and life below. Clouds often form dynamic patterns &mdash; sometimes scattered in patches, other times covering the entire sky<!--(which gave a spectacular view of solar eclipse in 2024)-->. While observing these skies, I often find myself imagining clouds stretching across the entire Milky Way's sky and what the "weather" of our galaxy might look like.

{% raw %}

<!--
<div class="row text-center">
<div class="col-sm mt-3 mt-md-0">
<figure>
{% include figure.liquid path="assets/img/cgm/greenlake_clouds.jpg" title="example image" class="img-fluid rounded z-depth-1 match-height" %}
<figcaption>Clouds above Green Lake, Seattle</figcaption>
</figure>
</div>
<div class="col-sm mt-3 mt-md-0">
<figure>
{% include figure.liquid path="assets/img/cgm/uw_solar_eclipse.png" title="example image" class="img-fluid rounded z-depth-1 match-height" %}
<figcaption>credit: University of Washington</figcaption>
</figure>
</div>
</div>
-->

{% endraw %}

<!--
Similar to the Earth, galaxies are surrounded by an atmosphere known as the circumgalactic medium (CGM). Extending to the galaxy's virial radius (and beyond), this diffuse, multiphase medium is thought to contain a substantial mass and serve as a gas budget for galactic star formation. I am interested in the CGM from the perspective of the baryon cycle, particularly connecting the CGM and central galaxy. The Milky Way is a good laboratory to test our understanding on the CGM, owing to ample observations with high data quality. -->

<br>
<h3>Nature of the Milky Way Disk-Halo Interface</h3>

The interface between the galactic disk and halo, known as the disk-halo interface (DHI), is a dynamic region where gas accretion, ejection, and recycling interplay. Despite its critical role in galaxy evolution, studying this very inner region of the circumgalactic medium (CGM) has been challenging due to its small scale (~few kpc) compared to the entire CGM (~few hundred kpc).
The Milky Way is an ideal laboratory for investigating the DHI, owing to ample observations with high data quality and spatial resolution.

Understanding gas accretion and recycling at the DHI is critical for unraveling the processes driving galaxy evolution. Key questions include: How does halo gas cool and accrete onto the star-forming disk? How does metal-poor gas survive and fuel star formation as observed in stellar populations? And how is gas ejected by feedback processes recycled back to the disk?

Metallicity serves as an excellent tracer of gas flows, their mixing, and origins; however, measuring metallicity of ionized gas remains challenging, primarily due to difficulties in constraining the amount of ionized hydrogen. In my recent work (<a href="https://ui.adsabs.harvard.edu/abs/2024ApJ...976..222C/abstract">Choi et al. 2024</a>), I measured and mapped the metallicity of ionized gas clouds at the Milky Way’s DHI using halo star-pulsar pairs, which provide precise ionizaton corrections. By analyzing UV spectra available from <a href="https://archive.stsci.edu/">MAST</a>, I determined ion content (metals) from absorption spectroscopy of halo stars, mostly observed with HST/COS and HST/STIS. The ionized gas content (electron column density) was constrained by the dispersion measures (DMs) of pulsars that lie in the same globular clusters as these UV-bright halo stars (see the schematic below).

This study reveals a large scatter in metallicity values (0.04–3.2 solar metallicity), suggesting that the DHI comprises a mixture of gaseous structures with multiple origins. Notably, the findings provide clear evidence of gas recycling processes, as indicated by the detection of a supersolar infalling cloud. We estimated the timescale for gas recycling processes at the DHI, often referred to as a "Galactic fountain", to be about tens of millions of years.

<div class="col-sm mt-3 mt-md-0">
<figure>
{% include figure.liquid path="assets/img/cgm/halo_dm_schematic.png" title="pulsar-halo star schematic" class="original-ratio" %}
<figcaption class="small-caption">A schematic of the metallicity study using pulsar DMs. The total electron column density derived from pulsar DMs provides an upper limit for ionized hydrogen column density of the cloud along the sight line. By fitting the data with a photoionization model, we estimated the metallicity of gas clouds at the DHI.</figcaption>
</figure>

<!-- Galaxies are surrounded by a gaseous halo, so does our Milky Way. It features an atmosphere of the galaxies known as the circumgalactic medium (CGM). Unlike Earth's atmosphere, which extends to heights comparable to Earth's radius and has a mass on the order of one-millionth that of Earth, the CGM typically extends to the virial radius of the galaxy -- approximately 300 kpc for the Milky Way, which has the radius is about 15 kpc -- and is thought to contain a much greater mass than that of the central galaxy itself. -->

<br>
<!--
<h3>Magellanic Stream: the Largest Gaseous Structure in the Sky</h3> -->
