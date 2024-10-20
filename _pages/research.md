---
layout: single
title: "Research"
permalink: /research
author_profile: true
classes: wide
# excerpt: " "
header:
  overlay_image: /assets/photos/Headers/pressure_ridge.jpg
---

<style>
  body {
    font-size: 18px;
  }
  h2 {
    font-size: 32px;  */
  }

  .button-grid {
    display: grid;
    grid-template-columns: repeat(2, 1fr); /* 2 columns */
    gap: 20px; /* Space between buttons */
    margin: 20px; /* Margin around the grid */
  }

  .button {
    background-color: gray; /* Bootstrap primary color */
    color: white; /* Text color */
    padding: 20px; /* Padding inside the button */
    text-align: center; /* Center text */
    font-size: 24px; /* Font size */
    font-weight: bold; /* Bold text */
    text-decoration: none; /* Remove underline from link */
    border-radius: 8px; /* Rounded corners */
    transition: background-color 0.3s; /* Smooth background color transition */
  }

  .button:visited {
    background-color: gray;
    color: white
  }

  .button:hover {
    background-color: #0056b3; /* Darker shade on hover */
  }

  .section {
    margin: 40px 0; /* Space between sections */
  }
</style>

<div>
    <p>
        The focus of my current research is on paleoclimate data assimilation and numerical ocean modeling. I have used these methods to investigate 
        the atmospheric and oceanic drivers of ice sheet loss in West Antarctica on a range of timescales. See more details on these research topics 
        and additional research I have been involved in below.
    </p>
</div>

<div class="button-grid">
  <a href="#paleoDA" class="button">Paleoclimate reconstruction from data assimilation</a>
  <a href="#oceanmodeling" class="button">Numerical Ocean Modeling near West Antarctica</a>
  <a href="#elnino" class="button">Reconstructing El Niño activity from corals</a>
  <a href="#geophysics" class="button">Geophysical constraints from radar surveys in Antarctica</a>
</div>

<div class="section" id="paleoDA">
  <h2>Paleoclimate reconstruction from data assimilation</h2>
  <p>
    ​I use a Bayesian data assimilation method (the Ensemble Kalman filter) to generate 2D reconstructions of various climate states in the past centuries. I use a prior estimate 
    from a climate model simulation and update that estimate using proxy observations from ice cores, coral records, and tree rings from across the globe. 
    The reconstructions were originally published in O'Connor et al., 2021a in GRL. 
  </p>
  <p>
    My research focuses on reconstructions in the Southern Hemisphere, where westerly winds and sea level pressure influence numerous important processes, including glacier retreat in Antarctica and Southern Ocean carbon uptake. Most climate observations in Antarctica started only ~40 years ago (~1979), making it very difficult to contextualize recent activity and project future changes in Antarctica. 
  </p>
  <p style="font-size: 14px !important;">
    <img src="/assets/photos/PaleoViz/pda_schematic.jpg" alt="Schematic of paleoclimate data assimilation">
    Proxy data are typically used for reconstrucitng past temperature. However, they are also useful for reconstructing climate at remote regions, as long as their climates covary. 
    The figure on the right shows the covariance between West Antarctic winds and temperatures around the globe, as captured by a climate model. Yellow dots show proxy locations. 
  </p>
</div>

<div class="section" id="oceanmodeling">
  <h2>Numerical Ocean Modeling near West Antarctica</h2>
  <p>Content for Section 2 goes here. This can include text, images, or other elements.</p>
</div>

<div class="section" id="elnino">
  <h2>Reconstructing El Niño activity from corals</h2>
    <p>
        Following on to research I started as an undergraduate at Georgia Tech, I have also led and collaborated on several studies
        that use coral oxygen isotope records from the central tropical Pacific. These records provide invaluable constraints for 
        reconstructing past El Niño activity. 
    </p>
</div>

<div class="section" id="geophysics">
  <h2>Geophysical constraints from radar surveys in Antarctica</h2>
  <p>
        As part of my doctorate work at the University of Washington, I was fortunate to be a part of a major geophysical compaign
        at Hercules Dome, Antarctica. We conducted ice penetrating radar surveys to investigate ice sheet dynamics at the site
        and select an ideal location for drilling the next U.S. deep ice core. 
    </p>
</div>