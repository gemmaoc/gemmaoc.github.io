---
layout: single
title: "Research"
permalink: research
author_profile: true
classes: wide
# excerpt: " "
header:
  overlay_image: assets/photos/Headers/pressure_ridge.JPG
---

<style>
  body {
    font-size: 16px;
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
  <h3>Overview</h3>
  <p>
    Direct observations of past climate data are brief, especially over remote regions such as Antarctica -- where reliable climate observations span only the satellite era 
    (1979 or later). Proxy records (​ice cores, coral records, and tree rings) record past climate states on longer timescales. I use a Bayesian data assimilation method to generate 2D climate reconstructions over the past centuries using constraints from proxy data. I use the ensemble Kalman filter data assimilation method, starting with a prior estimate 
    from a climate model simulation which I update using a global database of proxy observations. This produces gridded annual-mean resolution reconstructions of multiple climate states
    (including temperature, sea level pressure, and wind).
  </p>

  <p style="font-size: 14px !important;">
    <img src="/assets/photos/PaleoViz/pda_schematic.jpg" alt="Schematic of paleoclimate data assimilation">
    Proxy data are typically used for reconstructing past temperature. However, they are also useful for reconstructing climate at remote regions as long as their climates covary. 
    The figure on the right shows the covariance between West Antarctic winds and temperatures around the globe, as captured by a climate model. Red and blue regions show strong covariances; yellow dots show proxy locations. If a proxy record lies on a red or blue region, it is useful for reconstructing West Antarctic winds.
  </p>
  <h3>Associated studies</h3>
  <p>
    The reconstructions were originally published in <a href="https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2021GL095999" target="blank">O'Connor et al., 2021</a>. They are available for download at <a href="https://zenodo.org/records/5507607#.Y6OOl-yIb0o" target="blank">Zenodo</a>. 
  </p>
  <p>
    Reconstructions with single-proxy types assimilated (e.g., corals only, or ice cores only) were published in O'Connor et al., 2023 (available for download <a href="https://zenodo.org/records/8007655" target="blank">here</a>). Additional reconstructions using updated climate model priors are in review and will be available upon acceptance. These reconstructions have provided constraints in several applications, including the drivers of West Antarctic ice loss (O'Connor et al., 2023), Antarctic sea ice variability (Fogt et al., 2024), and Southern Ocean meltwater trends (Schneider et al., in review). 
  </p>

  <h3>Interactive visualization</h3>
  <p>
    <a href="https://jortuck.github.io/PaleoclimateVisualizer/" target="blank">
    <img src="/assets/photos/PaleoViz/Web_app_preview_SLP.jpg" alt="Preview of paleoclimate visualizer web application">
    </a>
  </p>
  <p>
    Click on the image above to go to a web application to interact with the reconstructions. Several reconstructions are available, each made with a different climate model prior. 
    The web application was custom built by my underaduate student, Jordan Tucker, as part of a summer RA position. 
  </p>

</div>

<div class="section" id="oceanmodeling">
  <h2>Numerical Ocean Modeling near West Antarctica</h2>
  <p>
    I use high-resolution numerical ocean models to understand the physical mechanisms governing ice loss in West Antarctica, which poses a major threat to sea level rise in 
    the coming decades to centuries. Melting is occurring via complex and coupled wind-ocean-ice processes that are sparsely observed. Ocean models are therefore an invaluable tool for understanding the mechanisms driving these processes in West Antarctica. 
  </p>
  <p>
    I use a regional domain of the MITgcm model (Nakayama et al., 2018) that spans the region surrounding West Antarctica, as shown in panel b below. I focus on understanding the influence of different wind patterns on the transport of warm ocean water (Circumpolar Deep Water), which reaches the glaciers via deep bathymetric troughs (shown in panel a). The results from these simulations are under review, but place new importance on meridional winds and sea ice (which affect local surface heat fluxes) as a driver of historical glacier retreat. 
  </p>
  <p style="font-size: 14px !important;">
    <img src="/assets/photos/PaleoViz/maps_recon_model_winds.jpg">
    Left: Wind (quivers) and sea level pressure (color) trends near West Antarctica over the 20th century in a proxy reconstruction. Right: mean wind and mean ocean temperature
    at 400m depth in the MITgcm model configuration I use. The cyan box is the Amundsen Sea Embayment region, where rapid glacier retreat is occurring. 
  </p>
</div>

<div class="section" id="elnino">
  <h2>Reconstructing El Niño activity from corals</h2>
    <p>
        Following on to research I started as an undergraduate at Georgia Tech, I have also led and collaborated on several studies
        that use coral oxygen isotope records from the central tropical Pacific. These records provide important constraints for 
        reconstructing past El Niño activity at up to monthly resolution. 
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