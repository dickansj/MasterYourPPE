+++

## This is a template for a blank page section.
## Copy into a new md file. Remember to change active to "true" and use weight to set order on page.
## You can use the other options below, just uncomment as needed.
## Place any html after the bottom 3 plus signs. You can use the div container with Bootstrap classes.
## See https://getbootstrap.com/docs/4.5/layout/grid/ and the docs there (or other content/home md files on this site) for examples.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = false  # Activate this widget? true/false
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
  <div class="row align-items-center mt-4">
    <div class="col-xs-12 col-sm-12 col-md-4 col-lg-4 col-xl-4">
      <h3>Will a mask protect me?</h3>
      <p class="text-left">A good face covering that is worn correctly will substantially reduce the chance of breathing infected airborne droplets or of spreading infectious particles to others.</p>
    </div>
    <div class="col-xs-12 col-sm-12 col-md-8 col-lg-8 col-xl-8">
      <img class="img-fluid" src="https://github.com/dickansj/MasterYourPPE/blob/master/assets/images/home/maskhow.jpg?raw=true" alt="How to properly wear a mask">
      <p class="text-muted small">Graphic by Hollister Breslin</p>
    </div>
  </div> 
  <div class="row">
    <div class="col-xs-12 col-sm-12 col-md-12 col-lg-12 col-xl-12">
      <p class="text-left">Noting the concentration and persistence of small droplets within enclosed areas, it is very important that everyone wear a good face covering. This is to prevent droplets from accumulating in breathing spaces. And of course, it’s prudent to continue to wash hands often, and to avoid crowds.</p>
    </div>
  </div> 
  
</div>
