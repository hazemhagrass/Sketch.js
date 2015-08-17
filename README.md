# Sketch.js
This Plugin is inspired from Sketch.js plugin [here](http://intridea.github.io/sketch.js/), it is an easy-to-use jQuery plugin that allows you to create canvases upon which visitors can draw, more functionality added to the original plugin.

### Installation
To use Sketch.js in your project, just grab the latest sketch.js (or minified) from GitHub repo and include it in your project after jQuery.

### Usage
```sh
<canvas id="simple_sketch" width="800" height="500" style="border:2px solid #000;"></canvas>
<script type="text/javascript">
    $(function() {
        $('#simple_sketch').sketch({});
    });
</script>
```
If background needed for board then it can be added as an option to sketch:
```sh
$('#simple_sketch').sketch({
    background: "letters.png"
});
```

### Compatibility

Sketch.js has been tested on Chrome (OS X), Firefox (OS X), Safari (OS X), Android Browser (Honeycomb 3.1). It suffers significant performance degradation on mobile browsers due to general HTML5 Canvas performance issues.

### License

Copyright (C) 2011 by Michael Bleigh and Intridea, Inc.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
