# Filters.css

Really easy to use image filters, patterns and color blending.
Intended to help make full image backgrounds on websites better.

http://davidfurlong.github.io/filters.css

## Instructions

### Filters.css for background images: (fully supported)

#### CSS
	#someName {
		background: url('https://s3.amazonaws.com/ooomf-com-files/pHyYeNZMRFOIRpYeW7X3_manacloseup%20copy.jpg');
		position: relative;
		display: block;
		z-index: 1;
	}

	#someName:after {
		content: '';
		top: 0;
		left: 0;
		z-index: -1;
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

#### Color Effects

- Fade
- Saturate
- Tint
- Opacity
- Black & White (.bw)
- Dark
- Bright
- Sepia
- Contrast
- Invert
- Hue

#### Patterns

- Stripes-h
- Dark Stripes-h
- Stripes-v
- Dark Stripes-v
- Glossy
- Blueprint
- Dots
- Dark Dots
- Cubes
- Dark Cubes
- Pluses
- Steps
- LED
- Hexagon
- Noise

#### Colors (Flat UI)

- Spectrum
- Turqoise
- Emerald
- Peter-river
- amethyst
- Wet-asphalt
- Green-sea
- Nephritis
- Belize-hole
- Wisteria
- Midnight-blue
- Sunflower
- Carrot
- Alizarin
- Clouds
- Concrete
- Orange
- Pumpkin
- Pomegranite
- Silver
- Asbestos

#### Blend Modes

- Multiply
- Screen
- Overlay
- Darken
- Lighten
- Color-Dodge
- Color-burn
- Hard light
- Soft Light
- Difference
- Exclusion
- Hue
- Saturation
- Color
- Luminosity

### Compatibility
IE 9+, 

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


### Contributing

Things to do:
- Add Instagramesque filters which are more advanced and use canvas
- Add normals colors
- Allow applying of multiple filters
- Reduce nr of filters

### Attributions

[Flat UI Colors](http://flatuicolors.com/ "Flat UI Colors")

I got some of the initial css code for the patterns from the below, they're awesome, check them out!

[SVG Patterns](http://philbit.com/svgpatterns/)

[CSS3 Patterns](http://lea.verou.me/css3patterns/)
