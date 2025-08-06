---
title: "Research"
permalink: /_research/bedrock_river_research/
author_profile: True
layout: single
classes: wide
---


<span style="font-weight: bold; font-size: 1.75rem; color: rgb(247, 163, 9);">Bedrock Anisotropy and Meander Growth</span>


**Project Overview**
<p style="font-size: 0.8rem;">
Put simply, bedrock meandering rivers are sinuous channels that flow directly over bedrock or a very thin sediment cover. They are supply-limited, which means water's transport capacity always exceed sediment supply, so the river can remove sediment faster than it's being supplied to the system, and morphological change depends on how much sediment is available in the system.
Bedrock rivers can be found in a variety of environments and, due to the limited sediment cover, are capable of incising directly into the underlying rock over geologic timescales. 
As a result, they preserve valuable records of rock uplift, fault activity, and long-term landscape evolution (e.g., strath terraces). <br><br>

However, the mechanisms by which bedrock channels meander have only been partially explored. 
While some maintain a stable single-thread form for millions of years, others transition more rapidly into multi-threaded systems.

Because tetconic, climatic, lithologic, or any combincation of these forcings can influence the stability of bedrock meandering rivers,
this study focuses on the role of lithology in maintaining single-thread channel stability. 
To explore threshold behavior, I utilize a 1-D bedrock incision model adapted from Howard and Knutson (1984) by Profs. Sarah Schanz and Briany Yanites. <br><br>

Supported in full by an NSF-funded research grant awarded to Prof. <a href="https://sites.coloradocollege.edu/sschanz/" target="_blank">Sarah Schanz</a>, this project was carried out from junior summer (2022) to senior spring (2023) at Colorado College.
</p>

**Introduction**
<p style="font-size: 0.8rem;"> The role of lithology in active bedrock meandering rivers can be partitioned into three primary mechanisms: </p>

<div style="float: right; width: 320px; margin-left: 1.5rem; margin-bottom: 1rem; text-align: center;">
  <img src="/assets/research_images/bedrock_research/slaking.jpg" alt="Slaking bedrock" style="width: 100%; border-radius: 6px;">
  <p style="font-size: 0.55rem; color: #666; margin-top: 0.5rem;">
    <em>Figure 1. Slaking bedrock of the Roslyn Formation in central Washington State, USA. Image provided by Prof. Sarah Schanz.</em>
  </p>
</div>

 <ul style="font-size: 0.8rem; line-height: 1.6; margin-left: 20px;"> <li style="margin-bottom: 10px;"> <strong>Rock strength and erosion resistance:</strong> Stronger and more deeply exhumed lithologies exhibit greater erosion resistance and maintain stable channel forms more readily than younger, softer rocks (Bursztyn et al., 2015). </li> <li style="margin-bottom: 10px;"> <strong>Channel width control:</strong> An inverse relationship exists between rock strength and channel width, with stronger substrate strength typically associated with narrower channel widths (Allen et al., 2013). </li> <li style="margin-bottom: 10px;"> <strong>Weathering processes:</strong> Differential weathering processes such as slaking and freeze-thaw cycles create asymmetry between sub-aerial and submerged bedrock erodibility, promoting channel widening (Montgomery, 2004). </li> </ul>

**Methods**

<p style="font-size: 0.8rem;">
To understand how anisotropic bedrock strength influences river behavior, two key erosional processes that determine channel evolution are quantitatively examined. Lateral erodibility (kl) controls how readily the river can widen its channel through sidewall erosion, while vertical erodibility (kf) governs the rate of downward incision into the bedrock. These parameters are central to understanding where and how erosion occurs, since anisotropic strength allows rivers to preferentially erode along certain directions. <br><br>

Because these erodibility constants are not well-constrained through field measurements or laboratory experiments, I tested a range of empirically derived values to explore their effects on channel behavior. 
The vertical erodibility values tested were -0.000001, -0.000005, -0.00001, -0.00005, and -0.0001, while lateral erodibility values ranged from 0.001 to 0.1 (specifically: 0.001, 0.005, 0.01, 0.05, 0.1). <br><br>

Besides, previous models have largely assumed static channel width channel geometry (Leopold & Wolman, 1957), as they are computationally efficient and simple to implment. A key innovation of this model allows the channel width to change with lateral migration and/or channel depth to change with vertical incision. Three distinct channel geometry types are simulated: 1. with constant width and height (no_change) 2. rectanglular 3. trapezoidal. (Figure. 2)<br><br>
</p>
<div style="float: bottom; width: 800px; margin-left: 1.5rem; margin-bottom: 1rem; text-align: center;">
  <img src="/assets/research_images/bedrock_research/kl_0.05_kf_-0.000001.jpg" alt="channel geometry" style="width: 100%; border-radius: 6px;">
  <p style="font-size: 0.8rem; color: #666; margin-top: 0.5rem;">
    <em>Figure 2. Comparison of planforms at 100 ky for different channel types: no change, rectangular, and trapezoidal. kl, kf, and initial slope held constant at 0.05, -0.000001, and 0.0001, respectively. The trapezoidal channel exhibits high-frequency, low-amplitude oscillations , which are indicators of frequent cutoffs.</em>
  </p>
</div>
<p style="font-size: 0.8rem;">
Lastly, follwoing traditional geomorphological convetions, channels with a sinuosity greater than 1.5 were considered as meandering rivers. 
</p>

**Insights**
<p style="font-size: 0.8rem;">
A single thread meandering bedrock river can evolve into a straight channel, meandering channel, or transit to exhibit braided patterns, depending on the balance between lateral and vertical erosion rate and the geometry of the river channel. 
</p>

<div style="float: bottom; width: 800px; margin-left: 1.5rem; margin-bottom: 1rem; text-align: center;">
  <img src="/assets/research_images/bedrock_research/comparison_of_simulations.jpg" alt="all the simulations" style="width: 100%; border-radius: 6px;">
  <p style="font-size: 0.8rem; color: #666; margin-top: 0.5rem;">
    <em>Figure 3. A total of 125 simulations of channels with different lateral erodibility, vertical erodiblity, and channel geometry, all starting from a sinuosity value of 1.42, were run for 100,000 yrs. The arrows in the figure indicate whether the sinuosity of a partiuclar channel decreases or increases after 100,000 yrs.  </em>
  </p>
</div>



**References**


<ul style="font-size: 0.8rem; line-height: 1.6; margin-left: 20px;">
  <li>
    Allen, G. H., Barnes, J. B., Pavelsky, T. M., & Kirby, E. (2013). Lithologic and tectonic controls on bedrock channel form at the northwest Himalayan front: BEDROCK CHANNEL FORM, MOHAND, INDIA. <em>Journal of Geophysical Research: Earth Surface</em>, v. 118(3), p. 1806–1825. <a href="https://doi.org/10.1002/jgrf.20113">https://doi.org/10.1002/jgrf.20113</a>.
  </li>
  <li>
    Bursztyn, L., Pederson, J. L., Tressler, C., Mackley, R. D., & Mitchell, K. J. (2015). Rock strength along a fluvial transect of the Colorado Plateau: Quantifying a fundamental control on geomorphology. <em>Earth and Planetary Science Letters</em>, 429, 90-100. <a href="https://doi.org/10.1016/j.epsl.2015.07.042">https://doi.org/10.1016/j.epsl.2015.07.042</a>.
  </li>
  <li>
  Howard, A. D., & Knutson, T. R. (1984). Sufficient conditions for river meandering: A simulation approach. <em>Water Resources Research</em>, v. 20(11), p. 1659–1667.<a href="https://doi.org/10.1029/WR020i011p01659">https://doi.org/10.1029/WR020i011p01659</a>.
</li>
<li>
  Leopold, L. B., & Wolman, M. G. (1957). River channel patterns: Braided, meandering, and straight (Professional Paper 282-B). <em>U.S. Geological Survey</em>. <a href="https://pubs.usgs.gov/publication/pp282B">https://pubs.usgs.gov/publication/pp282B</a>.
</li>
  <li>
    Montgomery, D. R. (2004). Observations on the role of lithology in strath terrace formation and bedrock channel width. <em>American Journal of Science</em>, v. 304(5), p.454–476. <a href="https://doi.org/10.2475/ajs.304.5.454">https://doi.org/10.2475/ajs.304.5.454</a>.
  </li>
</ul>


**Research Output**

<a href="/assets/misc/Undergrade_Thesis_ZS.pdf" target="_blank" rel="noopener noreferrer">
  View Thesis (PDF)
</a>

<a href="/assets/misc/GSA_2024 Presentation_ZS.pdf" target="_blank" rel="noopener noreferrer">
  View Slides (PDF)
</a>




