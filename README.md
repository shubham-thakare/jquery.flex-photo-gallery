# JQuery Flex Photo Gallery
Flex Photo Gallery is a jQuery plugin which makes use of CSS3 Flexbox to create a responsive, justified grid layout and gallery for showing your images. It also provides the popup modal for viewing the selected image.

<b><h3>How to use it:</h3></b>
<b>1. Import the jQuery Flex Photo Gallery plugin and other required resources into your html document.<br/></b>
	&lt;script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.3/jquery.min.js"></script>
    <br/>
    &lt;script type="text/javascript" src="js/jquery.flex-photo-gallery.js"></script>
    <br/>
    &lt;link rel="stylesheet" type="text/css" href="css/jquery.flex-photo-gallery.css"/>
    
<b>2. Define the array objects containing images to be presented in the gallery.<br/></b>
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
    
<b>3. Create a container in which you want to display the image gallery.<br/></b>
    &lt;div id="gallery"></div>
  
<b>4. Activate the plugin and done.<br/></b>
    $('#gallery').flexPhotoGallery({<br/>
        &nbsp;&nbsp;&nbsp;&nbsp;imageArray: images,<br/>
        &nbsp;&nbsp;&nbsp;&nbsp;isViewImageOnClick: true<br/>
    });
    
    Set isViewImageOnClick = false if you don't wan't to enlarge the image on click event. Default value is true.  
 
