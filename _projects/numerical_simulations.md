---
layout: page
title: Numerical Simulations of Sand Dunes
description: CFD-DEM simulations of sand dunes revealing grain-scale dynamics inaccessible to experiments
img: assets/img/force.jpg
importance: 3
category: work
---

## Numerical Simulations of Sand Dunes

Laboratory experiments provide direct observations of dune dynamics, but many quantities remain inaccessible — forces acting on individual grains, instantaneous flow fields, and grain-scale interactions between colliding dunes, for example. Numerical simulations bridge this gap.

In this project, sand dunes were simulated by coupling two complementary methods: **Large-Eddy Simulations (LES)** for the continuous fluid phase and the **Discrete Element Method (DEM)** for the granular phase. Each grain is tracked individually, allowing access to grain-scale quantities that experiments cannot directly measure. Simulations involved up to **100,000 grains**, capturing the full complexity of dune morphodynamics from formation to interaction.

---

### Formation of a Subaqueous Barchan Dune

A turbulent water flow acts on an initially conical pile of grains, which progressively deforms into a barchan dune. The flow direction is from **top to bottom**.

<div class="row mt-3 justify-content-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include video.liquid path="assets/video/grains_with_time.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true loop=true muted=true %}
  </div>
</div>
<div class="caption">
  CFD-DEM simulation of a turbulent water flow acting on a pile of grains deforming into a barchan dune. Flow direction: top to bottom.
</div>

<ul>
  <li>
    Alvarez, C.A., & Franklin, E.M. (2020).
    <strong>Shape evolution of numerically obtained subaqueous barchan dunes.</strong>
    <em>Physical Review E</em>, 101, 012905.
    <a href="https://doi.org/10.1103/PhysRevE.101.012905" target="_blank">DOI</a>
  </li>
</ul>

---

### Grain-Scale Force Fields

One of the key advantages of numerical simulations is direct access to forces acting on each grain. This simulation shows the **instantaneous streamwise force field** — the force component aligned with the flow direction (top to bottom) — over a fully developed barchan dune.

<div class="row mt-3 justify-content-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include video.liquid path="assets/video/F_px.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true loop=true muted=true %}
  </div>
</div>
<div class="caption">
  Instantaneous streamwise force fields over a barchan dune. Each grain is colored by the magnitude of the force aligned with the flow direction (top to bottom).
</div>

<ul>
  <li>
    Alvarez, C.A., & Franklin, E.M. (2021).
    <strong>Force distribution within a barchan dune.</strong>
    <em>Physics of Fluids</em>, 33, 013313.
    <a href="https://doi.org/10.1063/5.0033964" target="_blank">DOI</a>
  </li>
</ul>

---

### Interacting Barchan Dunes

When two barchan dunes travel in the same direction, they interact in a complex dance of grain exchange. This simulation captures two dunes chasing each other, revealing the back-and-forth transmission of grains between the bedforms at the grain scale.

<div class="row mt-3 justify-content-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include video.liquid path="assets/video/barchan_interaction_compressed.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true loop=true muted=true %}
  </div>
</div>
<div class="caption">
  CFD-DEM simulation of two barchan dunes chasing each other. Grain transmission back and forth between the dunes is visible at the grain scale. Credit: Nicolao C. Lima.
</div>

<ul>
  <li>
    Lima, N.C., Assis, W.R., Alvarez, C.A., & Franklin, E.M. (2024).
    <strong>Barchan-barchan dune repulsion investigated at the grain scale.</strong>
    <em>Journal of Geophysical Research: Earth Surface</em>, 129, e2024JF007741.
    <a href="https://doi.org/10.1029/2024JF007741" target="_blank">DOI</a>
  </li>
</ul>
