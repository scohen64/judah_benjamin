# Paths of Memory: A Sephardi Migration Story Map
This repository documents Sephardi migration paths using an interactive Leaflet story map.
The map integrates a linked Google Sheets template and scrolling narrative to visualize locations, movements, and community histories.
It supports embedded images, audio, and video, along with Leaflet TileLayer and GeoJSON overlays to enhance geographic and cultural context.

🔗 Explore the live project here: [https://sepharad.miami.edu](https://sepharad.miami.edu/) 


## Live links (replace with your own)
- Leaflet Map https://scohen64.github.io/danino_migration_path/#1
- Google Sheets template https://docs.google.com/spreadsheets/d/19OpksAb7ttMBtbDGYH-Vva01lUYO_7vyMv3QLcPHFM8/edit?gid=0#gid=0

## Create Your Own Migration Path and Send Us the Link to Upload Into the World Sephardic Database
- See step-by-step tutorial in *Hands-On Data Visualization* https://HandsOnDataViz.org/leaflet-storymaps-with-google-sheets.html
- When done, send us the link to shaicohen@miami.edu. 

#### Geocode your address data with Google Sheets add-on
To geocode (find latitude and longitude coordinates), we recommend installing the free [Geocoding by SmartMonkey add-on for Google Sheets](https://gsuite.google.com/marketplace/app/geocoding_by_smartmonkey/1033231575312). Insert your addresses in place of the samples in the Geocoding Details tab, then use Add-Ons > Geocoding > Geocode Details menu. Learn more in *Hands-On Data Visualization* https://handsondataviz.org/geocode.html

#### To finalize your map, you need to either:
- Download each Google Sheets tab as a CSV file and upload into a `csv` subfolder in your GitHub repo
  - OR
- Get your own Google Sheets API Key to insert into `google-doc-url.js`

## Credits (and licenses)
This project is part of the *Sephardi Spaces Project* at the University of Miami, developed by [Shai Cohen](https://www.linkedin.com/in/shai-cohen-7133052a/). The project explores the histories, migrations, and cultural heritage of Sephardi communities through digital tools and public humanities.

© Sephardi Spaces – University of Miami.
Content is shared under a Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0), unless otherwise noted.

Developed by [Ilya Ilyankou](https://github.com/ilyankou) and [Jack Dougherty](https://github.com/jackdougherty) with support from Connecticut Humanities and Trinity College, CT. Inspired by Code for Atlanta mapsfor.us (2016) https://github.com/codeforatlanta/mapsforus (BSD-3-Clause). Adapted from MUX Lab, Map Effects 100: https://github.com/muxlab/map-effects-100, see http://muxlab.github.io/map-effects-100/Leaflet/11_scroll-driven-map-navigation.html.

We use [Google Sheets API version 4](https://developers.google.com/sheets/api), with these open-source components:

- Leaflet v1.7.1 https://leafletjs.com (BSD-2-Clause)
- jQuery v3.5.1 https://code.jquery.com (MIT)
- PapaParse v5.3.0 to parse CSV with JavaScript (MIT)
- Font Awesome v5.8.1 https://cdn.fontawesome.com (MIT, SIL OFL 1.1)
- leaflet-providers (v1.10.2) https://github.com/leaflet-extras/leaflet-providers (BSD-2-Clause)
- Leaflet.awesome-markers (v2.0.4), manually updated to svg to allow hex and material icons https://github.com/sigma-geosistemas/Leaflet.awesome-markers (MIT)
- Leaflet.ExtraMarkers (v1.0.5) https://github.com/coryasilva/Leaflet.ExtraMarkers (MIT)
- jQuery-CSV (v1.0.11) https://github.com/evanplaice/jquery-csv (MIT)
- Single Element CSS Spinner (31 May 2016) https://github.com/lukehaas/css-loaders (MIT)
- Lightbox by Lokesh Dhakar (v.2.11.3) https://github.com/lokesh/lightbox2 (MIT)
