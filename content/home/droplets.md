+++

## This is a template for a blank page section.
## Copy into a new md file. Remember to change active to "true" and use weight to set order on page.
## You can use the other options below, just uncomment as needed.
## Place any html after the bottom 3 plus signs. You can use the div container with Bootstrap classes.
## See https://getbootstrap.com/docs/4.5/layout/grid/ and the docs there (or other content/home md files on this site) for examples.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 30  # Order that this section will appear.

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
  
  <div class="row align-items-xl-center">
    <div class="col-xs-12 col-sm-12 col-md-6 col-lg-6 col-xl-8">
      <h3>What is really going on?</h3>
      <p class="text-left">The <b><a href="https://www.nytimes.com/2020/08/11/health/coronavirus-aerosols-indoors.html" target="_blank">latest research</a></b> confirms that most people become infected with Covid-19 by inhaling contaminated droplets that are ejected when talking, singing, eating, sneezing, coughing, etc.</p>
      <p class="text-left">Infectious virus particles have been observed in both large and small droplets. Larger droplets vary in size down to 0.5mm. These fall to the ground quickly, usually within 6 feet of where they are generated.</p>
    </div>
    <div class="col-xs-12 col-sm-12 col-md-6 col-lg-6 col-xl-4 my-4 order-xs-last order-sm-last order-md-first order-lg-first order-xl-first">
      <img class="img-fluid" src="https://i.imgur.com/ZxVItVB.png" alt="The spread of droplets">
    </div>
  </div>

  <div class="row">
    <div class="col-xs-12 col-sm-12 col-md-12 col-lg-12 col-xl-12">
      <p class="text-left">Smaller droplets range in size from about 0.5mm down to 0.001mm and can <b><a href="https://economictimes.indiatimes.com/news/science/coronavirus-can-travel-up-to-8-metres-from-exhalation-linger-in-air-for-hours-mit-scientist-says/articleshow/74928356.cms?from=mdr" target="_blank">remain suspended in air for hours.</a></b> These can also travel long distances on air currents.  In enclosed environments with still air, small droplets can accumulate in the area where they are being generated until the area becomes <b><a href="https://english.elpais.com/society/2020-10-28/a-room-a-bar-and-a-class-how-the-coronavirus-is-spread-through-the-air.html" target="_blank">highly infectious</a></b>.</p>
      <p class="text-left">For these reasons, it is important to wear an <b><a href="https://www.masteryourppe.com/testing/" target="_blank">effective face covering</a></b> and avoid crowds. And, to help lower the risk of Covid-19 transmission further, see these mask-wearing <b><a href="https://www.masteryourppe.com/tips">tips and tricks</a></b>.</p>
    </div>
  </div>
  

</div>
