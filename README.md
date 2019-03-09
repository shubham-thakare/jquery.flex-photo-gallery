# jquery.flex-photo-gallery

# How to use it:
1. Import the jQuery Flex Photo Gallery plugin and other required resources into your html document.<br/>
	&lt;script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.3/jquery.min.js"></script>
    <br/>
    &lt;script type="text/javascript" src="js/jquery.flex-photo-gallery.js"></script>
    <br/>
    &lt;link rel="stylesheet" type="text/css" href="css/jquery.flex-photo-gallery.css"/>
    
2. Define the array objects containing images to be presented in the gallery.<br/>
    var images = <br/>
	[<br/>
      &nbsp;&nbsp;{<br/>
        &nbsp;&nbsp;&nbsp;&nbsp;"url" : "path_to_image",<br/>
        &nbsp;&nbsp;&nbsp;&nbsp;"width" : image_width,<br/>
        &nbsp;&nbsp;&nbsp;&nbsp;"height" : image_height<br/>
      &nbsp;&nbsp;},<br/>
      &nbsp;&nbsp;{<br/>
        &nbsp;&nbsp;&nbsp;&nbsp;"url" : "path_to_image",<br/>
        &nbsp;&nbsp;&nbsp;&nbsp;"width" : image_width,<br/>
        &nbsp;&nbsp;&nbsp;&nbsp;"height" : image_height<br/>
      &nbsp;&nbsp;},<br/>
      &nbsp;&nbsp;........<br/>
    ];
    
3. Create a container in which you want to display the image gallery.<br/>
    &lt;div id="gallery"></div>
  
4. Activate the plugin and done.<br/>
    $('#gallery').flexPhotoGallery({<br/>
        &nbsp;&nbsp;&nbsp;&nbsp;imageArray: images,<br/>
        &nbsp;&nbsp;&nbsp;&nbsp;isViewImageOnClick: true<br/>
    });
    
    Set isViewImageOnClick = false if you don't wan't to enlarge the image on click event. Default value is true.  
 
