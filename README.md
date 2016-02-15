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
</div>
```
###step3
Setting KSlider
add this in script tag at bottom of body
``` javascript

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
		/*---------------------------------------------------------------*/
		a= 0;
		count = $("#Slide ul li").length;
		swidth = $('#slider').width();
		left = ((swidth/2) - width);
		$('#slider #cont').css( "left",left);
		action = 0;
		$(document).ready(function(){
			time();
		});
		$("#slide ul li").mousedown(function(){action = 1;});
		$("#slide ul li").mouseup(function(){if(action == 1){action = 0;}});
		$("#slide ul li").mouseout(function(){if(action == 1){action = 0;}});
```
Height,width is a Height,width of images in KSlider<br/>
distance is a distance of images from center of rotation
``` javascript
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
	* distance is distance of image from center of rotation
	*/
	distance = 200;
	/*---------------------------------------------------------------*/
```
##About Me
I am student in India and working as Software Developer in India<br/>
[kanduganesh@gmail.com](mailto:kanduganesh@gmail.com)
