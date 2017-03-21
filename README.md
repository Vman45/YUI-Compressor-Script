# YUI-Compressor-Script (Linux)
Combine and Minify your CSS and JS

##Description: 
Uses the [YUI Compressor](http://yui.github.io/yuicompressor/) to compress and minify js and css files.

##Usage:
```
sudo min <uncompressed filename> <compressed filename>
sudo min <uncompressed filename>
sudo min <directory>
```

##Example: 
To minify the file script.js just run the command from it's location
```
sudo min script.js
```

Filename of <uncompressed filename> must end in .js or .css
If <compressed filename> is not specified then .min will be placed before the file extension
If a directory is given then it is looking for .css or .js extentions and combine all files with that extention into style.min.css or script.min.css at the given directory.
