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

<script src="https://raw.githubusercontent.com/dickansj/MasterYourPPE/master/assets/js/newsCollapse.js"></script>

<div class="container" style="min-width: 0; min-height: 0">

  <div class="row justify-content-center">
    <div class="col-xs-12 col-sm-12 col-md-6 col-lg-6 col-xl-6 mb-4 text-center">
      <button class="btn btn-primary" type="button" style="min-width: 0" data-toggle="collapse" data-target="#moisture" role="button" aria-expanded="false" aria-controls="moisture" onclick="location.href = '#moisture';">
        <i class="fas fa-tint"></i>&nbsp;&nbsp;<b>Moisture Penetration</b>
      </button>
    </div>
    <div class="col-xs-12 col-sm-12 col-md-6 col-lg-6 col-xl-6 mb-4 text-center">
      <button class="btn btn-primary" type="button" style="min-width: 0" data-toggle="collapse" data-target="#particle" role="button" aria-expanded="false" aria-controls="particle" onclick="location.href = '#moisture';">
        <i class="fas fa-shield-alt"></i>&nbsp;&nbsp;<b>Particle Filtration</b>
      </button>
    </div>
  </div>
   
  <p><a id="moisture"></a></p>
  <div class="collapse show" id="moisture">
    <div class="row my-4">
      <div class="col-xs-12 col-sm-12 col-md-12 col-lg-12 col-xl-12">
        <h3>How well do different masks block water droplets?</h3>
        <p class="text-left">Since exposure to contaminated respiratory droplets is a common means of viral infection (and the <b><a href="https://www.cdc.gov/coronavirus/2019-ncov/science/science-briefs/scientific-brief-sars-cov-2.html?CDC_AA_refVal=https%3A%2F%2Fwww.cdc.gov%2Fcoronavirus%2F2019-ncov%2Fmore%2Fscientific-brief-sars-cov-2.html" target="_blank">primary mode of SARS-CoV-2 infection</a></b>), we tested how different masks block water droplets, simulating droplets from a cough or sneeze. When water droplets land on a solid surface, they can either ball up without penetrating the material (which is <em>hydrophobic</em>, or "water-hating"), or they can wet the surface and soak through the <em>hydrophilic</em> ("water-loving") material. So we wanted to find out what kind of mask would best resist moisture penetration.</p>
      </div>
    </div>
    <div class="row align-items-center mb-4">
      <div class="col-xs-12 col-sm-12 col-md-12 col-lg-11 col-xl-11">
        <h5>Results</h5>
        <p class="text-left"><i class="fas fa-times" style="color: #ff7600"></i>&nbsp;&nbsp;<em>Single-ply materials</em>, such as poly blends and cotton, showed immediate penetration to the inside when the top surface was sprayed with water.</p>
        <p class="text-left"><i class="fas fa-times" style="color: #ff7600"></i>&nbsp;&nbsp;Cotton gave moisture readings even before spraying, due to its hydrophilic nature.</p>
        <p class="text-left"><i class="fas fa-times" style="color: #ff7600"></i>&nbsp;&nbsp;Masks made from 100% polyester were dry at first but did allow water penetration.</p>
        <p class="text-left"><i class="fas fa-check" style="color: #68cd00"></i></i>&nbsp;&nbsp;Various <em>3-ply masks</em> that performed well in our particle filtration tests also resisted water significantly better than single-ply masks. See our data below for detail.</p>
      </div>
    </div>
    <div class="row align-items-center mx-4 mb-4">
      <div class="col-xs-12 col-sm-12 col-md-12 col-lg-12 col-xl-12 mx-auto d-block float-xs-none">
         <img class="img-responsive" src="https://github.com/dickansj/MasterYourPPE/blob/master/assets/images/testing/moisture-spray-crunch.png?raw=true" alt="Comparison of Moisture Penetration in Masks: With Water Spray">
      </div>
      <div class="col-xs-12 col-sm-12 col-md-12 col-lg-12 col-xl-12 mx-auto d-block float-xs-none">
         <img class="img-responsive" src="https://github.com/dickansj/MasterYourPPE/blob/master/assets/images/testing/moisture-nospray-crunch.png?raw=true" alt="Comparison of Moisture Penetration in Masks: Without Water Spray">
      </div>
    </div>
    <div class="row align-items-center mb-4 justify-content-between">
      <div class="col-xs-12 col-sm-12 col-md-12 col-lg-8 col-xl-6">      
        <h5>Setup</h5>
        <p class="text-left">We measured the water penetration of various mask materials with a moisture meter typically used to measure water content in wood or plaster board. When the meter's two probes are inserted into a material, any water present will conduct electricity between the probes, and the meter measures this conductivity.</p>
      </div>
      <div class="col-xs-12 col-sm-12 col-md-12 col-lg-4 col-xl-6 flex-grow-1">
        <img class="img-responsive" src="https://github.com/dickansj/MasterYourPPE/blob/master/assets/images/testing/moisture-meter-crunch.png?raw=true" alt="moisture meter">
      </div>
    </div>
    <div class="row align-items-center mb-4 justify-content-between">
      <div class="col-xs-12 col-sm-12 col-md-12 col-lg-12 col-xl-4">
        <p class="text-left">We modified the probes into large copper pads that would sit behind the face mask, detecting if water had penetrated through the material to the copper pad test side.</p>
      </div>
      <div class="col-xs-12 col-sm-12 col-md-6 col-lg-6 col-xl-5 my-4 flex-xs-grow-1 flex-sm-grow-1">
        <img class="img-responsive" src="https://github.com/dickansj/MasterYourPPE/blob/master/assets/images/testing/meter-pads-crunch.png?raw=true" alt="moisture meter pads">
      </div>
      <div class="col-xs-12 col-sm-12 col-md-4 col-lg-4 col-xl-3 my-4 flex-xs-grow-1 flex-sm-grow-1">
        <img class="img-responsive" src="https://github.com/dickansj/MasterYourPPE/blob/master/assets/images/testing/moisture-setup-crunch.png?raw=true" alt="moisture meter setup">
      </div>
    </div>
    <div class="row mb-4">
      <div class="col-xs-12 col-sm-12 col-md-12 col-lg-12 col-xl-12">
        <p class="text-left">The copper pads were mounted on a PVC surface with holes drilled along the gap. These holes connected to a flexible plenum, provided by a rubber diaphragm. This setup simulated human breath and provided a slow flow of air through the mask during tests.</p>
        <p class="text-left">Moisture readings were taken under variable conditions, including with and without the application of skin contact and water spray.</p>
      </div>
    </div>
    <div class="row align-items-center">
      <div class="col-xs-12 col-sm-12 col-md-11 col-lg-4 col-xl-4 mx-auto d-block mb-4">
        <img class="img-responsive" src="https://github.com/dickansj/MasterYourPPE/blob/master/assets/images/testing/masknospray.jpg?raw=true" alt="Mask setup no spray">        
      </div>
      <div class="col-xs-12 col-sm-12 col-md-11 col-lg-4 col-xl-4 mx-auto d-block mb-4">
        <img class="img-responsive" src="https://github.com/dickansj/MasterYourPPE/blob/master/assets/images/testing/maskspray0.jpg?raw=true" alt="Mask setup spray 0 min">
      </div>
      <div class="col-xs-12 col-sm-12 col-md-11 col-lg-4 col-xl-4 mx-auto d-block mb-4">
        <img class="img-responsive" src="https://github.com/dickansj/MasterYourPPE/blob/master/assets/images/testing/maskspray1.jpg?raw=true" alt="Mask setup spray 1 min">
      </div>
    </div>
  </div>
  
  <div class="collapse" id="particle">
    <div class="row">
      <div class="col-xs-12 col-sm-12 col-md-12 col-lg-12 col-xl-12">
        <h3>How well do common masks filter particles?</h3>
        <p class="text-left">In addition to moisture penetration, we measured in our sample masks a second indicator of their efficacy: the percentage of small particles blocked by each mask material. So which mask types best filter particles in the size range of airborne droplets?</p>
        <br>
        <h5>Results</h5>
        <p class="text-left"><i class="fas fa-times" style="color: #ff7600"></i>&nbsp;&nbsp;<em>Household fabrics</em> and masks made from <em>polyester or cotton</em> offered relatively weak filtration, though they likely still provide some benefit.</p>
        <p class="text-left"><i class="fas fa-check" style="color: #68cd00"></i></i>&nbsp;&nbsp;Masks with <em>3 layers</em> (including common surgical masks) showed filtration nearly identical to that of medical-grade N95 masks, blocking more than 95% of particles in many cases.</p>
        <br>
        <p> This plot compares the actual filtering efficiency of masks and materials for particle sizes of 1um and 0.3um.  Note that 0.3um is the size used in industry for particle filtering efficiency rating. </p>
      </div>
    </div>
    <div class="row align-items-center mt-4">
      <div class="col-xs-12 col-sm-12 col-md-12 col-lg-10 col-xl-9 mx-auto d-block float-xs-none">
         <img class="img-responsive" src="https://github.com/dickansj/MasterYourPPE/blob/master/assets/images/testing/Chart%20of%20filter%20efficiency%20%2005.JPG?raw=true" alt="Comparison of Filtration Efficiencies">
      </div>
    </div>
    <div class="row justify-content-center">
      <div class="col-xs-12 col-sm-12 col-md-12 col-lg-10 col-xl-9 mb-4>
        <p class="text-justify"><em>The 0.3- and 1.00-micron filtration efficiencies of different filter materials, masks, and respirators.</em></p>
      </div>
    </div>
    <div class="row align-items-left">
      <div class="col-xs-12 col-sm-12 col-md-12 col-lg-12 col-xl-12">
        <h5>Setup</h5>
      </div>
    </div>
    <div class="row align-items-center justify-content-around">
      <div class="col-xs-12 col-sm-12 col-md-8 col-lg-8 col-xl-8">
        <p class="text-left">We used a Fluke 985 Particle Counter to measure the filtration efficiency of commercially available masks and respirators and that of other commonly available materials (more than 70 samples in total).  The testing apparatus consisted of a 4-inch PVC pipe cap with a 1/2-inch access hole drilled on the side where the particle counter's conical test port was inserted.  Above the access hole, we mounted an adjustable hose clamp to provide a tight seal between the cap and the filter material being tested.  Each material was tested for two minutes and the data was normalized against unfiltered measurements of the room air.  Subsequent testing of the same filter material yielded slightly different counts; however the variation was usually below 0.5% of the initial values.</p>
      </div>
      <div class="col-xs-12 col-sm-12 col-md-4 col-lg-4 col-xl-4 order-xs-last order-sm-last order-md-first order-lg-first order-xl-first my-4" style="max-width:288px;">
        <img class="img-fluid" src="https://i.imgur.com/zRnrI99.png" alt="testing1">
      </div>
    </div>
    <div class="row align-items-center justify-content-around">
      <div class="col-xs-12 col-sm-12 col-md-4 col-lg-4 col-xl-4 my-4" style="max-width:288px;">
        <img class="img-fluid" src="https://i.imgur.com/wGjUPlB.png" alt="testing2">
      </div>
      <div class="col-xs-12 col-sm-12 col-md-8 col-lg-8 col-xl-8">
        <p class="text-left">The reader should note that these test results are <b>not</b> scientifically valid.  The results may provide a fair indication of filter efficiency and could be used to compare the performance of filter material types. However, the results do not imply that the data should be relied upon to make actionable decisions on filter, mask, or respirator selection.</p>    
      </div>
    </div>
  </div>
    
</div>
