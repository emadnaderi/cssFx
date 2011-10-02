cssFx
------

cssFx is a standalone polyfill that inserts the vendor-specific CSS3 properties necessary for old and new browsers. This saves you tons of time, maintenance, and bandwidth!

Usage
------
 * Include a script tag in your source:

``` html
<script src="cssfx.min.js"></script>
```

 * Give any external stylesheets you want processed the "cssfx" class:

 ``` html
 <link rel="stylesheet" href="cssfx.css" class="cssfx">
 ```

Browsers Supported
------

  * Firefox 3+
  * Chrome 1+
  * Internet Explorer 6+
  * Safari 3+
  * Opera 9+

Properties Supported
------
Border radius, box shadow, flex box, gradients, multiple columns, transforms, transitions, opacity, inline-block, ellipsis, and more.

Todo
------

  * rgba
  * @import support
  * media query support
  * specific box-shadow properties
  * border-image
  * don't push empty style tags to DOM
