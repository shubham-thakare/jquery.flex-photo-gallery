# jQuery Flex Photo Gallery
Flex Photo Gallery is a jQuery plugin which makes use of CSS3 Flexbox to create a responsive, justified grid layout and gallery for showing your images. It also provides the popup modal for viewing the selected image with the navigation buttons.

![!png](https://raw.githubusercontent.com/shubham-thakare/jquery.flex-photo-gallery/master/example/screenshots/Flex%20Gallery%20Desktop.PNG)

## How to use it:
```xml
1. Download the jquery.flex-photo-gallery plugin files.
```

```xml
2. Import the jQuery Flex Photo Gallery plugin and other required resources into your html document.
```
```javascript
<script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.3/jquery.min.js"></script>
<script type="text/javascript" src="js/jquery.flex-photo-gallery.js"></script>
<link rel="stylesheet" type="text/css" href="css/jquery.flex-photo-gallery.css"/>
```

```xml
3. Define the array objects containing images to be presented in the gallery.
```
```javascript
	var images =
	[
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
```

```xml
4. Create a container in which you want to display the image gallery.
```
```html
	<div id="gallery"></div>
```
  
```xml
5. Activate the plugin and done.
```
```javascript
	$('#gallery').flexPhotoGallery({
		imageArray: images,
		isViewImageOnClick: true
	});
```

```xml
Set isViewImageOnClick = false if you don't wan't to enlarge the image on click event. Default value is true.
```
