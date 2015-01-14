wak-image-magick
================

Wakanda module to use [ImageMagick](http://www.imagemagick.org).

About
-----
* ImageMagick/6.9.0
* libcairo/1.12.18
* libfontconfig/2.11.1
* libfreetype/2.5.4
* libglib/2.43.2
* libharfbuzz/0.9.37
* libjpeg/9a
* libpixman/0.32.6
* libpango/1.36.8
* libtiff/4.0.3
* libpng/1.6.15
* libffi/3.2.1

Supported [commands](http://www.imagemagick.org/script/command-line-tools.php): identify, compare, composite, conjure, convert, mogrify, montage, stream.

##Install
###Linux
Folder content of Modules/image-magick/Linux64/ needs to be executable.
```
chmod +x
```

##Example
Resize image with ImageMagick
```javascript
// load module
var imageMagick = require('image-magick');
// resize image only if bigger
imageMagick.convert('convert test.jpg -resize 64x64\> small_test.jpg');
```
