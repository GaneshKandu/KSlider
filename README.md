# Rotating-Slider
Rotating Images Slider


##Screenshot example
![](https://github.com/GaneshKandu/Rotating-Slider/blob/master/sceenshot/screenshot.gif)
## Desc
its a Rotating Images Slider<br/>
all Images are Rotating in Circular motion
KSlider<br/>
where K is Initial of My Last Name

## coding

add this in your Head tag<br/>
add JQuery also
```html
	<link rel="stylesheet" type="text/css" href="css/kslider.mini.css">
	<script src="js/kslider.mini.js"></script> 
```
###step1

setting width and height in &lt;style&gt; tag 
``` css
#slider {
	width: 600px;
	height: 400px;
}
```
###step2
adding Images to KSlider 

``` html

<div id="slider" >
	<div id="cont">
		<div id="Slide">
			<ul>
				<li><img class="imgzoom" src="images/kslider (1).jpg"/></li>
				<li><img class="imgzoom" src="images/kslider (2).jpg"/></li>
				<li><img class="imgzoom" src="images/kslider (3).jpg"/></li>
				<li><img class="imgzoom" src="images/kslider (4).jpg"/></li>
				<li><img class="imgzoom" src="images/kslider (5).jpg"/></li>
			</ul>
		</div>
	</div>
	<div id="zoomimg">
		<img></img>
	</div>
</div>
```
###step3
initialising KSlider
add this in script tag at bottom of body<br/>
Height,width is a Height,width of images in KSlider<br/>
distance is a distance of images from center of rotation<br/>
speed is speed of rotation of image in millisecond<br/>
valign is alignment of images
```javascript
		/*---------------------------------------------------------------*/
		/*
		* width is width of image
		*/
		width = 300;
		/*
		* height is height of image
		*/
		height = 200;
		/*
		* distance is distance of image
		*/
		distance = 200;
		/*
		* speed is speed of rotation of image in millisecond
		*/
		speed = 50;
		/*
		* valign is a alignment
		* 0.top
		* 1.middle
		* 2.bottom
		*/
		valign = 1;
		/*---------------------------------------------------------------*/
		$(document).ready(function(){
			init_kslide();
		});
```

##About Me
I am student in and working as Software Developer in India<br/>
[kanduganesh@gmail.com](mailto:kanduganesh@gmail.com)
