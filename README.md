For Twitter Bootstrap just includes 140 glyphicons, I started this 
project that makes full glyphicons (420) available at Bootstrap.

## Reference

[Twitter Bootstrap](http://twitter.github.com/bootstrap) is a 
excellent front-end framework.

[Glyphicons](http://glyphicons.com/) is a library of precisely 
prepared monochromatic icons and symbols, and the small PNG 
format is free for both personal and commercial use.

Blue Daniel has generated the CSS sprite image file and CSS styles 
on [his website](http://supercerebral.com/glyphicons-to-halflings-sprite/). 
I used this files and added a white sprite file.

## Usage

Copy files in "img" and glyphicons.css in "css" to some place 
in your website.

Change the relative path in glyphicons.css to point to your 
sprite image files.

Import glyphicons.css in your page like this:

	<link href="/path/to/glyphicons.css" rel="stylesheet" />

Display glyphicons:

	<i class="icon-g-[icon_name]"></i>
	<i class="icon-g-[icon_name] icon-g-white"></i>

Add "icon-g-white" class will displays white icon.

## Note

Accroding to the [License of Glyphicons](http://glyphicons.com/glyphicons-licenses/):

The GLYPHICONS FREE can be used both commercially and for personal use, but you must 
always add a link to [glyphicons.com](http://glyphicons.com/) in a prominent place 
(e.g. the footer of a website), include the CC-BY license and the reference to
[glyphicons.com](http://glyphicons.com/) on every page using GLYPHICONS.

## Icon Index

(TODO...)

