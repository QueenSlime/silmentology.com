+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 1000 # Order that this section will appear.

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
  # gradient_start = "DeepSkyBlue"
  # gradient_end = "SkyBlue"
  
  # Background image.
  image = ""  # Name of image in `static/media/`.
  image_darken = 0  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  image_size = "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
  image_position = "center"  # Options include `left`, `center` (default), or `right`.
  image_parallax = false  # Use a fun parallax-like fixed background effect? true/false

  # Text color (true=light or false=dark).
  text_color_light = false

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["20px", "0", "50px", "0"]

[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++

<!-- jQuery -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/2.1.1/jquery.min.js" type="text/javascript"></script>
			
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/lightgallery.js@1.2.0/dist/css/lightgallery.css" />
<script src="https://cdn.jsdelivr.net/npm/lightgallery.js@1.2.0/dist/js/lightgallery.min.js"></script>


<div class="cont">
  <div class="page-head">
  <div class="demo-gallery">
    <ul id="lightgallery">
      <li data-responsive="https://sachinchoolur.github.io/lightgallery.js/static/img/1-375.jpg 375, https://sachinchoolur.github.io/lightgallery.js/static/img/1-480.jpg 480, https://sachinchoolur.github.io/lightgallery.js/static/img/1.jpg 800" data-src="https://sachinchoolur.github.io/lightgallery.js/static/img/1-1600.jpg"
      data-sub-html="<h4>Fading Light</h4><p>Classic view from Rigwood Jetty on Coniston Water an old archive shot similar to an old post but a little later on.</p>">
        <a href="">
          <img class="img-responsive" src="https://sachinchoolur.github.io/lightgallery.js/static/img/thumb-1.jpg">
          <div class="demo-gallery-poster">
            <img src="https://sachinchoolur.github.io/lightgallery.js/static/img/zoom.png">
          </div>
        </a>
      </li>
      <li data-responsive="https://sachinchoolur.github.io/lightgallery.js/static/img/2-375.jpg 375, https://sachinchoolur.github.io/lightgallery.js/static/img/2-480.jpg 480, https://sachinchoolur.github.io/lightgallery.js/static/img/2.jpg 800" data-src="https://sachinchoolur.github.io/lightgallery.js/static/img/2-1600.jpg"
      data-sub-html="<h4>Bowness Bay</h4><p>A beautiful Sunrise this morning taken En-route to Keswick not one as planned but I'm extremely happy I was passing the right place at the right time....</p>">
        <a href="">
          <img class="img-responsive" src="https://sachinchoolur.github.io/lightgallery.js/static/img/thumb-2.jpg">
          <div class="demo-gallery-poster">
            <img src="https://sachinchoolur.github.io/lightgallery.js/static/img/zoom.png">
          </div>
        </a>
      </li>
      <li data-responsive="https://sachinchoolur.github.io/lightgallery.js/static/img/13-375.jpg 375, https://sachinchoolur.github.io/lightgallery.js/static/img/13-480.jpg 480, https://sachinchoolur.github.io/lightgallery.js/static/img/13.jpg 800" data-src="https://sachinchoolur.github.io/lightgallery.js/static/img/13-1600.jpg"
      data-sub-html="<h4>Sunset Serenity</h4><p>A gorgeous Sunset tonight captured at Coniston Water....</p>">
        <a href="">
          <img class="img-responsive" src="https://sachinchoolur.github.io/lightgallery.js/static/img/thumb-13.jpg">
          <div class="demo-gallery-poster">
            <img src="https://sachinchoolur.github.io/lightgallery.js/static/img/zoom.png">
          </div>
        </a>
      </li>
      <li data-responsive="https://sachinchoolur.github.io/lightgallery.js/static/img/4-375.jpg 375, https://sachinchoolur.github.io/lightgallery.js/static/img/4-480.jpg 480, https://sachinchoolur.github.io/lightgallery.js/static/img/4.jpg 800" data-src="https://sachinchoolur.github.io/lightgallery.js/static/img/4-1600.jpg"
      data-sub-html="<h4>Coniston Calmness</h4><p>Beautiful morning</p>">
        <a href="">
          <img class="img-responsive" src="https://sachinchoolur.github.io/lightgallery.js/static/img/thumb-4.jpg">
          <div class="demo-gallery-poster">
            <img src="https://sachinchoolur.github.io/lightgallery.js/static/img/zoom.png">
          </div>
        </a>
      </li>
  </div>
</div>

<script>
lightGallery(document.getElementById('lightgallery'), {
    thumbnail: 'true',
    animateThumb: 'true',
    showThumbByDefault: 'true',
	fullScreen: 'true',
	share: 'true'
}); 
</script>

Boop on your head

<link href="https://cdnjs.cloudflare.com/ajax/libs/nanogallery2/3.0.2/css/nanogallery2.min.css" rel="stylesheet" type="text/css">
<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/nanogallery2/3.0.2/jquery.nanogallery2.min.js"></script>

<div id="nanogallery2"

data-nanogallery2 = '{
"thumbnailHeight": 150,
"thumbnailWidth": 150,
"itemsBaseURL": "https://nanogallery2.nanostudio.org/samples/"
}' >

<a href = "berlin1.jpg"   data-ngThumb = "berlin1_t.jpg" > Berlin 1 </a>
<a href = "berlin2.jpg"   data-ngThumb = "berlin2_t.jpg" > Berlin 2 </a>
<a href = "berlin3.jpg"   data-ngThumb = "berlin2_t.jpg" > Berlin 3 </a>
</div>
