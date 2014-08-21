# Filters.css

Really easy to use image filters, patterns and color blending.
Intended to help make full image backgrounds on websites better.

## Instructions

### Filters.css for background images: (fully supported)

#### CSS
	#someName:after {
		content: '';
		top: 0;
		left: 0;
		height: 100%;
		width: 100%;
		position: absolute;
		background: url('https://s3.amazonaws.com/ooomf-com-files/pHyYeNZMRFOIRpYeW7X3_manacloseup%20copy.jpg');
	}

#### HTML

	<div id="someName" class="tint"></div> // Effects

OR

	<div id="someName" class="stripes-v"></div> // Patterns

OR

	<div id="someName" class="amethyst screen"></div> // Blend Modes

### Filters.css for img tags: (blend modes not supported)

#### HTML

	<img id="someOtherName" class="tint" src="someSource.jpg"> // Only Effects & Patterns

### List of class names

		    </ul>
		</div>
		</div>
		<div id="group2">
		<div id="d2" class="wrapper-dropdown-3" tabindex="1">
		    <div>Patterns</div>
		    <ul class="dropdown">
		        <li><a href="#">Stripes-h</a></li>
		        <li><a href="#">Dark Stripes-h</a></li>
		        <li><a href="#">Stripes-v</a></li>
		        <li><a href="#">Dark Stripes-v</a></li>
		        <li><a href="#">Glossy</a></li>
		        <li><a href="#">Blueprint</a></li>
		        <li><a href="#">Dots</a></li>
		        <li><a href="#">Dark Dots</a></li>
		        <li><a href="#">Cubes</a></li>
		        <li><a href="#">Dark Cubes</a></li>
		        <li><a href="#">Pluses</a></li>
		        <li><a href="#">Steps</a></li>
		        <li><a href="#">LED</a></li>
		        <li><a href="#">Hexagon</a></li>
		        <li><a href="#">Noise</a></li>
		    </ul>
		</div>
		</div>
		<div id="group3">
		<div id="d3" class="wrapper-dropdown-3" tabindex="1">
		    <div>Color (FlatUI)</div>
		    <ul class="dropdown">
		        <li><a href="#">Spectrum</a></li>
		        <li><a href="#">Turqoise</a></li>
		        <li><a href="#">Emerald</a></li>
		        <li><a href="#">Peter-river</a></li>
		        <li><a href="#">amethyst</a></li>
		        <li><a href="#">Wet-asphalt</a></li>
		        <li><a href="#">Green-sea</a></li>
		        <li><a href="#">Nephritis</a></li>
		        <li><a href="#">Belize-hole</a></li>
		        <li><a href="#">Wisteria</a></li>
		        <li><a href="#">Midnight-blue</a></li>
		        <li><a href="#">Sunflower</a></li>
		        <li><a href="#">Carrot</a></li>
		        <li><a href="#">Alizarin</a></li>
		        <li><a href="#">Clouds</a></li>
		        <li><a href="#">Concrete</a></li>
		        <li><a href="#">Orange</a></li>
		        <li><a href="#">Pumpkin</a></li>
		        <li><a href="#">Pomegranite</a></li>
		        <li><a href="#">Silver</a></li>
		        <li><a href="#">Asbestos</a></li>
		    </ul>
		</div>
		<div id="d4" class="wrapper-dropdown-3" tabindex="1">
		    <div>Blend</div>
		    <ul class="dropdown">
		        <li><a href="#">Multiply</a></li>
		        <li><a href="#">Screen</a></li>
		        <li><a href="#">Overlay</a></li>
		        <li><a href="#">Darken</a></li>
		        <li><a href="#">Lighten</a></li>
		        <li><a href="#">Color-Dodge</a></li>
		        <li><a href="#">Color-burn</a></li>
		        <li><a href="#">Hard light</a></li>
		        <li><a href="#">Soft Light</a></li>
		        <li><a href="#">Difference</a></li>
		        <li><a href="#">Exclusion</a></li>
		        <li><a href="#">Hue</a></li>
		        <li><a href="#">Saturation</a></li>
		        <li><a href="#">Color</a></li>
		        <li><a href="#">Luminosity</a></li>

### Compatibility
IE 9 + 

### Using your own colors/configuring

### [Flat UI Colors](http://flatuicolors.com/ "Flat UI Colors")

### License

The MIT License (MIT)

Copyright (c) 2014 David Furlong

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

### Attributions 

I got some of the initial css code for the patterns from the below, they're awesome, check them out!

[SVG Patterns](http://philbit.com/svgpatterns/)

[CSS3 Patterns](http://lea.verou.me/css3patterns/)
