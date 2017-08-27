# Custom Sticky
Terry Do (hou.dobaotrung@gmail.com)

## Overview
Custom Sticky is small, free open-source plugin which helps you in making sidebar sticks after scrolling a short path and stay where it is after a long path.

## Licenses
* MIT License

## Compatibility
* Jquery v1.7.1 or above is required.

## Usage
	$("#yoursidebar").customSticky();

## Options    

<dl>
  <dt>_road_</dt>
  <dd>Define the scroll path's length that the sidebar doesn't fixed anymore and stay where it is. <b>Default</b>: 1000 (px).</dd>
  
  <dt>_destroy_</dt>
  <dd>Destroy the plugin. <b>Default</b>: false.</dd>
  
  <dt>_unstickBefore_</dt>
  <dd>Shouldn't use along with _road_. This will be the element which your sidebar stop being fixed before its top. <b>Default</b>: NULL.</dd>

  <dt>_offsetTop_, _offsetBottom_, _offsetLeft_, offsetRight</dt>
  <dd>Positioning the element after being fixed. <b>Default</b>: 0;</dd>
</dl>