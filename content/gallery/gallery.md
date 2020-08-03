+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 2  # Order that this section will appear.

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

            <meta name="viewport" content="user-scalable=no, width=device-width, initial-scale=1, maximum-scale=1">          
            
            <!-- jQuery -->
            <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/2.1.1/jquery.min.js" type="text/javascript"></script>
          
            <!-- nanogallery2 -->
            <link  href="https://cdnjs.cloudflare.com/ajax/libs/nanogallery2/3.0.2/css/nanogallery2.min.css" rel="stylesheet" type="text/css">
            <script  type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/nanogallery2/3.0.2/jquery.nanogallery2.min.js"></script>
        
              <h1>gallery made with nanogallery2</h1>

              <!-- ### position of the gallery ### -->
              <div id="nanogallery2">gallery_made_with_nanogallery2</div>
            
              <script>
                 jQuery(document).ready(function () {

                    jQuery("#nanogallery2").nanogallery2( {
                        // ### gallery settings ### 
                        thumbnailHeight:  150,
                        thumbnailWidth:   150,
                        itemsBaseURL:     'https://nanogallery2.nanostudio.org/samples/',
                        
                        // ### gallery content ### 
                        items: [
                            { src: 'berlin1.jpg', srct: 'berlin1_t.jpg', title: 'Berlin 1' },
                            { src: 'berlin2.jpg', srct: 'berlin2_t.jpg', title: 'Berlin 2' },
                            { src: 'berlin3.jpg', srct: 'berlin3_t.jpg', title: 'Berlin 3' }
                          ]
                      });
                  });
              </script>