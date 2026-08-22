---
title: "Home"
layout: homelay
sitemap: false
permalink: /
---
<h2 class="home-hero">{{ site.name }}</h2>
<p class="home-hero-sub">{{ site.title }}, {{ site.institution }}</p>
<div class="chip-container" markdown="0">
<a href="{{ site.url }}{{ site.baseurl }}/research" class="chip">Multiphase Flows</a>
<a href="{{ site.url }}{{ site.baseurl }}/research" class="chip">Shock&ndash;Droplet Interaction</a>
<a href="{{ site.url }}{{ site.baseurl }}/research" class="chip">Cavitation</a>
<a href="{{ site.url }}{{ site.baseurl }}/research" class="chip">Hypersonics</a>
<a href="{{ site.url }}{{ site.baseurl }}/research" class="chip">Reduced-Order Modeling</a>
<a href="{{ site.url }}{{ site.baseurl }}/research" class="chip">GPU-Accelerated CFD</a>
</div>
High-speed vehicles rarely encounter clean air. Rain along a hypersonic flight path, fuel droplets in a detonating combustor, and particulate ingested by a scramjet inlet all introduce a second phase whose behavior sets the heat loads and mass transfer the vehicle actually experiences.
When a shock passes over a droplet, the droplet deforms, develops surface instabilities, and breaks apart over microseconds — and the details of that breakup are difficult to measure and expensive to resolve.
My research develops numerical methods for these flows and looks for ways to make them cheap enough to study systematically.
<div class="callout callout-success" markdown="0">
<div class="callout-title"><i class="fa-solid fa-award callout-icon"></i> NSF International Research Experience for Students, 2025</div>
<p>Funded a summer at DLR Cologne developing POD-based dimensionality reduction for compressor cascade optimization, with the Fan and Compressor Group of the Institute of Propulsion Technology.</p>
</div>
### About me
I am a PhD student in aerospace engineering at Embry-Riddle Aeronautical University, working in the Computational Fluids and Aerodynamics Laboratory. I hold a dual MS from ERAU and Universidad del Valle, where I remain part of the IMPETUS INDOMITUS group. My current work uses the Multi-Component Flow Code to study shock-induced droplet deformation with seeded cavitation nuclei, focusing on how initial perturbations select the surface instability wavelengths that govern aerobreakup.

Before this I spent a summer at DLR Cologne as an NSF IRES fellow, and a summer at NASA Ames in the Aerothermodynamics Branch, where I used metric-based mesh adaptation to improve backshell heating estimates for the Dragonfly aeroshell. I completed my BS in aerospace engineering, with a minor in computer science, at the University of Central Florida.

Alongside the physics, I am interested in what makes these simulations tractable at scale — GPU parallelization, reduced-order and data-driven models, and more speculatively, quantum-accelerated approaches to CFD. I am also looking to pair the computational side of my work with experimental experience in high-speed flow facilities and diagnostics.
