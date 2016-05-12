[![npm](https://img.shields.io/npm/v/nativescript-svg.svg)](https://www.npmjs.com/package/nativescript-svg)
[![npm](https://img.shields.io/npm/dt/nativescript-svg.svg?label=npm%20downloads)](https://www.npmjs.com/package/nativescript-svg)
#NativeScript SVG

##Install
`tns plugin add nativescript-svg`

#

###Usage

You use it in the same way you use Image source.

**there are limitations: load from URL and the base64 encondig aren't working**

```js
var SVG = require("nativescript-svg");
var svgParser = new SVG.ImageSourceSVG();

var source = svgParser.imageFromResource('foxie');

var path = '//somepath/file.svg';
source = svgParser.loadFromFile(path);
```

