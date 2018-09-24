Back to top
================

> Back to top button shown as you scroll down

Getting started
================
Dependencies
----------------
The required dependencies are:

* [jQuery](http://jquery.com/)
* [Font Awesome](http://fortawesome.github.io/Font-Awesome/)

Download
----------------
### Manually
The files can be downloaded from:

* Minified [JS](https://github.com/immohammadjaved/backtotop/dist/backtotop.min.js) and [CSS](https://github.com/immohammadjaved/backtotop/dist/backtotop.min.css) for production usage
* Un-minified [JS](https://github.com/immohammadjaved/backtotop/dist/backtotop.js) and [CSS](https://github.com/immohammadjaved/backtotop/dist/backtotop.css) for development

Installation
----------------
Include the JS and CSS file in your index.html file: 

```html
<link rel="stylesheet" href="backtotop.min.css">
<script src="backtotop.min.js"></script>
```

Usage
================
You must initialize the module by calling the <code>init</code> function of the module:

```javascript
backToTop.init({
	theme: 'classic', // Available themes: 'classic', 'sky', 'slate'
	animation: 'fade' // Available animations: 'fade', 'slide'
});
```

Demo
================
See [Live Demo](https://immohammadjaved.github.io/Bootpalette/).

License
================
[MIT License](http://en.wikipedia.org/wiki/MIT_License)