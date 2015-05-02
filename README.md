

### ibanner ###
>v.0.0.1

Touch enabled jQuery plugin that lets you create beautiful responsive ibanner slider.
[Visit Owl ibanner landing page](http://zanjs.com/ibanner)

###Features:
* Responsive
* Touch Events
* Mouse Slide Events
* Fully Customizable
* Choose the number of items to be displayed
* Multiple Sliders
* CSS3 3d Transitions
* Custimizable controls
* JSON 
* Custom events
* Helpful callbacks

> Tested on IE7, IE8, IE9, IE10, Chrome, Safari, Firefox, Opera, iPhone, iPad, Chrom on Google Nexus.


### More Demos
See what Owl can do:
* [With auto scaling images](http://zanjs.com/ibanner/demos/images.html)
* [Full Width](http://zanjs.com/ibanner/demos/full.html)
* [Custom Widths](http://zanjs.com/ibanner/demos/custom.html)
* [One Item](http://zanjs.com/ibanner/demos/one.html)
* [More demos](http://zanjs.com/ibanner/#more-demos)

### 1.Getting Started
Load jQuery(1.7+) and include Owl ibanner plugin files

```html
<!-- Basic stylesheet -->
<link rel="stylesheet" href="owl-ibanner/owl.ibanner.css">
 
 <!-- Default Theme -->
<link rel="stylesheet" href="owl-ibanner/owl.theme.css">
 
<!-- Include js plugin -->
<script src="owl-ibanner/owl.ibanner.js"></script>
```
### 2.Set up your HTML
You don't need any special markup. All you need is to wrap your divs inside the container element <div class="owl-ibanner">. Class "owl-ibanner" is mandatory to apply proper styles that come from owl.ibanner.css file.

```html
<div class="owl-ibanner">
  <div> Your Content </div>
  <div> Your Content </div>
  <div> Your Content </div>
  <div> Your Content </div>
  <div> Your Content </div>
  <div> Your Content </div>
  <div> Your Content </div>
  ...
</div>
```
### 3.Call the plugin
Now call the Owl initializer function and your ibanner is ready.

```html
$(".owl-ibanner").ibanner();
```
### 4. For more details visit [ibanner landing page](http://zanjs.com/ibanner)




License
------------
The MIT License (MIT)
