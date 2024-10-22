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
  h3 {
    font-size: 24px;  */
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

<!-- <div>
    <p>
        The focus of my current research is on paleoclimate data assimilation and numerical ocean modeling. I have used these methods to investigate 
        the atmospheric and oceanic drivers of ice sheet loss in West Antarctica on a range of timescales. See more details on these research topics 
        and additional research I have been involved in below.
    </p>
</div> -->

<div class="button-grid">
  <a href="#paleoDA" class="button">Paleoclimate reconstruction from data assimilation</a>
  <a href="#oceanmodeling" class="button">Numerical Ocean Modeling near West Antarctica</a>
  <a href="#elnino" class="button">Reconstructing El Niño activity from coral oxygen isotopes</a>
  <a href="#geophysics" class="button">Geophysical constraints from radar surveys in Antarctica</a>
</div>

<div class="section" id="paleoDA">
  <h2>Paleoclimate reconstruction from data assimilation</h2>
  <h3>Overview</h3>
  <p>
    Direct observations of past climate data are brief, especially over remote regions such as Antarctica -- where reliable climate observations span only the satellite era 
    (1979 or later). Proxy records, such as ice cores, corals, and tree rings, can be used to reconstruct past climate states on longer timescales. I use a Bayesian data assimilation 
    method to generate 2D climate reconstructions over the past centuries, using a climate model simulation as the prior and proxy observations. This approach can be used to generate gridded 
    reconstructions of multiple climate states, including temperature, sea level pressure, and wind.
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
    Reconstructions with single-proxy types assimilated (e.g., corals only, or ice cores only) were published in O'Connor et al., 2023 (available for download <a href="https://zenodo.org/records/8007655" target="blank">here</a>). Additional reconstructions using updated climate model priors are in review and will be available upon acceptance. 
  </p>
  <p>
    These reconstructions have provided constraints in several applications, including the drivers of West Antarctic ice loss (<a href="https://tc.copernicus.org/articles/17/4399/2023/"
    target="blank">O'Connor et al., 2023</a>), Antarctic sea ice variability (<a href="https://cp.copernicus.org/articles/20/53/2024/" target="blank">Fogt et al., 2024</a>), 
    and Southern Ocean meltwater trends (<a href="https://doi.org/10.22541/essoar.172411232.25724214/v2" target="blank">Schneider et al., in review</a>). 
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
    In West Antarctica, the most rapid ice loss is occurring via exposure to warm ocean water that lies at depth, called Circumpolar Deep Water (CDW; see left figure below). CDW surrounds Antarctica, just north of the continental shelf. Near West Antarctica, CDW transport toward the glaciers and ice shelves is influenced by several processes, including winds, sea ice, and meltwater inputs. I use a regional domain of the MITgcm model (Nakayama et al., 2018; model domain on right panel) to investigate the influence of different wind patterns on the poleward transport of CDW. The results from these simulations highlight the importance on meridional winds and sea ice (which affect local surface heat fluxes) as a driver of historical glacier retreat (this work is in review). 
  </p>
  <p style="font-size: 14px !important;">
    <img src="/assets/photos/PaleoViz/mitgcm_profile_map_dark.jpg"> 
  </p>
</div>

<div class="section" id="elnino">
  <h2>Reconstructing El Niño activity from corals</h2>
    <p>
        I have also led and collaborated on several studies that use coral oxygen isotope records from the central tropical Pacific, in collaboration with Kim Cobb and colleagues at Georgia Tech during my undergraduate studies. 
        These records provide important constraints for reconstructing past El Niño activity at up to monthly resolution. 
    </p>
    <p>
        In 2016, I participated in a field expedition to Christmas Island, in the central tropical Pacific. 
        We collected several mini coral cores, seawater samples, and in situ logger data. Using these cores and data, we showed that coral oxygen isotopes indeed faithfully recordes the extreme conditions from the 2015/16 El Niño
        event, which experienced major warming and freshening. By comparing the records with in salinity measurements, we estimate that warming contributes ~70% of the oxygen isotope changes, and freshening contributes the remaining ~30%. 
        These results are published in <a href="https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2021GL094036" target="blank">O'Connor et al., 2021</a>. 
    </p>
    <img src="/assets/photos/PaleoViz/coral_analysis.jpg">
  <h3>Additional Studies</h3>
  <ol>
    <li>Corals from the central tropical Pacific indicate El Niño-Southern Oscillation variability is ~25% stonger relative to preindustrial conditions: <a href="https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2019GL083906" 
    target="blank">Grothe et al., 2020</a></li>
    <li>Coral ensembles reveal warming and freshening trends in the central tropical Pacific over the 20th century: <a href="https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2021GL094051"
    target="blank">Hitt et al., 2022</a></li>
    <li>Paired oceanographic and oxygen isotope observations reveal large differences in the warming vs. freshening contributions to coral oxygen isotope records due to ocean dynamics: 
    <a href="https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2023GL104454" target="blank">Stevenson et al., 2023</a></li>
  </ol>
</div>

<div class="section" id="geophysics">
  <h2>Geophysical constraints from radar surveys in Antarctica</h2>
  <h3>Ice core site selection at Hercules Dome</h3>
  <p>
        As part of my doctorate work at the University of Washington, I was fortunate to be a part of a major geophysical compaign at Hercules Dome, Antarctica. We conducted ice penetrating radar surveys 
        to investigate ice sheet dynamics at the site and select an ideal location for drilling the next U.S. deep ice core, which will ideally capture conditions from ~130,000 years ago -- the last time
        the Earth was as warm as it is today. These conditions will provide insight into whether West Antarctica collapsed during this period, providing context for the natural stability of the ice sheet. 
    </p>
    <p>
        A location in the West Dome region has been selected as a promising location to drill the ice core (<a href="https://www.cambridge.org/core/journals/journal-of-glaciology/article/site-for-deep-ice-coring-at-west-hercules-dome-results-from-groundbased-geophysics-and-modeling/85E176550C0C909331E8B5B9C4915494" target="blank">Fudge et al., 2022</a>). 
        It appears to have simple and undisrupted layers of ice, meaning that drilling an ice core there would likely allow for a continuous reconstruction of past climate from a single location. It also appears to be frozen at the bedrock, suggesting that the deepest layers of ice have been preserved and that there is potential for getting ice from 130,000 years ago.
    </p>
    <div style="display: flex; flex-direction: column; align-items: center; text-align: center; margin: 20px;">
        <img src="/assets/photos/PaleoViz/herc_dome_results.jpg" alt="Hercule Dome survey results" style="max-width: 100%; height: auto; border: 0;">
        <p style="margin-top: 10px; font-size: 14px; width: 100%">Left: radargram showing smoth ice layers at West Dome, where the ice core will be drilled in the coming years. Right: map of Hercules Dome and the radar surveys completed during our field season. Source: Fudge et al., 2022</p>
    </div>
  <h3>Additional Studies</h3>
  <ol>
    <li>Hercules Dome radar surveys reveal ancient U-shaped valleys indicative of previous fast-flowing ice, which suggests that this location may have served as a nucleation center
        for the West Antarctic Ice Sheet: <a href="https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2021GL096218" target="blank">Hoffman et al., 2024</a></li>
    <li>South Pole radar surveys indicate thawed and stable subglacial lake: <a href="https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2021GL096218" target="blank">Hills et al., 2022</a></li>
    <li>Learn more about the ongoing <a href="https://herculesdome.org/" target="blank">Hercule Dome ice core project</a>.</li>
  </ol>

</div>
