+++

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

  <div class="row align-items-center justify-content-around">
    <div class="col-xs-12 col-sm-12 col-md-3 col-lg-3 col-xl-3 mb-4">
      <a data-toggle="collapse" href="#science" role="button" aria-expanded="false" aria-controls="science">
        <img class="img-fluid" src="https://github.com/dickansj/MasterYourPPE/blob/master/assets/images/news/covid-science.png?raw=true" alt="Coronavirus Science">
      </a>
    </div>
    <div class="col-xs-12 col-sm-12 col-md-3 col-lg-3 col-xl-3 mb-4">
      <a data-toggle="collapse" href="#healthcare" role="button" aria-expanded="false" aria-controls="healthcare">
        <img class="img-fluid" src="https://github.com/dickansj/MasterYourPPE/blob/master/assets/images/news/covid-healthcare.png?raw=true" alt="Healthcare and Treatment">
      </a>
    </div>
    <div class="col-xs-12 col-sm-12 col-md-3 col-lg-3 col-xl-3 mb-4">
      <a href="https://covid19.who.int/" target="_blank" alt="WHO Coronavirus Dashboard"><img class="img-fluid" src="https://github.com/dickansj/MasterYourPPE/blob/master/assets/images/news/who-dashboard.png?raw=true"></a>
    </div>
  </div>

  <div class="collapse" id="science">
    <div class="row align-items-center justify-content-around">
      <div class="card">
        <img class="card-img-top" src="https://miro.medium.com/max/2190/1*2J1YRGI9VhWVcUlAVXLImA.jpeg">
        <div class="card-body">
          <h5 class="card-title">A Supercomputer Analyzed Covid-19 — and an Interesting New Theory Has Emerged</h5>
          <p class="card-text">A closer look at the Bradykinin hypothesis</p>
        </div>
        <div class="card-footer">
          <small class="text-muted">Medium - Thomas Smith</small>
        </div>
      </div>
    </div>
  </div>
  
  <div class="collapse" id="healthcare">
    <div class="row align-items-center justify-content-around">
      <div class="card card-body">
        Under Construction
      </div>
    </div>
  </div>

  
</div>
