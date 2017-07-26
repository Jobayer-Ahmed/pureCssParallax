PureCssParallax
===========

Simple parallax scrolling effect inspired by **[Parallax.js](http://pixelcog.github.io/parallax.js/)** implemented as a **CSS3** plugin.
http://

## Installation

Download the Packege or include **parallax.min.css** in your document just before including CSS.

``` html
<link rel="stylesheet" href="/path/to/parallax.min.css">
```

## Usage

You can use the following syntax to enable **Parallax** in your page:

``` html
<div class="herounit">
	<img src="/path/to/image.jpg" class="heroimg">
	<div class="container">
		<p>Main Content</p>
	</div>
</div>
```

## Options

To make image **Responsive** please change css "**Top**" property. Follow the rule below.

**hight/width*100**

After change it will look like:

top: calc(((100vh - [**Your Calculation**]]vw) / 4) * -2);

You can also controll the scrolling speed by changing **translateZ** property of heroimage.

If you dont want to add cross browser support then remove **-webkit-overflow-scrolling** from container class.

## Contributing

If you have a pull request you would like to submit, please ensure that you update the minified version of the library along with your code changes. This project uses **[CSS Minifier](https://cssminifier.com/)** to perform code compression.
