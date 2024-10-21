---
permalink: photos
layout: single
title: "Photos"
author_profile: true
classes: wide
header:
  overlay_image: assets/photos/Headers/mcmurdo_sea_ice.jpeg
---
<h2> Hercules Dome, Antarctica</h2>
<div style="display: flex; flex-direction: column; align-items: center; text-align: center; margin: 20px;">
  <img src="assets/photos/herc_dome_map.png" alt="map from Fudge et al., 2022" style="max-width: 50%; height: auto; border: 0;">
  <p style="margin-top: 10px; font-size: 14px; width: 50%">Map of Hercules Dome and the radar surveys completed during our field season in 2019/2020. Source: Fudge et al., 2022</p>
</div>
<div class="gallery" style="display: flex; flex-wrap: wrap;">
  {% assign images = site.static_files %}
  {% for image in images %}
    {% if image.path contains "/assets/photos/Antarctica" %}
      <div class="col-4" style="flex: 1 1 50%; padding: 10px;">
        <img src="{{ image.path }}" alt="Gallery Image" style="width:100%; margin-bottom:15px; border-radius: 15px;" />
      </div>
    {% endif %}
  {% endfor %}
</div>

<h2> Christmas Island, Kirabati</h2>
<p style="font-size: 16px;">
    In November, 2016 (just after the very strong 2015/15 El Niño event), I participated in a field expedition led by Kim Cobb to Christmas Island in the Republic of Kiribati.
    We drilled living and fossil coral cores, collected seawater samples, and serviced in situ loggers to collect ocean condition data from the coral sites. 
</p>
<div style="display: flex; flex-direction: column; align-items: center; text-align: center; margin: 20px;">
  <img src="assets/photos/xmas_island_map.jpg" alt="map from Grothe et al., 2022" style="max-width: 60%; height: auto; border: 0;">
  <p style="margin-top: 10px; font-size: 14px; width: 60%">Map of Christmas Island, which lies in the heart of the El Niño region. Source: Grothe et al., 2020</p>
</div>
<div class="gallery" style="display: flex; flex-wrap: wrap;">
  {% assign images = site.static_files %}
  {% for image in images %}
    {% if image.path contains "/assets/photos/Xmas Island" %}
      <div class="col-4" style="flex: 1 1 50%; padding: 10px;">
        <img src="{{ image.path }}" alt="Gallery Image" style="width:100%; margin-bottom:15px; border-radius: 15px;" />
      </div>
    {% endif %}
  {% endfor %}
</div>
