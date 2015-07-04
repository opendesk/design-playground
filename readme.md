![]( ./images/opendesk-logo.png )

[Opendesk]( https://www.opendesk.cc/ ) is a global platform for local making. You may use the to download, make and buy work space furniture.

OpenDesk has a global network of makers and a collection of furniture by a range of international designers. 
Because OpenDesk furniture is designed for digital fabrication, you may download the digital file and make locally - on demand - anywhere in the world.
***

OpenDesk Design Playground
===
<span style=display:none; >[View as web page]( http://opendesk.github.io/design-playground/ "View file as a web page." ) </span>
<input type=button value='View file as source code on GitHub' onclick=window.location.href='https://github.com/opendesk/design-playground/tree/gh-pages'; />
## Concept

### Mission  
<!-- a statement of a rationale, applicable now as well as in the future -->

* To enable OpenDesk projects to be viewed, edited and created using a variety of [free, open source software]( https://en.wikipedia.org/wiki/Free_and_open-source_software ) as well as innovative proprietary solutions

### Vision  
<!--  a descriptive picture of a desired future state -->

* To help create new ways of visualizing, collaborating and improving OpenDesk projects 
* To leave behind the notion that you need 2D plans on paper in order to build things

## DXF Projects
Scripts that read 2D DXF files downloaded from [OpenDesk]( http://opendesk.cc ) and transform the data into 3D models viewable in your browser.



### [OpenDesk Standing Table DXF]( http://opendesk.github.io/design-playground/opendesk-standing-table/latest/ )

* Assembled components positioned by algorithm ~ except for angled components
* Latest update: 2015-07-04
* [Original design]( https://www.opendesk.cc/lean/standing-desk ) by [Joni Steiner]( https://www.opendesk.cc/designers/joni-steiner ) and [Nick Ierodiaconou]( https://www.opendesk.cc/designers/nick-ierodiaconou )

### [OpenDesk 5 to 30 Minute Chair DXF]( http://opendesk.github.io/design-playground/opendesk-5-to-30-minute-chair/latest/ )

* Assembled components positioned by algorithm ~ except for angled components
* [Original design]( https://www.opendesk.cc/atfab/5-to-30-minute-chair ) by [AtFAB]( http://atfab.co/ )

### [OpenDesk One to Several Table DXF]( http://opendesk.github.io/design-playground/opendesk-one-to-several-table/latest/ ) 

* Assembled components positioned by algorithm
* Probably the most finished demo as of this writing
* [Designed]( https://www.opendesk.cc/atfab/one-to-several-table ) by [AtFAB]( http://atfab.co/ )

### [OpenDesk Rotational Table DXF]( http://opendesk.github.io/design-playground/opendesk-rotational-table/latest/ ) 

* Assembled components positioned, gasp!, by eye
* [Designed]( https://www.opendesk.cc/atfab/rotational-table ) by [AtFAB]( http://atfab.co/ )

### [Display atFab DXF files Demo]( http://opendesk.github.io/design-playground/display-atfab-dxf/latest/ )  
[Read Me]( http://opendesk.github.io/design-playground/display-atfab-dxf/ )

* View several [AtFAB]( https://www.opendesk.cc/atfab ) DXF files in 3D  
* Latest update: 2015-06-27
* The first script in this series


### Roadmap

* Toggle display of names or references of each component
* Add indication of the outline of the whole original plywood sheet
* Allow for size of cutting tools
	* including depth
* Output to SVG, STL, PDF, Three.j JSON  and over formats
* Create pretty renderings
* Obtain assembled 3D positions from the original SketchUp files
* Display animation in order of the sequence of construction
* Add exploded view


## App Projects
Scripts that attempt to recreate the OpenDesk projects by creating 3D models on-the-fly using code with user-entered parameters.

### [Half Sheet Table Demo]( http://opendesk.github.io/design-playground/opendesk-half-sheet-table/latest/ ) 
[Read Me]( http://opendesk.github.io/design-playground/opendesk-half-sheet-table/ )

* View highly parameterized complex geometry 

### [Rotational Stools Demo]( http://opendesk.github.io/design-playground/opendesk-rotational-stools/latest/ )
[Read Me]( http://opendesk.github.io/design-playground/opendesk-rotational-stools/ )

* view fully parameterized with assemble disassemble, simple geometry  

### Roadmap

* Output to SVG, STL, PDF, Three.j JSON  and over formats
* Create pretty renderings


## Features

The current collection of scripts are built using [Three.js]( http://threejs.org/ ). [Three.js]( https://en.wikipedia.org/wiki/Three.js ) is an open-source JavaScript library dedicated to building 3D apps on top of the [WebGL]( https://get.webgl.org/) built into modern browsers.
By communicating directly with the GPU in your computer, WebGL apps are very fast. The Three.js library enable even entry level programmers to build highly interactive apps on top of WebGL.

* All scripts support zoom, pan and rotate
	* Rotate by dragging with left mouse button down or by pressing one finger
	* Zoom by using mouse scroll wheel or by pinching two fingers
	* Pan by dragging with right mouse button down or by pressing two fingers
* Free, open source software 
	* With source code and live demos viewable in your browser 
	* All available on GitHub 

It is hope that in the future apps based on other technologies such as [OnShape]( https://www.onshape.com/ ) or [Grasshopper on Rhino]( http://www.grasshopper3d.com/ ) and others are added to this collection of tools.
 
 
## Contacts

opendesk-community@googlegroups.com

See also similar work at [WikiHouse.GitHub.io]( http://wikihouse.github.io/viewer-experiments/ )

See also [AtFAB]( http://atfab.co )

##Copyright

Copyright © 2015 OpenDesk authors


## License

OpenDesk software is available under the [MIT License]( http://en.wikipedia.org/wiki/MIT_License) which states:

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the 'Software'),
to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

The software is provided 'as is', without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose and noninfringement.
In no event shall the authors or copyright holders be liable for any claim, damages or other liability, whether in an action of contract, tort or otherwise, arising from, out of or in connection with the software or the use or other dealings in the software.



## Change Log

2015-07-04 ~ Theo

* Update Read Me
* Add Standing Table DXF


2015-06-27 ~ Theo

* Added Dev Notes


2015-06-25 ~ Theo

* Add OpenDesk AtFAB DXF viewer
* Add DXF files
* Update read me files

OpenDesk designers each seem to have their own favorite way of creating DXF files. 
Designers use their own layer naming conventions, their own scale units and even varying DXF revisions.
Thus a different DXF reader will have to be built for each designer. 
I have started with AtFAB because they have a simple format.
The only issue with their method is that there is no indication that a polyline is a hole inside another polyline,
so I am having to identify these manually.
 
2015-06-24 ~ Theo

* Move files over from my repo to OpenDesk repos
* Added to read me docs
