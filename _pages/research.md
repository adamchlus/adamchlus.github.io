---
permalink: /research/
title: ""
header:
  image: /assets/images/rs_header.jpg

gallery1:
  - url: /assets/images/research/leaf_figure.jpg
    image_path: /assets/images/research/leaf_figure.jpg
    title: "Leaf-level chemometric spectroscopy workflow"

gallery2:
  - url: /assets/images/research/image_spectroscopy.jpg
    image_path: /assets/images/research/image_spectroscopy.jpg
    title: "Vicarious calibration of HySpex with tarps. Left: Me measuring tarps. Center: Image of tarp from HySpex. Right: Ground vs. airborne measured radiance"

gallery3:
  - url: /assets/images/research/3d_trait.jpg
    image_path: /assets/images/research/3d_trait.jpg
    title: "2D representation of the 3D patterns in canopy biochemistry"

gallery4:
  - url: /assets/images/research/con_cup.jpg
    image_path: /assets/images/research/con_cup.jpg
    title: "Conifer needle spectral sampling device (Photo by Z. Wang)"
  - url: /assets/images/research/toc_figure.jpg
    image_path: /assets/images/research/toc_figure.jpg
    title: "Top of canopy sampling tool"
---

# Leaf level spectroscopy  
Leaf-level chemometric spectroscopy is a non-destuctive method for rapidly characterizing the
chemical content of leaves (ex: nitrogen, phosphorus, calcium, sugars....). **I'm investigating
how the relationships between spectra and chemistry change through time and across plant types
to develop more robust predictive models.**  

{% include gallery id="gallery1" layout = '' %}


# Imaging spectroscopy
In the same way that leaf-level spectroscopy can be used to estimate a number of biochemical
properties of individual leaves, imaging spectroscopy can be used to estimate foliar biochemistry across
landscapes. **I'm using a combination of airborne and spaceborne imaging spectroscopy data
to research the inter- and intra-annual drivers of canopy biochemistry.** This work has involved combining
over 27 years of imagery from multiple instruments and required the development of custom radiometric, geometric
and atmospheric correction routines.

{% include gallery id="gallery2" layout = '' %}


# LiDAR
Imagers are mostly limited to seeing the top of the canopy but foliar biochemistry also varies
through the vertical profile of the canopy, driven largely by within-canopy environmental
gradients. **Using imaging spectroscopy to map top-of-canopy biochemistry and LiDAR to model the
within-canopy light enviroment I'm developing methods to map canopy biomchemistry in 3-dimensions.**   

<link rel="stylesheet" href="/assets/css/BeerSlider.css">
  <script src="/assets/js/BeerSlider.js" type="text/javascript" ></script>

<div id="slider" class="beer-slider" data-beer-label="">
  <img src="/assets/images/research/3d_rgb.jpg" alt="">
  <div class="beer-reveal" data-beer-label="">
    <img src="/assets/images/research/rgb_rgb.jpg" alt="">
  </div>
</div>
 
<script type="text/javascript">
new BeerSlider(document.getElementById('slider'));  
    </script>

Move the slider to compare natural color RGB and 3D RGB map of leaf mass per area.  


# Software
Whenever I can I use open-source software in my reseach and rely heavily on Python for most data analyses. In cases
where open-source software isn't available I develop my own, here are a few examples: 

- [HyTools](https://github.com/EnSpec/HyTools-sandbox) : Collaborative effort with other members of the ENSPEC lab to
  develop tools for processing imaging spectoscopy data  
- [pypwaves](https://github.com/adamchlus/pypwaves) : Full waveform LiDAR reading and processing library  
- [specIO](https://github.com/adamchlus/specIO) : Field spectrometer data reader (ASD, OO, SE and SVC)  
- [specGUI](https://github.com/adamchlus/specGUI) : A browser based GUI for viewing spectra in real time  


# Tools

{% include gallery id="gallery4" layout = '' %}

	
