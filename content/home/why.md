+++

## This is a template for a blank page section.
## Copy into a new md file. Remember to change active to "true" and use weight to set order on page.
## You can use the other options below, just uncomment as needed.
## Place any html after the bottom 3 plus signs. You can use the div container with Bootstrap classes.
## See https://getbootstrap.com/docs/4.5/layout/grid/ and the docs there (or other content/home md files on this site) for examples.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 10  # Order that this section will appear.

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
  <div class="row featurette">
    <div class="col-xs-12 col-sm-12 col-md-12 col-lg-12 col-xl-12 section-heading">
      <h1><b>Hey, wear your PPE!</b></h1>
    </div>
  </div> 
  <div class="row align-items-center my-4">
    <div class="col-xs-12 col-sm-12 col-md-4 col-lg-4 col-xl-4">
      <h3>Why?</h3>
      <p class="text-left">Because we all have to do our part to protect each other. <b><a href="https://www.cdc.gov/coronavirus/2019-ncov/index.html" target="_blank">Covid-19</a></b> is still here and it’s still dangerous to you and to those you care about. And because we all want Covid-19 to go away so we can get back to everything we love to do.</p>
    </div>
    <div class="col-xs-12 col-sm-12 col-md-3 col-lg-3 col-xl-3">
      <img class="img-fluid" src="https://github.com/dickansj/MasterYourPPE/blob/master/assets/images/home/MaskFrameStef24.png?raw=true" alt="A face mask and mask frame are simple, effective PPE">
      <p class="small text-center">Want to make your own mask frame? <b><a href="https://www.youtube.com/watch?v=kpPfyq7r8vA" target="_blank">It's easy, and here's how.</a></b></p>
    </div>
    <div class="col-xs-12 col-sm-12 col-md-5 col-lg-5 col-xl-5">
      <h3>Wait, how serious is this?</h3>
      <p class="text-left">Going by <b><a href="https://www.businessinsider.com/coronavirus-contagious-r-naught-average-patient-spread-2020-3" target="_blank">the numbers</a></b>, Covid-19 is roughly two times more contagious than the flu but with a mortality rate that is 10 times higher. It is very real and it poses a serious risk for those with a weakened immune or respiratory system or with other preexisting conditions--and this could be anyone!</p>
    </div>
  </div> 

</div>
