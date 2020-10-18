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

<div class="container-fluid" id="newsCollapsible">

  <div class="row align-items-center justify-content-around">
    <div class="col-xs-3 col-sm-3 col-md-3 col-lg-3 col-xl-3 mb-4">
      <button class="btn" type="button" data-toggle="collapse" data-parent="#newsCollapsible" data-target="#science" role="button" aria-expanded="false" aria-controls="science">
        <img class="img-fluid" src="https://github.com/dickansj/MasterYourPPE/blob/master/assets/images/news/covid-science512.png?raw=true" alt="Coronavirus Science">
      </button>
    </div>
    <div class="col-xs-3 col-sm-3 col-md-3 col-lg-3 col-xl-3 mb-4">
      <button class="btn" type="button" data-toggle="collapse" data-parent="#newsCollapsible" data-target="#healthcare" role="button" aria-expanded="false" aria-controls="healthcare">
        <img class="img-fluid" src="https://github.com/dickansj/MasterYourPPE/blob/master/assets/images/news/covid-healthcare512.png?raw=true" alt="Healthcare and Treatment">
      </button>
    </div>
    <div class="col-xs-3 col-sm-3 col-md-3 col-lg-3 col-xl-3 mb-4">
      <a href="https://covid19.who.int/" target="_blank" alt="WHO Coronavirus Dashboard"><img class="img-fluid" src="https://github.com/dickansj/MasterYourPPE/blob/master/assets/images/news/who-dashboard512.png?raw=true"></a>
    </div>
  </div>

  <div class="accordion-group">
    <div class="collapse" id="science">
      <div class="row align-items-center justify-content-around">
        <div class="col-xs-12 col-sm-12 col-md-9 col-lg-9 col-xl-8 my-4">
          <div class="card">
            <a href="https://elemental.medium.com/a-supercomputer-analyzed-covid-19-and-an-interesting-new-theory-has-emerged-31cb8eba9d63" target="_blank">
              <img class="card-img-top" src="https://miro.medium.com/max/2190/1*2J1YRGI9VhWVcUlAVXLImA.jpeg">
            </a>
            <div class="card-body">
              <a href="https://elemental.medium.com/a-supercomputer-analyzed-covid-19-and-an-interesting-new-theory-has-emerged-31cb8eba9d63" target="_blank">
                <h5 class="card-title">A Supercomputer Analyzed Covid-19 — and an Interesting New Theory Has Emerged</h5>
              </a>
              <p class="card-text text-left" style="font-style: italic">A closer look at the Bradykinin hypothesis.</p>
            </div>
            <div class="card-footer">
              <small class="text-muted">Medium - Thomas Smith</small>
            </div>
          </div>
        </div>
      </div>
      <div class="row align-items-center justify-content-around">
        <div class="col-xs-12 col-sm-12 col-md-9 col-lg-9 col-xl-8">
          <div class="card">
            <div class="card-header">More on the Science of COVID-19</div>
            <div class="card-body">
              <ul><a href="https://depts.washington.edu/pandemicalliance/covid-19-literature-report/latest-reports/" target="_blank">COVID-19 Literature Report (Pre-Prints)</a><small class="text-muted"> | Univ. Washington</small></ul>
              <ul><a href="https://www.nature.com/articles/d41586-020-00502-w" target="_blank">Ongoing Summary of Key COVID-19 Papers</a><small class="text-muted"> | Nature</small></ul>
              <ul><a href="https://www.sciencemag.org/news/2020/09/hidden-immune-weakness-found-14-gravely-ill-covid-19-patients" target="_blank">Hidden Immune Weakness Found in 14% of Gravely Ill COVID-19 Patients</a><small class="text-muted"> | Science</small></ul>
            </div>
          </div>
        </div>     
      </div>
    </div>
  </div>

  <div class="collapse" id="healthcare">
    <div class="row align-items-center justify-content-around">
      <div class="col-xs-12 col-sm-12 col-md-9 col-lg-9 col-xl-8 my-4">
        <div class="card">
          <a href="https://www.sciencemag.org/news/2020/09/provocative-results-boost-hopes-antibody-treatment-covid-19" target="_blank">
            <img class="card-img-top" src="https://www.sciencemag.org/sites/default/files/styles/inline__450w__no_aspect/public/antibody_1280p.jpg?itok=dKd3wFrd">
          </a>
          <div class="card-body">
            <a href="https://elemental.medium.com/a-supercomputer-analyzed-covid-19-and-an-interesting-new-theory-has-emerged-31cb8eba9d63" target="_blank">
              <h5 class="card-title">‘Provocative Results’ Boost Hopes of Antibody Treatment for COVID-19</h5>
            </a>
            <p class="card-text text-left" style="font-style: italic">Regeneron’s monoclonal antibody cocktail reduces viral load in people infected with SARS-CoV-2</p>
          </div>
          <div class="card-footer">
            <small class="text-muted">Science | Jon Cohen</small>
          </div>
        </div>
      </div>
    </div>
    <div class="row align-items-center justify-content-around">
      <div class="col-xs-12 col-sm-12 col-md-9 col-lg-9 col-xl-8">
        <div class="card">
          <div class="card-header">More on Healthcare & Treatment</div>
          <div class="card-body">
            <ul><a href="https://coronavirus.jhu.edu/covid-19-basics/understanding-covid-19" target="_blank">Understanding the COVID-19 Pandemic (Public Online Course)</a><small class="text-muted"> | Johns Hopkins University</small></ul>
            <ul><a href="https://coronavirus.jhu.edu/news" target="_blank">Curated Updates From the Coronavirus Resource Center</a><small class="text-muted"> | Johns Hopkins University</small></ul>
          </div>
        </div>
      </div>     
    </div>
  </div>
  
</div>
