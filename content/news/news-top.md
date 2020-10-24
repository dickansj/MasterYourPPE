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
  padding = ["0px", "0", "0px", "0"]

[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++

<script src="https://raw.githubusercontent.com/dickansj/MasterYourPPE/master/assets/js/newsCollapse.js"></script>

<div class="container" style="min-width: 0; min-height: 0">

  <div class="row align-items-center px-0" style="justify-content: space-evenly; min-width: 0; min-height: 0; overflow:hidden">
    <div class="col-xs-3 col-sm-3 col-md-3 col-lg-3 col-xl-3 mb-4 px-0" style="min-width: 0; min-height: 0">
      <button class="btn" type="button" style="min-width: 0" data-toggle="collapse" data-target="#science" role="button" aria-expanded="false" aria-controls="science" onclick="location.href = '#articles';">
        <img class="img-fluid" style="box-shadow: 0.4em 0.5em 0.75em -0.3em; border-radius: 1.7em" src="https://github.com/dickansj/MasterYourPPE/blob/master/assets/images/news/covid-science.png?raw=true" alt="Coronavirus Science">
      </button>
    </div>
    <div class="col-xs-3 col-sm-3 col-md-3 col-lg-3 col-xl-3 mb-4 px-0" style="min-width: 0; min-height: 0">
      <button class="btn" type="button" style="min-width: 0" data-toggle="collapse" data-target="#healthcare" role="button" aria-expanded="false" aria-controls="healthcare" onclick="location.href = '#articles';">
        <img class="img-fluid" style="box-shadow: 0.4em 0.5em 0.75em -0.3em; border-radius: 1.7em" src="https://github.com/dickansj/MasterYourPPE/blob/master/assets/images/news/covid-healthcare.png?raw=true" alt="Healthcare and Treatment">
      </button>
    </div>
    <div class="col-xs-3 col-sm-3 col-md-3 col-lg-3 col-xl-3 mb-4 px-0" style="min-width: 0; min-height: 0">
      <button class="btn" type="button" style="min-width: 0" onclick="window.open('https://covid19.who.int/','_blank');">
        <img class="img-fluid" style="box-shadow: 0.4em 0.5em 0.75em -0.3em; border-radius: 1.7em" src="https://github.com/dickansj/MasterYourPPE/blob/master/assets/images/news/who-dashboard.png?raw=true alt="WHO Coronavirus Dashboard">
      </button>
    </div>
  </div>

  <p><a id="articles"></a></p>

  <div class="collapse" id="science">
    <div class="row align-items-center justify-content-around">
      <div class="col-xs-12 col-sm-12 col-md-9 col-lg-9 col-xl-8 my-4">
        <div class="card">
          <a href="https://ashpublications.org/bloodadvances/article/4/20/4990/463793" target="_blank">
            <img class="card-img-top" src="https://ash.silverchair-cdn.com/ash/content_public/journal/bloodadvances/4/20/10.1182_bloodadvances.2020002657/1/advancesadv2020002657absf1.png?Expires=1606477954&Signature=fe9vKEshOM6vVK8h180P5fgV38b3a4LdJ5oQ6dMUWzAMup6ZkeiEVN9i9ExIyv4EfdYW3fGZiE8J-Z7w5076yL43qjF2VrUMnFuqR5dj2sH3vFO-WkkOS3eFHMJtF2mkIkRnaOFsiPETPkjhIkIknr3BEsAFpJIpT~0nB5-eHJvzUZyHv9niGabjzrSizQGqmX9nd1UR6xF5~AL4TwPInmsBPoKRlc27HKrSd0AqgMdiod9LGqsd7vxJEfAedN-qnHQZLTp4XqCnWqUBttpjSEwmxgCzczVDQJgRxyw013NqsolMHUAZldEFxv18Kvwqe7eomCbpcB~j9Ugpk~A4BA__&Key-Pair-Id=APKAIE5G5CRDK6RD3PGA">
          </a>
          <div class="card-body">
            <a href="https://ashpublications.org/bloodadvances/article/4/20/4990/463793" target="_blank">
              <h5 class="card-title">Reduced Prevalence of SARS-CoV-2 Infection in ABO Blood Group O</h5>
            </a>
            <p class="card-text text-left" style="font-style: italic">Blood group O is associated with a decreased risk for contracting infection by the SARS-CoV-2 coronavirus.</p>
          </div>
          <div class="card-footer">
            <small class="text-muted">Blood Advances | Barnkob et al.</small>
          </div>
        </div>
      </div>
    </div>
    <div class="row align-items-center justify-content-around">
      <div class="col-xs-12 col-sm-12 col-md-9 col-lg-9 col-xl-8">
        <div class="card">
          <div class="card-header">More on the Science of COVID-19</div>
          <div class="card-body">
            <ul><a href="https://elemental.medium.com/a-supercomputer-analyzed-covid-19-and-an-interesting-new-theory-has-emerged-31cb8eba9d63" target="_blank">A Supercomputer Analyzed Covid-19 — and an Interesting New Theory Has Emerged</a><small class="text-muted"> | Medium</small></ul>
            <ul><a href="https://depts.washington.edu/pandemicalliance/covid-19-literature-report/latest-reports/" target="_blank">COVID-19 Literature Report (Pre-Prints)</a><small class="text-muted"> | Univ. Washington</small></ul>
            <ul><a href="https://www.nature.com/articles/d41586-020-00502-w" target="_blank">Ongoing Summary of Key COVID-19 Papers</a><small class="text-muted"> | Nature</small></ul>
            <ul><a href="https://www.sciencemag.org/news/2020/09/hidden-immune-weakness-found-14-gravely-ill-covid-19-patients" target="_blank">Hidden Immune Weakness Found in 14% of Gravely Ill COVID-19 Patients</a><small class="text-muted"> | Science</small></ul>
          </div>
        </div>
      </div>     
    </div>
  </div>

  <div class="collapse" id="healthcare">
    <div class="row align-items-center justify-content-around">
      <div class="col-xs-12 col-sm-12 col-md-9 col-lg-9 col-xl-8 my-4">
        <div class="card">
          <a href="https://www.ashp.org/-/media/8CA43C674C6D4335B6A19852843C4052.ashx" target="_blank">
            <img class="card-img-top" src="https://www.ashp.org/-/media/assets/pharmacy-practice/resource-centers/Coronavirus/images/microsite/hero-1-microsite-883x441.ashx?h=441&w=883&la=en&hash=2EC9850512B045FEDC7DECEF361C9195A2EF8709">
          </a>
          <div class="card-body">
            <a href="https://www.ashp.org/-/media/8CA43C674C6D4335B6A19852843C4052.ashx" target="_blank">
              <h5 class="card-title">Assessment of Evidence for COVID-19-Related Treatment</h5>
            </a>
            <p class="card-text text-left" style="font-style: italic">A continually updated summary table of COVID-19-related treatments as well as their use and efficacy.</p>
          </div>
          <div class="card-footer">
            <small class="text-muted">Amer. Soc. of Health-System Pharmacists</small>
          </div>
        </div>
      </div>
    </div>
    <div class="row align-items-center justify-content-around">
      <div class="col-xs-12 col-sm-12 col-md-9 col-lg-9 col-xl-8">
        <div class="card">
          <div class="card-header">More on Healthcare & Treatment</div>
          <div class="card-body">
            <ul><a href="https://www.sciencemag.org/news/2020/09/provocative-results-boost-hopes-antibody-treatment-covid-19" target="_blank">Regeneron’s ‘Provocative Results’ Boost Hopes of Antibody Treatment for COVID-19</a><small class="text-muted"> | Science</small></ul>
            <ul><a href="https://coronavirus.jhu.edu/covid-19-basics/understanding-covid-19" target="_blank">Understanding the COVID-19 Pandemic (Public Online Course)</a><small class="text-muted"> | Johns Hopkins University</small></ul>
            <ul><a href="https://coronavirus.jhu.edu/news" target="_blank">Curated Updates From the Coronavirus Resource Center</a><small class="text-muted"> | Johns Hopkins University</small></ul>
          </div>
        </div>
      </div>     
    </div>
  </div>
  
</div>
