+++

## This is a template for a blank page section.
## Copy into a new md file. Remember to change active to "true" and use weight to set order on page.
## You can use the other options below, just uncomment as needed.
## Place any html after the bottom 3 plus signs. You can use the div container with Bootstrap classes.
## See https://getbootstrap.com/docs/4.5/layout/grid/ and the docs there (or other content/home md files on this site) for examples.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 20  # Order that this section will appear.

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
  <div class="row align-items-center justify-content-between my-4">
    <div class="col-xs-12 col-sm-12 col-md-6 col-lg-4 col-xl-4">
      <h3>What about "double-masking"?</h3>
      <p class="text-left">CDC recently recommended several <b><a href="https://www.cdc.gov/mmwr/volumes/70/wr/mm7007e1.htm?s_cid=mm7007e1_w" target="_blank">mask modifications</a></b> to increase fit, including the use of a mask fitter (frame) or wearing a second mask over a procedure mask.</p>
    </div>
    <div class="col-xs-12 col-sm-12 col-md-6 col-lg-6 col-xl-6">
    	<img class="img-fluid" src="https://github.com/dickansj/MasterYourPPE/blob/master/assets/images/home/cdcmaskguide-crunch.png?raw=true" alt="CDC mask fit techniques">
    </div>
  </div>
  <div class="row align-items-center justify-content-between my-4">
    <div class="col-xs-12 col-sm-12 col-md-6 col-lg-4 col-xl-4">
      <p class="text-left">Watch how we tested our simple mask frame against double-masking to see which approach better prevents unfiltered air leaks. Our results suggest the frame more effectively filters air--all without making it tough to breathe.</p>
    </div>
    <div class="col-xs-12 col-sm-12 col-md-6 col-lg-6 col-xl-6 video-container">
    	<iframe src="https://www.youtube.com/embed/lS0DN3vC22w" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
  </div> 

</div>
