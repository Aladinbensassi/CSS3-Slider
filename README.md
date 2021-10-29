[DEMO](http://codepen.io/Eliteware/full/BoBgqV/)
# CSS3-Slider
Pure CSS3 Slider with multiple animation options

Its easy to choose a version, all you have to do is call a different CSS file, the HTML is the same (except in the light version, where there is no legend or bullets) 

Different CSS files are for different slide effects
slider-def.css : Default
slider-ltr.css : Left to right
slider-ttb.css : Top to bottom
slider-btt.css : Bottom to top
slider-simp.css : Light

Example of Use 
```html
<head> 
  ... <!-- Your stuff --> 
  <link rel="stylesheet" href="style/slider-def.css"> 
</head>
```
And the only thing rest is adding the HTML
```html
<div id="slider">
   <div class="slides">
      <!-- First slide --> 
      <div class="slider">
         <div class="legend"></div>
         <div class="content">
            <div class="content-txt">
               <h1> Your title </h1>
               <h2> Your description </h2>
            </div>
         </div>
         <div class="images"> 
            <img src="ImagePath/ImageName.jpg"> 
         </div>
      </div>
      <!-- Second slide --> 
      <div class="slider">
         <div class="legend"></div>
         <div class="content">
            <div class="content-txt">
               <h1> Your title </h1>
               <h2> Your description </h2>
            </div>
         </div>
         <div class="images"> 
            <img src="ImagePath/ImageName.jpg"> 
         </div>
      </div>
      <!-- Third slide --> 
      <div class="slider">
         <div class="legend"></div>
         <div class="content">
            <div class="content-txt">
               <h1> Your title </h1>
               <h2> Your description </h2>
            </div>
         </div>
         <div class="images"> 
            <img src="ImagePath/ImageName.jpg"> 
         </div>
      </div>
      <!-- Fourth slide --> 
      <div class="slider">
         <div class="legend"></div>
         <div class="content">
            <div class="content-txt">
               <h1> Your title </h1>
               <h2> Your description </h2>
            </div>
         </div>
         <div class="images"> 
            <img src="ImagePath/ImageName.jpg"> 
         </div>
      </div>
   </div>
</div>
```
