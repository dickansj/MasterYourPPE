+++

## This is a template for a blank page section.
## Copy into a new md file. Remember to change active to "true" and use weight to set order on page.
## You can use the other options below, just uncomment as needed.
## Place any html after the bottom 3 plus signs. You can use the div container with Bootstrap classes.
## See https://getbootstrap.com/docs/4.5/layout/grid/ and the docs there (or other content/home md files on this site) for examples.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 40  # Order that this section will appear.

title = ""
subtitle = ""

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "navy"
  
  # Background gradient.
  #gradient_start = "#80CED7"
  #gradient_end = "#007EA7"
  
  # Background image.
  # image = "image.jpg"  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  # image_size = "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
  # image_position = "center"  # Options include `left`, `center` (default), or `right`.
  # image_parallax = true  # Use a fun parallax-like fixed background effect? true/false
  
  # Text color (true=light or false=dark).
  text_color_light = false

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["20px", "0", "20px", "0"]

[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++

<div class="container-fluid">
  <div class="row my-4">
    <div class="col-xs-12 col-sm-12 col-md-12 col-lg-12 col-xl-12">
      <h3>How well do different masks block water droplets?</h3>
      <p class="text-left">Since exposure to contaminated respiratory droplets is a common means of viral infection (and the <b><a href="https://www.cdc.gov/coronavirus/2019-ncov/science/science-briefs/scientific-brief-sars-cov-2.html?CDC_AA_refVal=https%3A%2F%2Fwww.cdc.gov%2Fcoronavirus%2F2019-ncov%2Fmore%2Fscientific-brief-sars-cov-2.html" target="_blank">primary mode of SARS-CoV-2 infection</a></b>), we tested how different masks block water droplets, simulating droplets from a cough or sneeze. When water droplets land on a solid surface, they can either ball up without penetrating the material (which is <em>hydrophobic</em>, or "water-hating"), or they can wet the surface and soak through the <em>hydrophilic</em> ("water-loving") material. So we wanted to find out what kind of mask would best resist moisture penetration.</p>
    </div>
  </div>
  <div class="row align-items-center mb-4">
    <div class="col-xs-12 col-sm-12 col-md-12 col-lg-8 col-xl-6">      
      <h5>Setup</h5>
      <p class="text-left">We measured the water penetration of 71 mask materials with a moisture meter typically used to measure water content in wood or plaster board. When the meter's two probes are inserted into a material, any water present will conduct electricity between the probes, and the meter measures this conductivity.</p>
    </div>
    <div class="col-xs-12 col-sm-12 col-md-12 col-lg-4 col-xl-6">
      <img class="img-fluid" src="https://github.com/dickansj/MasterYourPPE/blob/master/assets/images/testing/moisture-meter-crunch.png?raw=true" alt="moisture meter">
    </div>
  </div>
  <div class="row align-items-center mb-4">
    <div class="col-xs-12 col-sm-12 col-md-12 col-lg-12 col-xl-6">
      <p class="text-left">We modified the probes into large copper pads that would sit behind the face mask, detecting if water had penetrated through the material to the copper pad test side.</p>
    </div>
    <div class="col-xs-12 col-sm-12 col-md-8 col-lg-8 col-xl-4">
      <img class="img-fluid" src="https://github.com/dickansj/MasterYourPPE/blob/master/assets/images/testing/meter-pads-crunch.png?raw=true" alt="moisture meter pads">
    </div>
    <div class="col-xs-12 col-sm-12 col-md-4 col-lg-4 col-xl-2">
      <img class="img-fluid" src="https://github.com/dickansj/MasterYourPPE/blob/master/assets/images/testing/moisture-setup-crunch.png?raw=true" alt="moisture meter setup">
    </div>
  </div>
  <div class="row mb-4">
    <div class="col-xs-12 col-sm-12 col-md-12 col-lg-12 col-xl-12">
      <p class="text-left">The copper pads were mounted on a PVC surface with holes drilled along the gap. These holes connected to a flexible plenum, provided by a rubber diaphragm. This setup simulated human breath and provided a slow flow of air through the mask during tests.</p>
    </div>
  </div>
  <div class="row align-items-center mb-4">
    <div class="col-xs-12 col-sm-12 col-md-12 col-lg-12 col-xl-12">
      <h5>Results</h5>
      <p class="text-left"><i class="fas fa-times" style="color: #ff7600"></i>&nbsp;&nbsp;<em>Single-ply materials</em>, such as poly blends and cotton, showed immediate penetration to the inside when the top surface was sprayed with water.</p>
      <p class="text-left"><i class="fas fa-times" style="color: #ff7600"></i>&nbsp;&nbsp;Cotton gave moisture readings even before spraying, due to its hydrophilic nature.</p>
      <p class="text-left"><i class="fas fa-times" style="color: #ff7600"></i>&nbsp;&nbsp;Masks made from 100% polyester were dry at first but did allow water penetration.</p>
      <p class="text-left"><i class="fas fa-check" style="color: #68cd00"></i></i>&nbsp;&nbsp;Various <em>3-ply masks</em> that performed well in our particle filtration tests also resisted water significantly better than single-ply masks. See our data below for detail.</p>
    </div>
  </div>
</div>
