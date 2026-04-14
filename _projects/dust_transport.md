---
layout: page
title: Dust Transport on Earth and Mars
description: Experimental and numerical investigations of dust settling and vertical transport under Earth-to-Mars atmospheric conditions
img: assets/img/Mars_dust.jpg
importance: 4
category: work
---

## Dust Transport on Earth and Mars

Airborne dust plays a critical role in the climate systems of both Earth and Mars. On Earth, dust aerosols influence cloud formation, precipitation, and nutrient cycles across ocean basins. On Mars, dust governs atmospheric opacity, surface energy balance, and sand transport — and poses hazards to future human exploration. Despite its importance, dust dynamics remain poorly understood, particularly under the low-density atmospheric conditions of Mars.

This project combines **laboratory experiments** and **large-eddy simulations (LES)** to investigate two fundamental aspects of dust transport: how fast dust settles under low-density atmospheres, and how topography and convection interact to loft dust to high altitudes.

---

### Dust Settling Velocity Under Low-Density Atmospheres

Accurately predicting the speed at which dust settles is critical because it controls how long dust remains suspended in the atmosphere. However, under rarefied conditions — such as those on Mars — continuum mechanics breaks down and Stokes' law must be corrected for gas-particle slip. Previous measurements of these slip corrections relied on complex, indirect setups involving very few idealized particles, limiting their applicability to realistic scenarios.

Here, we measured dust settling velocity directly using **Time-Resolved Particle Image Velocimetry (TR-PIV)** under Earth-to-Mars atmospheric pressures. By tracking over **10,000 particles** simultaneously, TR-PIV provides a statistically robust approach that can be extended to realistic dust properties — including irregular shapes, variable size distributions, and different gas compositions.

<div class="row mt-3 justify-content-center">
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/fig_1_TRPIV.jpg" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">
Influence of particle size on dust settling on Earth and Mars.(a) Predicted settling time (in days) necessary for dust to fall down 1 km on
both planets. (b) Mars‐to‐Earth ratio of dust settling velocity.
</div>

**Key Points:**
- Dust settling velocity controls the residence time of dust in the atmosphere but is challenging to measure under low atmospheric density.
- TRPIV technique enables systematic investigations of dust settling under realistic conditions — including variable particle sizes, shapes, and concentrations — that were previously unachievable.

---

### Related Publications

<ul>
  <li>
    Alvarez, C.A., Gunn, A., Swann, C., Trimble, S.M., Ewing, R.C., & Lapôtre, M.G.A. (2024).
    <strong>Direct measurements of dust settling velocity under low-density atmospheres using time-resolved particle image velocimetry.</strong>
    <em>Geophysical Research Letters</em>, 51, e2024GL109958.
    <a href="https://doi.org/10.1029/2024GL109958" target="_blank">DOI</a>
  </li>
</ul>

---

### How Coarse Dust Reaches High Altitudes: The Role of Convection and Terrain

Current global climate models substantially underestimate the presence of coarse dust (d ≥ 20 µm) at high altitudes, suggesting that mechanisms driving vertical dust transport are poorly captured. Two candidates are **topography-induced shear** and **buoyancy-driven convection** — yet their combined effect had not been systematically investigated.

Using large-eddy simulations with Lagrangian particle tracking, we studied how a gentle hill topography and convective conditions interact to transport coarse dust particles of different sizes (5–100 µm) across a range of atmospheric stability conditions spanning neutral to highly convective regimes.

<div class="row mt-3 justify-content-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/dust_earth_temp_hill.jpg" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">
  Lagrangian particle trajectories at t = 3 min 25 sec for 60 µm particles under flat (left) and hill (right) topographies across neutral (ΔT = 0K), weak (ΔT = 0.5K), and strongly convective (ΔT = 4K) conditions. Colors indicate particle height above the surface.
</div>

**Key Findings:**
- Under neutral conditions, hill topography increases the probability of dust uplift by orders of magnitude relative to flat terrain.
- Even under very weak convective conditions, the hill's effect on vertical transport becomes negligible — convection dominates.
- These results help explain why coarse dust particles are found at much greater distances from their sources than current models predict.

---

### Related Publications

<ul>
  <li>
    Alvarez, C.A., Heisel, M., Kok, J.F., & Chamecki, M. (in preparation).
    <strong>On the combined effects of topography and convection on the vertical transport of coarse dust.</strong>
    <em>Journal of Geophysical Research: Atmospheres.</em>
  </li>
</ul>
