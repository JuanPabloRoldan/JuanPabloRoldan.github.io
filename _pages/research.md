---
title: "Research"
layout: gridlay
sitemap: false
permalink: /research/
---

## Research

I work on hypersonic and multiphase flows: how liquid structures deform and break apart under shock loading, how gases behave when the continuum assumption stops holding, and what it takes to compute either one at useful cost. Most of my simulation work uses [MFC](https://github.com/MFlowCode/MFC), an open-source compressible multi-component flow solver.

<div class="research-grid">

<div class="research-card">
<img src="{{ site.url }}{{ site.baseurl }}/images/research/aerobreakup.png" class="research-thumb" alt="Deformed droplet under shock loading">
<div class="research-body">
<h4 class="research-title">Shock-Driven Droplet Aerobreakup</h4>
<p class="research-desc">When a shock passes over a droplet, the droplet's velocity, mass, and final shape are all set by how it fragments. I study how the initial perturbation state governs which surface instability wavelengths get selected during high-Mach aerobreakup. Externally, this sets the impact conditions behind hypersonic rain erosion; internally, the same breakup physics governs atomization in liquid-fueled and detonation-based propulsion.</p>
</div>
</div>

<div class="research-card">
<img src="{{ site.url }}{{ site.baseurl }}/images/research/doped_drop.png" class="research-thumb" alt="Droplet seeded with sub-grid Lagrangian bubbles">
<div class="research-body">
<h4 class="research-title">Bubble-Laden Droplets and Cavitation Nuclei</h4>
<p class="research-desc">Real rain droplets carry entrained non-condensable gas and cavitation nuclei. I couple sub-grid Lagrangian bubbles governed by the Keller&ndash;Miksis equation two-way to an axisymmetric Eulerian diffuse-interface framework, to isolate whether the mechanical, pressure-driven response of those nuclei is large enough to alter a droplet's internal pressure field and early deformation independently of vaporization.</p>
</div>
</div>

<div class="research-card">
<img src="{{ site.url }}{{ site.baseurl }}/images/research/hypersonics.png" class="research-thumb" alt="Entry capsule with a detached bow shock and separated backshell wake">
<div class="research-body">
<h4 class="research-title">Hypersonic Aerothermodynamics and Vehicle Design</h4>
<p class="research-desc">Entry and high-speed vehicle aerothermodynamics. At NASA Ames I simulated chemically reacting flow over the Dragonfly aeroshell during Titan entry with US3D, focused on the separated backshell wake where heating predictions are most grid-sensitive, and built a metric-based mesh adaptation workflow to sharpen those estimates without refining uniformly. On the design side I lead <a href="https://github.com/JuanPabloRoldan/HyPyRider">HyPyRider</a>, a rapid analysis tool that generates hypersonic waverider geometries from a prescribed shock and evaluates their performance for early-stage trade studies.</p>
</div>
</div>

<div class="research-card">
<img src="{{ site.url }}{{ site.baseurl }}/images/research/rarefied_rpod.svg" class="research-thumb" alt="Collisionless molecular trajectories striking a surface">
<div class="research-body">
<h4 class="research-title">Rarefied and Free-Molecular Flows</h4>
<p class="research-desc">In vacuum, a thruster plume expands without enough intermolecular collisions to behave as a continuum, so what reaches a nearby surface depends on collisionless transport and on how molecules scatter off the wall. I co-developed <a href="https://github.com/plume-kit/PyRPOD">PyRPOD</a>, which characterizes visiting-vehicle thruster configurations by plume impingement, propellant usage, and safety metrics using free-molecular and gas&ndash;surface interaction models, applied to rendezvous and docking at the lunar Gateway.</p>
</div>
</div>

<div class="research-card">
<img src="{{ site.url }}{{ site.baseurl }}/images/research/pod.png" class="research-thumb" alt="">
<div class="research-body">
<h4 class="research-title">Reduced-Order and Data-Driven Modeling</h4>
<p class="research-desc">Optimization is only as affordable as the design space is small. At DLR Cologne, as an NSF IRES fellow, I applied proper orthogonal decomposition to airfoil geometry so that a compressor cascade optimizer works over a handful of energetic shape modes instead of dozens of raw design variables, and characterized the tradeoff between how far the dimensionality can be cut and how much optimization accuracy is lost.</p>
</div>
</div>

<div class="research-card">
<img src="{{ site.url }}{{ site.baseurl }}/images/research/quantumCircuit_1Dpoisson" class="research-thumb" alt="">
<div class="research-body">
<h4 class="research-title">Heterogeneous Computing for CFD</h4>
<p class="research-desc">I am building GPU capability in CUDA for the accelerator side, and working through IBM's Qiskit coursework on the quantum side. I led the technical development of a DTRA STTR proposal on air-blast prediction that would offload portions of the CFD workload from classical HPC onto quantum hardware.</p>
</div>
</div>

</div>
