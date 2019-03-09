# jquery.flex-photo-gallery

How to use it:
1. Import the jQuery Flex Photo Gallery plugin and other required resources into your html document.
    <script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.3/jquery.min.js"></script>
    <script type="text/javascript" src="js/jquery.flex-photo-gallery.js"></script>
    <link rel="stylesheet" type="text/css" href="css/jquery.flex-photo-gallery.css"/>
    
2. Define the array objects containing images to be presented in the gallery.
    var images = [
      {
        "url" : "path_to_image",
        "width" : image_width,
        "height" : image_height
      },
      {
        "url" : "path_to_image",
        "width" : image_width,
        "height" : image_height
      },
      ........
    ];
    
3. Create a container in which you want to display the image gallery.
    <div id="gallery"></div>
  
4. Activate the plugin and done.
    $('#gallery').flexPhotoGallery({
        imageArray: images,
        isViewImageOnClick: true
    });
    
    Set isViewImageOnClick = false if you don't wan't to enlarge the image on click event. Default value is true. 
