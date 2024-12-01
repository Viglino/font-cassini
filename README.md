# <img src="https://github.com/Viglino/font-cassini/blob/main/svg/bati/uEA10-paroisse-c.svg" height="40" /> Font-Cassini
*Icon font set of Cassini map symbols for use with GIS and spatial analysis tools*

[![](https://img.shields.io/npm/v/font-cassini.svg)](https://www.npmjs.com/package/font-cassini)
![](https://img.shields.io/npm/dt/font-cassini.svg)
![](https://img.shields.io/npm/dw/font-cassini)
![](https://img.shields.io/npm/l/font-cassini.svg)

I've collected in this repo icons and graphics I've been using in my projects.
Font-Cassini icons and font theme is designed mainly for GIS applications and web mapping tools. 
They can be easily included in a project using the font or svg images.

[See demo page and examples <img src="https://github.com/Viglino/font-cassini/blob/main/svg/search/uEA5F-search-map.svg" height="25" />](https://viglino.github.io/font-cassini/)

## <img src="https://github.com/Viglino/font-cassini/blob/main/svg/routing/uEA8F-timer.svg" height="35" align="left" />Getting started

###  NPM package

Font-Cassini is availiable on Github:
```console
npm install --save git+https://github.com/viglino/font-cassini.git
```
You can access the font or css in the `./font` and `./css` directory of the package.    
The svg sprites are located in the `./dist/font-cassini.svg` SVG file.

### using Font-Cassini

You can use Font-Cassini as a font or as SVG symbols or images.

To use it in a web page, just add the css in your project.
```html
<link href="https://viglino.github.io/font-cassini/css/font-cassini.css" rel="stylesheet" />
```
Then use an inline element with a class prefixed with `fc-` to add a new icon.    
<img src="https://github.com/Viglino/font-cassini/blob/main/svg/bati/uEA10-paroisse-c.svg" height="30" />
<img src="https://github.com/Viglino/font-cassini/blob/main/svg/geom/uEA02-polyline-pt.svg" height="30" />
```html
<!-- prefix: fc - icon name: paroisse-c -->
<i class="fc-paroisse-c"></i>
<!-- using a <span> is more semantically correct but a little bit verbose. -->
<span class="fc-polyline-pt"></span>
```
Or use it as an svg sprite (svg sprites are inlocated in the `./dist/font-cassini.svg` file):    
<img src="https://github.com/Viglino/font-cassini/blob/main/svg/geom/uEA03-polygon-pt.svg" height="30" />
```html
<svg class="font-cassini fc-3x"><use xlink:href="path/to/dist/font-cassini.svg#fc-polyline-pt" /></svg>
```

## <img src="https://github.com/Viglino/font-cassini/blob/main/svg/edit/uEA51-copy-poly.svg" height="35" align="left" />Contributing
Please use the [GitHub issue tracker](https://github.com/Viglino/font-cassini/issues) to ask for new features 
or create a pull request.    
Font is created from the files in the `./svg` folder, you only have to create a new file in this folder. 
Use the `./templates/template.svg` template to create a new icon.  
You can add a new glyph in the [font-cassini.json](https://github.com/Viglino/font-cassini/blob/main/font-cassini.json) file with a theme and search tags 
(other fields will be filled automatically).

Your contribution will be published under [Font-Cassini license](https://github.com/Viglino/font-cassini/blob/main/LICENSE.md) as per [GitHub's terms of service](https://help.github.com/articles/github-terms-of-service/#6-contributions-under-repository-license).

If you wan't to build the font and create the dist, use the build script (run `npm install` to install the dev dependencies before):
```console
npm run build
```
Use a local server (http://localhost:8181/) to see result on the page:
```console
npm start
```


## <img src="https://github.com/Viglino/font-cassini/blob/main/svg/map/uEA7A-map-book.svg" height="35" align="left" />Licenses

**Font-Cassini is licensed under [Apache-2.0](https://github.com/Viglino/font-cassini/blob/main/LICENSE-APACHE.md)**    
Copyright (c) 2024 Jean-Marc Viglino

[Font-Cassini](https://viglino.github.io/font-cassini/) is free, open source, and GPL friendly. 
You can use it for commercial projects, open source projects, or really almost whatever you want.
[Read full Font-Cassini license](https://github.com/Viglino/font-cassini/blob/main/LICENSE.md)

Dual-license can be used for each specific part:
* Font-Cassini **font** is licensed under the [SIL OFL 1.1 License](https://github.com/Viglino/font-cassini/blob/main/LICENSE-OFL.md)
* **Icons** and **SVG** files are licensed under the [CC BY 4.0 License](https://creativecommons.org/licenses/by/4.0/)
* **Codes** and all non font or icon files are licensed under the [MIT License](https://github.com/Viglino/font-cassini/blob/main/LICENSE-MIT.md)

Attribution is required by Apache, MIT, SIL OFL, and CC BY licenses. Font-Cassini files already 
contain embedded comments with sufficient attribution, so **you shouldn't need to 
do anything additional when using these files normally**.

