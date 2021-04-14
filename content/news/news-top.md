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

<script src="https://raw.githubusercontent.com/dickansj/MasterYourPPE/master/assets/js/newsCollapse.js"></script>

<div class="container" style="min-width: 0; min-height: 0">

  <div class="row align-items-center px-0" style="justify-content: space-evenly; min-width: 0; min-height: 0; overflow:hidden; flex-wrap:nowrap">
    <div class="col-xs-3 col-sm-3 col-md-3 col-lg-3 col-xl-3 mb-4 px-0" style="min-width: 0; min-height: 0">
      <button class="btn" type="button" style="min-width: 0" data-toggle="collapse" data-target="#science" role="button" aria-expanded="false" aria-controls="science" onclick="location.href = '#articles';">
        <img class="img-fluid" style="box-shadow: 0.4em 0.5em 0.75em -0.3em; border-radius: 1.7em" src="https://github.com/dickansj/MasterYourPPE/blob/master/assets/images/news/covid-science512-crunch.png?raw=true" alt="Coronavirus Science">
      </button>
    </div>
    <div class="col-xs-3 col-sm-3 col-md-3 col-lg-3 col-xl-3 mb-4 px-0" style="min-width: 0; min-height: 0">
      <button class="btn" type="button" style="min-width: 0" data-toggle="collapse" data-target="#healthcare" role="button" aria-expanded="false" aria-controls="healthcare" onclick="location.href = '#articles';">
        <img class="img-fluid" style="box-shadow: 0.4em 0.5em 0.75em -0.3em; border-radius: 1.7em" src="https://github.com/dickansj/MasterYourPPE/blob/master/assets/images/news/covid-healthcare512-crunch.png?raw=true" alt="Healthcare and Treatment">
      </button>
    </div>
    <div class="col-xs-3 col-sm-3 col-md-3 col-lg-3 col-xl-3 mb-4 px-0" style="min-width: 0; min-height: 0">
      <button class="btn" type="button" style="min-width: 0" onclick="window.open('https://covid19.who.int/','_blank');">
        <img class="img-fluid" style="box-shadow: 0.4em 0.5em 0.75em -0.3em; border-radius: 1.7em" src="https://github.com/dickansj/MasterYourPPE/blob/master/assets/images/news/who-dashboard512-crunch.png?raw=true alt="WHO Coronavirus Dashboard">
      </button>
    </div>
  </div>

  <p><a id="articles"></a></p>

  <div class="collapse show" id="science">
    <div class="row align-items-center justify-content-around">
      <div class="col-xs-12 col-sm-12 col-md-9 col-lg-9 col-xl-8 my-4">
        <div class="card">
          <div class="card-header lead" style="font-weight: bold; text-align: center">Science of COVID-19</div>
          <a href="https://www.bmj.com/content/372/bmj.n579" target="_blank">
            <img class="card-img-top" src="https://www.bmj.com/content/bmj/372/bmj.n579/F2.large.jpg">
          </a>
          <div class="card-body">
            <a href="https://www.bmj.com/content/372/bmj.n579" target="_blank">
              <h5 class="card-title">Risk of Mortality in Patients Infected With SARS-CoV-2 Variant of Concern 202012/1: Matched Cohort Study</h5>
            </a>
            <p class="card-text text-left" style="font-style: italic">A matched cohort study of patients infected with SARS-CoV-2 found a significantly increased mortality risk associated with the viral variant VOC-202012/01.</p>
          </div>
          <div class="card-footer">
            <small class="text-muted">BMJ | Robert Challen, Ellen Brooks-Pollock, Jonathan M. Read, et al.</small>
          </div>
        </div>
      </div>
    </div>
    <div class="row align-items-center justify-content-around">
      <div class="col-xs-12 col-sm-12 col-md-9 col-lg-9 col-xl-8">
        <div class="card">
          <div class="card-header" style="font-weight: bold; text-align: center">More on the Science of COVID-19</div>
          <div class="card-body">
            <p><a href="https://www.masteryourppe.com/#contact"><img src="https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat" class="mx-auto d-block"></a></p>
            <ul><a href="https://jamanetwork.com/journals/jamainternalmedicine/fullarticle/2773576" target="_blank">Estimated SARS-CoV-2 Seroprevalence in the US as of September 2020</a><small class="text-muted"> | JAMA Intern. Med.</small></ul>
            <ul><a href="https://english.elpais.com/society/2020-10-28/a-room-a-bar-and-a-class-how-the-coronavirus-is-spread-through-the-air.html" target="_blank">A Room, a Bar and a Classroom: How the Coronavirus Is Spread Through the Air</a><small class="text-muted"> | El Pais</small></ul>
            <ul><a href="https://amp.cnn.com/cnn/2020/10/30/health/household-spread-covid-19-wellness/index.html" target="_blank">Household Spread of COVID-19 Is Common and Quick, a New CDC Study Finds</a><small class="text-muted"> | CNN</small></ul>
            <ul><a href="https://ashpublications.org/bloodadvances/article/4/20/4990/463793" target="_blank">Reduced Prevalence of SARS-CoV-2 Infection in ABO Blood Group O</a><small class="text-muted"> | Blood Advances</small></ul>
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
          <div class="card-header lead" style="font-weight: bold; text-align: center">Healthcare & Treatment</div>
          <a href="https://www.nature.com/articles/d41586-021-00722-8" target="_blank">
            <img class="card-img-top" src="https://media.nature.com/lw800/magazine-assets/d41586-021-00722-8/d41586-021-00722-8_18979356.jpg">
          </a>
          <div class="card-body">
            <a href="https://www.nature.com/articles/d41586-021-00722-8" target="_blank">
              <h5 class="card-title">Rare COVID Reactions Might Hold Key to Variant-Proof Vaccines</h5>
            </a>
            <p class="card-text text-left" style="font-style: italic">Some people mount an immune response able to fend off a menagerie of coronavirus variants.</p>
          </div>
          <div class="card-footer">
            <small class="text-muted">Nature | Ewen Callaway</small>
          </div>
        </div>
      </div>
    </div>
    <div class="row align-items-center justify-content-around">
      <div class="col-xs-12 col-sm-12 col-md-9 col-lg-9 col-xl-8">
        <div class="card">
          <div class="card-header" style="font-weight: bold; text-align: center">More on Healthcare & Treatment</div>
          <div class="card-body">
            <p><a href="https://www.masteryourppe.com/#contact"><img src="https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat" class="mx-auto d-block"></a></p>
            <ul><a href="https://www.newscientist.com/article/2261092-do-oxford-astrazeneca-covid-19-vaccine-results-stand-up-to-scrutiny/" target="_blank">Do Oxford/AstraZeneca COVID-19 Vaccine Results Stand Up to Scrutiny?</a><small class="text-muted"> | New Scientist</small></ul>
            <ul><a href="https://www.ashp.org/-/media/8CA43C674C6D4335B6A19852843C4052.ashx" target="_blank">Assessment of Evidence for COVID-19-Related Treatment: An Updated Summary of Treatments</a><small class="text-muted"> | Amer. Soc. of Health-System Pharmacists</small></ul>            
            <ul><a href="https://www.sciencemag.org/news/2020/09/provocative-results-boost-hopes-antibody-treatment-covid-19" target="_blank">Regeneron’s ‘Provocative Results’ Boost Hopes of Antibody Treatment for COVID-19</a><small class="text-muted"> | Science</small></ul>
            <ul><a href="https://coronavirus.jhu.edu/covid-19-basics/understanding-covid-19" target="_blank">Understanding the COVID-19 Pandemic (Public Online Course)</a><small class="text-muted"> | Johns Hopkins University</small></ul>
            <ul><a href="https://coronavirus.jhu.edu/news" target="_blank">Curated Updates From the Coronavirus Resource Center</a><small class="text-muted"> | Johns Hopkins University</small></ul>
          </div>
        </div>
      </div>     
    </div>
  </div>
  
</div>
